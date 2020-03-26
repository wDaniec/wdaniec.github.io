Plan na sprint 1:
- Zapytać się Janka, które issue chce zrobić
- Zrobić jedno z issue:
    - https://github.com/pytorch/pytorch/issues/34392
    - https://github.com/pytorch/pytorch/issues/34380
    - https://github.com/pytorch/pytorch/issues/33290


Podsumowanie sprintu 1:
- Rozmawiałem z Jankiem i ustaliliśmy kto zabiera jakie issue. Zająłem się: https://github.com/pytorch/pytorch/issues/34392
- Po krótkiej wymianie wyszło, że ta zmiana jest niepotrzebna. Autor wysłał kilka propozycji alternatywnych issue
- Zacząłem pracę nad https://github.com/pytorch/pytorch/issues/33567
- Udało mi się postawić środowisko.
- Spędziłem ~6 godzin nad czytaniem gdzie co się znajduje
- Wiem już jak rozwiązać problem w prosty sposób, ale domyślam się, że będę musiał wejść trochę głebiej w kod.

Plan na sprint 2:
- Dokończenie issue nad którym w sumie nie zacząłem jeszcze pracy:
    - napisanie prostego rozwiązania na poziomie pythona i podesłanie go autorom, żeby dowiedzieć się czy jest wystarczające
    - Prawdopodobnie nie będzie dobre i będę musiał lepiej zrozumieć, jak są używane funkcje na  poziomie C/Cpp.


Podsumowanie sprintu 2:
- 24 marca: Zacząłem pracę nad poprawieniem kodu w pythonie. Podczas kodzenia zauważyłem, że funkcja abs wbudowana w torcha jest podlinkowana do funkcji dla zwykłego tensora. Problem z tym jest taki, że dużo prostych funkcji matematycznych jest napisane w cpp ze wstawkami niskopoziomowymi. Mało używałem cpp, więc ten task wydaje się potwornie trudny. Plus jest taki, że osoba, która pisała tę część odpisuje bardzo szybko. Chciałbym do końca tygodnia to naprawić.
