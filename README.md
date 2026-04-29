# Biblioteca Dallari - Sito statico

Sito statico semplice pronto per hosting su GitHub Pages.

## Struttura

- `index.html`: contenuto della pagina
- `styles.css`: stile e responsive design
- `staticwebapp.config.json`: configurazione legacy per Azure Static Web Apps, non usata da GitHub Pages
- `copy/copy.md`: copy sorgente
- `.github/workflows/github-pages.yml`: pubblicazione automatica su GitHub Pages

## Deploy su GitHub Pages

1. Apri le impostazioni del repository su GitHub.
2. Vai in `Settings` > `Pages`.
3. In `Build and deployment`, seleziona `GitHub Actions` come source.
4. Esegui il push su `main`: il workflow pubblicherà automaticamente il sito.

## Avvio locale

Apri `index.html` nel browser.
