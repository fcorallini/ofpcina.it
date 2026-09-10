# ofPCina

Sito statico di **ofPCina**, realizzato con [Hugo](https://gohugo.io/).

## Avvio rapido

Clonare il repository:

```bash
git clone git@github.com:fcorallini/ofpcina.it.git
cd ofpcina
```

Installa Hugo Extended. Su Ubuntu/Debian:

```bash
sudo apt update
sudo apt install hugo
```

Avvia il server di sviluppo:

```bash
hugo server --bind 127.0.0.1 --port 1314
```

Il sito sarà disponibile su [http://127.0.0.1:1314/](http://127.0.0.1:1314/). Hugo rigenera automaticamente le pagine quando si modificano file del progetto.

Per produrre la versione statica da pubblicare:

```bash
hugo --minify
```

I file generati vengono salvati in `public/`.

## Struttura delle cartelle

- `content/` — contenuti in Markdown: pagine, notizie, eventi e gallerie.
- `layouts/` — template Hugo e shortcode, inclusi navbar e homepage.
- `static/` — risorse copiate senza dal sito originale.
- `scripts/` — strumenti usati per importare o aggiornare contenuti.
- `archetypes/` — modelli per nuovi contenuti Hugo.
- `config.toml` — configurazione del sito e menu di navigazione.
- `public/` — output generato da Hugo; non modificare direttamente questi file e non committare.
