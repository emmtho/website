---
author: mos
category: php
revision:
  "2015-08-27": (A, mos) Första utgåvan i samband med kursen htmlphp version 2.
updated: "2015-08-27 14:11:28"
created: "2015-01-28 14:27:13"
...
PHP labb 5, PDO och SQLite
==================================

Laboration för att träna PHP, PDO och SQL med databasen SQLite.

<!--more-->



Förkunskaper {#forkunskaper}
-----------------------

Du har installerat en labbmiljö där du kan köra PHP, motsvarande [labbmiljön för kursen htmlphp](htmlphp/labbmiljo)".

Du har tillgång till kommandot `dbwebb` och du har clonat kursrepot för htmlphp-kursen.



Hämta labben {#hamta}
-----------------------

Labben automatgenereras för dig. Gör så här för att checka ut din personliga labb.

Gå till din kurskatalog i terminalen och kör följande kommando.

```bash
# Flytta till kurskatalogen
dbwebb create lab5
```

Materialet till labben skapas nu och sparas i din kurskatalog `me/kmom04/lab5` enligt följande.

| Fil                | Innehåll                                                              |
|--------------------|-----------------------------------------------------------------------|
| `instruction.html` | Beskrivning av labben och de uppgifter som skall göras.               |
| `answer.php`       | Här skall du skriva din kod för att lösa respektive uppgift i labben. |
| `CDbwebb.php`      | Används av `answer.php` för att testa din labb.                        |
| `answer.json`      | Används av `CDbwebb.php` för att testa din labb.                        |

Öppna filen `instruction.html` i en webbläsare och läs igenom de uppgifter som labben omfattar.

Öppna filen `answer.php` i din texteditor och koda ihop svaren på uppgifterna.

Du kan testa dina lösningar genom att köra programmet `answer.php` i din webbläsare, via din lokala webbserver.



Krav {#krav}
-----------------------

1. Gör de uppgifter som finns i labben `instruction.html`.

2. Skriv dina lösningar, på rätt plats, i filen `answer.php`.

3. Testkör din labb genom att köra filen `answer.php`.

4. Ladda upp, validera och publicera labben genom att göra följande kommando i kurskatalogen i terminalen.

```bash
# Flytta till kurskatalogen
dbwebb publish lab5
```

Rätta eventuella fel som dyker upp och publisera igen. När det ser grönt ut så är du klar. 



Extrauppgift {#extra}
-----------------------

Det finns ingen extra uppgift.



Tips från coachen {#tips}
-----------------------

Debugga och felsök genom att skriva ut variablernas olika innehåll med `echo`, `print_r()` eller `vardump()`.

Validera ofta. Så slipper du en massa valideringsfel i slutet av övningen.

Lycka till och hojta till i forumet om du behöver hjälp!



