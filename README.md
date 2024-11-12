# Symulator_Lotto

## Opis

Program symuluje grę w LOTTO, w której gracz typuje 6 liczb z zakresu 1–49. Celem jest jak najdokładniejsze odgadnięcie losowanych liczb. Nagrodą w grze są trafienia za 3, 4, 5 lub 6 poprawnych liczb.

## Zasady działania programu

1. Program zapyta użytkownika o 6 unikalnych liczb z zakresu 1–49.
2. Podczas wprowadzania liczb, program sprawdzi:
   - czy wprowadzone dane są liczbą,
   - czy liczba nie była wcześniej podana,
   - czy liczba mieści się w zakresie 1–49.
3. Po wprowadzeniu wszystkich 6 liczb:
   - Program posortuje liczby gracza rosnąco i wyświetli je.
4. Następnie program wylosuje 6 liczb z zakresu 1–49 i również wyświetli je na ekranie.
5. Program poinformuje gracza, ile liczb zostało trafionych.

## Jak uruchomić program

1. Upewnij się, że masz zainstalowanego Python 3.x
2. Pobierz repozytorium Symulator_Lotto
3. W terminalu przejdź do lokalizacji pliku i uruchom program poleceniem:
   python3 app.py