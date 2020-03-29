# The ludo game - avslutande projekt

I detta projekt ska ni implementera ett fia spel (Ludo på engelska). Spelet ska vara en .net core konsol applikation.

Det ska gå att spela spelet via en konsol applikation, två till fyra spelare vid samma dator.

Koden ska vara uppdelat i en konsol applikation och en class librarary som innehåller all logik, låt oss kalla det vår spelmotor / game engine.

Spelet ska spara i en databas (med code first och Entity Framework), så att det går att ta fram historik på alla tidigare spel. Om applikationen skulle stängas ner, ska det gå att komma tillbaka in i spelet.

# Programmering

Kod ska ligga i mappen **src**, varje team får enbart ha en kodbas!!

Se till att skåpa unit tests för spelet.

## Spelmotor (GameEngine)

Spelmotorn styra alla regler i spelet och kollar t.ex. om en spelpjäs får flyttas, om en spelar har vunnit, den initiala uppställning av alla spelpjäser på brädet, vilken spelar som är den nästa, hur en tärning ska bete sig, etc.

Implementera spelmotorn i ett separat klass bibliotek.

En instans av spelmotorn innehåller staten av ett helt spel, det skall vara möjligt att initialisera spelet med en given state, t.ek. om ska kunna spara och inläsa ett spel.

# Dokumentation

Skriv [user stories](https://www.mountaingoatsoftware.com/agile/user-stories) (i docs mappen), och starta inte koda något innan in har skrivet minst 3 user stories, men helst så det täcker hela fia spelet, men se hela tiden till att lägga till fler user stories.

Om ni använder någon externa källor (båda kod och annat) ange dom i dokumentationen.

Dokumentation ska skrivas med markdown (.md), ni väljer själv om ni vill skriva på svenska eller engelska, markdown filerna placeras i **docs** mappen.

# Betygsättning
Detta projekt är avslutande och bär störste delen av ert betyg för denna kurs.

Tillsammans med projektet ska skåpas en video som beskriver projektet.

## Koden
Ni kan göra så många branches baserat på *master* som ni önskar. När projektet är slut är det innehållet av master på ert **GitHub**-repo som räknas.

## Element i bedömning
* Dokumentaion
* En (och endast en) Visual Studio solution placerat i mappen Src
* Solutionen ska beså av minst två projekt:
  * En .NET Core console-application
  * Class Library med en game engine
* Koden kompilera och det går att köra projektet lokalt
* All logik som rör spelet, även kast av tärning, är placerat i spelmotorn
* Dokumentation av hur spelets element, klasser och funktionalitet
  * Ska finnas i Documentation-mappen
* Spelet ska spara i en databas (med code first och Entity Framework)
* Det ska gå att skåpa ett eller fler spel
* Det ska gå att försätta spela ett inte avslutat eksisterende spel
* Unit tests

* Async kod

## Frivilliga element (kan göras som extra)

* Dokument databas
* Prestanda optimering
* Datatjänst
* **MORE TO COME, kom med förslag**
