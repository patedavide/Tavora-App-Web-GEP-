# Tavora-App-Web-GEP-
Web app per la gestione e l’organizzazione delle serate in discoteca, pensata per ogni PR, che consente di gestire tavoli, clienti, prezzi, prenotazioni e altri dati relativi alla serata.

Problema che vuole risolvere: Difficoltà nella gestione e nell’organizzazione delle serate da parte dei PR, dovute all’utilizzo di informazioni sparse tra chat, fogli e app diverse, con il rischio di perdere dati relativi a clienti, tavoli, prenotazioni e prezzi.

Target: L’applicazione si rivolge ai PR e collaboratori del settore nightlife che necessitano di uno strumento pratico per gestire clienti, prenotazioni, tavoli e vendite. La web app mira a ottimizzare l’organizzazione delle serate, migliorare la collaborazione tra i membri dello staff e rendere più efficiente il lavoro dei PR, sia prima sia durante gli eventi.

Competitors: Social Tables, Eventbrite, Google Sheets/Excel e WhatsApp.

Technologie: GitHub, yUML.

##Requisiti funzionali 
User Story
US01 — Login / Registrazione
Come utente, voglio registrarmi e accedere al sistema tramite login, così da poter utilizzare le funzionalità del sistema.

US02 — Scelta della discoteca
Come PR, voglio scegliere la discoteca per la quale lavoro, così da gestire la mia attività nella discoteca selezionata.

US03 — Aggiunta della prenotazione di un tavolo
Come PR, voglio aggiungere una prenotazione di un tavolo, così da registrare la prenotazione di un cliente.

US04 — Eliminazione della prenotazione di un tavolo
Come PR, voglio eliminare una prenotazione di un tavolo, così da rimuovere una prenotazione non più necessaria.

US05 — Modifica della prenotazione di un tavolo
Come PR, voglio modificare una prenotazione di un tavolo, così da mantenere aggiornati i dati della prenotazione.

US06 — Modifica del prezzo di un pagante
Come PR, voglio modificare il prezzo di un pagante, così da aggiornare l'importo associato alla prenotazione.

US07 — Lista dei clienti
Come PR, voglio visualizzare la lista dei clienti, così da consultare i clienti associati alla mia attività.

US08 — Storico di ogni cliente
Come PR, voglio visualizzare lo storico di ogni cliente, così da conoscere le attività precedenti del cliente.

US09 — Profilo personale PR
Come PR, voglio visualizzare e gestire il mio profilo personale, così da gestire le mie informazioni personali.

US10 — Recupero password
Come utente, voglio recuperare la mia password, così da poter accedere nuovamente al sistema nel caso la dimentichi.

US11 — Ruoli e permessi
Come utente, voglio avere un ruolo e dei permessi associati al mio account, così da utilizzare le funzionalità previste per il mio ruolo.

US12 — Note sulla prenotazione
Come PR, voglio inserire e visualizzare note relative a una prenotazione, così da memorizzare informazioni aggiuntive sulla prenotazione.

US13 — Visualizzazione della programmazione settimanale
Come PR, voglio visualizzare la programmazione settimanale, così da conoscere gli eventi programmati.

US14 — Scheda cliente
Come PR, voglio visualizzare la scheda di un cliente, così da consultare le informazioni relative al cliente.

US15 — Storico tavoli cliente
Come PR, voglio visualizzare lo storico dei tavoli di un cliente, così da conoscere le precedenti prenotazioni del cliente.

US16 — Ricerca cliente
Come PR, voglio ricercare un cliente, così da trovare rapidamente le sue informazioni.

US17 — Note cliente
Come PR, voglio inserire e visualizzare note relative a un cliente, così da conservare informazioni aggiuntive sul cliente.

US18 — Gestione utenti, ruoli e permessi
Come Amministratore, voglio gestire gli utenti, i loro ruoli e i relativi permessi, così da controllare l'accesso alle funzionalità del sistema.

US19 — Selezione della lista
Come PR o Capolista, voglio selezionare una lista, così da gestire e consultare le attività associate alla lista selezionata.

US20 — Visualizzazione dell'albero gerarchico della lista
Come PR o Capolista, voglio visualizzare l'albero gerarchico della lista, così da conoscere la struttura organizzativa della lista e le relazioni tra i suoi membri.

US21 — Modifica dello stato di una prenotazione
Come PR o Capolista, voglio modificare lo stato di una prenotazione, così da mantenere aggiornate le informazioni relative alla sua gestione.

US22 — Consultazione degli omaggi disponibili
Come PR o Capolista, voglio consultare gli omaggi disponibili, così da conoscere i benefici ottenuti in base ai clienti portati e alle soglie raggiunte.

US23 — Consultazione dei conteggi dei clienti per periodo
Come PR o Capolista, voglio consultare i conteggi dei clienti per periodo, così da monitorare la mia attività e verificare i risultati raggiunti.

US24 — Consultazione dell'incasso generato
Come PR o Capolista, voglio consultare l'incasso generato dalla mia attività, così da monitorare i risultati economici relativi alle prenotazioni e ai clienti portati.

US25 — Gestione di più discoteche
Come PR, voglio poter lavorare per più discoteche, così da gestire la mia attività in diversi locali anche quando questa possibilità viene abilitata successivamente.

US26 — Gestione dei PR della propria lista
Come Capolista, voglio gestire i PR della mia lista, così da organizzare e controllare i membri che ne fanno parte.

US27 — Assegnazione dei PR alla propria lista
Come Capolista, voglio assegnare dei PR alla mia lista, così da organizzare la struttura del gruppo e includere nuovi collaboratori.

US28 — Rimozione dei PR dalla propria lista
Come Capolista, voglio rimuovere un PR dalla mia lista, così da mantenere aggiornata la composizione del gruppo.

US29 — Visualizzazione dei PR della propria lista
Come Capolista, voglio visualizzare i PR della mia lista, così da conoscere i membri del gruppo e monitorarne l'organizzazione.

US30 — Gestione delle prenotazioni della propria lista
Come Capolista, voglio gestire le prenotazioni della mia lista, così da coordinare le attività dei PR e controllare le prenotazioni associate al gruppo.

US31 — Consultazione dei conteggi della propria lista
Come Capolista, voglio consultare i conteggi della mia lista, così da monitorare i risultati complessivi del gruppo e l'attività dei suoi membri.

US32 — Consultazione degli incassi della propria lista
Come Capolista, voglio consultare gli incassi della mia lista, così da monitorare i risultati economici complessivi del gruppo.

US33 — Gestione delle informazioni della propria lista
Come Capolista, voglio gestire le informazioni della mia lista, così da mantenere aggiornati i dati organizzativi del gruppo.

US34 — Visualizzazione dei clienti della propria lista
Come Capolista, voglio visualizzare i clienti della mia lista, così da consultare i clienti gestiti dal gruppo e monitorarne l'attività.

US35 — Gestione delle note della propria lista
Come Capolista, voglio gestire le note della mia lista, così da conservare e consultare informazioni utili all'organizzazione del gruppo.

US36 — Configurazione delle soglie degli omaggi
Come Amministratore, voglio configurare le soglie degli omaggi per ogni discoteca, così da definire le condizioni per il riconoscimento dei benefici ai PR.

US37 — Gestione delle discoteche
Come Amministratore, voglio gestire le discoteche presenti nel sistema, così da mantenere aggiornate le informazioni dei locali e consentirne l'utilizzo da parte degli utenti autorizzati.

US38 — Gestione delle liste
Come Amministratore, voglio gestire le liste delle discoteche, così da organizzare la struttura dei gruppi e consentire la corretta assegnazione dei PR e dei Capolista.

US39 — Visualizzazione degli utenti registrati
Come Amministratore, voglio visualizzare gli utenti registrati, così da monitorare gli account presenti sulla piattaforma e amministrarne l'accesso.

US40 — Disattivazione di un account utente
Come Amministratore, voglio disattivare un account utente, così da impedire l'accesso al sistema agli utenti che non devono più utilizzarlo.

US41 — Gestione dei tavoli
Come Amministratore, voglio gestire i tavoli delle discoteche, così da mantenere aggiornata la disponibilità e la configurazione dei tavoli prenotabili.

US42 — Gestione degli eventi
Come Amministratore, voglio gestire gli eventi delle discoteche, così da mantenere aggiornata la programmazione disponibile agli utenti.

US43 — Generazione di report periodici
Come Amministratore, voglio generare report periodici, così da analizzare l'andamento delle attività e verificare i risultati delle discoteche e delle liste.

US44 — Visualizzazione del registro delle modifiche
Come Amministratore, voglio visualizzare il registro delle modifiche, così da verificare le operazioni eseguite nel sistema e facilitare le attività di controllo.

##Requisiti non funzionali
RNF01 — Sicurezza

RNF02 — Protezione delle password

RNF03 — Prestazioni

RNF04 — Disponibilità

RNF05 — Usabilità

RNF06 — Scalabilità

RNF07 — Privacy

RNF08 — Affidabilità

RNF09 — Controllo degli accessi

RNF10 — Tracciabilità delle operazioni

RNF11 — Integrità dei dati

RNF12 — Isolamento dei dati per ambito organizzativo

RNF13 — Verificabilità delle operazioni

##Requisiti di dominio
RD01 — Scelta della lista

RD02 — Albero gerarchico della lista

RD03 — Sblocco degli omaggi

RD04 — Conteggio dei clienti portati dal PR

RD05 — Lavoro per più discoteche

RD06 — Stato della prenotazione

RD07 — Persone portate da ogni cliente

RD08 — Incasso generato dal PR

RD09 — Gestione amministrativa del sistema

RD10 — Associazione delle liste alle discoteche

RD11 — Gerarchia dei membri della lista

RD12 — Gestione dell'appartenenza dei PR alle liste

RD13 — Ambito di gestione del Capolista

RD14 — Configurazione degli omaggi per discoteca

RD15 — Gestione delle informazioni dei tavoli

RD16 — Associazione degli eventi alle discoteche

RD17 — Reportistica amministrativa

RD18 — Disattivazione degli account

RD19 — Tracciabilità delle modifiche





