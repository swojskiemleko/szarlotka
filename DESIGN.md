# Szarlotka: design system slajdów

Slajdy wyglądają jak gra: płaskie, ciepłe kolory, gruby ciemnobrązowy kontur i twardy cień pod spodem. Ma to przypominać naklejki albo dużą kuchenną kreskówkę. Nie ma tu gradientów, szkła ani rozmytych cieni. Telewizor stoi daleko, więc wszystko jest duże, a na jednym slajdzie jest najwyżej jedna myśl.

## Tokeny (`:root` w `index.html`)

| Token | Wartość | Do czego |
|---|---|---|
| `--red` | `#e23d3d` | tytuły, czasownik z „se” (`.hl`) |
| `--green` | `#2f9e55` | „tak / dobrze”, numery kroków |
| `--ink` / `--ink2` | `#4a2c1a` / `#7a5a44` | tekst / tekst drugorzędny |
| `--line` | `#3b2314` | każdy kontur i każdy cień |
| `--cream` | `#fff8ee` | karty „papier” |
| `--wall` | `#ffe1c7` | tło ikon, ściana |
| `--gold` | `#f4b400` | pieczątka, wyróżnienie |
| tło | `#fdf4e7` + kratka | mantel kuchenny |
| `--ds-bw` | `clamp(3px,.45vh,5px)` | grubość konturu |
| `--ds-sh` | `0 clamp(5px,.9vh,9px) 0 var(--line)` | twardy cień |
| `--ds-r` | `clamp(16px,2.6vh,30px)` | promień kart |
| `--ds-gap` | `clamp(10px,2.4vh,28px)` | odstęp w siatce |

**Typografia:** tylko Fredoka (400/600/700). Rozmiary zależą od wysokości ekranu, bo telewizor jest zawsze w poziomie.

| Poziom | Rozmiar | Gdzie |
|---|---|---|
| display | `min(9vw,13vh)` | „La szarlotka” |
| title | `min(5.6vw,8.5vh)` | tytuł slajdu |
| body | `min(2.8vw,4.6vh)` | zdania na kartach |
| caption | `min(1.6vw,2.6vh)` | adres, podpisy |

## Elementy

- **`.ds-card`**: biała albo kremowa karta z konturem `--ds-bw`, cieniem `--ds-sh` i promieniem `--ds-r`.
- **`.ds-row`**: karta w jednym wierszu: kwadratowa ikona na tle `--wall`, a obok zdanie. Na slajdzie jest najwyżej 4 takie karty.
- **`.ds-tag`**: mała, lekko obrócona plakietka (np. flaga + Polonia).
- **`.ds-stamp`**: okrągła pieczątka w kolorze `--gold` („SIN GLUTEN”).
- **`.ds-steps`**: kroki z zielonym kółkiem z numerem. Na slajdzie dołączania kroki są po polsku.

## Zasady

1. Czasownik z „se” jest zawsze czerwony (`.hl`), bo to temat lekcji.
2. Obrazki z `img/` stoją na karcie i są lekko obrócone (±3°), jak naklejki.
3. Pierwszy slajd (dołączanie) jest po polsku, żeby wszyscy od razu wiedzieli, co robić. Reszta slajdów jest po hiszpańsku. Polskie tłumaczenie jest też w notatkach pilota.
4. Na slajdach nie ma emotek. Używamy obrazków z `img/`, rysunków SVG (kłos pszenicy) albo kropek statusu (`.dot`).
5. Tło to mantel w kratkę: kremowe `#fdf4e7` i czerwone pasy `rgba(226,61,61,.09)`. Kratka ma rozmiar `min(9vw,13vh)`, więc na telewizorze i na komputerze wygląda tak samo.
6. Ruch jest jeden: karty wskakują po kolei (`ds-in`, 60 ms odstępu). Nic nie miga w kółko.
