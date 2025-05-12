Knight's Quest
Opis projektu
Knight's Quest to dynamiczna gra 2D w stylu platformówki, stworzona w Pythonie z użyciem biblioteki Pygame. Gracz wciela się w jednego z trzech rycerzy, którzy muszą pokonywać różnorodnych przeciwników na coraz trudniejszych poziomach. Gra oferuje zaawansowane animacje, system bonusów, ekran wyboru postaci oraz przejścia między poziomami z efektami wizualnymi i dźwiękowymi.
Wymagania

Python 3.8+
Pygame 2.0+
Pliki zasobów (obrazy, dźwięki) w folderze assets/

Jak uruchomić grę?

Upewnij się, że masz zainstalowane Python i Pygame:pip install pygame


Sklonuj lub pobierz projekt.
Upewnij się, że struktura folderów i pliki zasobów są zgodne z opisem w strukturze projektu.
Przejdź do folderu projektu w terminalu i uruchom grę:python src/main.py



Sterowanie

Strzałki (lewo/prawo): Poruszanie się rycerzem.
Spacja: Skok.
Klawisz A: Atak mieczem.
Klawisze w menu:
Strzałki (lewo/prawo): Wybór rycerza.
Enter: Potwierdzenie wyboru.



Struktura projektu
project/
├── assets/
│   ├── images/
│   │   ├── player/
│   │   │   ├── Knight_1/
│   │   │   ├── Knight_2/
│   │   │   ├── Knight_3/
│   │   ├── enemy/
│   │   │   ├── Black_Werewolf/
│   │   │   ├── Skeleton_Warrior/
│   │   │   ├── Skeleton_Spearman/
│   │   │   ├── White_Werewolf/
│   │   │   ├── Red_Werewolf/
│   │   ├── bonus.png
│   │   ├── bonus_speed.png
│   │   ├── bonus_health.png
│   │   ├── bonus_score.png
│   ├── sounds/
│   │   ├── background.mp3
│   │   ├── notification.mp3
│   │   ├── level_up.mp3
│   │   ├── game_over.mp3
│   │   ├── start_game.mp3
│   │   ├── sword_sound_1.mp3
│   │   ├── sword_fend.mp3
│   │   ├── run.mp3
│   │   ├── jump.mp3
│   │   ├── dead.mp3
├── src/
│   ├── main.py
│   ├── game.py
│   ├── player.py
│   ├── enemy.py
│   ├── wall.py
│   ├── bonus.py
│   ├── menu.py
│   ├── level.py
│   ├── utils.py
└── docs/
    └── readme.md

Funkcjonalności

Wybór rycerza: Gracz może wybrać jednego z trzech rycerzy (różniących się wyglądem) na początku gry.
Zróżnicowani przeciwnicy: Pięć typów wrogów (wilkołaki, szkielety) z animacjami ataku, chodzenia, biegu i śmierci.
Dwa poziomy: Poziomy o większym rozmiarze i zaawansowanej strukturze, z większą liczbą przeciwników.
System ataku i skoku: Gracz może atakować wrogów i skakać, z odpowiednimi animacjami.
Przejścia między poziomami: Po pokonaniu wszystkich wrogów wyświetla się ekran "Next Level" z numerem poziomu.
System bonusów: Trzy typy bonusów:
Przyspieszenie (S): Zwiększa prędkość gracza na 5 sekund.
Zdrowie (H): Dodaje jedno życie.
Punkty (B): Dodaje 50 punktów.


Dźwięki: Muzyka tła, efekty dźwiękowe dla akcji (atak, skok, śmierć) oraz menu.
Interfejs: Wyświetlanie wyniku, zdrowia i numeru poziomu na ekranie.

Stworzone w ramach projektu edukacyjnego.
