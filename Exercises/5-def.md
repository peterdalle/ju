# Övning 5: Funktioner

**Mål:** Skapa funktioner för att bygga kodblock som kan ta emot, ändra och returnera ett värde.

Under [Referenser](#referenser) hittar du hjälp.

Längst ned finns också [Överkurs](#Överkurs) och [Facit](#facit).

## Gör detta

1. Skapa en funktion som heter `isprogrammer`
      - funktionen ska ta emot en variabel som heter `interests` som är en lista
      - funktionen ska kontrollera om interests innehåller `programmering` eller `python`
      - funktionen ska returnera `True` om interests innehåller programmering eller python, annars ska funktionen returnera `False`
2. Skapa variabeln `myinterests` som en lista med fem av dina intressen
3. Gör sedan en if-sats där du kallar på funktionen

## Referenser

Kom ihåg:

- det måste vara `:` i slutet av raden med `def`
- den kod som kommer på raden efter `:` måste indenteras med `Tab`

### Funktioner

Skapa funktion med namnet `hello`:
```py
def hello():
	print("Hello World!")
```

Kalla på funktionen `hello`:
```py
hello()
```

Skapa funktion som tar emot variabel och returnerar variabel:
```py
def hello(name, age):
	return("Hej {0}! Du är {1} år gammal.".format(name, age))
```

Kalla på funktionen `hello`:
```py
message = hello("John Doe", 25)
print(message)
```

Skapa funktion som kontrollerar om en ålder är under 18 år:
```py
def isunderaged(age):
	if age < 18:
		return(True)
	else:
		return(False)
```

Kalla på funktionen:
```py
print(isunderaged(15))
```

## Överkurs

Läs [Functions](https://www.learnpython.org/en/Functions).

Läs också [Modules and Packages](https://www.learnpython.org/en/Modules_and_Packages) om hur du använder funktioner som andra har skapat. Dessa funktioner förpackas ofta i så kallade *paket* eller *bibliotek*.

## Facit

Skapa funktion:
```py
def isprogrammer(interests):
	for hobby in interests:
		if hobby == "python" or hobby == "programmering" or hobby == "programmera":
			return(True)
		else:
			return(False)
```

Skapa lista med intressen och kalla på funktion:
```py
myinterests = ["python", "knyppling", "monopol", "ishockey", "x-games"]

if isprogrammer(myinterests):
	print("Du är programmerare.")
else:
	print("Du är inte programmerare.")
```
