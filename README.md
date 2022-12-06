# Task 1 *ZAPOZNANIE Z PRACĄ QA* :wrench:
## Subtask 1
**5** punktów ( *szklanka do połowy pełna :grinning:* )
### Subtask 3
Hej jestem Ewa :upside_down_face: Obecnie pracuję w administracji biurowej tzw. budżetówce. Początkowo nie myślałam o zmianie pracy na branżę IT jednak po paru latach pracy na systemach państwowych (okropnie przestarzałych) stwierdziłam, że mogę mój potencjał wykorzystać znacznie lepiej. Wybrałam ścieżkę QA ponieważ uważam, że mam ku temu najlepsze umiejętności: 
- jestem zdecydowanie psują- uwierzcie mi, potrafiłabym zepsuć czarną skrzynię gdyby tylko trafiła w moje ręce;
- uwielbiam majsterkowanie- wymiana kolanka w zlewie to dla nie problem, lubię grzebać tak aby dogrzebać się do najgłębiej ukrytych problemów, zadawać pytania i szukać na nie odpowiedzi, poznawać nowe;
- z wykształcenia: *KRYMINALIST(Y)KA*- studia wymagały pokładów cierpliwości, spostrzegawczości, kreatywności oraz odwagi, w życiu testera jak w życiu technika kryminalistyki - żaden, nawet najmniejszy ślad (bug), nie umknie mojej uwadze;
- jeśli chodzi o umiejętności komunikacyjne- lata współpracy z klientami (praca w sklepie odzieżowym, na infolinii, obsługa petentów) nauczyły mnie w sposób spokojny i zrównoważony tłumaczyć gdzie leży problem tak aby obie strony były zadowolone;
- *C I E R P L I W O Ś Ć*- to moje drugie imie. Jestem kwiatem lotosu na tafli jeziora i wiem co mówię. Jak już wyżej wspomniałam praca na systemach państwowych wymaga wiele cierpliwości. Przeciążenia systemu, error 404, ładowanie danych, które trwa w nieskończoność, bycie cierpliwym i opanowanym to klucz. 

*Wyzwanie QA to wstęp do mojego przebranżowienia. Chciałabym mieć możliwość rozwoju i samorealizacji, nie ukrywam, że możliwość pracy zdalnej z dowolnego miejsca na ziemi brzmi ciekawie. Samodzielnie zaczęłam się uczyć JavaScript, robię to jednak w wolnej chwili i wiem, że zajmie mi to jeszcze sporo czasu ale wiem też, że jest to przydatna wiedza w zakresie QA. Mam nadzieję, że to wyzwanie otworzy mi drzwi no nowego, lepszego, pełnego wyzwań życia.*
#### Subtask 4
Aplikacja służy do zaprezentowania danego gracza, jego umiejętności oraz osiągnięć. 
W aplikacji znajduję się zakładka, w której możemy dodać konkretnego gracza, po dodaniu możemy dopisać do niego mecze, w których brał udział oraz raport z konkretnego meczu. 
Zakładka mecze oraz raport wyświetlają się dopiero po kliknięciu w konkretnego gracza, brak możliwości samodzielnego dodania tych zakładek i przypisania do nich konkretnego gracza. 
Na stronie głównej znajdują się okna z ilością graczy, meczy, raportów oraz akcji jednak po kliknięciu nie wywołuje żadnej akcji co jest mało intuicyjne. Widzimy także okno ostatnia aktywność, które pokazuje jakie zmiany na stronie ostatnio zaszły.
Wybór tylko dwóch języków- dodałabym więcej.
Ogólny wygląd aplikacji moim zdaniem to 4/10, wielkość okien niedopasowana do ilości treści na stronie. Mało zakładek do wyboru, należy wejść w jedną z zakładek aby odkryły się kolejne. Bardzo prosty wygląd. Plus za jednakową odległość między boxami.
Strona jest średnio intuicyjna, nie wszystkie pola do wypełnienia są zrozumiałe, brak legendy lub chociaż dymków z podpowiedzią co należy wpisać w dane pole. 

- brak możliwości przeniesienia się do strony głównej przez naciśnięcie ikony SCOUTS PANEL

**ZAKŁADKA GRACZE**
- strona "rozjeżdża się" w poprzek strona 31-40 of 715
- wielokrotne występowanie tych samych osób w tabeli z tym samym wiekiem oraz pozycją
- w filtrach do wyszukiwania na stronie w języku polskim część napisana jest po polsku, część po angielsku
- brak możliwości przewinięcia tabeli na sam koniec lub sam początek
- brak możliwości uporządkowania graczy (rosnąco, malejąco) według wieku, recenzji, meczy lub raportów oraz brak ułożenia alfabetycznego (imię, nazwisko)
- brak możliwości dodania gracza z tego miejsca

**ZAKŁADKA DODAJ GRACZA**
- z poziomu *DODAJ GRACZA* brak listy przy polu *POZIOM ROZGRYWEK, GŁÓWNA POZYCJA, POZYCJA ALTERNATYWNA* do wyboru poziomu zaawansowania przez co cała tabela jest mniej spójna
- co oznacza pole *ŁĄCZY NAS PIŁKA ORAZ 90 MINUT*

**ZAKŁADKA MECZE**
- można dodać mecz z ilością zdobytych bramek, który dopiero się odbędzie w przyszłości

**ZAKŁADKA DODAJ RAPORT**
- brak możliwości dodania raportu z pozycji *DODAJ RAPORT*, cofa do zakładki *MECZE* 
- przy dodawaniu raportu żadna z list punktowych lub numerycznych nie numeruje automatycznie po naciśnięciu enter
- pogrubienie oraz podkreślenie tekstu nie działa wyłącza się po próbie dodania tekstu
-brak paska bocznego do przesuwania w górę i dół 

----------------

# Task 2 *TWORZENIE TEST CASE* :clipboard:
## Subtask 1
[**Zapraszam do obejrzenia moich Test Case na podstawie User Story**](https://docs.google.com/document/d/145BCbJmNvsBQwyAk2-DyKNk6xYN0Kx-LVsqLFNldfE0/edit?usp=share_link)

## Subtask 2
[**Zapraszam do obejrzenia moich Test Case na podstawie User Story mojej wyobraźni** :upside_down_face:](https://docs.google.com/document/d/1HaRPLeS1NCLNkClMsWqlzjkFCffxWHZGUW2SC_HApSU/edit?usp=share_link)

## Subtask 3
*Dlaczego piszemy przypadki testowe? [**Na co to komu potrzebne?**](https://www.youtube.com/watch?v=OO3FANjwKHY&t=1s)*

Myślę, że każdy przypadek testowy jest pewnym usystematyzowaniem pracy. Ja bardzo lubię w pracy mieć wszystko poukładane (czasem wprost przeciwnie do porządku w domu :upside_down_face:). Dobrze stworzony przypadek testowy pozwala określić priorytety. Jeżeli, któryś z test case'ów posiada *Priority Status* - **HIGH** wiadomo, że trzeba go zrobić w pierwszej kolejności, przed przypadkiem, którego priorytet to **LOW** (tak myślę, że tak to działa :information_desk_person:). Są w nim zawarte w skrócie najważniejsze założenia klienta, jeżeli coś nas oderwie od pracy, nie trzeba ponownie wczytywać się w User Story aby znaleźć co mamy kodować, wystarczy spojrzeć na tablekę i wszystko jasne :bowtie:. 

## Subtask 4
[**Pick Eat Up App on iOS**](https://docs.google.com/document/d/1n_EBd8jx52NtL1Yx2f7tCsnCzy8ArpHks68KQIhGtmA/edit?usp=share_link)

----------------

# Task 3 *TESTOWANIE I RAPORTOWANIE* :floppy_disk:
## Subtask 1
:bug: :point_right: [**Utworzenie formatki do zgłaszania błędów systemu- zgłoszone BUGI**](https://docs.google.com/document/d/1pJT0guVETYbu1QHkUSYyt0NqM4mVs0i4saPmrglkwwE/edit?usp=share_link)

## Subtask 2
:computer: :point_right: [**Testowanie według planów testów i raportowanie błędów**](https://docs.google.com/document/d/1BmVfNNmYYRR9f2B--5MBj5CcukGR8RzrFOlI1cnxETQ/edit?usp=share_link)

## Subtask 3
:chart_with_upwards_trend: :point_right: [**Raport z wykonanych testów**](https://docs.google.com/document/d/1WkmdhM8ds-kUNNt5_yjyYXlrUlNe7k04ilfPjoTmHMA/edit?usp=share_link)

----------------

# Task 4 *RAPORTOWANIE BŁĘDÓW* :crossed_flags:
## Subtask 2
:bug: :point_right: [**Raportowanie błędów znalezionych w trakcie godzinnego testowania :clock1:**](https://docs.google.com/document/d/190YCjngHsuw9TDGYNF61A6Q6-lLePe-97lDVzRGLPVU/edit?usp=share_link)

## Subtask 3
Aplikacja Focusly jest ukierunkowana na uporządkowanie naszej głowy. :seedling: Jest to apka, w której możemy wybrać cel jaki chcemy osiągnąć: zdrowy sen i emocje, poprawna relacja z jedzeniem i ludźmi, zdrowie psychiczne. Do wyboru mamy 4 zakładki. W pierwszej możemy wybrać zagadnienia, które nas interesują, to nad czym chcielibyśmy popracować np. w zakładce “Twój cel” możemy wybrać “Stres”, wtedy pokażą nam się lekcje, które pozwolą nam pracować nad nadmiernym stresem. Lekcje są podzielone na darmowe dla każdego użytkownika oraz zablokowane z dostępem tylko dla osób, które wykupiły subskrypcję. 

Focusly wydaje się być prostą w obsłudze aplikacją, ma przyjemny schemat kolorów, który do siebie pasuje i działa odprężająco dla wzroku  :eyes:. Ikony oraz przyciski są dość intuicyjne. Możemy przesunięciem palca w lewo lub w prawo przejść do kolejnej zakładki a po pojedynczym naciśnięciu otwierają nam się wybrane okna. Możemy przeczytać wybrany artykuł w aplikacji (nie przekierowuje do witryny internetowej) oraz posłuchać podcastu, co ważne podcasty działają w tle więc możemy ich słuchać po zablokowaniu telefonu (nie to co darmowa wersja Youtube :sunglasses:).  Aplikacja udostępnia aktualizacje średnio raz na 1-2 miesiące :point_right: [:chart_with_upwards_trend: *C L I C K*](https://drive.google.com/file/d/1MyKd7X0WSpVQadTmwGyUIznSCbsuq0DO/view?usp=share_link) :point_left:.

Widzę jednak wady, przede wszystkim:
- aplikacja nie jest podzielona na wersję darmową i premium co bardzo utrudnia użytkowanie. Co więcej materiały darmowe oraz płatne są bardzo pomieszane, nie wyświetlają się w kolejności np. najpierw wszystkie podcasty darmowe, następnie wszystkie premium, są ze sobą po prostu zmieszane, co można zobaczyć na załączonym wideo: :point_right: [:movie_camera: *C L I C K*](https://clipchamp.com/watch/dZJcp00O5U4) :point_left:,
- wybór konkretnego celu nie wpływa na całą aplikację, po przejściu do kolejnych zakładek: odkrywaj, oddychaj, muzyka, nie wyświetlają się proponowane ćwiczenia czy podcasty dla naszego celu,
- dość duża zużywalność baterii jak na samo klikanie i sprawdzanie opcji aplikacji bez słuchania podcastów (na załączonym zdjęciu konkuruje nawet z TikTokiem) :point_right: [:battery: *C L I C K*](https://drive.google.com/file/d/1fqNVfv-yYYmUNv-Wo8PQIKpE4rh9_lJ6/view?usp=share_link) :point_left:,
- zakładce Odkrywaj na samym dole mamy ARTYKUŁY, nie są one jednak poukładane w żaden sposób tematycznie, przewijając je w prawo przechodzimy przez depresję, bezsenność, wypalenie zawodowe czy problemy z bezpłodnością a po wyborze kategorii, która nas interesuje jak na przykład “Śpij dobrze” artykuły nie wyświetlają się wcale, warto by było dopasować artykuły do odpowiedniej kategorii, 
- przy zakładce Oddychaj nie ma do wyboru opcji haptyki, uważam, że warto by było dodać opcje haptyki przy ćwiczeniach oddechowych aby można je było wykonywać z zamkniętymi oczami dla większego relaksu lub przez osoby niewidome, 
 
Jakie różnice zauważyłam przy testowaniu aplikacji natywnej a internetowej? Przede wszystkim brak konieczności dostępu do internetu przy użytkowaniu aplikacji natywnej. Aplikacja, którą pobraliśmy w porównaniu ze stroną internetową z Task 3 jest dużo bardziej dopracowana wizualnie oraz systemowo. Aplikacje natywne są bardzo intuicyjne, przyciski których używamy najczęściej znajdują się tuż nad dołem ekranu, nie trzeba ich szukać tak jak w przypadku aplikacji internetowej. 

## Subtask 4
[Jira board :clipboard:](https://dabrowskaewa.atlassian.net/jira/software/projects/DIC/boards/1) (W czasie jaki sobie wyznaczyłam na to zadanie uadło mi się znaleźć tylko tyle bug'ów :bug:, to nie tak, że ja nie lubię pracować w grupie i dlatego robię te zadania sama, ja jestem na początku mojej ścieżki IT i bardzo bym nie chciała aby przez moje źle wykonane zadanie oberwała grupa :see_no_evil:)

----------------

# Task 5  *SQL*  :thought_balloon:
## Subtask 1
SQL *Structured Query Language* STRUKTURALNY JĘZYK ZAPYTAŃ :flashlight: 

:interrobang: ***ZAPYTANIA***:
- **SELECT * FROM**: wyświetl zawartość (gwiazdka oznacza wszytskie kolumny, jeśli chcemy wyświetlić jedną, konkretną należy w miejsce gwiazki wpisać jej nazwę);
- **GO**: rozdziela dany skrypt na kilka mniejszych w miejscach, w których chcemy go rozdzielić na końcu wpisujemy GO;
- **SELECT AS**: pokazuje wybrane kolumny, przy wpisaniu *AS* możemy zmienić do odczytu ich nazwę np z j. angielskiego na j. polski;
- **USE nazwa bazy danych GO**: przełącza do wybranej bazy danych;
- **CREATE TABLE nazwa tabeli (id int)**: utworzenie nowej tabeli;
- **ORDER BY nazwa kolumny** lub **ORDER BY nazwa kolumny ASC**: sortuje rosnąco;
- **ORDER BY nazwa kolumny DESC**: sortuje malejąco;
- **WHERE**: podajemy kolumnę, w której chcemy szukać danych
- **GROUP BY**: grupowanie na poszczególne wartości znajdujące się w kolumnie;

:speech_balloon: ***OPERATORY***:
- **BETWEEN AND**: operator do wybrania zakresu konkretnego zbioru pomiędzy liczbami;
- **>, <**: operator do wybrania zbioru większego lub mniejszego niż (liczba);
- **=**: operator do wybrania zakresu równego (liczba);
- **<> lub !=**: różny niż;
- **LIKE**: przeszukanie danych zgodnych z podaną dalej szukaną;
- **AND lub OR**: operatory służące do przeszukiwania więcej niż 1 frazy, AND możemy użyć do znalezienia 2 lub więcej kolumn które będa spełniały żądanie, OR możemy użyć do szukania kilku opcji; 
- **IS NUL lub IS NOT NULL**: IS NULL kolumny, które nie zostały wypełnione, IS NOT NULL kolumny które zostały wypełnione
- **( )**: nawias pozwala pogrupować nasze zapytanie na dwa lub więcej warunki;
- **JOIN**: wskazuje z którą tabelą, tabela powinna zostać połączona.

## Subtask 3
**1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.**

*SELECT * FROM actors
ORDER BY surname ASC*

[![1-surname.jpg](https://i.postimg.cc/CKvQBJcR/1-surname.jpg)](https://postimg.cc/VSCR29Qw)

**2. Wyświetl film, który powstał w 2019 roku.**

*SELECT * FROM movies
WHERE year_of_production = 2019*

[![2-movie.jpg](https://i.postimg.cc/jjgRxHNX/2-movie.jpg)](https://postimg.cc/gwZC46gX)

**3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.**

*SELECT * FROM movies
WHERE year_of_production BETWEEN 1900 AND 1999*

[![3-btween.jpg](https://i.postimg.cc/BvsjLBjf/3-btween.jpg)](https://postimg.cc/TK7dBmjt)

**4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$.**

*SELECT title, price FROM movies
WHERE price < 7*

[![4-price.jpg](https://i.postimg.cc/GhFQZqwZ/4-price.jpg)](https://postimg.cc/4m3Vcv35)

**5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.**

*SELECT * FROM actors
WHERE actor_id >= 4 AND actor_id <= 7*

[![5-actor-id.jpg](https://i.postimg.cc/fRwr5kgn/5-actor-id.jpg)](https://postimg.cc/WhH81pvX)

**6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.**

*SELECT * FROM customers
WHERE customer_id = 2 OR customer_id = 4 OR customer_id = 6*

[![6-customer.jpg](https://i.postimg.cc/MGcHMZwV/6-customer.jpg)](https://postimg.cc/B804R0Xn)

**7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.**

*SELECT * FROM customers
WHERE customer_id IN (1, 3, 5)*

[![7-cust.jpg](https://i.postimg.cc/MKbdNxh7/7-cust.jpg)](https://postimg.cc/7fh3TvPh)

**8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.**

*SELECT * FROM actors
WHERE name LIKE 'An%'*

[![8-name.jpg](https://i.postimg.cc/FRTJ3WqJ/8-name.jpg)](https://postimg.cc/dkT1KBJq)

**9. Wyświetl dane klienta, który nie ma podanego adresu email.**

*SELECT * FROM customers
WHERE email IS NULL*

[![9-null.jpg](https://i.postimg.cc/MGTcxbX6/9-null.jpg)](https://postimg.cc/BjrZBFxk)

**10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.**

[![5-actor-id.jpg](https://i.postimg.cc/fRwr5kgn/5-actor-id.jpg)](https://postimg.cc/WhH81pvX)



**6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.**



*SELECT * FROM customers

WHERE customer_id = 2 OR customer_id = 4 OR customer_id = 6*



[![6-customer.jpg](https://i.postimg.cc/MGcHMZwV/6-customer.jpg)](https://postimg.cc/B804R0Xn)



**7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.**



*SELECT * FROM customers

WHERE customer_id IN (1, 3, 5)*



[![7-cust.jpg](https://i.postimg.cc/MKbdNxh7/7-cust.jpg)](https://postimg.cc/7fh3TvPh)



**8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.**



*SELECT * FROM actors

WHERE name LIKE 'An%'*



[![8-name.jpg](https://i.postimg.cc/FRTJ3WqJ/8-name.jpg)](https://postimg.cc/dkT1KBJq)



**9. Wyświetl dane klienta, który nie ma podanego adresu email.**



*SELECT * FROM customers

WHERE email IS NULL*



[![9-null.jpg](https://i.postimg.cc/MGTcxbX6/9-null.jpg)](https://postimg.cc/BjrZBFxk)



**10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.**



*SELECT * FROM movies

WHERE (price > 9) AND (movie_id BETWEEN 2 AND 8)*



[![10-id.jpg](https://i.postimg.cc/50rLDK3W/10-id.jpg)](https://postimg.cc/gXvxZDQg)



# Task 6



## Subtask 1



**11. Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd 🙈**



*UPDATE customers SET surname='Miler' WHERE customer_id='3'*



[![1.jpg](https://i.postimg.cc/J7sMf6xR/1.jpg)](https://postimg.cc/8sg2WbxY)



**12. Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej.**



**13. Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com**



*UPDATE customers SET email='pati@mail.com' WHERE surname='Komor'*



[![3.jpg](https://i.postimg.cc/vZqvWBJn/3.jpg)](https://postimg.cc/LJPfSH64)



**14. Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).**



**15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag**



**16. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.**



*SELECT DISTINCT title FROM movies INNER JOIN sale*



[![16.jpg](https://i.postimg.cc/pr3GG9np/16.jpg)](https://postimg.cc/zHSF3G7r)



*SELECT * FROM movies
WHERE (price > 9) AND (movie_id BETWEEN 2 AND 8)*

[![10-id.jpg](https://i.postimg.cc/50rLDK3W/10-id.jpg)](https://postimg.cc/gXvxZDQg)

# Task 6

## Subtask 1

**11. Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd 🙈**

*UPDATE customers SET surname='Miler' WHERE customer_id='3'*

[![1.jpg](https://i.postimg.cc/J7sMf6xR/1.jpg)](https://postimg.cc/8sg2WbxY)

**12. Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej.**

**13. Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com**

*UPDATE customers SET email='pati@mail.com' WHERE surname='Komor'*

[![3.jpg](https://i.postimg.cc/vZqvWBJn/3.jpg)](https://postimg.cc/LJPfSH64)

**14. Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).**

**15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag**

**16. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.**

*SELECT DISTINCT title FROM movies INNER JOIN sale*

[![16.jpg](https://i.postimg.cc/pr3GG9np/16.jpg)](https://postimg.cc/zHSF3G7r)

**17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)**

*SELECT Name, surname FROM actors
UNION
SELECT Name, surname FROM customers
ORDER BY surname ASC*

[![17.jpg](https://i.postimg.cc/vmL5C4Cc/17.jpg)](https://postimg.cc/PLJLw5Xj)

**18. Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $ (Pamiętaj, że dolar to domyślna jednostka- nie używaj jej nigdzie).**

*UPDATE movies SET price = price + '2,5' where year_of_production >= '2000'*

[![18.jpg](https://i.postimg.cc/RVP36jnp/18.jpg)](https://postimg.cc/xczjBp5L)



## Subtask 2

11/15 :alien:

## Subtask 3
[***MOJE PORTFOLIO***](https://github.com/dabrowskae/PORTFOLIO_ED)


