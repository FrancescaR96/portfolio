L’obiettivo di questa tesi è stato sviluppare una metodologia per ricostruire le climatologie 1991-2020 delle stazioni Meteonetwork, utilizzando dati giornalieri di temperatura massima, minima, media e precipitazioni cumulate. Meteonetwork (MNW) è un ottimo esempio di rete gestita da citizen scientists, con un'alta densità spaziale e un'elevata ridondanza delle misurazioni. Tuttavia, la discontinuità temporale dei dati rappresenta una sfida: le stazioni più longeve, attive dal 2002, dispongono di un massimo di 20 di anni di osservazioni, insufficienti per calcolare climatologie su almeno 30 anni. 
Per testare la metodologia, sono state selezionate 43 stazioni tra le più longeve, uniformemente distribuite sul territorio italiano.
Questa metodologia si avvale di tecniche di machine learning (ML) per stabilire relazioni tra dati osservati e dataset di rianalisi grigliati da utilizzare per la ricostruzione delle serie osservate. Tra i diversi dataset di rianalisi è stato individuato quello più idoneo da usare come input per i modelli ML. Sono stati poi valutati due algoritmi, Support Vector Regression (SVR) e Random Forest (RF), per determinarne il migliore per ciascuna variabile. I modelli sono stati ottimizzati per ogni stazione e variabile, e le serie temporali ricostruite sono state utilizzate per calcolare le climatologie mensili.

Esempio di risultato ottenuto:
![Final_Climatologies_lmb021](https://github.com/user-attachments/assets/82abcdc2-f1b9-4459-a7de-63bb16c2a05a)

Tutto il lavoro è stato sviluppato in linguaggio Python
