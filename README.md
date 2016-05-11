# boxplot
## 1. Wizja
### Funkcjonalność podstawowa
Komponent ma za zadanie wyświetlać dane statystyczne w postaci wykresu pudełkowego w czasie rzeczywistym.
### Wygląd
Komponent nie jest samodzielnym oknem. Można dodać go w dowolnym miejscu w dowolnym Pane. Po dodaniu jego rozmiar jest niezmienny. Jeśli chcemy zbudować okno z samym komponentem, zamiast umieszczać go w panelu zdobywamy panel poprzez metodę getPane(). Ilość pudełek może rosnąć, jedynym ograniczeniem jest czytelność wykresów, o którą komponent dba rzucając RuntimeException, jeśli pudełka musiałyby być już za wąskie.
### Komunikacja
Komunikacja z komponentem nastąpi poprzez wykorzystanie metod wystawionego API.
### Format danych wejściowych
Dane wejściowe to obiekty typu double.
### Funkcjonalności dodatkowe
- konfigurowalny tryb usuwania nadliczbowych danych

## 2. Dokumentacja
### API
Dostępne do wykorzystania metody opisane są w folderze "doc" w formie javadoca

### Technologia
Wykorzystane zostały biblioteki JavaFX wchodzące w skład JDK 1.8.