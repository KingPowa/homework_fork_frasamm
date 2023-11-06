# Test per la selezione Informatico Junior

## Descrizione

Nella cartella [data](data/) sono presenti 55 matrici. Ogni matrice rappresenta il trascrittoma di un campione: sulle righe sono riportati i geni del genoma umano con la rispettiva espressione (conte).

---

### Primo esercizio
Partendo da questi dati tabulari il candidato dovrà:

1) Eliminare, per ogni campione, i geni poco espressi: ovvero, geni con meno di 10 conte.
2) Unire le matrici risultanti in un unico data frame ed eseguire un'analisi delle componenti principali.
3) Visualizzare il risultato.

---

### Secondo esercizio
Partendo dal risultato del primo esercizio, eseguire l'adattamento di una sequenza di modelli di spline naturali [^1], con gradi di libertà da 1 a 20. In particolare, è necessario mostrare come i gradi di libertà controllino il compromesso bias-varianza. 
Ottenuti i grafici richiesti, il candidato dovrà indicare quale modello si adatta meglio ai dati, e motivarne la scelta.

---

Il candidato può utilizzare qualsiasi strumento, linguaggio di programmazione o software che ritenga opportuno o consono all'analisi. 
Il codice utilizzato per eseguire gli esercizi deve essere condiviso su questo repository creando una richiesta di pull di un apposito branch o invitanto [@giusmar](https://github.com/giusmar) e [@ccolantuono](https://github.com/ccolantuono) a partecipare ad un fork.

[^1]: Le spline di regressione implicano la divisione dell'intervallo di x in k regioni distinte. All'interno di ciascuna regione, una funzione polinomio è adattata ai dati. Tuttavia, questi polinomi sono vincolati in modo che si uniscano senza problemi di confini regionali o nodi. A condizione che l'intervallo sia diviso in un numero sufficiente di regioni, ciò può produrre un adattamento estremamente flessibile.
