# lessons
## Lekcja 17.03.2024
1. [yay](https://yay.boo/)

## Lekcja 05.03.2024
1. Wymagania co do strony:
    1. co najmniej 10 różnych znaczników (tagów)
    2. co najmniej 2 linki
    3. co najmniej jedna podstrona
    4. co najmniej jeden obrazek
    5. ciekawa treść
    6. estetyczny wygląd
    7. co najmniej jedna tabela lub lista
2. Wymagania dodatkowe:
   1. element animowany
   2. użycie java scriptu do manipulowania zawartością strony
   3. własna treść (a nie tylko kopiowana z internetu)

## Lekcja 27.02.2024
1. Konto google
    1. Bezpieczeństwo haseł
2. Gemini
    1. Co ciekawego zwiedzić w Krakowie?
    2. Czemu ten html nie działa?
    3. Jakie potrawy mogę zrobić z X?
    4. Nie mam pomysłu o czym zrobić stronę internetową, masz jakiś pomysł?
    5. Zakładam zespół k-pop, masz pomysł na nazwę?
    6. Napisz mi bajkę o smokach i świniach.
4. ChatGPT
5. Kontynuujemy robienie strony

3 kolumny na stronie:
```
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Create three equal columns that floats next to each other */
.column {
  float: left;
  width: 33.33%;
  padding: 10px;
  height: 300px; /* Should be removed. Only for demonstration */
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

img {
    width: 100%;
    height: 100%;
    object-fit: contain
}
</style>
</head>
<body>

<h2>Three Equal Columns</h2>

<div class="row">
  <div class="column" style="background-color:#aaa; overflow:hidden">
    <h2>Column 1</h2>
    <p>Some text..dfsadfasdfdasdfasdfasdfasdfasfasdfasdfasd</p>
      <img src="https://sdpl.b-cdn.net/17158-large_default/obrazek-obrazki-10paz.jpg">

  </div>
  <div class="column" style="background-color:#bbb;">
    <h2>Column 2</h2>
    <p>Some text..</p>
  </div>
  <div class="column" style="background-color:#ccc;">
    <h2>Column 3</h2>
    <p>Some text..</p>
  </div>
</div>

</body>
</html>

```

## Lekcja 06.02.2024
1. Przypomnienie css
2. Przyporządkuj właściwości do odpowiednich znaczników tak aby strona cyceron.html wyglądała jak poniżej.
```
<style>
    hmm co tutaj {
        max-width: 600px;
        padding: 20px;
        margin: auto;
        background: wheat;
    }
    a co tutaj{
        color: sienna;
    }
    ciekawe co tutaj {
        color: steelblue;
    }
    jaki to moze być znacznik {
        font-style: italic;
    }
    coś wylosuję i zadziała {
        display: block;
        margin-left: auto;
        margin-right: auto;
        width: 50%;
    }
    dziwne u mnie działa {
        border: solid;
        border-radius: 25px;;
    }
</style>
```
3. Tłumaczenia słów dla ułatwienia


| angielski  | polski              |
|------------|---------------------|
| width      | szerokość           |
| padding    | margines wewnętrzny |
| max        | maksymalny          |
| background | tło                 |
| color      | kolor               |
| font       | czcionka            |
| border     | ramka               |
| margin     | margines zewnętrzny |
| radius     | promień             |
   
<img width="1284" alt="obraz" src="https://github.com/Anteklantek/lessons/assets/12928011/4adbbfa0-40f9-4815-a740-44931cbacff3">


## Lekcja 30.01.2024
1. Przypomnienie
    2.  Struktura dokumentu
    3.  Najważniejsze znaczniki
        4.  html
        5.  head
        6.  title
        7.  body
        8.  p
        9.  img
        10.  h1
        11.  a
        12.  style
    4. CSS selektory
   

## 7.11.23 Lekcja #2 scratch

### Excel przypomnienie
1. Przeciąganie
1. Formuły
1. Wypełnienie błyskawiczne
1. Wykresy
1. Tabele - filtrowanie i sortowanie

### Scratch: znajdowanie maksimum w zbiorze
https://scratch.mit.edu/projects/919921399/  
Skończyłeś? Poćwicz na keybr.com

## Lekcja 14.11.23 cwiczenie excel
1. Pobierz i wykonaj: https://docs.google.com/spreadsheets/d/1eKan25YonkKEbvuyJJWJDa6YEpsWdPMT/edit?usp=drive_link&ouid=116711237374671818765&rtpof=true&sd=true
2. Wgraj plik na https://easyupload.io/
3. https://forms.gle/FpPuUnWfi6tqp4dw9

## Lekcja 21.11.23
1. Iteracja
2. Pętla
3. Podwójna pętla
4. Tabliczka mnożenia

## Lekcja 28.11.23
1. Dokończenie poprzednich zadań
2. Python https://www.online-python.com/
3. Drukowanie
4. Zmienne
5. Pętle
6. Listy

## Lekcja 5.12.23
1. Python przypomnienie
2. Input z konsoli
3. Sumowanie inputu użytkownika

## Lekcja 12.12.23
https://www.w3schools.com/python/trypython.asp?filename=demo_compiler
https://programiz.pro/ide/python
1. Python przypomnienie
2. Losowanie liczb
# Polecenie dla zaawansowanych
1. Spróbuj napisać program w którym w pętli będziesz zgadywać liczbę wylosowaną przez komputer.
3. Wylosuj liczbę przy pomocy komendy randint(0,10) i zapisz do zmiennej wylosowana. Pamiętaj aby na górze dodać import: from random import randint
3. W pętli while pobieraj input użytkownika while True: wprowadzona_liczba = int(input())
3. Następnie sprawdź czy wprowadzona_liczba == wylosowana przy pomocy if <warunek>:
3. Jeśli tak to przerwij pętle. Użyj słowa kluczowego break; (bez nawiasu na końcu)
3. Poinformuj użytkownika, że udało mu się zgadnąć liczbę.
3. Jeśli to Ci się uda spróbuj zaimplementować grę w kamień papier nożyczki.
3. Niech 1 oznacza papier, 2 kamień a 3 nożyczki
3. Niech komputer wylosuje liczbę ozaczającą przedmiot
3. Następnie pobierz liczbę od użytkownika
3. Za pomocą paru if-ów sprawdź kto wygrał.
3. Powodzenia!

## Lekcja 19.12.23
### Zadania
#### Łatwe
1. Wypisz nieparzyste liczby od 1 do 1000.
2. Wypisz liczby podzielne przez 3 od 200 do 500.
3. Wypisz kwadraty liczb od 1 do 20
4. Wypisz resztę z dzielenia przez 11 z liczb od 30 do 50
5. Wypisz sumę 3 liczb wprowadzonych przez użytkownika
6. Wypisz "tak, jest parzysta" jeśli liczba wprowadzona przez uzytkownika jest parzysta
7. Wypisz "tak, jest mniejsza niż 10" jeśli liczba wprowadzona przez użytkownika jest mniesza niż 10
8. Wypisz pole prostokąta o bokach wprowadzonych przez użytkownika.
9. Wypisz mniejszą liczbę z dwóch liczb wprowadzonych przez użytkownika
10. Wypisz wiek użytkownika po wprowadzeniu przez niego daty.
#### Trudne
1. Wypisz choinkę z gwiazdek o wysokości wprowadzonej przezy użytkownika

```
      *
    ****
 *********
   ******
************
```
2. Wypisz sumę liczb wprowadzonych przez użytkownika. 0 kończy wprowadzanie kolejnych liczb.
3. Wypisz najmniejszą liczbę z listy zdefiniowanej w zmiennej "lista". Niech kod działa po modyfikacji listy.
5. Napisz grę w zgadywanie liczby wylosowane przez uzytkownika. Niech program co turę wypisuje czy użytkownik podał większą czy mniejszą liczbę.
6. Wypisz sumę "ważoną" liczb z listy zdefiniowanej w kodzie w zmiennej lista. Nie licz nieparzystych liczb. Parzyste liczby licz podwójnie. Niech kod działa po modyfikacji listy.

#### Pomoce dydatktyczne
1. gdzie kodzimy: www.online-python.com
1. zmienne: https://kt.academy/pl/article/py-zmienne
1. pętla for i while: https://kt.academy/pl/article/py-for
1. reszta z dzielenia: https://kt.academy/pl/article/py-wartosci
1. input użytkownika: https://pracownik.kul.pl/files/115165/public/awrspii/python/python_wczytywanie_if.pdf
1. listy: https://kt.academy/pl/article/py-listy
2. if, czyli jak zrobić coś w zależności od warunku: https://kt.academy/pl/article/py-warunki

## Lekcja 02.01.2024
1. Wszystkiego dobrego w nowym roku
2. Język html
3. Podstawowa struktura html:
```
<!DOCTYPE html>
<html>
<head>
    <title>Tytuł</title>
</head>
<body>
   <!-- zawartość -->
</body>
</html>

```
4. Podstawowe tagi: https://kompan.pl/blog/podstawowe-znaczniki-html/
5. Zrób stronę z przynajmniej jednym wyliczeniem, jednym zdjęciem, jednym linkiem i jednym paragrafem.

## Lekcja 16.01.2024
1. Style css
```
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
<style>
body {
  max-width: 600px;
  padding: 20px;
  margin: auto;
}
img {
max-width: 100%;
}
p {
font: Italian;
}
</style>
</head>
<body>
<marquee>WOW đźŻ </marquee>
 <div class="topnav">
  <a href="helmut.html">Helmut</a>
  <a href="tramino.html">Tramino</a>
</div> 
<h1>Wow tramwaje</h1>
<p>Szybko i bezpiecznie</p>
<a href="https://www.mpk.poznan.pl/pojazdy/tramwaje-liniowe/">Składy w poznaniu</a> 
<img src="https://upload.wikimedia.org/wikipedia/commons/1/1b/113_Silesian_Interurbans%2C_Citadis_car%2C_Bytom.jpg" alt="Italian Trulli">
</body>
</html> 
```
2. Menu
```
 <div class="topnav">
  <a href="helmut.html">Helmut</a>
  <a href="tramino.html">Tramino</a>
</div> 
```
3. [yay](https://yay.boo/)
4. Selektory: klasy, znacznika, konkretnego elementu

