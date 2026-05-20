# Progetto Basi di Dati - "Punto di Corda"

![Demo](demo.gif)


Il codice traduce in un'interfaccia grafica funzionante le operazioni interattive più critiche del kartodromo:

* **Nuovi Tesseramenti:** Inserimento dei clienti nel sistema con calcolo automatico della scadenza annuale della tessera.
* **Gestione Ingressi:** Assegnazione dinamica di piloti, turni e kart operativi interrogando in tempo reale le disponibilità del database.
* **Monitoraggio Pista:** Visualizzazione immediata delle sessioni programmate e dei piloti iscritti a ogni singola manche.
* **Classifiche Top 10:** Estrazione dei migliori tempi assoluti, con filtri dinamici per pilota e categoria. Questa funzionalità dimostra l'efficacia della ridondanza (`MigliorTempo`) progettata nel database per ottimizzare drasticamente i tempi di lettura.
