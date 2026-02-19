# 🔬 Relazioni di Laboratorio di Fisica

Benvenuti nella repository delle lezioni di Fisica e Matematica. Se sei un alunno, questo README ti serve a fare le relazioni di laboratorio.

Qui trovate i template delle due esperienze:

| File | Esperienza |
|------|-----------|
| `RelazioneLabMotoRU.html` | Moto Rettilineo Uniforme |
| `RelazioneLaboratorioConservazioneQuantitaMoto.html` | Conservazione della Quantità di Moto |

Ogni gruppo lavorerà su **un paragrafo** della relazione. Il vostro compito è produrre il contenuto della vostra sezione.

---

## Come lavorare: due percorsi possibili

### 🟢 Percorso A — Google Docs (consigliato)

Questo è il percorso più semplice. Ogni gruppo scrive la propria sezione su Google Docs, e i dati sperimentali vanno su un foglio Google condiviso.

**Documenti di testo (uno per sezione):**

1. Il professore vi condividerà un Google Doc per ciascuna sezione
2. Aprite il documento assegnato al vostro gruppo
3. Scrivete il contenuto della vostra sezione seguendo le indicazioni del template HTML (apritelo per vedere cosa vi si chiede)
4. Inserite le foto e i video direttamente nel documento

**Dati sperimentali (foglio condiviso):**

1. Il professore vi condividerà un Foglio Google per i dati
2. Ogni gruppo inserisce le proprie misure nelle celle indicate
3. Il foglio è unico e condiviso: potete vedere i dati di tutti

> Quando tutti i documenti saranno pronti, il professore li assemblerà nel file HTML finale — oppure, se c'è tempo, lo farete voi!

---

### 🔵 Percorso B — Modifica diretta dell'HTML su GitHub (avanzato)

Se vi sentite pronti, potete modificare direttamente i file HTML nella repo. Il risultato è più bello e professionale.

#### 1. Aprite il file

Dalla pagina principale della repo, cliccate sul file HTML che dovete modificare.

#### 2. Cliccate la matita ✏️

In alto a destra sopra il contenuto del file vedrete un'icona a forma di matita. Cliccatela per entrare in modalità modifica.

#### 3. Trovate la vostra sezione

Usate **Ctrl+F** (o **Cmd+F** su Mac) per cercare il titolo del paragrafo che vi è stato assegnato, ad esempio `Obiettivo` oppure `Procedimento`.

#### 4. Modificate il contenuto

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

#### 5. Inserire immagini e video

Per le immagini: prima caricate il file nella repo (vedi sotto), poi inserite nel punto giusto:

```html
<img src="nome_foto.jpg" alt="Descrizione della foto" style="max-width:100%">
```

Per i video potete:
- caricare il file nella repo e usare: `<video src="nome_video.mp4" controls style="max-width:100%"></video>`
- oppure incollare un link YouTube: `<a href="https://www.youtube.com/watch?v=XXXXX">Video dell'esperienza</a>`

#### 6. Fate il commit

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
| Obiettivo | 1 |
| Richiami teorici | 1 |
| Materiali e strumenti | 2 |
| Schema apparato | 2 |
| Procedimento | 3 |
| Video | 3 |
| Dati sperimentali | 4 |
| Elaborazione dati | 4 |
| Conclusioni | insieme |

- **Gruppo 1:** Amico, Barberini, Boscolo, Carletti, Cavaliere
- **Gruppo 2:** Chiovetta, Di Caro, Fartas, Feruglio, Gehad
- **Gruppo 3:** Lazzarini, Marigo, Maschera, Mason, Mazzari
- **Gruppo 4:** Merlo, Momoli, Paolella, Sacchetto, Salviato, Zambon

---

Buon lavoro! 💪
