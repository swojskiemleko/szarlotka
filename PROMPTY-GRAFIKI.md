# Nowy wygląd kuchni (gra w poziomie): prompty do AI

Plansze 1–6 (przybory, desery, mini-gry, formy) są już w grze. Tu są **tylko meble, blat i tło**, zrobione pod proporcje kuchni w poziomie, żeby nic się nie rozciągało ani nie powtarzało.

**Jak to zrobić:**
1. Użyj AI, które przyjmuje obrazek jako wzór, na przykład ChatGPT albo Gemini. Wszystko rób w jednej rozmowie.
2. Na początku wgraj 2 wzory stylu z gry (niżej) i wklej **STYL**.
3. Potem wklejaj prompty **po jednym**. Każdy daje jeden obrazek w podanym rozmiarze.
4. Gotowe obrazki wklej mi w czacie albo spakuj do ZIP-a jak poprzednio.

**Ważne:** rozmiar (proporcje) musi się zgadzać, bo obrazek wypełnia dokładnie miejsce mebla w grze. Jeśli AI zrobi kwadrat, poproś: „make it exactly W x H pixels”.

## Wzory stylu (wgraj oba do AI)

| manzanas.png | queso.png |
| --- | --- |
| ![Wzór: jabłka](https://swojskiemleko.github.io/szarlotka/img/manzanas.png) | ![Wzór: ser](https://swojskiemleko.github.io/szarlotka/img/queso.png) |

## STYL (wklej jako pierwszy, razem z 2 obrazkami)

```
I attached two images from my game. Make every next image in EXACTLY the same style:
cute cartoon illustration, thick dark-brown outlines (#3b2314), flat warm colors with one simple
lighter highlight, rounded friendly shapes, like a casual browser cooking game.
All furniture is light warm wood (honey oak) with dark-brown handles, the same wood in every image.
No text, no letters, no people.
```

---

## 1. Lodówka (700 × 1000, pionowa)

```
Exactly 700 x 1000 pixels. A flat FRONT view of a tall white two-door fridge that fills the whole
image edge to edge: a smaller freezer door on top (about one third) and a big fridge door below,
long vertical dark handles on the right side of both doors, two or three small fruit magnets.
No perspective, no shadow, no background, no floor.
```

## 2. Górna szafka szeroka, 3 drzwi (1700 × 500, bardzo szeroka)

```
Exactly 1700 x 500 pixels. A flat FRONT view of a wide wall-mounted kitchen cabinet that fills the whole
image edge to edge, with THREE equal doors side by side, light honey-oak wood with a simple frame panel,
small dark vertical handle on each door. No perspective, no shadow, no background.
```

## 3. Górna szafka, 2 drzwi (1250 × 500, szeroka)

```
Exactly 1250 x 500 pixels. A flat FRONT view of a wall-mounted kitchen cabinet that fills the whole
image edge to edge, with TWO equal doors side by side, the same light honey-oak wood and handles as before.
No perspective, no shadow, no background.
```

## 4. Dolna szafka, 2 drzwi (1050 × 500, szeroka)

```
Exactly 1050 x 500 pixels. A flat FRONT view of a lower kitchen cabinet (under the countertop) that
fills the whole image edge to edge, with TWO equal doors side by side, the same light honey-oak wood,
dark vertical handles near the middle. No perspective, no shadow, no background, no countertop on top.
```

## 5. Szuflady (700 × 500)

```
Exactly 700 x 500 pixels. A flat FRONT view of a kitchen drawer unit that fills the whole image edge
to edge: TWO equal wide drawers one above the other, the same light honey-oak wood, a dark horizontal
handle in the middle of each drawer. No perspective, no shadow, no background.
```

## 6. Piekarnik (700 × 500)

```
Exactly 700 x 500 pixels. A flat FRONT view of a built-in white kitchen oven that fills the whole image
edge to edge: a control strip on top with three dark round knobs, and below it a big DARK glass window
in the middle (the window covers roughly the middle 70% of the width and the lower 60% of the height),
a horizontal handle above the window. No perspective, no shadow, no background.
```

## 7. Blat (1024 × 1024, wzór powtarzalny)

```
Exactly 1024 x 1024 pixels. A SEAMLESS TILEABLE texture of a light warm-beige stone kitchen countertop
seen from above, same cartoon style but very calm: soft cream-beige color with a few small subtle speckles,
no outlines, no objects, no edges, no shadow. It must repeat without visible seams.
```

## 8. Tło za kuchnią (1920 × 1080, poziome)

```
Exactly 1920 x 1080 pixels. Background for a cooking game in landscape, same cartoon style:
a cozy kitchen wall with warm cream square tiles, a window with sunlight in the upper left part,
soft and calm colors. NO furniture, NO countertop, NO objects, no people, no text.
```

---

## Gdzie co trafia (nazwy plików w `img/`)

| Prompt | Plik | Miejsce w grze |
| --- | --- | --- |
| 1 | nevera | lodówka po lewej |
| 2 | armarioArriba3 | górna szafka nad blatem (szeroka) |
| 3 | armarioArriba2 | górna szafka po prawej |
| 4 | armarioAbajo2 | dolna szafka pod blatem |
| 5 | cajones | szuflady pod blatem |
| 6 | horno | piekarnik |
| 7 | piedra | powierzchnia blatu |
| 8 | cocina | tło za kuchnią |

Gra jest już na nie przygotowana: po wgraniu same zastąpią obecne obrazki.
