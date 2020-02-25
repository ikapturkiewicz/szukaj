# szukaj

Napisać skrypt wywoływany w następujący sposób:

     szukaj [-c katalog_docelowy] wzorzec .roz katalog

np. szukaj  sigwait  .h  /usr/include

Skrypt poszukuje wyrażeń pasujących do podanego wzorca we wszystkich 
plikach zwykłych o nazwach z rozszerzeniem .roz w gałęzi drzewa 
katalogów wskazanej przez katalog. Skrypt wypisuje na stdout tylko nazwę 
ścieżkową każdego pliku, zawierającego linię pasującą do wzorca.
Z opcją: -c katalog_docelowy skrypt kopiuje do wskazanego katalogu 
katalog_docelowy każdy plik zawierający dopasowane linie.

Skrypty powinny zawierać następującą obsługę błędów:
     - sygnalizować błędy składni (podając poprawną postać),
     - sygnalizować użycie niepoprawnego argumentu,
     - sygnalizować brak odpowiednich praw dostępu do plików lub katalogów.
