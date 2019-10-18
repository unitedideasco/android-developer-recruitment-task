# Android Recruitment Task

Napisz aplikację do wyświetlania listy filmów (w postaci listy lub kafelków) obecnie granych w kinach. Lista powinna mieć możliwość wyszukiwania autocomplete. Po naciśnięcu na dany film, powinny zostać wyświetlone szczegóły filmu.

## Wymagania biznesowe

* Wykorzystaj [API The Movie DB](https://www.themoviedb.org/documentation/api).
* Wyświetl kolekcję filmów obecnie granych w kinach (użyj endpointa `/movie/now_playing`).
* Stwórz ekran szczegółów z plakatem filmu (backdrop photo lub poster photo - wedle uznania), tytułem, datą wydania, oceną oraz krótkim opisem (`overview`). Dane mogą zostać przekazane do tego widoku lub może zostać wykonany dodatkowy call o szczegóły filmu.
* Na ekranie listy powinno być także zaimplementowane wyszukiwanie z podpowiadaniem (autocomplete). Użyj tutaj endpointa `/search/movie`.
* Powinniśmy mieć możliwość oznaczenia filmu jako ulubiony (dodanie gwiazdki na liście / kafelku oraz np. na toolbarze na ekranie szczegółów). Gwiazdka będzie włączona jeśli film jest ulubiony. Stan polubienia filmu ma być zapisywany i prezentowany po ponownym uruchomieniu aplikacji.

## Wymagania do kodu i projektu

* Projekt powinien być dostępny jako repozytorium git (dowolnie na: github, gitlab, bitbucket etc.), do którego chcielibyśmy otrzymać link,
* preferujemy Kotlin, ale Jave też akceptujemy,
* aplikacja powinna uruchamiać się na emulatorze oraz dowolnie wybranym modelu telefonu z Androidem (dla minSdk 19 i wyżej).
* UI wg własnego uznania - ważne, aby był przejrzysty,
* zadanie nie powinno zająć dłużej niż 2 dni.

## Ocena

Zadanie będzie oceniane pod kątem:

* Podejścia do architektury
* czytelności kodu
* dbałości o szczegóły.
