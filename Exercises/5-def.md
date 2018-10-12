# Övning 5: Funktioner

**Mål:** Konvertera temperaturer genom att bygga en funktion som kan ta emot, ändra och returnera ett värde.

Under [Referenser](#referenser) hittar du hjälp.

Längst ned finns också [Överkurs](#Överkurs) och [Facit](#facit).

## Gör detta

1. Skapa en funktion som heter `tofahrenheit`
2. Se till att funktionen kan ta emot en variabel som heter `celsius`
3. Funktionen ska konvertera Celsius till Fahrenheit och sedan returnera Fahrenheit
4. Kontrollera sedan vad du får för Fahrenheit när du skriver in 21 grader Celsius - se [tabell med celsius/fahrenheit](https://www.almanac.com/content/temperature-conversion)
4. Gör sedan det omvända (Fahrenheit till Celsius) med en funktion som heter `tocelsius`

Ekvationer:

- Fahrenheit = Celsius * 9/5 + 32
- Celsius = (Fahrenheit - 32) * 5/9

## Referenser

Kom ihåg:

- namn på funktionen måste ha parenteser, exempelvis `funktionsnamn()`
- det måste vara `:` i slutet av raden med `def`
- den kod som kommer på raden efter `:` måste indenteras med `Tab`
- för att returnera ett värde eller variabel använder du exempelvis `return(42)` eller `return(variabelnamn)`

### Funktioner

Skapa funktion med namnet `hello`:
```py
def sayhello():
	print("Hello World!")
```

Kalla på funktionen `hello`:
```py
sayhello()
```

Skapa funktion som tar emot variabel och returnerar variabel:
```py
def sayhello(name):
	return("Hej {0}!".format(name))
```

Kalla på funktionen `hello`:
```py
sayhello("John Doe")
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

Skapa funktion för att konvertera Celsius till Fahrenheit:
```py
def tofahrenheit(celsius):
	fahrenheit = celsius * 9/5 + 32
	return(fahrenheit)
```

Samt Fahrenheit till Celsius:
```py
def tocelsius(fahrenheit):
	celsius = (fahrenheit - 32) * 5/9
	return(celsius)
```
