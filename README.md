## Requisiti

Il progetto si pone l’obiettivo di sviluppare l’applicazione web **Search&Buy**, che implementa un sito di e-commerce. **Search&Buy** gestisce il processo di vendita di prodotti commerciali ed è composto da due macro-scenari principali:

1. **Gestione dei prodotti**
2. **Gestione del carrello**

### Gestione dei prodotti

Questo scenario riguarda la gestione del ciclo di vita dei prodotti, dalla pubblicazione alla vendita. Gli utenti venditori devono poter:

- Registrarsi all'applicazione
- Modificare i propri dati/preferenze
- Cancellare il proprio account

Per ogni venditore devono essere gestite le seguenti informazioni:

- Nome
- Tipo di attività
- Numero di telefono
- Partita IVA
- Recensioni

Un venditore registrato può collegarsi all’applicazione e:

- Inserire nuovi prodotti
- Modificare prodotti esistenti
- Cancellare prodotti esistenti (solo per gruppi di due persone)

Per ogni prodotto, le informazioni da gestire includono:

- Tipologia
- Nome
- Caratteristiche
- Prezzo
- Tipologia di spedizione
- Revisioni
- Offerte speciali (es. a seconda del giorno della settimana)

### Gestione del carrello

Questo scenario riguarda la gestione delle attività dei clienti all'interno di un'applicazione di e-commerce. I clienti devono poter:

- Registrarsi all'applicazione
- Modificare i propri dati/preferenze
- Cancellare il proprio account

Per ogni cliente devono essere memorizzate informazioni quali:

- Nome
- Cognome
- Informazioni relative all'account (es. meccanismo di pagamento: carta di credito o prepagata)

In fase di registrazione, gli utenti possono selezionare delle preferenze per la personalizzazione dei servizi, come ad esempio:

- Offerte speciali basate sulla tipologia di prodotto preferita
- Impostazioni di privacy

Gli utenti registrati devono poter:

- Effettuare il login al sito
- Ricercare un prodotto di interesse
- Aggiungere prodotti al carrello
- Concludere l’acquisto dei prodotti nel carrello

Inoltre, i clienti devono avere la possibilità di annullare uno o più acquisti effettuati nella stessa giornata.

Per la gestione e pianificazione degli acquisti, l'applicazione deve mantenere informazioni sulla disponibilità dei prodotti, gestendo anche lo scenario in cui un prodotto non sia più disponibile. L'applicazione deve inoltre conservare lo storico degli acquisti fatti dai clienti.
