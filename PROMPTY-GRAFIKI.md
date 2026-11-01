# Cała kuchnia jako jeden obrazek: prompt dla Gemini

Gra potrzebuje teraz **jednego obrazka całej kuchni**: lodówki, szafek, blatu, szuflad, piekarnika i ściany. Wtedy wszystko jest połączone, ma ten sam styl i nie ma osobnych ramek. Gra sama tnie ten obrazek na drzwi, które się otwierają.

**Jak to zrobić:**
1. Wejdź na gemini.google.com i wybierz tworzenie obrazów.
2. Wgraj **3 obrazki** naraz:
   - `makieta-kuchni.png` (jest w folderze `szarlotka`; pokazuje, gdzie co stoi),
   - `img/manzanas.png` i `img/queso.png` (wzory stylu).
3. Wklej prompt z sekcji niżej.
4. Jeśli obrazek wyjdzie kwadratowy albo meble będą w innych miejscach, napisz: „Keep the exact 21:9 shape and put every piece exactly where it is in the layout image.”
5. Gotowy obrazek wklej mi w czacie. Zapiszę go jako `img/kuchnia.jpg` i dopasuję miejsca drzwi do tego, co narysuje Gemini.

![Makieta](makieta-kuchni.png)

## Prompt

```
I attached 3 images.
Image 1 is a LAYOUT SKETCH of a kitchen (21:9, very wide). Image 2 and 3 show the ART STYLE.

Draw ONE finished picture of this kitchen, seen straight from the front (no perspective, flat like a
game background), in EXACTLY the art style of images 2 and 3: cute cartoon, thick dark-brown outlines,
flat warm colors with one simple highlight, rounded friendly shapes, like a casual cooking game.

Keep the layout EXACTLY like image 1: same 21:9 shape, every piece in the same place and the same size.
- Left: a tall white two-door fridge (small freezer door on top, big door below), standing on the floor.
- Top: two wall cabinets side by side, both with 2 doors that meet in the middle (handles in the middle).
  The left one has plain wooden doors. The right one is a glass cabinet: each door is a wooden frame
  with a big glass pane in the middle, exactly where the light-blue panes are in image 1. Behind the
  glass draw only an empty, slightly darker cabinet inside (no objects).
- Middle: an EMPTY wall with warm cream tiles, and below it ONE long light-stone countertop that runs
  from the fridge to the right edge. Nothing on the countertop and nothing on the wall.
- Under the countertop, touching each other with no gaps: a drawer unit with 2 drawers, a lower cabinet
  with 2 doors, and a white built-in oven with 3 knobs on top and a big dark glass window.
All cabinets are the same light honey-oak wood with dark-brown handles. Everything is joined into one
kitchen: the countertop sits directly on the lower cabinets, no frames or borders around the countertop.
The wall around the furniture is one calm, plain warm-cream color right up to the edges of the picture.

Do NOT copy the red labels from the sketch. No text, no letters, no people, no plants, no objects,
no window, no lamps.
```

## Co robi gra z tym obrazkiem

- Kuchnia ma zawsze proporcje 21:9. Wolne miejsce po bokach dostaje kolor ściany z obrazka, więc nie widać krawędzi.
- Każde drzwi to wycięty kawałek obrazka. Tak się otwierają:
  - **Szafki z 2 drzwiami:** oba skrzydła odchylają się na boki, każde na swoich zawiasach, i zostają otwarte. Ich tył jest ciemniejszy.
  - **Witryna (szklane drzwiczki):** przez szybę od razu widać prawdziwe rzeczy, które są w środku.
  - **Lodówka:** drzwi odchylają się w lewo.
  - **Szuflady:** wysuwają się w dół.
  - **Piekarnik:** pokrętła zostają, opada tylko klapa z szybą i widać ciemne wnętrze, a przy pieczeniu żar.
- Blat nie ma własnego tła, widać po prostu blat z obrazka. Rzeczy stoją na jego przedniej krawędzi.
- Lodówka ma zawsze ten sam rozmiar, otwarta i zamknięta.
- Dopóki nie ma `img/kuchnia.jpg`, gra używa obecnych osobnych mebli w tym samym układzie.
