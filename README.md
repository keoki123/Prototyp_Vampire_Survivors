# Unity Survival Prototype

Prototyp gry survival/action przygotowany w **Unity**.  
Repozytorium zawiera:

- **gotowy build gry** do uruchomienia
- **pełny projekt Unity** do dalszej edycji

---

## Jak uruchomić grę

Gotowy build znajduje się w folderze:

## `prototyp/`

Aby uruchomić grę:

1. Pobierz repozytorium z GitHuba
   - najlepiej przez **Code -> Download ZIP**
   - albo przez `git clone`

2. Rozpakuj pobrane pliki

3. Wejdź do folderu:

## `prototyp`

4. Uruchom plik:

## `.exe`

---

## Ważne

Nie należy pobierać ani uruchamiać samego pliku `.exe` osobno.

Build Unity działa poprawnie tylko wtedy, gdy plik `.exe` znajduje się razem z pozostałymi plikami builda w folderze `prototyp`.

Czyli trzeba mieć cały folder:

## `prototyp/`

a dopiero potem uruchomić `.exe`.

---

## Struktura repozytorium

### `prototyp/`
Folder z **gotowym buildem gry**.

To właśnie ten folder służy do:
- uruchomienia gry
- testowania prototypu bez Unity

### `my project/`
Folder z **pełnym projektem Unity**.

Zawiera pliki potrzebne do dalszej pracy nad grą, między innymi:
- `Assets`
- `Packages`
- `ProjectSettings`
- sceny
- skrypty
- UI
- animacje
- prefaby
- tekstury

Ten folder służy do:
- otwierania projektu w Unity
- edycji gry
- dalszego rozwoju projektu

---

## Jak otworzyć projekt w Unity

Jeżeli chcesz otworzyć projekt do edycji:

1. Uruchom **Unity Hub**
2. Kliknij **Add project**
3. Wskaż folder:

## `my project`

4. Otwórz projekt odpowiednią wersją Unity

---

## Zawartość prototypu

Aktualna wersja zawiera między innymi:
- ruch gracza
- przeciwników i ich animacje
- kilka typów przeciwników
- bossa
- system XP
- levelowanie
- menu level up
- pasek broni i miejsce na dodatki
- gotowy build gry

---

## Podsumowanie

- **chcesz zagrać** -> pobierz repozytorium i uruchom `.exe` z folderu `prototyp`
- **chcesz edytować projekt** -> otwórz folder `my project` w Unity

---

