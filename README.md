# MERGER_EVALUATION

Caso di studio teorico e anonimizzato per l'analisi di una fusione per incorporazione ai sensi dell'art. 172, comma 7, del TUIR.

## Descrizione

`index.html` è una dashboard HTML autonoma che illustra, a fini didattici:

- il limite patrimoniale applicabile al riporto delle perdite;
- il test di vitalita economica;
- l'analisi del periodo infrannuale pre-fusione;
- l'utilizzo dei risultati post-fusione come elementi confermativi della sostanza economica;
- una possibile struttura di memoria difensiva;
- le principali conclusioni e cautele metodologiche.

## Natura del caso

Il progetto utilizza esclusivamente etichette funzionali:

- **Societa A**, incorporata;
- **Societa B**, incorporante.

Nomi, date secondarie, importi e indicatori sono sintetici e modificati. Non sono presenti codici fiscali, partite IVA, nominativi, indirizzi, protocolli o riferimenti a procedimenti reali.

## Avvertenza

Questo repository ha finalita esclusivamente didattiche e informative.

Non costituisce:

- consulenza fiscale;
- consulenza legale;
- parere professionale;
- modello pronto per il deposito presso l'Agenzia delle Entrate o altra autorita.

L'applicazione dell'art. 172, comma 7, TUIR dipende dal testo normativo vigente *ratione temporis*, dalla documentazione contabile e societaria effettiva, dalle dichiarazioni fiscali e dalle circostanze del caso concreto.

## Utilizzo locale

Non sono richieste dipendenze, server o procedure di build.

1. Scaricare o clonare il repository.
2. Aprire `index.html` con un browser moderno.
3. Usare la navigazione laterale per consultare le sezioni.
4. Usare il comando **Stampa / PDF** per creare una copia stampabile.

## Pubblicazione con GitHub Pages

### Metodo consigliato

1. Caricare tutti i file di questo pacchetto nella root del repository.
2. Su GitHub aprire **Settings > Pages**.
3. In **Build and deployment**, scegliere **Deploy from a branch**.
4. Selezionare il branch `main` e la cartella `/ (root)`.
5. Salvare e attendere la pubblicazione.

In alternativa, il file puo essere collocato nella cartella `/docs`, selezionando `/docs` nelle impostazioni di GitHub Pages.

## Struttura del repository

```text
MERGER_EVALUATION/
├── index.html
├── 404.html
├── .nojekyll
├── README.md
└── LICENSE
```

## Personalizzazione

Le variabili del caso studio sono incorporate direttamente nell'HTML. Per modificare lo scenario:

1. aprire il file HTML in un editor come Visual Studio Code;
2. cercare i valori presenti nelle schede e nelle tabelle;
3. aggiornare gli importi mantenendo la coerenza tra:
   - perdite pregresse;
   - limite patrimoniale;
   - esiti del test di vitalita;
   - dati infrannuali;
   - risultati post-fusione.

Prima della pubblicazione, verificare che non siano stati inseriti dati personali, aziendali o fiscali reali.

## Licenza

Il codice e la documentazione sono distribuiti con licenza MIT. Vedere il file [`LICENSE`](LICENSE).

La licenza MIT consente utilizzo, copia, modifica, fusione, pubblicazione e distribuzione, purche l'avviso di copyright e il testo della licenza siano mantenuti.

## Autore

Carlo Rizzoli
