# Progetto Basi di Dati - Kartodromo Punto di Corda
# Gabriel Tavcar SM3201659 

![Demo dell'applicazione](demo.gif)


L'applicazione permette di gestire le operazioni quotidiane più importanti del kartodromo Punto di Corda. Le operazioni principali sono: 

* **Registrazione Nuovo Cliente:** Registrazione di un nuovo cliente prendendo in input: nome, cognome, data di nascita, email.
* **Assegnazione Turno e Kart:** Assegnazione di un kart e un turno a un cliente.
* **Turni e Piloti Registrati:** Schemata generale che permette la visualizzazione dei turni programmati con l'elenco dei piloti iscritti.
* **Visualizzazione Classifiche:** Classifica dei 10 migliori tempi assoluti, con possiiblità di cercare i tempi sul giro di un specifico utente filtrando i tempi per categoria.


* **Stack Tecnologico:**
  * **Frontend:** HTML5, CSS.
  * **Backend:** Python con framework Flask.
  * **Database:** MySQL hostato in locale tramite XAMPP con webserver Apache.


* **Sicurezza**
Tutte le operazioni di scrittura nel database (INSERT) e di ricerca (SELECT), utilizzano il parametro %s proteggendo la query dagli attacchi SQL Injection.
