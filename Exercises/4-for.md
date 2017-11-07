# Övning 4: for-loopar

**Mål:** Hantera for-loopar för att styra hur en lista ska presenteras på skärmen.

Under [Referenser](#referenser) hittar du hjälp.

Längst ned finns också [Överkurs](#Överkurs) och [Facit](#facit).

## Gör detta

1. Skapa variabeln `interests` med en lista med fem av dina intressen
2. Skriv en for-loop som skriver ut varje intresse från listan
3. Skriv en if-sats inuti for-loopen som kontrollerar om något av intressena är `python` eller `programmering`

## Referenser

Kom ihåg:

- det måste vara `:` i slutet av raden med `for`
- den kod som kommer på raden efter `:` måste indenteras med `Tab`

### Listor

Skapa lista med tal eller strängar:
```py
numbers = [1, 2, 3]
interests = ["python", "knyppling", "monopol"]
```

### For

Gå igenom lista rad för rad (`i` är en variabel som skapas automatiskt, du kan döpa den till vad som helst):
```py
for i in numbers:
	print(i)
```

Plocka ut första och andra värdet i listan med hjälp av listans index:
```py
print(interests[0]) # Första
print(interests[1]) # Andra
```

Ett annat sätt att gå igenom listan är med hjälp av listans index. Men först måste man ta reda på hur många rader det finns i listan med hjälp av `len()` som betyder length.
```py
num_interests = len(interests)

for i in num_interests:
	print(interests[i])
```

## Överkurs

Om man använder gemener och versaler kan det vara bra att endast jämföra med gemener (notera egenskapen `.lower()` på variabeln hobby).
```py
interests = ["PYTHON", "KNYPPLING", "MONOPOL"]

for hobby in interets:
	if hobby.lower() == "python":
		print("Yay! Du gillar Python!")
	else:
		print("Du HATAR Python!")
```

Läs [List Comprehension](https://www.learnpython.org/en/List_Comprehensions).

## Facit

Skapa variabler:
```py
interests = ["python", "knyppling", "monopol", "ishockey", "x-games"]
```

Gå igenom lista och leta efter "python", "programmering" eller "programmera":
```py
for hobby in interets:
	if hobby == "python" or hobby == "programmering" or hobby == "programmera":
		print("Yay! Du gillar Python eller programmering!")
	else:
		print("Varför HATAR du Python eller programmering?")
```
