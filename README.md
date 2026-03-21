# Biblioteca Dallari - Sito statico

Sito statico semplice pronto per hosting su Azure Static Web Apps.

## Struttura

- `index.html`: contenuto della pagina
- `styles.css`: stile e responsive design
- `staticwebapp.config.json`: configurazione routing e header per Azure Static Web Apps
- `copy/copy.md`: copy sorgente

## Deploy su Azure Static Web Apps

1. Crea una nuova risorsa Azure Static Web Apps dal portale Azure.
2. Collega il repository GitHub.
3. Usa queste impostazioni build:
   - App location: `/`
   - Api location: (vuoto)
   - Output location: `/`
4. Esegui il commit e push su `main`: il workflow GitHub Actions creato da Azure pubblicherà il sito.

## Avvio locale

Apri `index.html` nel browser.
