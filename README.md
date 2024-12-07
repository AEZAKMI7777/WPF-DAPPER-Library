# Library

System powinien dawać możliwość zarządzania książkami w bibliotece - aplikacja do obsługi przez osoby pracujące w bibliotece. Użytkownik może: dodawać/usuwać/modyfikować/wyświetlać: kategorie książek, oraz same książki.
Wymagane jest, aby każda książka była przypisana do minimum jednej kategorii (np. Stephen King - "IT" <-> Horror).
W systemie musi się znaleźć również obsługa wypożyczeń książek (nowa klasa, nowa tabela, etc.), z informacją jaka książka, od kiedy, do kiedy, nazwiskiem osoby wypożyczającej i numerem telefonu tej osoby.

Wymagania programu:

Program będzie zawierał, okna lub widoki w obrębie jednego okna
- przesyłanie informacji między view modelami
- Entity Fremwork do obsługi bazy danych
- Tabele w bazie
- automatyczne tworzenie bazy danych + tabeli
- obsługa kolekcji
- sorotowanie ksiązek po kategorii

Potencjalne ryzyka: 
- Brak testów:
Niewystarczające testy (jednostkowe, integracyjne) mogą skutkować niezauważeniem błędów, szczególnie w przesyłaniu danych między widokami.

- Problemy z rozszerzalnością:
Brak elastyczności w projekcie może utrudnić dodawanie nowych funkcji w przyszłości (np. obsługi więcej niż jednej biblioteki).

- Problemy z bazą danych. 
