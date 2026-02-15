Modellazione Dati: Definisci l'entità Dinner con i campi id (intero), description (testo), cost (intero), status (stringa) e tip (intero).

Inizializzazione Stato: Assicurati che ogni nuova cena inserita nel sistema parta automaticamente con lo stato impostato su pending.

Creazione (POST): Implementa l'endpoint POST /JR/DINNERS per permettere l'inserimento di una nuova cena tramite un oggetto JSON.

Recupero Specifico (GET): Sviluppa la funzionalità GET /JR/DINNERS/{id} per visualizzare i dettagli completi di una singola cena tramite il suo identificativo univoco.

Filtro Pendenze (GET): Crea l'endpoint GET /JS/DINNERS/PENDING per ottenere la lista di tutti gli ordini ancora in fase di preparazione.

Filtro Consegne (GET): Implementa l'endpoint GET /GR/DINNERS/DELIVERED per visualizzare esclusivamente gli ordini che sono già stati serviti al tavolo.

Aggiornamento Dinamico (PUT): Implementa l'endpoint PUT /JR/DINNERS/ per modificare i dati di una cena esistente inviando l'oggetto aggiornato.

Gestione Transizioni: Utilizza l'operazione di modifica per far avanzare lo stato della cena da pending a delivered o paid.

Logica di Business (Sconti e Mance): Gestisci la possibilità di variare il cost (in caso di sconti per reclami) e di registrare il tip solo quando l'ordine viene completato.

Validazione: Assicurati che i campi numerici come costo e mancia non siano negativi e che lo stato rispetti rigorosamente i tre valori ammessi: pending, delivered, paid.
