# Övning 6: Felhantering

**Mål:** Kunna förstå vad olika felmeddelanden betyder, och hur man löser dem.

Under [Referenser](#referenser) hittar du hjälp.

Längst ned finns också [Överkurs](#Överkurs) och [Facit](#facit).

## Gör detta

1. Kör den här koden och fundera kring (a) varför felet uppstår och (b) hur du åtgärdar felet:
      ```py
      name = "John Doe"
      print(Name)
      ```
2. Kör den här koden och fundera kring (a) varför felet uppstår och (b) hur du åtgärdar felet:
      ```py
      Print("John Doe")
      ```
3. Kör den här koden och fundera kring (a) varför felet uppstår och (b) hur du åtgärdar felet:
      ```py
      for workday in ["Måndag", "Tisdag", "Onsdag", "Torsdag", "Fredag"]
          print(workday)
      ```

## Referenser

Kom ihåg:

- det måste vara `:` i slutet av raden med `for`, `if`, `def`, etc
- den kod som kommer på raden efter `:` måste indenteras med `Tab`

### Typer av fel

![](/Exercises/my-code-isnt-working.png)

## Överkurs

Läs hur man hanterar fel i koden med hjälp av [Exception Handling](https://www.learnpython.org/en/Exception_Handling).

## Facit

1. I det första exemplet måste variabelnamnet skrivas `name` (och inte `Name`) eftersom Python gör skillnad på gemener och versaler:
      ```py
      name = "John Doe"
      print(name)
      ```
2. I det andra exemplet måste print skrivas `print` (och inte `Print`) eftersom Python gör skillnad på gemener och versaler:
      ```py
      print("John Doe")
      ```
3. I det tredje exemplet saknas ett `:` på slutet av for-loopen.
      ```py
      for workday in ["Måndag", "Tisdag", "Onsdag", "Torsdag", "Fredag"]:
          print(workday)
      ```
