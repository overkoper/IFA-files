# HTTP to:
- semantyczny język stron internetowych
+ protokół opisujący reguły komunikacji pomiędzy komputerami w sieci
+ protokół opaty na żądaniach klienta i opowiedziach serwera
- szyfrowany protokół transferu danych

# URL może zawierać:
+ parametry
+ hasło użytkownika
+ ścieżkę do pliku
+ subdomenę

# W HTTP klient:
+ wysyła żądanie
- przetwarza żądanie
- zwraca odpowiedź
+ inicjalizuje komunikację

# Stwierdzenie "HTTP jest protokołem bezstanowym":
- jest fałszywe
+ jest prawdziwe
+ oznacza, że każde żądanie jest rozpatrywane przez serwer niezależnie od innych
- każda odpowiedź serwera jest wysyłana za pomocą innego portu 

# Różnica między GET a POST polega na tym, że:
+ GET z założenia służy do pobrania zasobu, a POST do wysłania danych
- POST jest szyfrowany, a GET nie
- Dane wysłane poprzez GET są widoczne dla klienta i pośredników w komunikacji HTTP, a wysłane przez POST nie
- obie metody działają tak samo, róźnica jest nieistotna

# Odpowiedź w HTTP zazwyczaj zawiera:
+ Wersję protokołu komunikacji
- Kopię żądania
+ Nagłówek i ciało
+ Status odpowiedzi

# Kod odpowiedzi 200 oznacza, że:
- żądany zasób nie istnieje
- żądanie nie zostało zrozumiane przez serwer
- serwer odmawia podania kawy, ale może podać herbatę
+ żądanie zostało przetworzone pomyślnie

# Które z poniższych to *metody* HTTP?
- SSL
+ DELETE
+ POST
+ PUT

# Jak można wprowadzić “stan” w komunikacji po HTTP?
+ Za pomocą ciasteczek
- Wysyłać obiekt JSON z polem “state”
+ Za pomocą sesji po stronie serwera (wysyłany jest identyfikator sesji, najczęściej w nagłówkach)
- Wykonując tylko żądania typu GET

# Wysyłasz za pomocą formularza dane z rejestracji użytkownika w systemie. Imie, nazwisko, adres email, miasto. Jakiej metody HTTP (HTTP verb) użyjesz?:
- PUT
- TRACE
+ POST
- GET

# Jako klient (przeglądarka) wysyłasz żądanie do serwera. W odpowiedzi dostajesz … no właśnie, co możesz dostać? (wiele odpowiedzi)
+ ciało odpowiedzi (body) z danymi np w JSON albo z HTML-em
+ status/kod odpowiedzi (200/400/401/500 itd)
+ nagłówki
- torty (ang. birthday-cakes)

# Co daje wykorzystanie protokołu HTTPS (po SSL)?
+ przesyłana treść jest szyfrowana natomiast przesyłanie po HTTP jest zawsze jawnym tekstem
- zielona kłódka w przeglądarce chroni naszą stronę przed cyberterrorystami
- “robot” googla nie zbiera danych z naszej strony
- gwarancję, że programista wykonał wszystko zgodnie ze sztuką

# Co zwraca funkcja `fetch`?
+ obiekt Promise
- tekst odpowiedzi z serwera
- numer interwału
- nic nie zwraca

# W jakich stanach występują obiekty Promise?
+ pending, resolved, rejected
- incomplete, rejected
- then, catch
- nie da się tego określić

# Obiekt Response posiada metody, które pozwalają:
+ wyciągnąć dane tekstowe z odpowiedzi z serwera
+ odczytać kod HTTP odpowiedzi z serwera
- anulować żądanie
- zamknąć okno przeglądarki

# Co zwraca metoda `.then` obiektu Promise?
+ nowy obiekt Promise
- tablicę znaków
- wartość, którą zwróci funkcja przekazana jako argument wywołania do metody `.then`
- nic nie zwraca

# Do czego służy metoda `.catch` obiektu Promise?
+ do przechwycenia błędu, który wystąpi w trakcie działania tego obiektu
- do zatrzymania łańcucha obietnic
- do zatrzymania żądania HTTP
- bez niej nie zadziała metoda `.then`

# Jeżeli chciałbym, żeby mój fragment kodu uruchomił się po pomyślnym rozwiązaniu się 2 niezależnych obiektów Promise, to powinienem użyć:
+ `Promise.all`
- `Promise.every`
- `setTimeout` z długością interwału równą `0`
- `.then` na jednym z tych obiektów, a na drugim `.catch`

# Żeby z tablicy `[1, 2, 3]` otrzymać tablicę `[1, 3]` użyję:
+ filter
- map
- slice
- some

# Żeby z tablicy `[1, 2, 3]` otrzymać tablicę `[2, 4, 6]` użyję:
+ map
- filter
- some
- every

# Żeby z tablicy `[1, 2, 3]` otrzymać wartość `true` użyję:
- map
- filter
+ every
+ some

# Metoda `Array.prototype.forEach` zwraca:
+ undefined
- tablicę
- liczbę
- null

# Żeby z obiektu `{ x: 10, y: 20 }` otrzymać tablicę `['x', 'y']` użyję:
+ Object.keys
- Object.values
- Object.entries
- Object.create

# Żeby z obiektu `{ x: 10, y: 20 }` otrzymać tablicę `[10, 20]` użyję:
- Object.keys
+ Object.values
- Object.entries
- Object.create

# Kolejność atrybutów w obiekcie jest:
+ niegwarantowana
- stała
- alfabetyczna
- numeryczna

# Metoda `push` z prototypu Array zwraca:
+ długość tablicy po wykonaniu `push`
- długość tablicy przed wywołaniem `push`
- nową tablicę
- obiekt

# Żeby zmodyfikować tablicę, na którą wskazuje referencja ze zmiennej `var x = [1, 2, 3]` w taki sposób, że nie będzie już posiadała elementu `2` i jej długość skróci się o 1 użyję:
+ splice
- slice
- filter
- some

# Funkcje czyste:
+ nie modyfikują zmiennych zdefiniowanych poza ich ciałem
+ zwracają wartość
+ bazują swoje obliczenia na argumentach wywołania, a nie na zmiennych zdefiniowanych poza funkcją
- nie zwracają wartości

# Funkcje wyższego rzędu (Higher Order Functions):
+ mogą przyjmować funkcję jako argument
+ mogą zwracać funkcję jako wartość
- mają ponad 100 linii kodu
+ to m.in. `map`, `filter` i `reduce`

# Prototyp:
+ to obiekt
+ to obiekt, do którego odwołuje się inny obiekt, jeżeli zapytamy go o wartość atrybutu, którego nie posiada
+ mechanizm pozwalający na ponowne użycie pewnych fragmentów kodu bez rezerwowania dodatkowych obszarów pamięci
- to to samo co kontekst wywołania

# Wartość dostępna pod słowem kluczowym `this`:
+ wskazuje na tzw. kontekst wywołania funkcji
+ zależy od sposobu wywołania funkcji
+ zawsze wskazuje na obiekt
- może zostać ustawiona z użyciem funkcji `apply`, nawet jeżeli funkcja, na której wywołamy tę metodę jest zrobiona z użyciem metody `bind`

# NodeJS jest:
+ platformą, na której możemy uruchamiać skrypty w języku JavaScript
- biblioteką JavaScript
- funkcją
- niezbędny do uruchomienia aplikacji w Reakcie

# Webpack:
+ pozwala połączyć wiele plików z kodem JavaScript w jeden
+ pozwala zautomatyzować żmudne zadania front-endowe
- jest jedynym narzędziem do automatyzacji zadań dostępnym w NodeJS
- wymaga uprzedniego zainstalowania biblioteki `react` w systemie

# ESLint:
+ pozwala w automatyczny sposób wyeliminować niektóre złe praktyki w kodzie
- potrafi zbudować projekt, łącząc wiele plików w jeden
- przetwarza pliki SCSS na CSS
- jest niezbędny do działania narzędzia `Webpack`

# Zmienne utworzone za pomocą słowa kluczowego `let`:
- posiadają scope leksykalny (funkcyjny)
+ posiadają scope blokowy
- nie mogą zmieniać swojej wartości
+ posiadają taki sam scope jak `const`

# Czy mogę zmienić wartość atrybutu obiektu zapisanego w stałej `const`?
+ tak
- nie
- tak, ale tylko jeżeli zastąpię cały obiekt
- tak, ale tylko jeżeli użyję metody Object.create

# Metoda `Object.assign`:
- zwraca nowy obiekt
+ przyjmuje dowolną liczbę argumentów
+ przyjmuje tylko argumenty będące obiektami
- przyjmuje argumenty dowolnego typu

# Funkcje strzałkowe (arrow function):
+ są anonimowe
+ nie mogą pełnić roli konstruktora
+ nie posiadają własnego `this` - pożyczają go z miejsca, gdzie zostały zdefiniowane
+ nie posiadają własnego `arguments`

# Konstrukcja `let { a, b, c } = { a: 10, b: 20 }`:
+ utworzy 3 zmienne
+ sprawi, że w scope pojawi się zmienna `c` o wartości `undefined`
- utworzy obiekt z atrybutami `a`, `b` oraz `c`
- jest niepoprawna

# Jeżeli mam zmienne `let x = 10; let y = 20;` to zapis: `var foo = { x, y }`:
+ utworzy obiekt z atrybutami `x: 10` oraz `y: 20`
- wywoła błąd
- sprawi, że w zmiennej `foo` pojawi się wartość `undefined`
+ nazywa się `shorthand object notation`

# Jeżeli mam zmienne `let x = 10; let y = 20;` to zapis: `[x, y] = [y, x]`:
+ zamieni wartości przechowywane w tych zmiennych
+ sprawi, że zmienna `x` będzie posiadała wartość `20`
- jest niepoprawny składniowo
+ utworzy nową tablicę
