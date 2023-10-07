# Szablon LaTeX pracy dyplomowej dla Wydziału Elektrotechniki i Informatyki Politechniki Lubelskiej

To repozytorium zawiera szablon pracy dyplomowej przygotowanej w LaTeX zgodnie z wymaganiami na  moment 10.2023.

## Jak zacząć korzystać?

Szkic został zoptymalizowany pod edytor LaTeX Overleaf. Został przetestowany na oficjalnej instancji, ale powinien też działać na self-hostowanych. 

Instrukcja:

1. Pobierz repozytorium jako `.zip`.

2. Zarejestruj się w Overleaf lub otwórz własną instancję.

3. Kliknij `New project` i wybierz opcję z wysłaniem szkicu jako `.zip`.

4. Domyślnie projekt nie skompiluje się. Należy wejść w ustawienia projektu (ikonka domu w górnym, lewym rogu) i **zmienić kompilator `Compiler` z `pdfLaTeX` na `LuaLaTeX`.**

5. Pierwsze kompilowanie może zająć sporo czasu. 

6. Zacznij pisać pracę zgodnie z szablonem, nie musisz nic modyfikować, po prostu podmień dane na swoje. 

7. W pliku pokazano przykład cytowań, referencji, dodawania tabel z obsługą dzielenia na strony, dodawanie obrazków, listingów i wykresów. **Trzymaj się schematu, a całość ładnie sama się odpowiednio ponumeruje.**

## Co robi szablon?

Szablon jest zgodny z wymogami dot. pracy dyplomowej Politechniki Lubelskiej na Wydziale Elektrotechniki i Informatyki. Niektóre z wymogów, które realizowane są przez szablon:

- Automatyczne usuwanie tzw. sierotek.

- Odpowiednia numeracja elementów typu grafiki, tabele, listingi wraz z numerem rozdziału pracy.

- Lustrzane marginesy.

- Pusta strona po stronie tyłowej.

- Odpowiednio dobrane marginesy.

- Czcionka New Times Roman w pracy.

- Czcionka Arial dla strony tytułowej.
  
  ### Dodatkowo:

- Każdy element jest "klikalny",  w tym spis treści, cytowania czy referencje. To znaczy, na przykład w tekście można kliknąć w dany odnośnik do pracy z bibliografii (np. [22]), aby automatycznie przenieść się do tej pozycji w rozdziale z bibliografią. To samo dzieje się z innymi elementami, np. listingami czy grafikami.

- Obsługa listingów z odpowiednio dobraną czcionką.

- Podział bibliografii na źródła internetowe i źródła naukowe.

- I wiele więcej!

### Autorzy

Jestem tylko jednym z kilku autorów. Szkic powstał z pomocą takich deweloperów jak:

- [MorganMLGman](https://github.com/MorganMLGman)

- [Shogun-PB](https://github.com/Shogun-PB)

- [SEBAA300](https://github.com/SEBAA300)

- [Wittano](https://github.com/Wittano)

## Skąd pomysł na szablon?

LaTeX to świetne narzędzie do pisania skomplikowanych dokumentów, gdzie są trudne wymogi, a rozmiary projektu sprawiają, że ciężko pilnować i uważać na błędy. Niestety, WEII nie udostępnia szablonu LaTeX, a jedynie `.doc` (nawet nie `.docx`, który jest nieco łatwiejszy w interpretacji przez niezależne pakiety biurowe). To utrudnienie w pisaniu pracy dyplomowej, zwłaszcza dla osób niekorzystających z oprogramowania Microsoft Office oraz Microsoft Windows lub Apple macOS. LaTeX natomiast jest niezależny od platformy, a popularny edytor Overleaf jest uruchamiany w przeglądarce internetowej. To znacznie ułatwia pracę, a autor ma większą swobodę. 

Niegdyś WEII udostępniał własny szablon, ale po zmianie wymogów co do prac dyplomowych wycofano się z tej praktyki. Dlatego też postanowiliśmy stworzyć własny szkic, który znacznie ułatwi nam pracowanie nad pracą magisterską. Oczywiście szablon jest też zgodny z innymi typami prac, na przykład pracami inżynierskimi.
