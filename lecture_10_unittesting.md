# Unit testing with data

Tisdag 3:e mars 2020

![Draft](/dataatkomst/assets/images/draft.png)

Denna lektion handlar om hur vi kan och bör testa vår applikation som använder Entity Framework (och externa resurser över lag).

## Lektionsplan

Lektion från kl. 8:30 till kl. 16:30

* x

Lunch 12:00 till 13:00

* x

# Lektionsteori

Teori, exemplar och övningar. Bör genomgås innan lektionen.

## Viktig kurslitteratur

Detta är litteratur som är bas för denna lektion, detta bör läses innan man går på gång med lektionsteorin.

* [The different types of software testing](https://www.atlassian.com/continuous-delivery/software-testing/types-of-software-testing)
* [Dependency Inversion Principle](https://deviq.com/dependency-inversion-principle/) - Depend on abstractions, not concretions
* [Unit Tests with Dependency Injection](https://agostini.tech/2017/04/24/unit-tests-with-dependency-injection/)
  * [Fundamentals of Unit Testing: Understand Mock Object in Unit Testing](https://www.c-sharpcorner.com/UploadFile/dacca2/fundamental-of-unit-testing-understand-mock-object-in-unit/)

**OBS!** Entity Framework gir möjlighet till att simulera en databas i minnet, smidigt, men att kalla detta unit test är i mina ögon fel, mer rätt skulle integration test vara, och man får vara försiktig med detta, i alla fall försiktig med att kalla det unit test. Eftersom vi aldrig kan veta om databasen i minnet beter sig på precis samma sätt som produktions databasen.

* Microsoft: [InMemory test](https://docs.microsoft.com/en-us/ef/core/miscellaneous/testing/in-memory) 
  * [Unit Testing With Entity Framework and Entity Framework Core 2.1](https://dev.to/pcmichaels/unit-testing-with-entity-framework-and-entity-framework-core-2-1-1j2)
  * [Unit testing in ASP.NET Core with EF Sqlite in-memory and XUnit](https://raaaimund.github.io/tech/2019/05/07/aspnet-core-unit-testing-inmemory/)

## Bakgrunds litteratur

Detta är litteratur som är frivillig, och som kan kan används till at få en djupare insikt i ämnen i klassen.

* [Evil Unit Testing](https://coderanch.com/wiki/718795/Unit-Testing)

  * [Why unit tests should not use database?](https://stackoverflow.com/questions/15450957/why-unit-tests-should-not-use-database)

* [On the dark art of software estimation](https://techcrunch.com/2016/04/30/estimate-thrice-develop-once/)

  