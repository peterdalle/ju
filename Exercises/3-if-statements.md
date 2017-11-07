# Övning 3: if-satser

**Mål:** Kontrollera vad programmet gör med hjälp av `if`, `elif` och `else`.

Under [Referenser](#referenser) hittar du hjälp.

Längst ned finns också [Överkurs](#Överkurs) och [Facit](#facit).

## Gör detta

1. Skapa två variabler:
     - variabeln `age` med din ålder
     - variabeln `friendsage` med din bästa väns ålder
2. Skriv en if-sats som jämför din väns ålder med din ålder:
     - om åldrarna är identiska, visa meddelandet `Identiska åldrar!`
     - om åldrarna skiljer sig åt, visa meddelandet `Inte identiska åldrar!`
3. Skapa variabeln `agedifference` och räkna ut skillnaden mellan din ålder och din väns ålder

## Referenser

Kom ihåg:

- det måste vara `:` i slutet av raden med `if`, `elif` och `else`
- den kod som kommer på raden efter `:` måste indenteras med `Tab`

### If-satser

Kontrollera om en person är myndig:
```py
age = 16

if age >= 18:
	print("Myndig!")
else:
	print("Inte myndig!")
```

Kontrollera om åldern är 18 eller äldre, men under 65. Därefter, kontrollera om åldern är under 18. Om inget kriterium uppfyllts, kör slutligen koden under else:
```py
if age >= 18 and age < 65:
	print("Du är i arbetsför ålder.")
elif age < 18:
	print("Du är minderårig.")
else:
	print("Du är redo för hemmet.")
```

### Jämförelser

En jämförelse som `age == 18` kallas *uttryck*. Ett uttryck ger alltid resultatet `True` eller `False`. Ett uttryck kan vara mer eller mindre komplicerade genom att kombinera jämförelser med `and` samt `or`. Men undvik att göra det allt för komplicerat för då blir det svårläst!

Jämförelse | Beskrivning | Exempel
---------- | -------------- | --------------------------
`==` | Lika med | `age == 15`
`!=` | Inte lika med | `age != 15`
`>` | Större än | `age > 15`
`<` | Mindre än | `age < 15`
`<=` | Lika med eller mindre än | `age <= 15`
`>=` | Lika med eller större än | `age >= 15`
`and` | Båda jämförelser måste vara sanna | `age > 15 and age < 45`
`or` | Minst en jämförelse måste vara sann | `age == 18 or age == 65`
`not` | Negerar jämförelse | `age > 15 and not age == 50`

```py
age = 16
married = True

if age <= 18 and married:
	print("Du ingår i ett barnäktenskap.")
elif age >= 18 and married:
	print("Du är gift och myndig.")
elif married:
	print("Du är gift.")
elif not married:
	print("Du är inte gift.")
else:
	print("Du är en odefinierbar klump.")
```

## Överkurs

Läs [Conditions](https://www.learnpython.org/en/Conditions).

## Facit

Skapa variabler:
```py
age = 25
friendsage = 23
```

Jämför variabler:
```py
if age == friendsage:
	print("Identiska åldrar!")
else:
	print("Inte identiska åldrar!")
```

Räkna ut åldersskillnad:
```py
agedifference = age - friendsage
agedifference = abs(agedifference)
print("Skillnad i år: " + str(agedifference))
```

Notera:

- `abs` är en funktion som returnerar abslut tal, vilket innebär att minustecken plockas bort.
- `str` är en funktion som konverterar talet till sträng (annars kan de inte användas tillsammans).
