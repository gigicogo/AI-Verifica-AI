# ✅ Prima di usare l’IA — 12 decisioni per la PA

**Prima di usare l’IA** è una verifica individuale, in italiano, composta da 12 situazioni operative sull’uso dell’intelligenza artificiale nella Pubblica Amministrazione.

Il test aiuta a distinguere ciò che deriva dagli articoli 13 e 14 della Legge 132/2025, ciò che riguarda privacy e regole interne dell’ente e ciò che è invece una scelta di metodo, come il prompting o l’uso di fonti documentali.

## 🎯 A chi è rivolto

La verifica è pensata per dipendenti della Pubblica Amministrazione italiana, anche da remoto e in postazione individuale.

È utile per:

- funzionari ed esecutori che utilizzano o valutano strumenti di IA;
- direttori e dirigenti coinvolti nelle decisioni e nella governance dell’IA;
- referenti ICT, privacy, sicurezza e trasformazione digitale;
- formatori che vogliono proporre un test breve di consapevolezza operativa.

La durata stimata è di **15–20 minuti**, con una restituzione collettiva consigliata di circa 5 minuti.

## 🧠 L’obiettivo

Il test non verifica la memoria delle norme, ma la capacità di prendere decisioni adeguate in situazioni concrete.

In particolare, aiuta a distinguere:

- **obblighi e principi normativi**, come responsabilità umana, tracciabilità e informazione;
- **regole sulla protezione dei dati**, come minimizzazione e liceità del trattamento;
- **regole interne dell’ente**, come strumenti autorizzati e procedure di lavoro;
- **tecniche operative**, come prompt diretto, meta-prompting, RAG/NotebookLM e confronto tra risposte.

## 🗂️ Le quattro aree

| Area | Cosa valuta |
|---|---|
| **Ruoli e decisioni** | Responsabilità umana, supporto dell’IA, decisione amministrativa e informazione al destinatario. |
| **Dati e strumenti** | Minimizzazione, dati personali, strumenti autorizzati e condizioni d’uso. |
| **Metodi e fonti** | Uso delle fonti, citazioni verificabili, prompt e tecniche di lavoro. |
| **Tracciabilità** | Registrazione proporzionata dell’utilizzo dell’IA e conoscibilità del funzionamento. |

## 🕹️ Come funziona

1. Avvia la verifica.
2. Leggi uno dei 12 scenari simulati.
3. Scegli la risposta che ritieni più corretta.
4. Indica quanto ti senti sicuro: **poco**, **abbastanza** o **molto**.
5. Conferma la decisione e leggi il feedback.
6. Al termine, consulta punteggio, ripasso degli errori ed eventuali fonti.

Per ogni risposta viene registrato il **primo tentativo**. Il feedback indica la scelta più adeguata, la motivazione e, quando pertinente, il riferimento normativo o metodologico.

## 📊 Autovalutazione della sicurezza

Prima di confermare ogni risposta, il partecipante dichiara il proprio livello di sicurezza.

Alla fine, il sistema segnala anche gli errori commessi con **eccessiva sicurezza**: un elemento utile per riflettere sul rapporto tra fiducia, verifica e responsabilità.

Il punteggio finale è un feedback formativo, non una certificazione di competenze né un giudizio sulla conformità di un procedimento.

## 📄 Norme e riferimenti

L’esercitazione richiama in particolare:

- **Articolo 13 della Legge 132/2025**: professioni intellettuali, IA strumentale e di supporto, prevalenza del lavoro intellettuale e comunicazione chiara al destinatario della prestazione.
- **Articolo 14 della Legge 132/2025**: finalità dell’IA nella PA, conoscibilità del funzionamento, tracciabilità dell’utilizzo, autonomia del potere decisionale umano e misure tecniche, organizzative e formative.
- **GDPR — Regolamento UE 2016/679**: minimizzazione e liceità del trattamento dei dati personali.

### Fonti

- [Legge 132/2025, art. 13 — testo ufficiale](https://def.giustiziatributaria.gov.it/DocTribFrontend/executePrintArticolo.do?articolo=Articolo+13&codiceOrdinamento=0000000000000130000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000&id=%7B727C8823-31DE-4724-AFD5-1A4EC58809B3%7D)
- [Legge 132/2025, art. 14 — testo ufficiale](https://def.giustiziatributaria.gov.it/DocTribFrontend/executePrintArticolo.do?articolo=Articolo+14&codiceOrdinamento=0000000000000140000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000&id=%7B727C8823-31DE-4724-AFD5-1A4EC58809B3%7D)
- [GDPR — Regolamento UE 2016/679](https://eur-lex.europa.eu/eli/reg/2016/679/oj/ita)

## 💻 Come avviare la verifica

L’app è una **web app statica** contenuta in un unico file `index.html`.

- Non richiede iscrizione, account o API key.
- Non utilizza modelli IA connessi, servizi esterni o backend.
- Non raccoglie né trasmette i risultati.
- Funziona anche offline.
- Solo i link alle fonti ufficiali richiedono accesso a Internet.

### Avvio locale

1. Scarica o clona il repository.
2. Apri `index.html` con un browser moderno: Chrome, Firefox, Edge o Safari.
3. Seleziona **Inizia la verifica**.

### Clonare il repository

```bash
git clone [https://github.com/gigicogo/AI-Verifica-AI.git](https://github.com/gigicogo/AI-Verifica-AI.git)
cd AI-Verifica-AI
```

## 🖨️ Riepilogo e uso in aula

Al termine è possibile:

- visualizzare il punteggio complessivo;
- rivedere gli errori e le spiegazioni;
- scaricare un riepilogo individuale in `.txt`;
- stampare o salvare il risultato in PDF dal browser.

Per l’uso in aula:

1. Condividi il link o il file con i partecipanti.
2. Chiedi di rispondere individualmente, senza confrontarsi durante il test.
3. Non richiedere screenshot personali o invio dei punteggi.
4. Se vuoi valutare l’apprendimento, chiedi in forma anonima quali decisioni sono risultate più difficili.

L’app non registra nomi e non trasmette punteggi al formatore. Il riepilogo può essere scaricato solo su iniziativa del partecipante.

## 🛠️ Personalizzazione

Tutto il test è contenuto nel file `index.html`.

Le domande, le alternative, le spiegazioni e i riferimenti si trovano nell’array JavaScript `QUIZ`.

Per adattare il test a un ente o a un percorso formativo:

1. Modifica scenari, opzioni e risposte corrette.
2. Aggiorna spiegazioni e riferimenti normativi.
3. Verifica la coerenza tra domanda, risposta attesa e feedback.
4. Testa il file prima della pubblicazione.

## ⚠️ Limiti

Questo test:

- non è un parere legale;
- non sostituisce la formazione obbligatoria o le istruzioni dell’ente;
- non certifica la conformità di un procedimento;
- non sostituisce le valutazioni delle funzioni competenti;
- indica soltanto l’allineamento alle decisioni attese negli scenari simulati.

## 🧪 Possibili evoluzioni

- Aggiunta di nuovi scenari per diversi settori della PA.
- Versione per gruppi con confronto anonimo delle risposte.
- Esportazione del riepilogo in Markdown o PDF strutturato.
- Versione inglese.
- Integrazione con materiali formativi e checklist organizzative.
- Aggiornamento dei riferimenti normativi in caso di evoluzioni legislative.

## 🤝 Contribuire

Sono benvenuti suggerimenti su nuovi scenari, correzioni normative, miglioramenti didattici e materiali di supporto.

1. Apri una Issue per proporre un’idea o segnalare un problema.
2. Oppure apri una Pull Request con una modifica o un nuovo scenario.
3. Mantieni la coerenza tra scenario, risposta attesa, spiegazione e fonte.

---

## 📄 Licenza

Da definire: si suggerisce una licenza aperta (es. MIT o CC BY 4.0) per favorire il riuso da parte di altri formatori o altri enti. Sostituisci questo paragrafo con il testo della licenza scelta e il file `LICENSE` del repo.

## 👤 Autore e contesto

**Gianluigi Cogo**  
Content creator e technical writer interessato ad AI generativa, automazioni, viaggi e strumenti digitali. Consulente e docente sui temi dell’IA generativa nella Pubblica Amministrazione.

L’app nasce come esercitazione nel percorso operativo **“L’IA nella Pubblica Amministrazione — Percorso operativo per l’uso consapevole, sicuro e governato dell’IA generativa”** (20 ore: percorso base per funzionari ed esecutori + modulo governance per direttori e dirigenti). Per info sul corso contattami usando i social qui sotto.

- 📮 **Newsletter:** [gigicogo.substack.com](https://gigicogo.substack.com)
- 📝 **Blog:** [medium.com/webeconoscenza](https://medium.com/webeconoscenza)
- ▶️ **YouTube:** [youtube.com/@gigicogo](https://youtube.com/@gigicogo)
- 💼 **LinkedIn:** [linkedin.com/in/gigicogo](https://www.linkedin.com/in/gigicogo)
