# Database first

Måndag 16:e mars 2020

I denna lektion starter introduktionen av Entity framework. Eftersom ni redan har jobbat med databaser känns det mest naturligt att starta med den typ av migration som heter database-first, and andra variant i Entity Framework Core (EFC) är code-first. OBS EFC har inte stöd för model-first (men det är bra att vet om vad det är).

Vi försätter med trådning, denna gång med fokus på async och await.

## Lektionsplan
Lektion från kl. 8:30 till kl. 16:30

* 8:30 Uppsamling från förra lektion
  * Boarding card
  * Frågor till klassen från klassen
* 9:00 Introduktion av dagens ämnen, database first och async/await
* 9:30 Grupp diskussion av dagens ämnen
  - Mindmaps (30 min)
  - Rotation av mindmaps 5 min per grupp (40 min)
  - Förberedelse av presentation (10 min)
  - Presentation 2 min per grupp (20 min)

Lunch 12:00 till 13:00

* 13:00 Programmeringsövning i grupp, projekt 3
  * Kommer att finnas i GitHub classroom

  * CRC cards med spion

- 13:45 Mobprogramming med spion
  - 15 min per driver, check-in och push till Github
- 16:00 Avslutning och frågor i klassen
  - Landing card
- 16:30 Slut på lektion

# Lektionsteori

Teori, exemplar och övningar. Bör genomgås innan lektionen.

## Viktig kurslitteratur
Detta är litteratur som är bas för denna lektion, detta bör läses innan man går på gång med lektionsteorin.

**Database first**

* [Database Migration: What It Is and How to Do It](https://rollout.io/blog/database-migration/)
* [What is Entity Framework Core?](https://www.learnentityframeworkcore.com/#what-is-entity-framework-core)
* [Code-First vs Model-First vs Database-First: Pros and Cons](https://www.ryadel.com/en/code-first-model-first-database-first-vs-comparison-orm-asp-net-core-entity-framework-ef-data/)
* [Database First](https://entityframeworkcore.com/approach-database-first)
* [Generating a model from an existing database](https://www.learnentityframeworkcore.com/walkthroughs/existing-database), om du vill testa detta använd en egen databas från tidigare kurs eller [Adventure Works](https://github.com/microsoft/sql-server-samples/tree/master/samples/databases/adventure-works) (jag rekommendera att starta med en enkel databas)

**Trådning, async och await**

* [Getting Started with C#'s Async and Await Keywords](https://www.pluralsight.com/guides/csharp-async-await-keywords-getting-started)
* [The Ultimate Guide to Async/Await in C# and ASP.NET](https://exceptionnotfound.net/async-await-in-asp-net-csharp-ultimate-guide/)
* [How YOU can make your .NET programs more responsive with async/await in .NET Core, C# and VS Code](https://dev.to/dotnet/how-you-can-make-your-net-programs-faster-with-asynchronous-code-in-net-core-c-and-vs-code-471c)
  

## Bakgrunds litteratur
Detta är litteratur som är frivillig, och som kan kan används till at få en djupare insikt i ämnen i klassen.

* Wikipedia: [Schema migration](https://en.wikipedia.org/wiki/Schema_migration)
* Microsoft: [Async/Await - Best Practices in Asynchronous Programming](https://docs.microsoft.com/en-us/archive/msdn-magazine/2013/march/async-await-best-practices-in-asynchronous-programming)
* Stephen Cleary: [Async and Await](https://blog.stephencleary.com/2012/02/async-and-await.html) and [Happy Birthday Async](https://blog.stephencleary.com/2017/09/happy-birthday-async.html)
* Microsoft: [Asynchronous programming](https://docs.microsoft.com/en-us/dotnet/csharp/async)
* Getting Started with C#'s Async and Await Keywords, the following articles
  * [Understanding Control Flow with Async and Await in C#](https://www.pluralsight.com/guides/understand-control-flow-async-await/)
  * [Using Task.Run in Conjunction with Async/Await](https://www.pluralsight.com/guides/using-task-run-async-await)
  * [Advanced Tips for Using Task.Run With Async/Await](https://www.pluralsight.com/guides/advanced-tips-using-task-run-async-wait)
