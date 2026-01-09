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


# Capitolo 2 – Tecnologie per l’acquisizione e l’analisi dei documenti

## 2.1 Acquisizione del testo dai documenti
- Estrazione del testo da PDF nativi
- OCR per documenti scansionati
- Confronto tra i due approcci

## 2.2 Document Understanding e Machine Learning
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


# Capitolo 3 – Analisi dei requisiti e progettazione della soluzione

## 3.1 Requisiti funzionali
- Caricamento dei documenti PDF
- Estrazione delle informazioni rilevanti
- Proposta automatica di articoli e modelli compatibili

## 3.2 Architettura della soluzione
- Panoramica dell’architettura
- Modulo di analisi documentale
- Integrazione con il database esistente

## 3.3 Strategie di associazione documento–entità
- Approccio basato su regole
- Approccio basato su similarità
- Soluzioni ibride


# Capitolo 4 – Implementazione della soluzione

## 4.1 Dataset e tipologia dei documenti
- Tipologie di report di laboratorio analizzati
- Struttura dei documenti PDF
- Problematiche riscontrate nei dati reali

## 4.2 Pipeline di elaborazione dei documenti
- Pre-processing dei PDF
- Estrazione del testo
- Normalizzazione e pulizia dei dati
- Estrazione delle informazioni chiave

## 4.3 Integrazione con l’applicazione esistente
- Architettura delle API
- Flussi di comunicazione
- Gestione dei risultati dell’analisi

## 4.4 Scelte progettuali e implementative
- Motivazioni delle tecnologie adottate
- Compromessi e limitazioni


# Capitolo 5 – Valutazione dei risultati e confronto tra le soluzioni

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
