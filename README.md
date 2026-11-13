<div align="center">

<img src="logo.png" alt="Krevn Studio" width="120">

# Krevn Studio

**Piccolo studio indipendente di tre persone. App iOS e Android, siti web, open source.**

[**krevn-studio.pages.dev →**](https://krevn-studio.pages.dev/)

[Instagram @studiokrevn](https://www.instagram.com/studiokrevn/) · [r/KrevnStudio](https://www.reddit.com/r/KrevnStudio/) · [krevnstudio@gmail.com](mailto:krevnstudio@gmail.com)

</div>

---

## Cos'è

Il sito ufficiale di Krevn Studio. Una sola pagina, bilingue (inglese e italiano), senza framework e senza build.

## Contenuto

- **App**: Micro Viaggi, Aethel, Relics, Rinnova, Pixel Routines
- **Siti web**: [Vibely for Spotify](https://github.com/krevn-studio/spotifyGenres) (open source) e Bora (in sviluppo)
- **Team**: Giovanni Mattia Torrente (Founder, CEO), Gabriele Serli, Claudio Amendola
- **Supporto**: contatti e link social

## Stack

| | |
|---|---|
| Markup, stile, script | un solo `index.html` |
| Lingue | dizionari EN/IT in pagina (`data-i18n`, `data-i18n-html`) |
| Font | Cormorant Garamond e Inter |
| Hosting | Cloudflare Pages |

## Struttura

```
index.html     pagina, stili e traduzioni
icons/         icone delle app e dei siti
logo.png       logo
favicon.png    favicon
og-image.png   anteprima per i social
.nojekyll      disattiva Jekyll su GitHub Pages
```

## Eseguirlo in locale

```bash
git clone https://github.com/krevn-studio/krevnstudio-website.git
cd krevnstudio-website
python3 -m http.server 8080
```

Apri `http://127.0.0.1:8080/`.

## Modificare

- **Testi**: ogni stringa ha una chiave in entrambi i dizionari (EN e IT). Aggiornale insieme.
- **Nuova app o sito**: copia una card esistente, aggiungi l'icona in `icons/` (PNG 256×256, angoli arrotondati trasparenti) e le chiavi di traduzione.
- **Deploy**: ogni push su `main` ripubblica il sito su Cloudflare Pages.

## Palette

| Colore | Hex |
|---|---|
| Sfondo | `#061713` |
| Card | `#0E241B` |
| Crema | `#EFE2C4` |
| Salvia | `#9DB07C` |
| Testo secondario | `#A2AE9C` |

## Copyright

© Krevn Studio. Nomi, loghi e icone delle app sono dei rispettivi autori e non sono riutilizzabili senza permesso.
