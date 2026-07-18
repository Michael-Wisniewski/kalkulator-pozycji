# Kalkulator Pozycji Futures

Prosty kalkulator pozycji dla rynku kontraktów futures.

Aplikacja pomaga szybko obliczyć parametry transakcji na podstawie ceny wejścia, poziomu Stop Loss, ryzyka oraz dźwigni.

## Funkcje

- Obliczanie wielkości pozycji (Position Size)
- Obliczanie wymaganego marginu
- Szacowanie ceny likwidacji
- Obliczanie odległości do likwidacji
- Obliczanie szerokości Stop Lossa
- Częściowy Take Profit
- Obsługa pozycji LONG i SHORT
- Zapis ustawień w pamięci przeglądarki
- Responsywny interfejs dla komputerów i urządzeń mobilnych

## Walidacja i bezpieczeństwo

Kalkulator nie tylko wykonuje obliczenia, ale również wykrywa najczęstsze błędy podczas przygotowywania zleceń futures.

Przed otwarciem pozycji sprawdzane są między innymi:

- poprawność wszystkich danych wejściowych,
- poprawne zakresy wartości (ryzyko, dźwignia, Take Profit itp.),
- automatyczne wykrywanie kierunku pozycji (LONG/SHORT),
- wystarczające saldo futures do otwarcia pozycji,
- czy likwidacja nie nastąpi przed osiągnięciem Stop Lossa,
- poprawność parametrów częściowego zamknięcia pozycji (Close Quantity),
- blokowanie kopiowania wyników w przypadku wykrycia niebezpiecznej konfiguracji.

Dzięki temu kalkulator pomaga uniknąć typowych błędów, takich jak otwarcie zbyt dużej pozycji, niewystarczający margin czy zastosowanie zbyt wysokiej dźwigni prowadzącej do likwidacji przed Stop Lossem.

## Uruchomienie

`https://Michael-Wisniewski.github.io/kalkulator-pozycji/`

Lub lokalnie:

Pobierz plik `index.html` i otwórz go w przeglądarce.

> Uwaga: podczas otwierania kalkulatora bezpośrednio z pamięci telefonu niektóre mobilne przeglądarki mogą ograniczać dostęp do schowka. W takim przypadku przyciski kopiowania zostaną automatycznie ukryte — wyniki nadal można zaznaczyć i skopiować ręcznie.

## Prywatność

Kalkulator działa w całości po stronie przeglądarki.

- nie wysyła żadnych danych do Internetu,
- nie wykorzystuje plików cookies,
- nie gromadzi informacji o użytkowniku.

## Zastrzeżenie

Kalkulator ma charakter pomocniczy i nie stanowi porady inwestycyjnej.

Wyniki należy traktować jako wartości orientacyjne i przed otwarciem pozycji zweryfikować je na platformie transakcyjnej.

Autor nie ponosi odpowiedzialności za decyzje inwestycyjne podjęte na podstawie obliczeń kalkulatora.

## Licencja

Projekt udostępniony na licencji MIT.