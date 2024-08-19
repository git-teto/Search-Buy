# Search-Buy

Il progetto si pone l'obiettivo di sviluppare l'applicazione web Search&Buy che implementa un sito di e-commerce. 
Search&Buy gestisce il processo di vendita di prodotti commerciali ed è composto di due macro-scenari principali:
- gestione dei prodotti;
- gestione del carrello.
  
Di seguito sono analizzate in dettaglio le caratteristiche dei due macroscenari introdotti.Esistono due tipologie di utenti: venditore e cliente.

Il primo macro-scenario (gestione dei prodotti) consiste nella gestione del ciclo di vita dei prodotti dalla pubblicazione alla vendita.
Gli utenti venditori devono potersi registrare all'applicazione, modificare i propri dati/preferenze, cancellarsi.
Per ogni venditore si dovranno gestire informazioni quali nome, tipo di attività, numero di telefono, partita iva, recensioni, etc.
Un venditore, una volta registrato, può collegarsi all'applicazione e inserire nuovi prodotti o modificare/cancellare prodotti
esistenti di cui è responsabile (solo per gruppi di due persone).
Per ogni prodotto si dovranno gestire informazioni quali ad esempio tipologia, nome, caratteristiche, prezzo, tipologia di spedizione, revisioni,
offertespeciali a seconda del giorno della settimana, etc.

Il secondo scenario (gestione del carrello) consiste nella classica gestione delle attività dei clienti all'interno di una applicazione di
e-commerce. I clienti devono potersi registrare, modificare i propri dati/preferenze, cancellarsi. 
Per ogni utente si devono memorizzare informazioni personali (ad es., nome, cognome) ed informazioni relative all'account generato. 
Al cliente vengono anche associate informazioni riguardanti il meccanismo di pagamento dei prodotti (ad es., carta di credito o carta prepagata). 
Inoltre, in fase di registrazione gli utenti possono selezionare delle preferenze (tra le quali quelle di privacy e relative
all'applicazione) per la personalizzazione dei servizi (ad esempio, offerte speciali in bacheca per la tipologia di prodotto preferita). In questo sce-
nario, gli utenti registrati (min 2) possono fare login al sito, ricercare un prodotto di interesse, aggiungerlo al carrello e concludere l'acquisto dei
prodotti nel carrello. In aggiunta, all'utente viene data la possibilità di annullare uno o più acquisti effttuati nella stessa giornata. Per la gestione e
pianificazione degli acquisti, l'applicazione deve mantenere informazioni sulla disponibilità di un determinato prodotto, gestendo lo scenario di
prodotto non più disponibile. L'applicazione dovrà inoltre mantenere lo storico degli acquisti fatti dai clienti.
