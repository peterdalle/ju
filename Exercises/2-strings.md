# Övning 2: Strängar

**Mål:** Manipulera text i strängar.

Under [Referenser](#referenser) hittar du hjälp.

Längst ned finns också [Överkurs](#Överkurs) och [Facit](#facit).

## Gör detta

1. Skapa variablen `text` med innehållet `Python är ett programmeringsspråk för otrevliga människor`.
2. Byt ut `otrevliga` mot `smarta`. Men spara det i en ny variabel som heter `truth`.
3. Gör om texten till versaler.

## Referenser

Kom ihåg:

- strängvariabler inleds och avslutas med `"`
- strängvariabler över flera rader inleds och avslutas med `"""`
- strängvariabler kan innehålla citattecken, men måste inledas och avslutas med `'` i stället.

### Skapa och läs delar av strängar

Skapa en sträng:
```py
text = "The quick brown fox jumps over the lazy dog"
```

Ta ut första tecknet i strängen:
```py
print(text[0])
```

Visa tre första tecknen i strängen (på position 0-2):
```py
print(text[0:2])
```

Ta reda på hur många tecken strängen är:
```py
print(len(text))
```

Konvertera ett tal till en sträng med `str`:
```py
age = 25
print("Du är " + str(age) + " år gammal.")
```

### Manipulera strängar

Byt ut *fox* mot *journalist* i strängen:
```py
print(text.replace("fox", "journalist"))
```

Ta bort text från strängen:
```py
print(text.replace("The quick brown fox ", ""))
```

Gör om text till gemener, versaler eller inledande versal för varje ord:
```py
print(text.lower())
print(text.upper())
print(text.title())
```

Hitta ordet *quick* i strängen och returnera positionen för första tecknet av ordet:
```py
print(text.find("quick"))
```

Försök hitta ord ord som inte finns i strängen. Vad händer då? Då returneras -1:
```py
print(text.find("journalism"))
```

## Överkurs

Läs mer om [Basic String Operations](https://www.learnpython.org/en/Basic_String_Operations).

## Facit

```py
text = "Python är ett programmeringsspråk för otrevliga människor"
truth = text.replace("otrevliga", "smarta")
truth = truth.upper()
print(truth)
```
