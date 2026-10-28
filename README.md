# Prima di usare l'IA — 12 decisioni per la PA

Una web app educativa, in **italiano**, per una verifica individuale al termine dei primi due blocchi della Sessione 3 del Modulo B.

## Cosa contiene

- **12 scenari** con decisioni a scelta multipla, commento e riscontro normativo.
- **Autovalutazione della sicurezza** con cui si risponde (poco, abbastanza, molto): alla fine segnala anche gli errori dati con eccessiva sicurezza.
- Quattro aree: **ruoli e decisioni**, **dati e strumenti**, **metodi e fonti**, **tracciabilità**.
- **Punteggio finale**, ripasso degli errori ed esportazione individuale in `.txt`; stampa come PDF dal browser.
- Nessuna iscrizione, nessun account, nessun modello IA connesso, nessun servizio esterno e nessuna raccolta dei risultati.

## Come avviarla sul computer

1. Scarica `index.html`.
2. Aprilo con un browser moderno (Chrome, Firefox, Edge, Safari).
3. Seleziona **Inizia la verifica**.

Funziona anche **offline**. Solo i link alle fonti ufficiali richiedono accesso a Internet.

## Pubblicare con GitHub Pages

1. Crea un repository, per esempio `test-legge-132-pa`.
2. Carica `index.html` (e questo `README.md`) nella cartella principale del repository.
3. Vai in **Settings > Pages** e seleziona **Deploy from a branch**, branch `main` e cartella `/(root)`.
4. Una volta pubblicato, condividi l'indirizzo GitHub Pages.

Non sono necessarie API key, dipendenze, build né backend. Il contenuto del repository è accessibile pubblicamente se il repository o il sito Pages sono pubblici: non aggiungere fascicoli reali o dati personali.

## Destinatari e durata

- Dipendenti della Pubblica Amministrazione italiana, anche da remoto e in postazione individuale.
- Durata stimata: **15–20 minuti**. Consigliata una restituzione collettiva di 5 minuti.
- Gli esempi sono **fittizi e generalisti**, riutilizzabili con enti diversi.

## Quali norme e metodi distingue

**Articolo 13 della Legge 132/2025**: professioni intellettuali, IA strumentale e di supporto, prevalenza del lavoro intellettuale, comunicazione chiara al destinatario della prestazione.

**Articolo 14 della Legge 132/2025**: finalità dell'IA nella PA, conoscibilità del funzionamento e tracciabilità dell'utilizzo, autonomia del potere decisionale umano, misure tecniche, organizzative e formative.

**Da non confondere con gli obblighi degli artt. 13 e 14**: minimizzazione e liceità dei dati (GDPR), scelta dell'ambiente autorizzato (anche in base alle regole interne), e tecniche di lavoro come *meta-prompting*, RAG/NotebookLM o confronto delle risposte. Sono concetti didatticamente collegati, non strumenti imposti per legge dagli articoli 13 e 14.

### Fonti

- [Legge 132/2025, art. 13 — testo ufficiale](https://def.giustiziatributaria.gov.it/DocTribFrontend/executePrintArticolo.do?articolo=Articolo+13&codiceOrdinamento=0000000000000130000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000&id=%7B727C8823-31DE-4724-AFD5-1A4EC58809B3%7D)
- [Legge 132/2025, art. 14 — testo ufficiale](https://def.giustiziatributaria.gov.it/DocTribFrontend/executePrintArticolo.do?articolo=Articolo+14&codiceOrdinamento=0000000000000140000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000&id=%7B727C8823-31DE-4724-AFD5-1A4EC58809B3%7D)
- [GDPR — Regolamento UE 2016/679](https://eur-lex.europa.eu/eli/reg/2016/679/oj/ita)

## Uso in aula

Condividi il link in chat. Chiedi a ciascun partecipante di rispondere individualmente, senza confrontarsi con altri durante il test. Non richiedere screenshot personali: se desideri verificare l'apprendimento, puoi chiedere anonimamente quali decisioni sono risultate più difficili.

La web app non registra nomi e non trasmette punteggi al formatore. Il riepilogo può essere scaricato **solo su iniziativa del partecipante**.

## Modifiche

Il test è integralmente contenuto nel file `index.html`. Le domande, le alternative, le spiegazioni e i riferimenti si trovano nell'array JavaScript `QUIZ`. Per adattare casi o normativa, aggiornare questo array e verificare la coerenza delle risposte prima della pubblicazione.

## Limiti

Il test **non è un parere legale**, non sostituisce la formazione obbligatoria o le istruzioni dell'ente, e non certifica la conformità di un procedimento. Il punteggio indica soltanto l'allineamento alle decisioni attese per gli scenari simulati.
