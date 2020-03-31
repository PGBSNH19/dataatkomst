# Unit testing with data

Måndag den 30:e mars 2020

Denna lektion handlar om hur vi kan och bör testa vår applikation som använder Entity Framework (och externa resurser över lag).

## Lektionsplan

Lektion från kl. 8:30 till kl. 16:30

* 8:30 Uppsamling från förra lektion    
  - Boarding card, PM på teams till Stephan
* 9:15 Presentationer av The SpacePort
  - 5 min per grupp (8 grupper), 40 min
* 10:15 Code review av The SpacePort
* 11:30 Introduktion av dagens ämnen, unit testing

Lunch 12:00 till 13:00

* 13:00 Programmeringsövning i grupp, slut projekt
  * Kommer att finnas i GitHub classroom


- 13:45 Mobprogramming
  - 15 min per driver, check-in och push till Github
- 16:30 Slut på lektion

# Lektionsteori

Teori, exemplar och övningar. Bör genomgås innan lektionen.

## Viktig kurslitteratur

Detta är litteratur som är bas för denna lektion, detta bör läses innan man går på gång med lektionsteorin.

* [The different types of software testing](https://www.atlassian.com/continuous-delivery/software-testing/types-of-software-testing)
* [Unit Tests For Every Bug Fix](http://iedaddy.com/2016/11/unit-tests-every-bug-fix/)
* [7 Popular Unit Test Naming Conventions](https://dzone.com/articles/7-popular-unit-test-naming)
* [Unit Tests, How to Write Testable Code and Why it Matters](https://www.toptal.com/qa/how-to-write-testable-code-and-why-it-matters)
* Unit Test Patterns for .NET: [Part 1](https://www.typemock.com/unit-test-patterns-for-net/), [Part 2 : The Isolation Pattern](https://www.typemock.com/unit-test-patterns-part-ii)

Mocking and fakes

* [Dependency Inversion Principle](https://deviq.com/dependency-inversion-principle/) - Depend on abstractions, not concretions
* [The anatomy of robust unit testing (with examples in C#)](https://raygun.com/blog/unit-testing-examples-and-anatomy/)
* [Fundamentals of Unit Testing: Understand Mock Object in Unit Testing](https://www.c-sharpcorner.com/UploadFile/dacca2/fundamental-of-unit-testing-understand-mock-object-in-unit/)
* [Mocking DbContext and DbSet with Moq](https://www.jankowskimichal.pl/en/2016/01/mocking-dbcontext-and-dbset-with-moq/)

**OBS!** Entity Framework gir möjlighet till att simulera en databas i minnet, smidigt, men att kalla detta unit test är i mina ögon fel, mer rätt skulle integration test vara, och man får vara försiktig med detta, i alla fall försiktig med att kalla det unit test. Eftersom vi aldrig kan veta om databasen i minnet beter sig på precis samma sätt som produktions databasen.

* [Testing components using EF Core](https://docs.microsoft.com/en-us/ef/core/miscellaneous/testing/)
* Microsoft: [InMemory test](https://docs.microsoft.com/en-us/ef/core/miscellaneous/testing/in-memory) 
  * [Unit Testing With Entity Framework and Entity Framework Core 2.1](https://dev.to/pcmichaels/unit-testing-with-entity-framework-and-entity-framework-core-2-1-1j2)
  * [Unit testing in ASP.NET Core with EF Sqlite in-memory and XUnit](https://raaaimund.github.io/tech/2019/05/07/aspnet-core-unit-testing-inmemory/)

## Bakgrunds litteratur

Detta är litteratur som är frivillig, och som kan kan används till at få en djupare insikt i ämnen i klassen.

* [Evil Unit Testing](https://coderanch.com/wiki/718795/Unit-Testing)
* [Why unit tests should not use database?](https://stackoverflow.com/questions/15450957/why-unit-tests-should-not-use-database)
* [On the dark art of software estimation](https://techcrunch.com/2016/04/30/estimate-thrice-develop-once/)
* [Testing your C# code with xUnit](https://www.codemotion.com/magazine/dev-hub/backend-dev/testing-your-c-code-with-xunit/)

**Host Builder**, the Microsoft way to work with Configuration, Servies and Logging

* Exempel, host builder och Entity Framework
  * Demo video: https://youtu.be/UEogi9HAflE
  * GitHub: https://github.com/PGBSNH19/dot-net-core-generic-host-demo
* [Get started with .NET Generic Host](https://snede.net/get-started-with-net-generic-host/)
* [Generic Host Builder in ASP .NET Core 3.1](https://wakeupandcode.com/generic-host-builder-in-asp-net-core-3-1/)
* [.NET Generic Host](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/host/generic-host?view=aspnetcore-3.1)
* [Having Fun with the .NET Core Generic Host](https://jmezach.github.io/2017/10/29/having-fun-with-the-.net-core-generic-host/)
* [Using IHost .net core console applications](https://garywoodfine.com/ihost-net-core-console-applications/)
* [Exploring the new project file, Program.cs, and the generic host](https://andrewlock.net/exploring-the-new-project-file-program-and-the-generic-host-in-asp-net-core-3/)