---
author: mos
category: python
revision:
  "2017-06-14": (D, efo) Uppdaterade till ny kursstruktur med funktioner i kmom03.
  "2015-08-25": (C, mos) Uppdaterade till dbwebb v2.
  "2014-08-27": (B, mos) Gneomgången och uppdaterad inför kursstart.
  "2014-07-03": (A, mos) Första utgåvan i samband med kursen python.
updated: "2015-08-25 12:49:49"
created: "2014-07-03 06:38:04"
...
Python med funktioner
==================================

Vi ska i denna laboration träna på funktioner, argument och returvärden i Python.

<!--more-->


Förkunskaper {#forkunskaper}
-----------------------

Du har jobbat igenom artikeln "[Installera en labbmiljö till Python](installera-en-labbmiljo-till-python)" och du kan grundläggande konstruktioner i Python.



Hämta labben {#hamta}
-----------------------

Labben automatgenereras för dig. Gör så här för att checka ut din personliga labb.

Gå till din kurskatalog i terminalen.

```bash
# Flytta till kurskatalogen
dbwebb create lab3
```

Materialet till labben ligger nu i din kurskatalog i `me/kmom03/lab3` enligt följande.

| Fil                | Innehåll                                                              |
|--------------------|-----------------------------------------------------------------------|
| `instruction.html` | Beskrivning av labben och de uppgifter som skall göras, öppna och läs via en webbläsare.               |
| `answer.py`        | Här skall du skriva din kod för att lösa respektive uppgift i labben. |
| `Dbwebb.py`        | Används av `answer.py` för att testa din labb.                        |
| `.answer.json`      | Används av `Dbwebb.py` för att testa din labb.                        |

Öppna filen `instruction.html` i en webbläsare och läs igenom de uppgifter som labben omfattar.

Öppna filen `answer.py` i din texteditor och koda ihop svaren på uppgifterna.

Du kan testa dina lösningar genom att köra programmet `answer.py` som ett vanligt Python-program. Labben rättar sig själv.

```python
$ python3 answer.py
```

Glöm inte att validera ofta, då slipper du bekymmer i slutet.

Hamnar du i bekymmer så finns det ledtrådar som du kan få. Du aktiverar ledtrådarna för respektive uppgift i filen `answer.py`.

Du behöver göra ett visst antal uppgifter för att bli godkänd på labben. Sedan finns extra uppgifter du kan utföra om du så väljer. [Varför skall jag göra extrauppgiftena](kurser/faq/varfor-gora-extra-uppgifter)?

[YOUTUBE src=7pPjt__amAM width=630 caption="Kenneth visar hur man kommer igång med labbarna."]



Krav {#krav}
-----------------------

1. Gör de uppgifter som finns i labben `instruction.html`.

2. Skriv dina lösningar, på rätt plats, i filen `answer.py`.

3. Testkör din labb genom att köra filen `answer.py`.

4. Ladda upp och validera labben genom att göra följande kommando i kurskatalogen i terminalen.

```bash
# Flytta till kurskatalogen
dbwebb validate lab3
```

Rätta eventuella fel som dyker upp och validera igen. När det ser grönt ut så är du klar.



Extrauppgift {#extra}
-----------------------

Det finns ingen extra uppgift.



Tips från coachen {#tips}
-----------------------

Debugga och felsök genom att skriva ut variablernas olika innehåll med `print()`.

Testa att köra labben i debuggern och stega igenom hur den validerar dina svar.

Validera ofta. Så slipper du en massa valideringsfel i slutet av övningen.

Lycka till och hojta till i forumet om du behöver hjälp!
