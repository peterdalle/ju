# Programmeringsuppgifter i Python

Här finner du tre uppgifter du ska lösa i Python. De börjar enkelt och blir svårare och svårare. Tanken med uppgifterna är att du ska få bekanta dig med olika delar av Python och på så vis bygga upp en kunskap som gör att du kan bryta ned stora komplexa problem i mindre, enklare problem. Ta hjälp av kursmaterialet på https://github.com/peterdalle/ju och av varandra! Vi diskuterar lösningarna i slutet av veckan så du behöver inte lämna in uppgiften.

## Uppgift 1: Räkna antal ord

**Mål:** att bekanta dig med Pythons dokumentation och att hitta bra sajter när du googlar efter hjälp.

Hur många ord innehåller textsträngen `text` nedan med ett citat från filosofen John Stuart Mill? Det är ett problem som vi enkelt kan lösa genom att räkna för hand (svaret är 41). 

```py
text = "If all mankind minus one, were of one opinion, and only" \
" one person were of contrary opinion, mankind would be no more" \
" justified in silencing that one person, than he, if he had" \
" the power, would be justified in silencing mankind."
```

Men hur många ord innehåller textsträngen om du försöker skriva ett program som låter Python räkna? Tänk på hur orden separeras, och fundera på om du kan dela textsträngen på de ställen där orden separeras.

Hjälp på vägen:

- Läs om funktionen [`split()`](https://docs.python.org/3.7/library/stdtypes.html#str.split) och [`len()`](https://docs.python.org/3.7/library/functions.html?highlight=len#len>) i Pythons dokumentation
- Googla på "split string python"

## Uppgift 2: Räkna antal specifika ord

**Mål:** att kunna bryta ned ett komplext problem i mindre, enklare delar.

Om du har lyckats lösa första uppgiften bör du nu också ha möjligheten att leta efter specifika ord. Hur många gånger förekommer ordet "justified"?  <!-- Svar: 2 gånger -->

Hjälp på vägen:

- Använd `for` och `if` för att gå igenom en lista med ord och se om varje ord matchar ett specifikt ord
- Gör gemener med [`lower()`](https://docs.python.org/3.7/library/stdtypes.html#str.lower)
- Gör versaler med [`upper()`](https://docs.python.org/3.7/library/stdtypes.html#str.upper)

## Uppgift 3: Gör en sökfunktion för ord

**Mål:** att skapa en funktion som kan återanvändas.

Nu har du förhoppningsvis lyckats räkna hur många gånger ett specifikt ord förekommer. Nu är nästa uppgift att förpacka det i en funktion som du kan återanvända.

Gör en funktion som heter `countword()` som tar emot två variabler. En variabel kallad `word` (ordet som du vill söka efter) och en variabel kallad `text` (texten som ska sökas igenom). Se till att funktionen returnerar ett heltal för hur många gånger ordet förekommer i textsträngen. Alltså, om ordet inte förekommer så returneras 0, om ordet förekommer en gång, returneras 1 etc.

1. Hur många gånger förekommer ordet "mankind"?
2. Hur många gånger förekommer ordet "opinion"?

Hjälp på vägen:

- Läs om [`replace() ` på Stack Overflow](https://stackoverflow.com/questions/9452108/how-to-use-string-replace-in-python-3-x), en webbplats för frågor om programmering
- Googla på "replace string python"
