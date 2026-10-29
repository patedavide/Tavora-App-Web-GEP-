# 🎧 Tavora — Web App per la gestione delle serate in discoteca

La tua lista, il tuo network, la tua notte. 

Tavora è una web application progettata per semplificare la gestione e l'organizzazione delle serate in discoteca, offrendo ai PR, ai Capolista e agli Amministratori un unico ambiente in cui gestire prenotazioni, clienti, tavoli, liste, eventi, conteggi e incassi.
## 📑 Indice
* 1. Panoramica del progetto
* 2. Problema e obiettivi
* 3. Target e attori
* 4. Competitor
* 5. Tecnologie e strumenti
* 6. Funzionalità dell'applicazione
* 7. Requisiti funzionali e User Story
* 8. Requisiti non funzionali
* 9. Requisiti di dominio
* 10. Attori e ruoli
* 11. Matrice dei permessi
* 12. Regole di dominio principali
* 13. Diagrammi UML
* 14. Sicurezza e protezione dei dati
* 15. Evoluzione del progetto
## 🎯 1. Panoramica del progetto

Tavora nasce con l'obiettivo di digitalizzare e centralizzare le attività organizzative dei PR che lavorano nel settore nightlife.

L'applicazione permette di raccogliere in un unico sistema tutte le informazioni necessarie per organizzare una serata: clienti, prenotazioni, tavoli, prezzi, liste, collaboratori, eventi e risultati economici.

Il sistema prevede tre ruoli principali:

* PR: gestisce i propri clienti e le prenotazioni relative alle discoteche e alle liste a cui è associato.
* Capolista: coordina i PR della propria lista, ne monitora le attività e consulta i risultati complessivi del gruppo.
* Amministratore: gestisce gli utenti, i permessi, le discoteche, le liste, i tavoli, gli eventi e la reportistica.

La piattaforma è concepita per essere utilizzabile sia nella fase di preparazione della serata sia durante lo svolgimento dell'evento.

## 💡 2. Problema e obiettivi
### Il problema

L'organizzazione delle serate in discoteca si basa spesso su strumenti separati, come chat, fogli di calcolo e applicazioni di messaggistica. Questa frammentazione rende difficile mantenere le informazioni aggiornate e condividere correttamente i dati tra i membri dello staff.

### Le principali criticità sono:

* Dispersione delle informazioni tra strumenti differenti.
* Difficoltà nel monitorare prenotazioni e disponibilità dei tavoli.
* Possibilità di perdere dati relativi ai clienti.
* Difficoltà nel consultare lo storico delle prenotazioni.
* Gestione poco centralizzata di prezzi e note.
* Scarsa visibilità sui conteggi e sugli incassi.
* Difficoltà nel coordinamento tra PR e Capolista.
* Assenza di un registro centralizzato delle modifiche.
### Gli obiettivi

Tavora si propone di:

* Centralizzare le informazioni in un'unica piattaforma.
* Semplificare la gestione delle prenotazioni.
* Rendere più rapida la ricerca dei clienti.
* Organizzare le liste e le relative gerarchie.
* Migliorare il coordinamento tra i membri dello staff.
* Monitorare i conteggi e gli incassi per periodo.
* Gestire gli omaggi sulla base di soglie configurabili.
* Garantire un accesso alle funzionalità basato sui ruoli.
* Migliorare la tracciabilità delle operazioni.
## 👥 3. Target e attori

Tavora si rivolge ai professionisti e ai collaboratori del settore nightlife che necessitano di uno strumento pratico per gestire le proprie attività.

Attore	Descrizione
PR	Gestisce clienti, prenotazioni, prezzi, note e attività personali.
Capolista	Coordina i PR della propria lista e monitora prenotazioni, conteggi e incassi del gruppo.
Amministratore	Amministra utenti, ruoli, discoteche, liste, tavoli, eventi, soglie degli omaggi e report.
Discoteca	Rappresenta il locale a cui sono associati eventi, tavoli, liste e regole organizzative.

La discoteca è un'entità organizzativa del sistema, non necessariamente un utente autenticato.

## 🏆 4. Competitor

Le principali alternative considerate per Tavora sono:

Competitor	Ambito principale	Differenza rispetto a Tavora
Social Tables	Organizzazione di eventi e disposizione degli ospiti	Tavora si concentra sulle attività operative dei PR e sulle liste della nightlife.
Eventbrite	Pubblicazione, promozione e gestione di eventi e biglietti	Tavora integra anche prenotazioni dei tavoli, clienti, gerarchie e conteggi dei PR.
Google Sheets / Excel	Gestione dei dati tramite fogli di calcolo	Tavora mira a centralizzare dati, permessi, storico e operazioni in un sistema strutturato.
WhatsApp	Comunicazione e coordinamento tra collaboratori	Tavora organizza le informazioni operative senza dipendere esclusivamente dalle chat.

Questi strumenti possono risolvere singoli aspetti dell'organizzazione, mentre Tavora punta a riunire in un'unica piattaforma le attività centrali del lavoro dei PR.

## 🛠️ 5. Tecnologie e strumenti

Gli strumenti indicati per il progetto sono:

* GitHub: repository del progetto, versionamento del codice e collaborazione.
* yUML: creazione e rappresentazione dei diagrammi UML.

L'architettura applicativa, il framework frontend, il backend e il sistema di persistenza dei dati dovranno essere documentati quando le relative scelte tecnologiche saranno definite.

## ⚙️ 6. Funzionalità dell'applicazione

Le funzionalità sono suddivise in undici aree principali.

### 6.1 Autenticazione e gestione dell'account
* Registrazione di un utente.
* Accesso tramite login e verifica delle credenziali.
* Recupero della password.
* Visualizzazione e modifica del profilo personale.
* Associazione di ruoli e permessi agli account.
* Visualizzazione degli utenti registrati.
* Disattivazione degli account utente.
### 6.2 Gestione delle discoteche
* Visualizzazione e selezione delle discoteche disponibili.
* Creazione e modifica delle informazioni di una discoteca.
* Gestione amministrativa dei locali.
* Associazione delle liste alle discoteche.
* Possibilità per un PR di lavorare per più discoteche, quando abilitata.
### 6.3 Gestione delle liste
* Selezione della lista di lavoro.
* Creazione e gestione delle liste.
* Associazione delle liste alle discoteche.
* Modifica delle informazioni della lista.
* Visualizzazione dell'albero gerarchico e dei membri.
* Assegnazione e rimozione dei PR.
* Consultazione dei PR appartenenti alla lista.
* Inserimento e consultazione delle note della lista.
### 6.4 Gestione delle prenotazioni
* Creazione, modifica, visualizzazione ed eliminazione delle prenotazioni.
* Associazione delle prenotazioni ai clienti, ai tavoli e agli eventi pertinenti.
* Modifica dello stato della prenotazione.
* Inserimento e consultazione delle note.
* Modifica del prezzo associato al pagante.
* Gestione delle prenotazioni della propria lista da parte del Capolista.
### 6.5 Gestione dei clienti
* Visualizzazione della lista dei clienti.
* Ricerca rapida dei clienti.
* Consultazione della scheda cliente.
* Visualizzazione dello storico delle attività.
* Consultazione dello storico dei tavoli prenotati.
* Inserimento e visualizzazione delle note.
* Registrazione del numero e dei nomi delle persone portate da ciascun cliente.
* Consultazione dei clienti associati alla propria lista.
### 6.6 Gestione dei tavoli
* Creazione e configurazione dei tavoli.
* Visualizzazione delle informazioni dei tavoli.
* Modifica dei dati e delle caratteristiche.
* Associazione dei tavoli alle discoteche.
*Gestione delle informazioni necessarie alla prenotazione.
### 6.7 Programmazione ed eventi
* Visualizzazione della programmazione settimanale.
* Consultazione degli eventi programmati.
* Creazione di nuovi eventi.
* Modifica delle informazioni degli eventi.
* Associazione degli eventi alle rispettive discoteche.
### 6.8 Gestione degli omaggi
* Consultazione degli omaggi disponibili.
* Configurazione delle soglie per ogni discoteca.
* Definizione delle condizioni per il riconoscimento dei benefici.
* Sblocco degli omaggi al raggiungimento delle soglie previste.
* Visualizzazione dei benefici ottenuti dai PR.
### 6.9 Conteggi e statistiche
* Conteggio dei clienti portati da ogni PR.
* Consultazione dei conteggi per periodo.
* Visualizzazione dei conteggi complessivi della propria lista.
* Monitoraggio dell'attività dei PR.
* Analisi dei risultati dei gruppi.
### 6.10 Gestione degli incassi
* Consultazione dell'incasso generato dal PR.
* Monitoraggio dell'incasso generato per la discoteca.
* Consultazione dell'incasso spettante al PR, secondo le regole definite.
* Consultazione degli incassi della propria lista.
* Analisi dei risultati economici delle attività.
### 6.11 Gestione amministrativa e reportistica
* Gestione di utenti, ruoli e permessi.
* Gestione di discoteche e liste.
* Configurazione delle soglie degli omaggi.
* Gestione di tavoli ed eventi.
* Disattivazione degli account.
* Generazione di report periodici.
* Consultazione del registro delle modifiche.
* Analisi di conteggi e incassi.
## 📋 7. Requisiti funzionali e User Story

Le User Story descrivono le funzionalità attese dal punto di vista dei diversi attori. Ogni requisito è identificato da un codice univoco per facilitarne la consultazione, l'implementazione e la verifica.

7.1 Autenticazione e account
ID	User Story
US01 — Login / Registrazione	Come utente, voglio registrarmi e accedere al sistema tramite login, così da poter utilizzare le funzionalità del sistema.
US09 — Profilo personale PR	Come PR, voglio visualizzare e gestire il mio profilo personale, così da gestire le mie informazioni personali.
US10 — Recupero password	Come utente, voglio recuperare la mia password, così da poter accedere nuovamente al sistema nel caso la dimentichi.
US11 — Ruoli e permessi	Come utente, voglio avere un ruolo e dei permessi associati al mio account, così da utilizzare le funzionalità previste per il mio ruolo.
US18 — Gestione utenti, ruoli e permessi	Come Amministratore, voglio gestire gli utenti, i loro ruoli e i relativi permessi, così da controllare l'accesso alle funzionalità del sistema.
US39 — Visualizzazione degli utenti registrati	Come Amministratore, voglio visualizzare gli utenti registrati, così da monitorare gli account presenti sulla piattaforma e amministrarne l'accesso.
US40 — Disattivazione di un account utente	Come Amministratore, voglio disattivare un account utente, così da impedire l'accesso al sistema agli utenti che non devono più utilizzarlo.
7.2 Discoteche, liste e gerarchie
ID	User Story
US02 — Scelta della discoteca	Come PR, voglio scegliere la discoteca per la quale lavoro, così da gestire la mia attività nella discoteca selezionata.
US19 — Selezione della lista	Come PR o Capolista, voglio selezionare una lista, così da gestire e consultare le attività associate alla lista selezionata.
US20 — Albero gerarchico della lista	Come PR o Capolista, voglio visualizzare l'albero gerarchico della lista, così da conoscere la struttura organizzativa della lista e le relazioni tra i suoi membri.
US25 — Gestione di più discoteche	Come PR, voglio poter lavorare per più discoteche, così da gestire la mia attività in diversi locali anche quando questa possibilità viene abilitata successivamente.
US26 — Gestione dei PR della propria lista	Come Capolista, voglio gestire i PR della mia lista, così da organizzare e controllare i membri che ne fanno parte.
US27 — Assegnazione dei PR alla propria lista	Come Capolista, voglio assegnare dei PR alla mia lista, così da organizzare la struttura del gruppo e includere nuovi collaboratori.
US28 — Rimozione dei PR dalla propria lista	Come Capolista, voglio rimuovere un PR dalla mia lista, così da mantenere aggiornata la composizione del gruppo.
US29 — Visualizzazione dei PR della propria lista	Come Capolista, voglio visualizzare i PR della mia lista, così da conoscere i membri del gruppo e monitorarne l'organizzazione.
US33 — Gestione delle informazioni della propria lista	Come Capolista, voglio gestire le informazioni della mia lista, così da mantenere aggiornati i dati organizzativi del gruppo.
US38 — Gestione delle liste	Come Amministratore, voglio gestire le liste delle discoteche, così da organizzare la struttura dei gruppi e consentire la corretta assegnazione dei PR e dei Capolista.
7.3 Prenotazioni e tavoli
ID	User Story
US03 — Aggiunta della prenotazione di un tavolo	Come PR, voglio aggiungere una prenotazione di un tavolo, così da registrare la prenotazione di un cliente.
US04 — Eliminazione della prenotazione di un tavolo	Come PR, voglio eliminare una prenotazione di un tavolo, così da rimuovere una prenotazione non più necessaria.
US05 — Modifica della prenotazione di un tavolo	Come PR, voglio modificare una prenotazione di un tavolo, così da mantenere aggiornati i dati della prenotazione.
US06 — Modifica del prezzo di un pagante	Come PR, voglio modificare il prezzo di un pagante, così da aggiornare l'importo associato alla prenotazione.
US12 — Note sulla prenotazione	Come PR, voglio inserire e visualizzare note relative a una prenotazione, così da memorizzare informazioni aggiuntive sulla prenotazione.
US21 — Modifica dello stato di una prenotazione	Come PR o Capolista, voglio modificare lo stato di una prenotazione, così da mantenere aggiornate le informazioni relative alla sua gestione.
US30 — Gestione delle prenotazioni della propria lista	Come Capolista, voglio gestire le prenotazioni della mia lista, così da coordinare le attività dei PR e controllare le prenotazioni associate al gruppo.
US41 — Gestione dei tavoli	Come Amministratore, voglio gestire i tavoli delle discoteche, così da mantenere aggiornata la disponibilità e la configurazione dei tavoli prenotabili.
7.4 Clienti e storico
ID	User Story
US07 — Lista dei clienti	Come PR, voglio visualizzare la lista dei clienti, così da consultare i clienti associati alla mia attività.
US08 — Storico di ogni cliente	Come PR, voglio visualizzare lo storico di ogni cliente, così da conoscere le attività precedenti del cliente.
US14 — Scheda cliente	Come PR, voglio visualizzare la scheda di un cliente, così da consultare le informazioni relative al cliente.
US15 — Storico tavoli cliente	Come PR, voglio visualizzare lo storico dei tavoli di un cliente, così da conoscere le precedenti prenotazioni del cliente.
US16 — Ricerca cliente	Come PR, voglio ricercare un cliente, così da trovare rapidamente le sue informazioni.
US17 — Note cliente	Come PR, voglio inserire e visualizzare note relative a un cliente, così da conservare informazioni aggiuntive sul cliente.
US34 — Visualizzazione dei clienti della propria lista	Come Capolista, voglio visualizzare i clienti della mia lista, così da consultare i clienti gestiti dal gruppo e monitorarne l'attività.
US35 — Gestione delle note della propria lista	Come Capolista, voglio gestire le note della mia lista, così da conservare e consultare informazioni utili all'organizzazione del gruppo.
7.5 Programmazione, conteggi, incassi e omaggi
ID	User Story
US13 — Programmazione settimanale	Come PR, voglio visualizzare la programmazione settimanale, così da conoscere gli eventi programmati.
US22 — Consultazione degli omaggi disponibili	Come PR o Capolista, voglio consultare gli omaggi disponibili, così da conoscere i benefici ottenuti in base ai clienti portati e alle soglie raggiunte.
US23 — Conteggi dei clienti per periodo	Come PR o Capolista, voglio consultare i conteggi dei clienti per periodo, così da monitorare la mia attività e verificare i risultati raggiunti.
US24 — Incasso generato	Come PR o Capolista, voglio consultare l'incasso generato dalla mia attività, così da monitorare i risultati economici relativi alle prenotazioni e ai clienti portati.
US31 — Conteggi della propria lista	Come Capolista, voglio consultare i conteggi della mia lista, così da monitorare i risultati complessivi del gruppo e l'attività dei suoi membri.
US32 — Incassi della propria lista	Come Capolista, voglio consultare gli incassi della mia lista, così da monitorare i risultati economici complessivi del gruppo.
7.6 Amministrazione ed eventi
ID	User Story
US36 — Configurazione delle soglie degli omaggi	Come Amministratore, voglio configurare le soglie degli omaggi per ogni discoteca, così da definire le condizioni per il riconoscimento dei benefici ai PR.
US37 — Gestione delle discoteche	Come Amministratore, voglio gestire le discoteche presenti nel sistema, così da mantenere aggiornate le informazioni dei locali e consentirne l'utilizzo da parte degli utenti autorizzati.
US42 — Gestione degli eventi	Come Amministratore, voglio gestire gli eventi delle discoteche, così da mantenere aggiornata la programmazione disponibile agli utenti.
US43 — Generazione di report periodici	Come Amministratore, voglio generare report periodici, così da analizzare l'andamento delle attività e verificare i risultati delle discoteche e delle liste.
US44 — Registro delle modifiche	Come Amministratore, voglio visualizzare il registro delle modifiche, così da verificare le operazioni eseguite nel sistema e facilitare le attività di controllo.
🔒 8. Requisiti non funzionali

I requisiti non funzionali definiscono le caratteristiche qualitative che il sistema deve rispettare.

ID	Requisito	Descrizione
RNF01	Sicurezza	Proteggere il sistema da accessi non autorizzati e utilizzi impropri.
RNF02	Protezione delle password	Conservare le password mediante funzioni di hashing sicure e procedure appropriate di verifica.
RNF03	Prestazioni	Garantire tempi di risposta adeguati durante le operazioni principali.
RNF04	Disponibilità	Rendere il sistema accessibile in modo affidabile, compatibilmente con l'infrastruttura adottata.
RNF05	Usabilità	Offrire un'interfaccia intuitiva e comprensibile, adatta all'utilizzo durante l'organizzazione delle serate.
RNF06	Scalabilità	Consentire la crescita del numero di utenti, discoteche, liste e prenotazioni.
RNF07	Privacy	Proteggere i dati personali e limitarne l'utilizzo alle finalità autorizzate.
RNF08	Affidabilità	Ridurre il rischio di perdita o incoerenza dei dati.
RNF09	Controllo degli accessi	Consentire l'utilizzo delle funzionalità esclusivamente agli utenti autorizzati.
RNF10	Tracciabilità delle operazioni	Registrare le operazioni rilevanti effettuate dagli utenti.
RNF11	Integrità dei dati	Mantenere coerenti le relazioni tra utenti, clienti, prenotazioni, tavoli, eventi e liste.
RNF12	Isolamento dei dati per ambito organizzativo	Impedire che gli utenti accedano a dati esterni alle discoteche e alle liste per cui sono autorizzati.
RNF13	Verificabilità delle operazioni	Rendere verificabili le modifiche e le operazioni rilevanti attraverso controlli e registrazioni adeguate.

I requisiti costituiscono obiettivi progettuali. Soglie numeriche di prestazione, disponibilità e recupero dovranno essere definite durante la progettazione tecnica.

## 🧩 9. Requisiti di dominio

I requisiti di dominio descrivono le regole organizzative e operative proprie del settore nightlife.

ID	Requisito	Descrizione
RD01	Scelta della lista	Gli utenti autorizzati selezionano la lista con cui intendono operare.
RD02	Albero gerarchico della lista	Il sistema rappresenta la struttura della lista e le relazioni tra i membri.
RD03	Sblocco degli omaggi	Gli omaggi vengono riconosciuti al raggiungimento delle soglie previste.
RD04	Conteggio dei clienti portati dal PR	Il sistema permette di conteggiare i clienti attribuiti all'attività di ciascun PR.
RD05	Lavoro per più discoteche	Un PR può operare per più discoteche quando tale possibilità è abilitata.
RD06	Stato della prenotazione	Ogni prenotazione può assumere uno stato che ne rappresenta la situazione operativa.
RD07	Persone portate da ogni cliente	Il sistema consente di registrare il numero e, quando necessario, i nominativi delle persone portate da un cliente.
RD08	Incasso generato dal PR	Il sistema permette di consultare i risultati economici attribuiti al PR secondo le regole definite.
RD09	Gestione amministrativa del sistema	L'Amministratore gestisce le principali entità e configurazioni della piattaforma.
RD10	Associazione delle liste alle discoteche	Le liste sono associate ai locali per i quali vengono utilizzate.
RD11	Gerarchia dei membri della lista	La struttura organizzativa identifica il Capolista e i PR appartenenti al gruppo.
RD12	Appartenenza dei PR alle liste	Il sistema gestisce l'assegnazione e la rimozione dei PR dalle liste.
RD13	Ambito di gestione del Capolista	Il Capolista opera sulle liste e sulle attività per cui dispone delle autorizzazioni.
RD14	Configurazione degli omaggi per discoteca	Le soglie e le condizioni degli omaggi possono essere configurate per ciascuna discoteca.
RD15	Informazioni dei tavoli	I tavoli sono associati a una discoteca e possiedono informazioni necessarie alla prenotazione.
RD16	Associazione degli eventi alle discoteche	Ogni evento è associato al locale in cui si svolge.
RD17	Reportistica amministrativa	L'Amministratore può analizzare i dati aggregati attraverso report periodici.
RD18	Disattivazione degli account	Gli account possono essere disattivati dagli utenti autorizzati a svolgere tale operazione.
RD19	Tracciabilità delle modifiche	Le modifiche rilevanti devono poter essere ricostruite attraverso un registro delle operazioni.
🛡️ 10. Attori e ruoli
PR

Il PR è l'utente operativo che gestisce i clienti e le prenotazioni.

Può:

Selezionare una discoteca e una lista tra quelle autorizzate.
Creare, modificare ed eliminare prenotazioni secondo i permessi assegnati.
Consultare clienti, schede e storico delle attività.
Inserire note sui clienti e sulle prenotazioni.
Consultare eventi, conteggi, incassi e omaggi disponibili.
Gestire il proprio profilo personale.
Capolista

Il Capolista coordina le attività dei PR appartenenti alla propria lista.

Può:

Consultare la gerarchia e i membri della lista.
Assegnare o rimuovere PR dalla propria lista.
Gestire le prenotazioni della propria lista nei limiti delle autorizzazioni.
Consultare i clienti associati al gruppo.
Gestire le informazioni e le note della lista.
Monitorare conteggi, incassi e omaggi.
Amministratore

L'Amministratore gestisce la configurazione e il controllo della piattaforma.

Può:

Gestire gli utenti, i ruoli e i permessi.
Consultare gli account registrati e disattivarli.
Creare e modificare le discoteche.
Gestire le liste e le loro associazioni.
Configurare tavoli, eventi e soglie degli omaggi.
Generare report periodici.
Consultare il registro delle modifiche.
Discoteca

La discoteca è l'entità organizzativa di riferimento per:

Liste e gruppi di PR.
Eventi e programmazione.
Tavoli e disponibilità.
Regole per conteggi, incassi e omaggi.
Ambiti di autorizzazione e separazione dei dati.
## 🗂️ 11. Matrice dei permessi

La tabella seguente rappresenta la proposta iniziale dei permessi. Le autorizzazioni definitive dovranno essere validate durante la progettazione.

Legenda: ✓ = previsto; — = non previsto nella proposta iniziale; Da definire = autorizzazione da stabilire.

Funzionalità	PR	Capolista	Amministratore
Registrazione e login	✓	✓	✓
Gestione del profilo personale	✓	✓	✓
Selezione della discoteca	✓	✓	—
Selezione della lista	✓	✓	—
Visualizzazione dell'albero gerarchico	✓	✓	—
Gestione delle prenotazioni	✓	✓	—
Modifica dello stato delle prenotazioni	✓	✓	—
Gestione dei clienti	✓	✓	—
Consultazione dello storico dei clienti	✓	✓	—
Gestione dei PR della lista	—	✓	—
Assegnazione e rimozione dei PR	—	✓	—
Gestione delle informazioni della lista	—	✓	✓
Consultazione dei conteggi	✓	✓	✓
Consultazione degli incassi	✓	✓	✓
Consultazione degli omaggi	✓	✓	—
Configurazione delle soglie degli omaggi	—	—	✓
Gestione delle discoteche	—	—	✓
Gestione delle liste	—	✓	✓
Gestione dei tavoli	—	—	✓
Gestione degli eventi	—	—	✓
Gestione di utenti, ruoli e permessi	—	—	✓
Disattivazione degli account	—	—	✓
Generazione di report periodici	—	—	✓
Consultazione del registro delle modifiche	—	—	✓
Nota: la matrice indica le autorizzazioni previste a livello funzionale. I controlli effettivi dovranno essere applicati anche lato server e verificati per ogni discoteca, lista e risorsa interessata.
## 📐 12. Regole di dominio principali

Le seguenti regole sintetizzano il comportamento atteso del sistema.

### 12.1 Ambito organizzativo
Le liste sono associate alle discoteche.
Gli utenti possono operare soltanto nelle liste e nelle discoteche per cui risultano autorizzati.
Il Capolista gestisce esclusivamente la propria area organizzativa.
L'accesso a più discoteche per un PR dipende dall'abilitazione della relativa funzionalità.
### 12.2 Prenotazioni
Ogni prenotazione deve essere identificabile e associata alle informazioni necessarie alla sua gestione.
Le prenotazioni devono poter essere create, modificate ed eliminate dagli utenti autorizzati.
Lo stato della prenotazione deve rappresentarne la situazione operativa.
Le note devono poter essere consultate dagli utenti autorizzati.
Le modifiche ai prezzi devono rispettare i permessi assegnati e le regole economiche applicabili.
### 12.3 Clienti e conteggi
I clienti devono poter essere ricercati e identificati attraverso una scheda.
Lo storico deve consentire di consultare le attività precedenti associate al cliente.
Il sistema deve permettere di registrare le persone portate da ciascun cliente.
I conteggi devono essere consultabili per periodo e per ambito organizzativo.
L'attribuzione dei clienti ai PR deve seguire regole coerenti e verificabili.
### 12.4 Incassi e omaggi
I conteggi economici devono rispettare le regole di attribuzione definite per le prenotazioni e i clienti.
Le soglie degli omaggi devono poter essere configurate per discoteca.
Il riconoscimento dei benefici deve dipendere dalle soglie e dalle condizioni effettivamente configurate.
Gli incassi individuali e quelli della lista devono essere consultabili soltanto dagli utenti autorizzati.

Le formule di conteggio, i criteri per gli incassi e le condizioni esatte di sblocco degli omaggi dovranno essere definite esplicitamente prima dell'implementazione.

## 🖼️ 13. Diagrammi UML

I diagrammi UML descrivono i casi d'uso previsti per i diversi ruoli del sistema.

Inserisci le immagini nella cartella principale del repository oppure modifica i percorsi in base alla posizione effettiva dei file.

### 13.1 Diagramma dei casi d'uso — Capolista

!Diagramma UML dei casi d'uso del Capolista

Il diagramma rappresenta le operazioni disponibili al Capolista, tra cui la gestione della propria lista, il coordinamento dei PR e la consultazione dei risultati del gruppo.

### 13.2 Diagramma dei casi d'uso — PR

!Diagramma UML dei casi d'uso del PR

Il diagramma rappresenta le operazioni del PR relative a clienti, prenotazioni, tavoli, eventi, conteggi e informazioni personali.

### 13.3 Diagramma dei casi d'uso — Amministratore

!Diagramma UML dei casi d'uso dell'Amministratore

Il diagramma rappresenta le operazioni amministrative relative agli utenti, ai ruoli, alle discoteche, alle liste, ai tavoli, agli eventi e alla reportistica.

## 🔐 14. Sicurezza e protezione dei dati

La sicurezza è un requisito trasversale dell'applicazione.

La progettazione dovrà considerare almeno i seguenti aspetti:

Autenticazione: verifica dell'identità dell'utente prima di consentire l'accesso alle funzionalità protette.
Protezione delle password: utilizzo di algoritmi di hashing dedicati alle password e di procedure sicure per il recupero dell'accesso.
Autorizzazione: verifica dei ruoli e dei permessi per ogni operazione sensibile.
Isolamento dei dati: controllo dell'accesso ai dati appartenenti alle diverse discoteche e liste.
Privacy: trattamento dei dati personali secondo le finalità autorizzate e le normative applicabili.
Integrità: validazione degli input e controllo della coerenza delle relazioni tra le entità.
Tracciabilità: registrazione delle modifiche rilevanti, includendo quando opportuno autore, data, operazione e risorsa coinvolta.
Gestione degli account: possibilità di disattivare gli account non più autorizzati.

I controlli di sicurezza dovranno essere applicati anche lato server, evitando di affidare la protezione dei dati esclusivamente all'interfaccia utente.

## 🚀 15. Evoluzione del progetto

Le funzionalità descritte costituiscono la base funzionale di Tavora. Lo sviluppo potrà essere organizzato progressivamente.

### Fase 1 — Funzionalità fondamentali
Registrazione, login e recupero password.
Gestione dei ruoli e dei permessi.
Selezione della discoteca e della lista.
Gestione delle prenotazioni.
Gestione dei clienti e delle relative schede.
Configurazione iniziale dei tavoli e degli eventi.
### Fase 2 — Organizzazione delle liste
Visualizzazione dell'albero gerarchico.
Assegnazione e rimozione dei PR.
Gestione delle informazioni e delle note delle liste.
Gestione delle prenotazioni del gruppo.
Consultazione dei clienti della propria lista.
### Fase 3 — Conteggi e risultati economici
Conteggio dei clienti portati.
Consultazione dei conteggi per periodo.
Calcolo e consultazione degli incassi secondo le regole definite.
Configurazione e verifica delle soglie degli omaggi.
Consultazione dei risultati aggregati della lista.
### Fase 4 — Amministrazione e controllo
Gestione completa di utenti e discoteche.
Gestione amministrativa di liste, tavoli ed eventi.
Report periodici.
Registro delle modifiche.
Verifica dei requisiti di sicurezza, privacy e integrità.
Sviluppi successivi
Abilitazione della gestione di più discoteche per singolo PR.
Miglioramento delle statistiche e degli strumenti di analisi.
Definizione di ulteriori funzionalità in base alle esigenze operative.

La suddivisione proposta è indicativa e non sostituisce la pianificazione effettiva dello sviluppo.

## 📌 Conclusione

Tavora vuole offrire ai professionisti della nightlife uno strumento unico, strutturato e affidabile per organizzare le serate in discoteca.

Centralizzando prenotazioni, clienti, tavoli, liste, collaboratori, conteggi e incassi, il progetto mira a ridurre la frammentazione delle informazioni, migliorare la collaborazione tra i PR e rendere più semplice il controllo delle attività.

La definizione dei requisiti funzionali, non funzionali e di dominio costituisce la base per progettare un sistema coerente con le esigenze operative dei PR, dei Capolista e degli Amministratori.


