# JU1203 Datajournalistik: Python-programmering

*Denna sida innehåller Python-kod och Jupyter Notebooks för kursen JU1203 Fördjupad journalistik: Datajournalistik (9 hp), en del i [journalistprogrammet på JMG, Göteborgs universitet](https://jmg.gu.se/utbildning/journalistutbildning/kandidatprogrammet).*

[Python](https://sv.wikipedia.org/wiki/Python_(programspr%C3%A5k)) är ett populärt programmeringsspråk som kan användas för att skapa hemsidor och program. Python är väldigt flexibelt och är enkelt att använda jämfört med andra språk.

Målet är att lära sig grunderna i programmering i allmänhet och Python i synnerhet. Du behöver ingen förkunskap i programmering sedan tidigare, utan vi börjar från grunden.

***Ta med egen dator!*** 

Läs guiden [Lär dig programmera med Python på Ludo.co](https://www.ludu.co/course/programmera-med-python) (steg 2-6: från variabler/datatyper till funktioner) innan föreläsningarna/workshop så att du kan ställa frågor när vi sedan testar i praktiken. Vi kommer att gå igenom alla delar i guiden.

Kontakta [Peter M. Dahlgren](http://jmg.gu.se/om-institutionen/personal?userId=xdpete) om du har några frågor.

## Översikt

Vad vi kommer att göra, bortsett från föreläsningarna:

1. Installera [Anaconda](https://www.continuum.io/downloads/) (välj Python version 3+) som innehåller Python och Jupyter Notebooks. ***Ladda gärna ned Anaconda innan föreläsningen!***
2. Lära känna Jupyter Notebooks.
3. Göra övningarna.
4. Styra vad som händer i programmet med `if`-satser och `for`-loopar.
5. Skriva funktioner med `def`, vilket delar upp programmet i delar.
6. Avsluta med ett större projekt såsom en nyhetsrobot eller scraping av hemsidor.

## Övningar

Övning | Mål
:---------------- | :---------------------------------------
[Övning 1: Variabler](/Exercises/1-variables.md) | Skapa, ändra och kombinera variabler.
[Övning 2: Strängar](/Exercises/2-strings.md) | Manipulera text i strängar.
[Övning 3: If-satser](/Exercises/3-if-statements.md) | Kontrollera vad programmet gör med hjälp av if, elif och else.
[Övning 4: For-loopar](/Exercises/4-for.md) | Hantera for-loopar för att styra hur en lista ska presenteras på skärmen.
[Övning 5: Funktioner (def)](/Exercises/5-def.md) | Skapa funktioner för att bygga kodblock som kan ta emot, ändra och returnera ett värde.
[Övning 6: Felhantering](/Exercises/6-errors.md) | Kunna förstå vad olika felmeddelanden betyder, och hur man löser dem.

## Projekt

Notebook | Beskrivning
:---------------- | :---------------------------------------
[Nyhetsrobot för filmrecension](/newsrobot-moviereview.ipynb) | Web scraping av filmdatabasen IMDb för att sedan enklare kunna skriva en filmrecension.
[Nyhetsbevakning av polisens händelser](/polisen.ipynb) | Web scraping av alla polisens händelser som sedan sparas till en CSV-fil som kan öppnas i Excel.

## Jupyter Notebooks - tangentbordsgenvägar

- **`Ctrl+Enter`** = kör cell
- **`ESC`** = gå ur en cell
- **`Tab`** = autocomplete
- **`a`** = infoga cell ovan
- **`b`** = infoga cell under
- **`dd`** = radera cell

Se också [28 Jupyter Notebook tips, tricks and shortcuts](https://www.dataquest.io/blog/jupyter-notebook-tips-tricks-shortcuts/).

# Lär dig mer om Python

- In [References](https://github.com/peterdalle/mij/tree/master/References) you'll find example code snippets
- Read [Learn more Python](https://github.com/peterdalle/mij/blob/master/learn-more-python.md) to find documentation, help and other Python resources

Om nyhetsrobotar:

- [Sirens nya robot [Robotea] bevakar från ax till limpa](https://www.medievarlden.se/2017/06/sirens-nya-robot-bevakar-fran-ax-till-limpa/), som även är nominerad till [stora journalistpriset 2017](https://www.aftonbladet.se/nyheter/a/6rAp0/andrev-walden-nomineras-till-stora-journalistpriset)
- [The First News Report on the L.A. Earthquake Was Written by a Robot](http://www.slate.com/blogs/future_tense/2014/03/17/quakebot_los_angeles_times_robot_journalist_writes_article_on_la_earthquake.html)
- [“Robot Journalism”: The damage done by a metaphor](http://datadrivenjournalism.net/news_and_analysis/robot_journalism_the_damage_done_by_a_metaphor)
