# Analiza Przyczyn Wypadków w NYC

## Opis projektu

Projekt ten skupia się na analizie danych dotyczących wypadków drogowych w Nowym Jorku. Celem jest zrozumienie głównych przyczyn wypadków i przedstawienie ich w formie graficznej.

## Proces Pracy z Danymi

### 1. Wyczyszczenie i Uporządkowanie Danych

Projekt rozpoczyna się od szczegółowego procesu czyszczenia danych, który obejmuje:
- Usunięcie niekompletnych lub nieprawidłowych wpisów
- Normalizacja formatów danych
- Wypełnienie brakujących wartości, gdy to możliwe
- Usunięcie duplikatów
- Optymalizacja, poprzez konwersję kolumn obiektowych na kategorie w celu poprawy zużycia pamięci
- Usunięcie zbędnych błędów poprzez stosowanie .copy() i zmiany niektórych wierszy

### 2. Zapisanie Nowej Bazy Danych

Po uporządkowaniu danych, tworzona jest nowa baza danych, która zawiera tylko czyste i przetworzone informacje. Ta baza danych jest następnie wykorzystywana do dalszej analizy i wizualizacji.

### 3. Przedstawienie Graficzne

W ramach projektu przygotowywane są wizualizacje, które pomagają zrozumieć dane. Przykłady wizualizacji to:
- Wykresy słupkowe przedstawiające najczęstsze przyczyny wypadków
- Mapy cieplne pokazujące obszary z największą liczbą wypadków
- Wykresy liniowe ilustrujące trendy w czasie
- Poprawiony plik z wizualizacją dla najniebezpieczniejszych czynników wypadków w każdej z dzielnic NY, uwzględniający wiele kolumn i informację o najniebezpieczniejszej przyczynie

## Wnioski

Na podstawie przeprowadzonej analizy i wizualizacji, projekt dostarcza wniosków dotyczących głównych przyczyn wypadków w Nowym Jorku. Te informacje mogą być wykorzystane przez odpowiednie służby do poprawy bezpieczeństwa na drogach. 

Dodatkowe poprawki:
- Kolumna 'borough' została znormalizowana, aby wszystkie wartości były zapisane z wielkich liter (str.upper())
- Nowy plik z wyczyszczonymi danymi został zapisany w formacie .csv.gz, aby zmniejszyć jego rozmiar i przyspieszyć działanie
- Usunięcie niepotrzebnych tabel w punktach, gdzie pokazywano jedynie jedną przyczynę wypadku