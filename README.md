# 🔬 Relazioni di Laboratorio di Fisica

Benvenuti nella repository delle lezioni di Fisica e Matematica. Se sei un alunno, questo README ti serve a fare le relazioni di laboratorio. Qui trovate i template delle due esperienze:

| File | Esperienza |
|------|-----------|
| `RelazioneLabMotoRU.html` | Moto Rettilineo Uniforme |
| `RelazioneLaboratorioConservazioneQuantitaMoto.html` | Conservazione della Quantità di Moto |

Ogni gruppo lavorerà su **un paragrafo** della relazione. Il vostro compito è sostituire il testo in rosso (i campi `todo`) con il contenuto vero.

---

## Come modificare un file

### 1. Aprite il file

Dalla pagina principale della repo, cliccate sul file HTML che dovete modificare (es. `relazione_MRU.html`).

### 2. Cliccate la matita ✏️

In alto a destra sopra il contenuto del file vedrete un'icona a forma di matita. Cliccatela per entrare in modalità modifica.

### 3. Trovate la vostra sezione

Usate **Ctrl+F** (o **Cmd+F** su Mac) per cercare il titolo del paragrafo che vi è stato assegnato, ad esempio `Obiettivo` oppure `Procedimento`.

### 4. Modificate il contenuto

Sostituite il testo tra i tag. Ad esempio, se trovate:

```html
<p class="todo">Descrivere lo scopo dell'esperienza...</p>
```

sostituitelo con il vostro testo:

```html
<p>Lo scopo dell'esperienza è verificare che un carrello
in moto rettilineo uniforme mantenga velocità costante,
confrontando le velocità misurate su due tratti diversi
della rotaia.</p>
```

> **Nota:** quando sostituite il contenuto, togliete `class="todo"` dal tag — così il testo non apparirà più in rosso.

### 5. Inserire immagini e video

Per le immagini: prima caricate il file nella repo (vedi sotto), poi inserite nel punto giusto:

```html
<img src="nome_foto.jpg" alt="Descrizione della foto" style="max-width:100%">
```

Per i video potete:
- caricare il file nella repo e usare: `<video src="nome_video.mp4" controls style="max-width:100%"></video>`
- oppure incollare un link YouTube: `<a href="https://www.youtube.com/watch?v=XXXXX">Video dell'esperienza</a>`

### 6. Fate il commit

Quando avete finito, scorrete in basso fino alla sezione **"Commit changes"**:

- Nel campo del messaggio scrivete **cosa avete fatto**, ad esempio: `Completata sezione Procedimento - MRU`
- Lasciate selezionato "Commit directly to the main branch"
- Cliccate il pulsone verde **Commit changes**

Fatto! 🎉

---

## Come caricare immagini o video nella repo

1. Dalla pagina principale della repo, cliccate **Add file → Upload files**
2. Trascinate i vostri file (foto, grafici, video)
3. Scrivete un messaggio di commit (es. `Aggiunta foto apparato MRU`)
4. Cliccate **Commit changes**

> ⚠️ **Attenzione ai nomi dei file!** Usate nomi senza spazi e senza accenti (es. `apparato_mru.jpg`, non `foto apparato MRU (1).jpg`). Il nome che date al file deve corrispondere esattamente a quello che scrivete nell'`<img src="...">`.

---

## Come vedere l'anteprima della relazione

L'HTML non viene renderizzato direttamente su GitHub. Per vedere il risultato:

1. Dalla pagina del file, cliccate **Raw**
2. Copiate l'URL dalla barra degli indirizzi
3. Incollatelo su [htmlpreview.github.io](https://htmlpreview.github.io/)

Oppure, più semplicemente: scaricate il file sul vostro computer e apritelo con il browser.

---

## Regola d'oro

> **Un paragrafo, un gruppo.** Non modificate le sezioni degli altri gruppi. Se trovate un errore in una sezione non vostra, segnalatelo al gruppo responsabile.

---

## Assegnazione delle sezioni

| Sezione | Gruppo |
|---------|--------|
| Obiettivo | |
| Richiami teorici | |
| Materiali e strumenti | |
| Schema apparato | |
| Procedimento | |
| Video | |
| Dati sperimentali | |
| Elaborazione dati | |
| Conclusioni | |

*Il professore compilerà questa tabella con i nomi dei gruppi.*

---

Buon lavoro! 💪
