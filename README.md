# Salone Blu — sito web

Questo repository contiene il sito a pagina singola di **Salone Blu** (Giovanni Bianco, Mapello), pronto per essere pubblicato con **GitHub Pages**.

## File inclusi

- `index.html` — l'intero sito (HTML + CSS + immagini incorporate, un unico file autosufficiente)
- `.nojekyll` — file vuoto che dice a GitHub di NON processare il sito con Jekyll (evita problemi con file/cartelle che iniziano con `_`)

## Come pubblicarlo su GitHub Pages

### 1. Crea un repository su GitHub
1. Vai su [github.com](https://github.com) ed effettua l'accesso (o crea un account gratuito).
2. Clicca su **"New repository"** (in alto a destra, icona `+` → "New repository").
3. Dai un nome al repository, ad esempio `salone-blu`.
4. Lascialo **Public** (necessario per GitHub Pages gratuito).
5. Non aggiungere README, .gitignore o licenza (li carichiamo noi).
6. Clicca **"Create repository"**.

### 2. Carica i file
1. Nella pagina del repository appena creato, clicca su **"uploading an existing file"** (o "Add file" → "Upload files").
2. Trascina dentro (o seleziona) i file `index.html` e `.nojekyll` scaricati.
   - Attenzione: `.nojekyll` è un file "nascosto" (inizia con il punto). Se il tuo sistema operativo non te lo mostra, va bene anche saltarlo: non è obbligatorio, è solo una precauzione.
3. Scrivi un messaggio di commit (es. "Primo caricamento del sito") e clicca **"Commit changes"**.

### 3. Attiva GitHub Pages
1. Nel repository, vai su **Settings** (in alto).
2. Nel menu a sinistra clicca su **Pages**.
3. Sotto "Build and deployment" → "Source", seleziona **"Deploy from a branch"**.
4. In "Branch" seleziona `main` (o `master`) e la cartella `/ (root)`, poi clicca **Save**.
5. Attendi 1–2 minuti: GitHub ti mostrerà l'indirizzo del sito pubblicato, del tipo:
   ```
   https://<tuo-nome-utente>.github.io/salone-blu/
   ```
6. Apri quel link: il sito è online! 🎉

### 4. Aggiornamenti futuri
Ogni volta che vuoi modificare il sito:
1. Vai nel repository su GitHub, apri `index.html`.
2. Clicca sull'icona della matita (✏️) per modificare, oppure carica di nuovo il file aggiornato tramite "Add file" → "Upload files" (sovrascrivendo quello esistente).
3. Salva le modifiche (commit): dopo circa un minuto il sito pubblico si aggiorna da solo.

### (Opzionale) Dominio personalizzato
Se in futuro vuoi collegare un dominio tuo (es. `salonblu.it`) invece di usare l'indirizzo `github.io`, nella stessa pagina **Settings → Pages** trovi il campo "Custom domain": basta inserire il dominio e configurare i record DNS indicati da GitHub.

---

Per qualsiasi modifica al contenuto del sito (testi, foto, orari, prezzi), basta scrivermi e aggiorno direttamente il file `index.html`.
