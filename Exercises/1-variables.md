# Övning 1: Variabler

**Mål:** Skapa, ändra och kombinera variabler.

Under [Referenser](#referenser) hittar du hjälp.

Längst ned finns också [Överkurs](#Överkurs) och [Facit](#facit).

## Gör detta

1. Skapa tre variabler:
     - en variabel som heter `age` med din ålder
     - en variabel som heter `firstname` med ditt förnamn
     - en variabel som heter `lastname` med ditt efternamn
2. Visa variablernas innehåll på skärmen
3. Skapa två nya variabler:
     - skapa variabeln `name` genom att slå ihop `firstname` och `lastname`
     - skapa variabeln `initials` med dina initialer från `firstname` och `lastname`
4. Visa de nya variablernas innehåll på skärmen

## Referenser

### Skriv ut text på skärmen

Skriv ut valfri text på skärmen:
```py
print("Hello World!")
```

### Typer av variabler

Ger en variabel ett värde:
```py
name = "John"      # Textsträng (engelska: string)
age = 25           # Heltal (int)
height = 175.3     # Decimaltal (float)
married = False    # Boolean (boolean)
```

### Strängar

Slå ihop två variabler:
```py
nyvariabel = variabel1 + variabel2
```

Använda citattecken i en sträng:
```py
nickname = 'John "The Ripper" Doe'
```

Skriva en sträng på flera rader:
```py
biography = """This is my complete biography.
I will write at least
three lines and that's it.
"""
```

### Listor

Listor börjar alltid på 0.

```py
# En lista över intressen.
interests = ["python", "journalistik", "skriva"]

# Skriv ut listans innehåll genom att använda index, alltså [0], [1], och så vidare.
print("Dina tre intressen är:")
print(interests[0])
print(interests[1])
print(interests[2])
```

## Överkurs

En dictionary innehåller par av typen nyckel/värde. Detta är ett effektivt sätt att gruppera information som hör ihop. Fördelen är inte bara att informationen är samlad i en och samma variabel (`person` i det här fallet), utan också att dictionary kan innehålla komplexa datastrukturer. Notera också att en dictionarty ser ut precis som [JSON](https://sv.wikipedia.org/wiki/JSON).
```py
person = { 'name': "John Doe",
           'age': 25,
           'height': 175.3
         }

print(person["name"])
print(person["age"])
```

I stället för att slå ihop mängder med variabler, och därefter visa dem på skärmen, kan man använda `.format(name, age, length)` för att separera variablerna från texten som ska presenteras. Detta gör man för att koden blir mer lättläst. Ordningen på variablerna representeras sedan av ett nummer. `{0}` är första variabeln, `{1}` är andra variabeln, och så vidare:
```py
name = "John"
age = 25
height = 175.3

print("{0} är {1} år gammal och är {2} cm lång".format(name, age, length))
```

## Facit

Skapa variabler:
```py
age = 25
firstname = "John"
lastname = "Doe"
name = firstname + " " + lastname
initials = firstname[0] + lastname[0]
```

Skriv ut variablernas innehåll genom att bara skriva deras namn:
```py
age
firstname
lastname
name
initials
```

Eller skriv ut variablernas innehåll med `print(variabel)` (rekommenderas):
```py
print(age)
print(firstname)
print(lastname)
print(name)
print(initials)
```
