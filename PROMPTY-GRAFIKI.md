# Brakujące grafiki do gry: prompty do dowolnego AI

W grze jest już 18 obrazków w jednym stylu (kucharz, szarlotka, składniki). Brakuje przyborów, deserów, frontów mebli, obrazków do mini-gier (plansze 4–6) i teł. Bez nich gra pokazuje emoji i proste rysunki.

**Jak to zrobić, żeby styl się zgadzał:**
1. Użyj AI, które przyjmuje obrazek jako wzór, na przykład ChatGPT albo Gemini.
2. Na początku rozmowy **wgraj 2 obrazki z gry jako wzór stylu**: `img/manzanas.png` i `img/queso.png`. Możesz je zapisać z https://swojskiemleko.github.io/szarlotka/img/manzanas.png i …/img/queso.png.
3. Wklej najpierw **STYL**, a potem kolejne prompty, wszystkie w tej samej rozmowie.
4. Gotowe obrazki wklej mi w czacie. Potnę je, wytnę tło i podłączę.

Jeśli AI pomiesza kolejność albo zrobi inną liczbę przedmiotów, wygeneruj jeszcze raz albo napisz mi, co jest gdzie.

---

## Wzory stylu (wgraj oba do AI)

| manzanas.png | queso.png |
| --- | --- |
| ![Wzór: jabłka](https://swojskiemleko.github.io/szarlotka/img/manzanas.png) | ![Wzór: ser](https://swojskiemleko.github.io/szarlotka/img/queso.png) |

Więcej obrazków w tym stylu (jeśli AI potrzebuje):

![kucharz](https://swojskiemleko.github.io/szarlotka/img/chef.png) ![szarlotka](https://swojskiemleko.github.io/szarlotka/img/tarta.png) ![masło](https://swojskiemleko.github.io/szarlotka/img/mantequilla.png) ![jajko](https://swojskiemleko.github.io/szarlotka/img/huevo.png)

## STYL (wklej jako pierwszy, razem z 2 obrazkami-wzorami)

```
I attached two images from my game. Make every next image in EXACTLY the same style:
cute cartoon illustration, thick dark-brown outlines (#3b2314), flat bright colors with one simple
lighter highlight, rounded friendly shapes, like a casual browser cooking game.
No text, no letters, no labels, no shadows on the background.
```

## Plansza 1: przybory (3×3)

```
One image: a grid of 3 rows x 3 columns, 9 separate objects in that same style, each centered in its
own cell with lots of empty space around it, objects never touch. Plain pure white background.
Exact order, left to right, top to bottom:
Row 1: a wooden cutting board with a handle; a kitchen knife; a vegetable peeler.
Row 2: a wooden spoon; a box grater; a small round fine-mesh sieve with a handle.
Row 3: an empty mixing bowl; an empty frying pan with a handle; an empty square metal baking tin.
```

## Plansza 2: jabłko i desery (2×2)

```
One image: a grid of 2 rows x 2 columns, 4 separate objects in that same style, each centered in its
own cell with lots of empty space around it, objects never touch. Plain pure white background.
Exact order:
Row 1: one single red apple with a green leaf; a scoop of vanilla ice cream in a small glass bowl.
Row 2: a swirl of white whipped cream; one red strawberry.
```

## Plansza 3: drzwi mebli (2×2)

Te obrazki stają się w grze drzwiami, które się otwierają. Muszą być **płaskie, na wprost, bez perspektywy** i wypełniać całą komórkę.

```
One image: a grid of 2 rows x 2 columns, 4 flat FRONT views in that same style, each one fills its
whole cell, no perspective, no shadow, small white gap between cells. Exact order:
Row 1: a tall white fridge door with a long vertical handle on the right;
a wooden kitchen cupboard door with a vertical handle on the right.
Row 2: a wooden drawer front with a horizontal handle near the top;
a small white oven front with three knobs on top and a dark glass window.
```

---

## Mini-gry (obieranie, krojenie, mieszanie, pieczenie)

Te obrazki widać w zbliżeniu blatu, gdy uczeń obiera, kroi, miesza i piecze. Ważne:
- **Plansze 5 i 6 są widziane z góry**, prosto z góry, bez perspektywy.
- Na planszy 6 forma ma być **ta sama, w tym samym miejscu i rozmiarze** w każdej komórce, bo w grze obrazki płynnie się przenikają.

## Plansza 4: obrane jabłko i ciasto (1×3)

```
One image: 1 row x 3 columns, 3 separate objects in that same style, each centered in its own cell
with lots of empty space around it, objects never touch. Plain pure white background.
Exact order, left to right:
a peeled apple (pale cream-yellow flesh, no skin, small stem on top, same size and shape as the red apple);
a big smooth ball of light-yellow shortcrust dough;
a small smooth ball of the same dough (half the size).
```

## Plansza 5: deska, patelnia i miska z góry (2×4)

```
One image: a grid of 2 rows x 4 columns, 8 separate objects in that same style, ALL SEEN STRAIGHT
FROM ABOVE (top-down view, no perspective), each centered in its own cell with lots of empty space
around it, objects never touch. Plain pure white background. Exact order, left to right, top to bottom:
Row 1: an empty wooden cutting board (wide rectangle, short handle on the right side);
an empty black frying pan with the handle pointing right;
the same frying pan with raw pale-yellow apple cubes;
the same frying pan with golden caramelized apple cubes and brown cinnamon specks.
Row 2: an empty round light-blue mixing bowl;
the same bowl with separate small piles of yellow corn flour, white potato starch, white powdered sugar,
butter pieces and one egg yolk (not mixed);
the same bowl with one smooth ball of light-yellow dough;
a small pile of peeled apple cubes (pale yellow).
```

## Plansza 6: szarlotka w formie, krok po kroku (2×4)

```
One image: a grid of 2 rows x 4 columns. In EVERY cell the SAME square metal baking tin, SEEN STRAIGHT
FROM ABOVE (top-down, no perspective), same size, same position, same light, filling most of the cell.
Same cartoon style. Plain pure white background between cells. Exact order, left to right, top to bottom:
Row 1: 1) the tin empty; 2) the tin with raw pale dough pressed flat as the base;
3) the base baked light golden; 4) the baked base covered with cooked yellow apple pieces with cinnamon specks.
Row 2: 5) the apples covered with raw pale crumbly dough crumbs; 6) the same cake baked: golden-brown crumble top;
7) the baked cake dusted with white powdered sugar; 8) the same sugared cake cut into 9 square pieces (3 x 3).
```

---

## Tła (każde osobno)

**Telefon** (pionowe):
```
Vertical 1080x1920 background in that same cartoon style: a cozy empty kitchen wall with warm cream
tiles and a window with sunlight in the upper part. NO furniture, NO objects, no people, no text.
Soft, calm colors so game objects placed on top stay readable.
```

**Telewizor** (poziome):
```
Horizontal 1920x1080 background in that same cartoon style: a cozy kitchen with warm cream tiles,
wooden shelves with a few jars and a window with sunlight. Soft and calm, plenty of empty space
in the center for big text, no people, no text.
```

**Blat w zbliżeniu** (pionowe; widać go, gdy uczeń robi mini-grę):
```
Vertical 1080x1500 background in that same cartoon style: a top-down view of a light wooden kitchen
countertop with simple wood grain. Completely EMPTY: no objects, no food, no tools, no text.
```

---

## Gdzie co trafia (nazwy plików w `img/`)

| Plansza | Pliki (w kolejności) |
| --- | --- |
| 1 | tabla, cuchillo, pelador, cuchara, rallador, colador, bol, sarten, molde |
| 2 | manzana, helado, nata, fresa |
| 3 | nevera, armario, cajon, horno |
| 4 | manzanaPelada, masa, masaPeque |
| 5 | tablaTop, sartenTop, sartenManzanas, sartenCanela, bolTop, bolMezcla, bolMasa, manzanaTrozos |
| 6 | moldeVacio, moldeMasa, moldeBase, moldeManzanas, moldeCrumble, moldeHorneado, moldeAzucar, moldeCortado |
| tła | cocina (telefon), fondo (telewizor), encimera (blat) |

Już są i nie trzeba ich robić: chef, tarta, manzanas, mantequilla, huevo, harina, fecula, azucarGlas, levadura, vainilla, canela, tomate, cebolla, pescado, queso, zanahoria, sal, arroz.
