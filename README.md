# GarageScan — Inventario Attrezzi, Viti & Ferramenta

Web App PWA installabile gratuitamente su **GitHub Pages** (`https://<tuo-utente>.github.io/<nome-repository>/`).

## Caratteristiche Principali
- **Animazione Saracinesca Garage (~5,2s):** Apertura graduale con saracinesca opaca, esposizione della parete attrezzi vettoriale e chiusura fluida.
- **Archivio Silenzioso da 1.163 Voci DIY:** Lavora in background per suggerire voci mentre digiti e precompilare nome, misura, categoria e illustrazione vettoriale quando fotografi un'etichetta o una scatola.
- **4 Schede Pulite:** *Il Mio Garage*, *Scatta / Aggiungi* (Fotocamera + OCR + ricerca rapida), *Da Comprare* (con Modalità Negozio) e *Impostazioni*.
- **Sincronizzazione P2P Codice Garage / QR:** Condividi l'inventario su più dispositivi senza registrazione né server proprietari.
- **Installabile su Android & iOS + Funzionamento Offline (Service Worker) + Backup JSON/CSV.**

## Come pubblicare su GitHub Pages
1. Crea un nuovo repository pubblico su GitHub (es. `garagescan`).
2. Carica tutti i file contenuti in questo pacchetto (`index.html`, `manifest.json`, `sw.js`, `icon.svg`, `.nojekyll`, `README.md`) nella cartella principale (`root`) del repository.
3. Vai su **Settings → Pages**, seleziona **Deploy from a branch** → branch `main` e cartella `/ (root)`, quindi clicca **Save**.
4. Dopo circa 1 minuto l'app sarà online all'indirizzo `https://<tuo-utente>.github.io/garagescan/`.
