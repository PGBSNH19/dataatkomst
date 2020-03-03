# Clean code

Torsdag 5:e mars 2020

![Draft](/dataatkomst/assets/images/draft.png)

Denna lektion handlar om hur vi kan producera kod som är lätt att läsa och underhålla, också kallat Clean Code. För att uppnå Clean Code kommer vi i denna lektion att fokusera på best practice för kod, enhetstestar och SOLID principen. Detta bygger på [lektion 18](https://csharp.2019.plus.jakobkallin.com/18/) och [lektion 22](https://csharp.2019.plus.jakobkallin.com/22/) i C#-kursen.

## Lektionsplan
Lektion från kl. 8:30 till kl. 16:30

* 8:30 Uppsamling från förra lektion
  * Boarding card
* 9:00 Introduktion av dagens ämnen
* 9:30 Grupp diskussion av dagens ämnen
  - Mindmaps (30 min)
  - Rotation av mindmaps 5 min per grupp (40 min)
  - Förberedelse av presentation (10 min)
  - Presentation 2 min per grupp (20 min)

Lunch 12:00 till 13:00

- 13:00 Programmeringsövning i grupp, Barista försatt
  - Finns i GitHub classroom
- 16:00 Avslutning och frågor i klassen
  - Landing card
- 16:30 Slut på lektion

## Lektionsteori

Teori, exemplar och övningar. Bör genomgås innan lektionen.
tech.io

## Viktig kurslitteratur
Detta är litteratur som är bas för denna lektion, detta bör läses innan man går på gång med lektionsteorin.

### Kod best practice
* [5 Tips for Junior C# Developers to Write Cleaner C# Code](https://programmingwithmosh.com/csharp/5-tips-for-junior-c-developers-to-write-cleaner-c-code/)
* Video (54 min): [Clean Code, Episode 1](https://cleancoders.com/episode/clean-code-episode-1/show)
* [The Boy Scout Rule](https://medium.com/@biratkirat/step-8-the-boy-scout-rule-robert-c-martin-uncle-bob-9ac839778385), se bakgrunds litteratur som innehåller hela denna artikelserie
* [Architectural principles](https://docs.microsoft.com/en-us/dotnet/standard/modern-web-apps-azure-architecture/architectural-principles)

### Naming
* [C# Coding Standards and Naming Conventions](https://www.dofactory.com/reference/csharp-coding-standards)
* [Naming - summary of Clean Code part 1](https://hashnode.com/post/clean-code-summary-part-1-naming-ciymphs8x00002w53maa5d30d)

### Automatiserad test (Enhetstest / Unittest)

* [The different types of software testing ](https://www.atlassian.com/continuous-delivery/software-testing/types-of-software-testing)

* [You Still Don’t Know How to Do Unit Testing](https://stackify.com/unit-testing-basics-best-practices/)
* [C#-Fluent Interfaces for Unit Testing](https://medium.com/@ghadeer.kenawi/c-fluent-interfaces-for-unit-testing-860d9019e21d), kanske inte den bästa artikel om precis test av Fluent API, men den bästa som jag har hittat tills vidare.

### SOLID
* [The Principles of OOD](http://butunclebob.com/ArticleS.UncleBob.PrinciplesOfOod)
* [S.O.L.I.D. Software Development, One Step at a Time](http://www.codemag.com/article/1001061)

## Bakgrunds litteratur
Detta är litteratur som är frivillig, och som kan kan används till at få en djupare insikt i ämnen i klassen.

### Automatiserad test
* [Unit testing best practices with .NET Core and .NET Standard](https://docs.microsoft.com/en-us/dotnet/core/testing/unit-testing-best-practices)

### Kod best practice
[What is clean code?](http://www.informit.com/articles/article.aspx?p=1235624&seqNum=3), från artiklen av [Grady Booch](https://twitter.com/tottinge):

> Clean code is simple and direct. Clean code reads like well-written prose. Clean code never obscures the designer's intent but rather is full of crisp abstractions and straightforward lines of control.

Martin Fowler in [Refactoring: Doing Design After the Program Runs](https://www.martinfowler.com/distributedComputing/refactoring.pdf):
> Any damn fool can write code that a computer can understand, the trick is to write code that humans can understand.

* Microsoft: [Naming Guidelines](https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/naming-guidelines)
* [Ottinger's Rules for Variable and Class Naming](http://www.maultech.com/chrislott/resources/cstyle/ottinger-naming.html)
* [Difference Between Cohesion and Coupling](https://stackoverflow.com/a/3085419/4675814)
* [OOP Concept for Beginners: What is Encapsulation](https://stackify.com/oop-concept-for-beginners-what-is-encapsulation/)
* [97 Journey Every Programmer should Accomplish](https://medium.com/@biratkirat/97-journey-every-programmer-should-accomplish-a0c53dbbfd47)

### SOLID
* [SOLID architecture principles using simple C# examples](https://www.codeproject.com/Articles/703634/SOLID-architecture-principles-using-simple-Csharp)
* [SOLID Principle with C# Example](https://www.codeproject.com/Tips/1033646/SOLID-Principle-with-Csharp-Example)
* [S.O.L.I.D: The First 5 Principles of Object Oriented Design](https://scotch.io/bar-talk/s-o-l-i-d-the-first-five-principles-of-object-oriented-design#toc-single-responsibility-principle)

**Inversion of Control (IOC) och Dependency Injection (DI):**

* Kapitel 11 - Adapting to Inversion of Control: [C# Smorgasbord (pdf)](https://cdn.filipekberg.se/fekberg-blog/csharp-smorgasbord-free/Filip_Ekberg-CSharp_Smorgasbord.pdf)
* [Kursbok](book.md): Kapitel: 10 Service configuration with dependency injection
* [Adding decorated classes to the ASP.NET Core DI container using Scrutor ](https://andrewlock.net/adding-decorated-classes-to-the-asp.net-core-di-container-using-scrutor/)

### States in code
* [Object-Oriented Design Decisions: Stateful or Stateless Classes?](https://dzone.com/articles/stateful-or-stateless-classes)
