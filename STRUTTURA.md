# Titolo

Applicazione di tecnologie di Text Extraction e Machine Learning per il riconoscimento e la classificazione di documenti tecnici in ambito Fashion

# Introduzione

- Contesto della digitalizzazione documentale
- Gestione dei documenti non strutturati in ambito industriale
- Obiettivi del progetto di tesi
- Struttura del documento

# Capitolo 1 – Contesto applicativo e dominio del problema

## 1.1 Il settore dell’abbigliamento e i processi di certificazione
- Produzione dei modelli finiti
- Articoli e componenti riutilizzabili
- Importanza dei test di laboratorio nella messa in produzione

## 1.2 Struttura del sistema informativo esistente
- Modelli finiti e articoli
- Relazioni gerarchiche tra modelli e componenti
- Gestione delle prove di laboratorio e dei report PDF

## 1.3 Criticità del processo attuale
- Inserimento manuale dei report
- Errori di associazione documento–articolo
- Difficoltà operative per utenti poco esperti

## 1.4 Obiettivi funzionali del progetto
- Supporto automatico al caricamento dei report
- Riduzione degli errori umani
- Miglioramento dell’esperienza utente


# Capitolo 2 – Background e stato dell'arte

## 2.1 Acquisizione del testo dai documenti
- Estrazione del testo da PDF nativi
- OCR per documenti scansionati
- Confronto tra i due approcci

## 2.2 Information Extraction
- Information Extraction
- Named Entity Recognition (NER)
- Classificazione dei documenti

## 2.3 Soluzioni commerciali
- Servizi OCR e Document AI in cloud
- Vantaggi: accuratezza, scalabilità, affidabilità
- Svantaggi: costi, lock-in tecnologico, privacy

## 2.4 Soluzioni open source
- Motori di Text Extraction open source
- Framework di machine learning


# Capitolo 3 – Progettazione

## 3.1 Analisi del problema applicativo
- Contesto operativo dell’applicazione
- Tipologia dei documenti trattati
- Obiettivi dell’automazione documentale
- Vincoli di integrazione con il sistema informativo esistente

## 3.2 Analisi dei requisiti
- Caricamento e gestione dei documenti PDF
- Estrazione delle informazioni rilevanti
- Proposta automatica di articoli e modelli compatibili
- Supporto a documenti eterogenei
- Requisiti di accuratezza, scalabilità e manutenibilità
- Considerazioni sui costi operativi e sulla sostenibilità della soluzione

## 3.3 Scelte progettuali e approcci considerati
- Approccio basato su servizi gestiti (Google Cloud Document AI)
- Approccio basato su modelli custom (PDF parser e spaCy)
- Motivazioni della scelta di un approccio comparativo
- Analisi preliminare di vantaggi e svantaggi dei due paradigmi

## 3.4 Architettura generale della soluzione
- Panoramica dell’architettura complessiva
- Posizionamento dei moduli di analisi documentale
- Integrazione con l’applicazione e il database esistenti
- Flussi di comunicazione ad alto livello

## 3.5 Strategie di associazione documento–entità
- Associazione basata su regole deterministiche
- Associazione basata su similarità semantica
- Strategie ibride e criteri decisionali
- Impatto dell’approccio di estrazione sul processo di associazione


# Capitolo 4 – Implementazione

## 4.1 Fine-tuning con Google Cloud
- Panoramica del servizio Document AI
- Tipologia di processor utilizzati
- Configurazione e deploy dei modelli
- Formato e struttura dell’output prodotto
- Integrazione tramite API con l’applicazione esistente

## 4.2 Implementazione del modello di NER
- Estrazione del testo dai PDF nativi
- Parsing e normalizzazione del contenuto testuale
- Pipeline di Information Extraction
- Modello di Named Entity Recognition basato su spaCy
- Gestione delle regole e delle fasi di post-processing

## 4.3 Integrazione con l’applicazione esistente
- Architettura delle API
- Flussi di comunicazione tra i servizi
- Gestione e persistenza dei risultati dell’analisi
- Utilizzo dei dati estratti nei processi applicativi


# Capitolo 5 – Valutazione dei risultati e confronto

## 5.1 Metodologia di valutazione
- Dataset di test
- Metriche di valutazione

## 5.2 Risultati sperimentali
- Analisi quantitativa
- Analisi qualitativa degli errori

## 5.3 Analisi dei costi
- Costi delle soluzioni commerciali
- Costi delle soluzioni open source
- Valutazione nel contesto industriale

## 5.4 Discussione dei risultati
- Vantaggi e limiti delle soluzioni adottate
- Considerazioni sulla scalabilità
- Impatto sul processo aziendale


# Conclusioni e sviluppi futuri
- Riepilogo del lavoro svolto
- Obiettivi raggiunti
- Possibili sviluppi futuri:
  - Miglioramento dei modelli di machine learning
  - Introduzione di meccanismi di feedback utente
  - Estensione ad altri domini applicativi
