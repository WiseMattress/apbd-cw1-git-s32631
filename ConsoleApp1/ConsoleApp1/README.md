1. Kiedy Git wykona fast-forward, a kiedy powstaje merge commit?
    Fast-forward jest wtedy gdy główna gałąź się nie zmieniła od momentu stworzenia gałęzi pocznej i wtedy git przesuwa wskaźnik do przodu, 
    Merge commit jest wtedy gdy w obu gałęziach były niezależne zmiany

2. Czym w praktyce różni się merge od rebase?
    Merge łączy obie historie i tworzy przy tym nowy węzeł
    Rebase zmienia lokację nowych commitów ze swojego popredniego miejsca na sam koniec gałęzi głównej

3. W jaki sposób został rozwiązany konflikt w Twoim repozytorium?
   tbh na początku nie wiedziałem co dokładnie zrobić, pamiętałem z zajęć żeby kliknąć ten zielony przycisk na górze ale zamiast tego wyszukałem jak to zrobić w internecie
    i po prostu usunąłem ręcznie te (<<<<<<<<<, ========== i >>>>>>>>>>>>) wyenerowane przez gita
   