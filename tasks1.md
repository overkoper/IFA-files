# Git jest systemem kontroli wersji:
+ rozproszonym
- scentralizowanym
- lokalnym
- płatnym

# Github to:
+ serwis www, umożliwiający przechowywanie wersjonowanego kodu
- element gita
- firma, która strzowyła gita
- aplikacja, którą możemy zainstalować w systemie Linux

# Żeby utrzowyć lokalną kopię zdalnego repozytorium, jeżeli znam jego adres muszę użyć komendy:
+ git clone
- git fetch
- git init
- git push

# Commit w gicie posiada informacje o:
+ wcześniejszym commicie
+ autorze
- systemie operacyjnym autora
- późniejszym commicie

# Merge to:
+ operacja połączenia dwóch gałęzi w repozytorium
+ operacja, której rezultat zależy od gałęzi, na którą wskazuje HEAD
- operacja nieodwracalna
- operacja wykonywana przy komendzie `git fetch`

# Nową gałąź w repozytorium mogę utworzyć używając polecenia:
+ `git checkout -b`
+ `git branch`
- `git status`
- `git stash`

# Operacja `git pull`:
+ może wywołać konflikt
+ składa się z operacji `fetch` oraz `merge`
- tworzy nowe repozytorium
- wymaga uprawnień administratora

# Scrum:
+ jest frameworkiem
- służy do zarządzania pracą tylko i wyłącznie w projektach informatycznych
- sprawdza się w każdym projekcie informatycznym
- narzuca zespołowi szacowanie z użyciem kart

# Jedną z metod szacowanie w Scrumie jest wykorzystanie jednostki `story point`:
+ jest ona relatywną jednostką określającą pracochłonność zadania
- określa ona czas potrzebny na zrobienie zadania
- doświadczone zespoły w danym sprincie realizują więcej `story pointów` niż początkujące
- określa ona trudność zadania

# Scrum master:
+ pilnuje zasad Scruma
- zarządza zespołem i przydziela programistom zadania
- jest zastępcą Product Ownera i może podejmować decyzje dotyczące wizji produktu
- zarządza Product Backlogiem

# Semantyczny kod `HTML` to taki, w którym:
+ użyte znaczniki nadają dodatkowe znaczenie treści
- mamy zachowane wcięcia w kodzie
- użyte znaczniki zmieniają wygląd dokumentu
- nazwy klas są pisane w konwencji camelCase

# Znacznik `<img>`:
+ jest znacznikiem samozamykającym się
+ potrzebuje atrybutu `src`, żeby przeglądarka załadowała plik graficzny
+ domyślnie posiada `display: inline`
- domyślnie posiada `display: block`
- domyślnie posiada `display: inline-block`

# Prawdą jest, że:
+ arkusze stylów należy podłączać w sekcji `<head>`, a skrypty pod koniec sekcji `<body>`
- arkusze stylów muszą być podłączone w sekcji `<head>`, żeby działały
- pliki z rozszerzeniem `.js` zawsze ładowane są przez przeglądarkę jako ostatnie
- plik w języku HTML musi posiadać sekcję `<body>`

# Precyzyjność selektorów jest zależna od użytych w nich:
+ nazw klas
+ nazw id
+ nazw znaczników HTML
- nazw pseudoklas
- nazw pseudoelementów

# Jeżeli precyzyjność selektorów w pliku CSS jest jednakowa i dotyczą one tego samego elementu to:
+ wyższy priorytet mają deklaracje występujące bliżej końca pliku
+ bloki deklaracji ulegają połączeniu - deklaracje wcześniejsze zostają nadpisane przez deklaracje z późniejszego bloku, dotyczące tej samej właściwości 
- bloki deklaracji całkowicie się nadpisują - żadne deklaracje z tego występującego wcześniej nie zostaną zastosowane
- deklaracje bliżej początku pliku decydują całkowicie o ostatecznym wyglądzie elementu

# Przy `display: flex;` właściwość `justify-content` odpowiada za:
+ rozłożenie elementów w linii poziomej
+ rozłożenie elementów w linii pionowej, jeżeli użyjemy `flex-direction: column;`
- wysokość elementów
- szerokość elementów

# Przy `display: flex;` właściwość `align-self` zadziała, jeżeli:
+ element nadrzędny posiada właściwość `display: flex;`
- element posiada właściwość `display: flex;`
- element posiada `z-index` większe niż `0`
- w elemencie nadrzędnym nie występuje tekst

# Media queries służą do:
+ aplikowania deklaracji CSS w zależności od cech ekranu
- wyszukiwania elementów, które nie mieszczą się w obrębie swojego nadrzędnego elementu
- zwiększenia prędkości pobierania plików CSS z sieci
- opóźnienia ładowania plików JS do momentu, gdy CSS załaduje się w całości

# Jeżeli element posiada `position: absolute;` to jego położenie możemy ustawić:
+ za pomocą właściwości `left` oraz `right`
+ względem najbliższego przodka posiadające `position: relative`
+ względem najbliższego przodka posiadającego `position: absolute`
- względem dolnej krawędzi ekranu

# Kod CSS można osadzić na stronie, korzystając ze znaczników:
+ style
+ link
- css
- meta

# Stany, w jakich może znaleźć się hiperłącze (znacznik `a`) należy stylować w kolejności:
+ link, visited, hover, active
- link, hover, visited, active
- link, mouseover, mouseleave, click
- enter, leave, hover, disabled

# Właściwość `display: none`:
+ ukrywa element i sprawia, że layout strony budowany jest tak jakby go nie było
- usuwa element i sprawia, że nie możemy go znaleźć za pomocą skryptu JS
- jest błędna - `display` może przyjmować tylko wartości: `block`, `flex`, `inline` i `grid`
- nie działa w Internet Explorerze 11

# Selektor `.fizz .buzz` wyszukuje elementy, które:
+ posiadają klasę `buzz` i wśród swoich przodków posiadają element z klasą `fizz`
- posiadają klasy `buzz` i `fizz`
- posiadają klasę `buzz` lub klasę `fizz`

# Wartości typu prostego w momencie przepisywania ich z jednej zmiennej do drugiej:
+ są kopiowane
- są przekazywane przez referencję
- nie można wykonać na nich takiej operacji
- są usuwane z pierwszej zmiennej

# Jeżeli odwołamy się do atrybutu, który nie istnieje w danym obiekcie, to:
+ interpreter JS spróbuje odnaleźć jego wartość w prototypie tego obiektu
- wyrzuci błąd
- zwróci zawsze `null`
- zwróci zawsze `undefined`

# Zmienne w JS (zadeklarowane słowem kluczowym `var`) mają zakres widoczności (scope):
+ funkcyjny
+ leksykalny
- blokowy
- nieokreślony

# Funkcje w JS:
+ mogą być przechowywane w zmiennych
+ mogą być przekazywane jako wartości argumentów wywołania innych funkcji
- nie mogą być zwracane jako wartość z innych funkcji
- są typami prostymi

# Jeżeli wykonany zostanie kod `x = 10`, to:
+ interpreter utworzy tzw. zmienną globalną
+ obiekt `window` otrzyma atrybut `x` o wartości 10
- przeglądarka wyrzuci błąd
- zmienna `x` otrzyma wartość `10` o ile wcześniej użyliśmy dyrektywy `use strict`

# Wartość, do której funkcja utworzona słowem kluczowym `function` ma dostęp pod słowem kluczowym `this`:
+ zawsze jest obiektem
+ jest określana w momencie wywołania funkcji
- jest określana w momencie zdefiniowania funkcji
- może zostać przypisana do funkcji na zawsze z użyciem metody `apply` lub `call`

# Która z metod do operacji na DOM zwraca wartość, na której możemy wykonać metodę `forEach`?
+ document.querySelectorAll
- document.querySelector
- document.getElementById
- document.getElementsByClassName

# Jeżeli utworzę element DOM z użyciem funkcji `document.createElement`, to:
+ żeby go zobaczyć będę musiał go przyczepić do elementu DOM już istniejącego w dokumencie
+ będę mógł modyfikować jego cechy (klasę, tekst itp.) nawet jeżeli nie jest wstawiony do dokumentu
- zobaczę go tylko, jeżeli przyczepię go do dowolnego innego elementu utworzonego za pomocą `document.createElement`
- zobaczę go od razu na stronie 

# Funkcja `setTimeout` zwraca:
+ liczbę
- funkcję
- ciąg znaków
- tablicę

# Operator `typeof` dla liczba zwraca:
+ ciąg znaków
- wartość "float"
- wartość "string"
- wartość typu "number"

# CSS najlepiej dołączać do HTML:
- w znacznikach <style> bezpośrednio pod fragmentami kodu HTML, którego dotyczą
- bezpośrednio do elementów html, np. <p style="">
+ w head strony za pomocą <link>
- na dole strony, tuż przed zamknięciem tagu <body>

# Normalize.css:
- służy do wyzerowania wszystkich marginesów i paddingów
+ niweluje różnice pomiędzy domyślnymi stylami przeglądarek
+ zazwyczaj jest pomocny
- jest zbędny, powoduje tylko problemy

# Prawidłowy zapis zgodny z BEM dla "nieaktywnego przycisku submit w formularzu" to:
+ `<input class="form__submit form__submit--disabled" />`
- `<input class="form__form__submit--disabled" />`
- `<input class="form--submit--disabled" />`
- `<input class="form_submit form_submit-disabled" />`

# Framework CSS:
- jest preprocesorem CSS
+ pozwala na budowanie layoutu strony w oparciu o dodawanie klas CSS do elementu
- pozwala na przechowywanie danych użytkownika w przeglądarce
+ może zostać nawet przez początkującego programistę

# Kolejność wyświetlania elementów na stronie możemy w CSS zmienić za pomocą własności:
+ flex-direction
+ order
+ float
+ position

# Mobile first to:
+ projektowanie i pisanie kodu najpierw dla urządzeń mobilnych, a dopiero później dla desktopów
+ korzystanie głównie z media-queries z regułami typu "min-width..."
- umieszczeniu w treści HTML na górze treści dla urządzeń mobilnych, a poniżej dla desktopów

# W media-queries możemy odwołać się do:
+ szerokości okna przeglądarki
+ wysokości okna przeglądarki
+ orientacji ekranu
- systemu operacyjnego urządzenia

# Wskaż poprawny sposób zapisu media-queries wewnątrz pliku CSS
+ `@media (min-width: 800px)`
+ `@media screen and (min-width: 800px)`
+ `@media all and (min-width: 800px) and (max-width: 900px)`
- `<link rel="stylesheet" media="screen and (min-width: 800px)" href="tablet.css"` />

# Relatywne jednostki to:
+ em
- px
+ rem
+ %

# Aby wybrany element HTML został kontener grid CSS:
- musimy dodać do elementu klasę "grid-container"
+ musimy elementowi kontera przypisać własność display: grid lub display: inline-grid
- musi to być element `<grid>`
- musimy elementowi kontera przypisać własność display: block, a jego dzieciom display: grid

# Które z poniższych uznajemy za "dobrą praktykę" w pisaniu kodu?
+ Rozdzielenie kodu HTML, CSS i JS
+ Dodawanie atrybutów alt do obrazków
- Wyświetlanie wszystkich obrazków za pomocą CSS (background-image)
- Załacznie zewnętrznych skryptów JS na początku kodu HTML

# Komentarze w kodzie
- są bezwzględnie wymagane
- są szczególnie przydatne w środowisku produkcyjnym
+ są zbędne jeśli kod sam się wyjaśnia
- dodawane są tylko na końcu kodu

# Element <head>:
- może być nagłówkiem całej strony, ale też sekcji lub artykułu
+ jest bezpośrednim dzieckiem elementu html
- zawiera np. nawigację i h1
+ zawiera title

# Atrybut "lang":
- określa język załączonego skryptu (np. JS, PHP)
- jest dodawany wyłącznie do znacznika html
+ może zostać użyty na dowolnym znaczniku HTML
+ wskazuje w jakim języku jest treść znacznika do którego został przypisany

# Jeśli chcemy, aby pole w formularzu było wymagane, to nadajemy mu
- klasę "required"
- atrybut "formvalidate"
- placeholder
+ atrybut "required"

# Co to znaczy, że nasz kod zawiera semantyczny HTML?
- wygląd elementów dostosowany jest do ich zawartości
- opisujemy zawartość elementów za pomocą klas CSS
+ znaczniki html odzwierciedlają swoją zawartość
+ treść dokumentu posiada logiczną strukturę

# Zdjęcie autora strony powinno w kodzie zostać umieszczone:
- w HTML wewnątrz tagu <author>
- jako tło za pomocą CSS
+ w HTML za pomocą <img>
- w <head> strony

# W JS `boolean`, `number`, `string` to:
- operatory 
- typy zmiennych
+ typu danych
- typy funkcji

# `typeof([1,2,3,4])` to:
- number
- undefined
- array
+ object

# Która z poniższych nazw zmiennych jest **niepoprawna gramatycznie**?
- secondElement
+ 2element
+ element 2
- element_second

# Wyrażenie `"kot2" + (parseInt("29.7") + 1)` zwróci:
- string "kot231"
- string "kot2301"
+ string "kot230"
- liczbę 32

# Zaznacz prawdziwe stwierdzenia
- let o tej samej nazwie i zakresie można deklarować wielokrotnie
+ const o tej samej nazwie i zakresie można deklarować tylko raz
+ let o tej samej nazwie i zakresie można wielokrotnie przypisać różne wartości
- const o tej samej nazwie i zakresie można wielokrotnie przypisać różne wartości

# Zapis `(a === b)`:
- przypisuje wartości a wartość b
- sprawdza wyłącznie czy a i b są tego samego typu
+ porównuje typ i wartość a i b
+ zwróci true jeśli typ lub wartość a i b są zgodne

# Co zwraca i usuwa ostatni element tablicy "array"?
- array.last()
- array.shift()
- array.push()
+ array.pop()

# Funkcja w JS służy do:
+ uporządkowania kodu poprzez podzielenie go na logiczne struktury
+ umożliwienia wielokrotnego wywoływanie tego samego fragmentu kodu
+ ograniczenia zakresu działania zmiennych (var)
- rozszerzenia funkcjonalności przeglądarki

# Parametry funkcji:
+ mogą mieć domyślne wartości
+ służą do przekazania zmiennych do funkcji
- mogą być wyłącznie stringami
- każda funkcja musi posiadać co najmniej jeden parametr

# Polecenie `return` w funkcji:
+ zwraca wartość
- powoduje wykonanie kodu funkcji od początku
- wraca do poprzedniej linii kodu
+ przerywa działanie funkcji

# DOM to:
+ reprezentacja HTML w przeglądarce
- Data Oriented Model
+ drzewo elementów o uporządkowanej strukturze
- model deklarujący wygląd elementów

# Na stronie mamy 5 elementów z klasą "someClass". Aby wybrać wszystkie należy skorzystać z:
- `document.querySelectorAll('#someClass')`
- `document.querySelector('.someClass')`
+ `document.getElementsByClassName('someClass')`
+ `document.querySelectorAll('.someClass')`

# someButton.click() spowoduje:
- dodanie event listenera oczekującego na zdarzenie click na elemencie "someButton"
+ wywołanie kliknięcia na elemencie "someButton"
- zliczanie kliknięć w element "someButton"
- błąd

# Aby wywołać funkcję cyklicznie, np. co sekundę należy skorzystać z:
- pętli while... do..
- setTimeout
+ setInterval
- jQuery

# localStorage:
- jest czyszczone po zamknięciu okna lub karty przeglądarki
- służy do przechowania danych użytkownika na serwerze
+ służy do przechowania danych w przeglądarce
+ może zostać wyczyszczone przez użytkownika

# W jaki sposób możemy odczytać wartość o kluczu "surname" przechowywaną w sessionStorage?
+ `sessionStorage.surname`
- `localStorage.surname`
- `localStorage.getItem('surname')`
+ `sessionStorage.getItem('surname')`

# Jak można zmienić kolor tekstu wszystkich akapitów z klasą "info" na czerwony?
- `document.querySelectorAll('.info').color = 'red'`
- `document.querySelectorAll('.info').style.color = 'red'`
- `document.querySelector('.info').style.color = 'red'`
+ dodając CSS `.info { color: red }`