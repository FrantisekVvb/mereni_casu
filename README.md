# Přesýpací hodiny

Interaktivní animace přesýpacích hodin exportovaná z After Effects (Lottie). Po dopadnutí písku animace zastaví; tlačítkem **Otočit hodiny** spustíte otočení a další cyklus přesypávání.

## Spuštění

Otevřete `index.html` v prohlížeči, nebo spusťte lokální server:

```bash
npm install
npm run dev
```

Poté otevřete [http://127.0.0.1:8766](http://127.0.0.1:8766).

## Online verze (GitHub Pages)

Po pushi na větev `main` se aplikace automaticky nasadí přes GitHub Actions. Adresa bude:

**https://frantisekvvb.github.io/presypaci_hodiny/**

(Poprvé může nasazení trvat 1–2 minuty.)

## Jak to funguje

1. Po načtení stránky písek sám začne padat (~8 s).
2. Animace se zastaví a zobrazí se tlačítko **Otočit hodiny**.
3. Kliknutím se hodiny otočí a písek znovu padá.
4. Cyklus lze opakovat – střídá se první a druhé přesypání.

## Struktura

- `index.html` – stránka
- `styles.css` – styly
- `main.js` – logika animace a ovládání
- `assets/hourglass.json` – Lottie animace (pouze přesýpací hodiny)

## Technologie

- [Lottie Web](https://github.com/airbnb/lottie-web) 5.12
- Statický web (HTML, CSS, JS) – vhodné pro GitHub Pages
