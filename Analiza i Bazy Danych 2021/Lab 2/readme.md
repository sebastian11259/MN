# Ćwiczenie 1 - TIER protocol i tidy data

Celem ćwiczenia jest pobranie i uporządkowanie przydzielonego zbioru danych zgodnie z protokołem TIER i zasadami "tidy data".

Dla przypomnienia:

- W uporządkowanych danych:
  - Każda zmienna tworzy kolumnę.
  - Każda obserwacja tworzy rząd.
  - Każdy typ jednostki obserwacyjnej tworzy tabelę.

-  [TIER Protocol](https://www.projecttier.org/tier-protocol/)

 Mamy 5 zbiorów danych.

 1. weather.txt - dane pogodowe.
 3. tb.csv - dane o gruźlicy w różnych grupach pacjentów (tabela koduje jednocześnie informacje o wieku i o płci w kolumnach i zawiera dużo pustych miejsc)
 4. billboard.csv - notowania billboardu (w tabeli jest data wejścia na listę i ranking w kolejnych tygodniach, nie da się wprost odczytać rankingu w danym tygodniu kalendarzowym i jest dużo pustych miejsc)
 1. drinks.csv Dane i informacje: https://fivethirtyeight.com/features/dear-mona-followup-where-do-people-drink-the-most-beer-wine-and-spirits/
 4. earthquake_data.csv https://fivethirtyeight.com/features/the-rock-isnt-alone-lots-of-people-are-worried-about-the-big-one/ (należy zmienić nazwy kolumn i przygotować tabelę łączącą wiek, płeć i odpowiedź na pytanie "Do you think the "Big One" will occur in your lifetime?"



Numer swojego datasetu uzyskujemy ze wzoru **(N mod 6) +1**, gdzie N to liczba liter w nazwisku.