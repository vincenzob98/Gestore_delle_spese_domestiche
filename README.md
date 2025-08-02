# Gestore_delle_spese_domestiche
Contesto del Progetto
Gestire le spese domestiche in modo semplice e strutturato aiuta a tenere sotto controllo il budget familiare. Questo progetto propone un'app Python (utilizzabile su Google Colab) che permette di registrare le spese quotidiane, visualizzare report mensili e individuare rapidamente le transazioni più significative.

Obiettivo
Fornire uno strumento pratico per tracciare, riassumere e analizzare le proprie spese domestiche attraverso operazioni semplici e immediate, interamente basate su file CSV.

Funzionalità Principali
Aggiunta di una transazione: inserisci data, descrizione e importo.
Report mensile: riepilogo delle transazioni aggregate per mese.
Top 10 transazioni: elenco delle 10 spese più alte archiviate.
Struttura dei Dati
Le spese vengono salvate in un file chiamato registro_spese.csv.
Il formato previsto è il seguente (vedi anche il file di esempio registro_spese.csv incluso nella repository):

| Data | Descrizione | Importo | |------------|-------------------------|---------| | 18/06/2023 | Rata mutuo | 1231 | | 15/02/2021 | Acquisto scooter | 4323 | | 01/05/2024 | Spesa supermercato | 58.3 | | 25/05/2024 | Cena ristorante | 47 | | 01/06/2024 | Bolletta luce | 89.4 |

Attenzione: Non includere dati personali reali nella repository. Utilizza eventualmente il file di esempio fornito.

Esempio di file registro_spese.csv
Data,Descrizione,Importo
18/06/2023,Rata mutuo,1231
15/02/2021,Acquisto scooter,4323
01/05/2024,Spesa supermercato,58.3
25/05/2024,Cena ristorante,47
01/06/2024,Bolletta luce,89.4
Come utilizzare l'applicazione
Apri il notebook in Google Colab.
Assicurati di avere nella stessa cartella il file registro_spese.csv.
Segui il menu per:
Aggiungere una nuova spesa.
Ottenere il report mensile.
Visualizzare la Top 10 delle spese più elevate.
Requisiti
Python 3.x
Librerie standard (csv, os)
Google Colab oppure un ambiente Python classico
Esempi di output
2024-05 105.3
2024-06 89.4
18/06/2023 Rata mutuo 1231
15/02/2021 Acquisto scooter 4323
Note sulla privacy
Non caricare mai dati sensibili o personali pubblicamente nelle repository.
Inserisci o condividi solo file di esempio come quello fornito per rispettare la privacy degli utenti.

Licenza
MIT

Contatti

Creato nell’ambito del corso ProfessionAI, a cura di Vincenzo Barone e supervisione di ProfessionAI, autore Giuseppe Gullo.
