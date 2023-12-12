---
title: User Stories
parent: Scoping
layout: home
nav_order: 6
---
# Definizione User Stories
Definiamo di seguito una serie di User Story utili a catturare meglio alcuni requisiti, analizzati, ad esempio, dal punto di vista dell'utente che interagisce con il sistema.

## Name: registrazione utente
> - <b> Definizione: </b> una persona si vuole registrare nella piattaforma, creando un nuovo utente nel sistema
>> - <b> Role: </b> futuro utente
>> - <b> Action: </b> registrazione nel sistema
>> - <b> Benefit: </b> creazione utente e raccolta informazioni personali e conseguente possibilità di accesso
> - <b> CoS: </b> il futuro utente deve avere un punto di accesso al sistema, che comprenda una pagina per registrarsi e una per autenticarsi. I dati devono essere salvati tenendo conto della privacy e dati sensibili, nonché sicurezza

## Name: login
> - <b> Definizione: </b> una persona vuole accedere alle funzionalità dell'applicazione e i servizi offerti
>> - <b> Role: </b> utente già registrato
>> - <b> Action: </b> accesso al sistema con autenticazione
>> - <b> Benefit: </b> autenticazione e sfruttamento dei servizi offerti dall'applicazione
> - <b> CoS: </b> è necessaria una pagina per il login, nella quale la password dell'utente deve essere mascherata, o eventualmente visibile su richiesta

## Name: creazione nuovo gruppo di viaggio
> - <b> Definizione: </b> un utente vuole creare un nuovo gruppo di viaggio da organizzare
>> - <b> Role: </b> utente
>> - <b> Action: </b> creazione di un nuovo gruppo di viaggio che comprenda un insieme di partecipanti (altri utenti) e un luogo di destinazione sotto forma di meta di partenza/meta finale
>> - <b> Benefit: </b> organizzazione tra utenti già registrati al fine di condividere un futuro viaggio
> - <b> CoS: </b> pagina relativa alla creazione di un nuovo viaggio e possibilità di aggiunta di altri partecipanti sotto forma di invito

## Name: utenti amici
> - <b> Definizione: </b> un utente vuole poter gestire una sua rete di amicizie all'interno dellìapplicazione
>> - <b> Role: </b> utente
>> - <b> Action: </b> cercare utenti e richiedere l'amicizia
>> - <b> Benefit: </b> creazione di una rete di contatti, semplificando la creazione di gruppi di viaggio
> - <b> CoS: </b> un utente vuole ricercare un altro utente mediante username o contatto memorizzato in rubrica (mail o numero di telefono) e richiedere l'amicizia. Un utente preferirebbe anche condividere il suo contatto mediante link o QR code

## Name: aggiunta partecipanti ad un gruppo di viaggio
> - <b> Definizione: </b> un capo viaggio vuole poter aggiungere partecipanti ad un gruppo di viaggio esistente
>> - <b> Role: </b> capo viaggio
>> - <b> Action: </b> aggiunta/modifica di utenti già registrati come partecipanti al gruppo di viaggio
>> - <b> Benefit: </b> condivisione del viaggio con più utenti amici
> - <b> CoS: </b> un utente vuole sfruttare una view opportuna per invitare un utente a partecipare ad un viaggio, mediante invito in-app (tramite amicizia) o invito condivisibile mediante altri mezzi

## Name: aggiunta idee
> - <b> Definizione: </b> un utente partecipante ad un gruppo di viaggio vuole poter proporre una propria idea, in modo facile ed intuitivo
>> - <b> Role: </b> utente partecipante ad un gruppo viaggio
>> - <b> Action: </b> un utente vuole poter proporre al gruppo di viaggio una propria idea, sotto forma di tappa o evento o altra idea inerente, da votare se inserire nell'itinerario di viaggio
>> - <b> Benefit: </b> miglior coordinazione tra utenti e organizzazione dell'itinerario. Storico delle idee proposte
> - <b> CoS: </b> pagina per poter aggiungere la propria idea, con descrizione, link e posizione della tappa/evento. 

## Name: visualizzazione delle idee
> - <b> Definizione: </b> un utente vuole poter visualizzare tutte le idee proposte in maniera ben strutturata e visibile a tutti, senza che siano trascurate alcune proposte
>> - <b> Role: </b> utente partecipante ad un gruppo viaggio
>> - <b> Action: </b> un utente vuole poter navigare con facilità tra le idee proposte e poter votare, mediante sondaggi real-time, per le idee preferite e accettate
>> - <b> Benefit: </b> miglior coordinazione tra utenti e organizzazione dell'itinerario
> - <b> CoS: </b> la visualizzazione deve favorire una chiara lettura di tutte le idee proposte e una valutazione di quelle che un utente vuole accettare, con una chiara visione sull'andamento delle proposte più in voga. La visualizzazione deve distinguere attrazioni turistiche da eventi stabiliti in una data fissa (idee proposte senza data e con data)

## Name: creazione trip di viaggio
> - <b> Definizione: </b> un capo viaggio vuole poter generare il trip in base alle scelte effettuate sulle idee proposte e accettare dai vari partecipanti
>> - <b> Role: </b> capo viaggio
>> - <b> Action: </b> generare il trip di viaggio una volta che i partecipanti sono d'accordo sulle attività da effettuare
>> - <b> Benefit: </b> generazione di un trip globalmente accettato dal gruppo, miglior condivisione dell'itinerario
> - <b> CoS: </b> il sistema deve poter proporre un itinerario coerente con le proposte e date accettate dai partecipanti e che sia il più corto possibile in termini di tempistiche/distanze (sempre nel rispetto del tempo di viaggio)

## Name: modifica del trip generato
> - <b> Definizione: </b> un capo viaggio vuole poter modificare l'itinerario 
>> - <b> Role: </b> capo viaggio
>> - <b> Action: </b> modifica itinerario già generato in caso di cambiamenti di qualsiasi tipo (ad esempio necessità o cambi di programma)
>> - <b> Benefit: </b> miglior flessibilità di organizzazione dell'itinerario
> - <b> CoS: </b> pagina che visualizzi l'itinerario generato e tool di editing per poter aggiungere, rimuovere o adattare l'ordine delle tappe

## Name: segnare le tappe già visitate
> - <b> Definizione: </b> un utente, durante il viaggio, vuole poter segnare le tappe già visitate o gli eventi a cui si è già partecipati, mantenendo aggiornata la lista TO-DO delle tappe da fare
>> - <b> Role: </b> capo viaggio
>> - <b> Action: </b> marking di una tappa/evento come visitata o effettuata
>> - <b> Benefit: </b> miglior tracciamento della progresssione dell'itinerario in corso
> - <b> CoS: </b> pagina per marcare le tappe/eventi visualizzabile solo per il capo viaggio, e visualizzarli chiaramente per tutti divisi tra effettuati e da fare

## Name: navigazione itinerario
> - <b> Definizione: </b> un utente vorrebbe poter specificare eventuali necessità di spostamento mediante mezzi pubblici
>> - <b> Role: </b> utente
>> - <b> Action: </b> specificare eventuali mezzi pubblici da utilizzare
>> - <b> Benefit: </b> miglior creazione dell'itinerario in base ai mezzi di trasporto disponibili
> - <b> CoS: </b> possibilità di poter indicare, per le varie città, come ci si intende spostare; possibilità di poter navigare su una mappa con vari filtri, per mostrare ad esempio le fermate di determinati mezzi pubblici proposti e altre informazioni utili

## Name: pubblicità e sponsorizzazioni
> - <b> Definizione: </b> il sistema deve poter dar risalto a servizi e aziende turistiche che sponsorizzano l'applicazione, in modo da consigliarli e pubblicizzarli se un gruppo organizza un viaggio affine ad essi
>> - <b> Role: </b> applicazione mobile
>> - <b> Action: </b> mostrare in primo piano consigli inerenti a servizi offerti da terze parti sponsor dell'applicazione e del suo sviluppo
>> - <b> Benefit: </b> maggior offerta all'utente, miglior rapporto con gli sponsor
> - <b> CoS: </b> l'utente non deve sentirsi troppo obbligato ad accettare proposte relative ad aziende sponsor

## Name: monitoraggio dell'applicazione
> - <b> Definizione: </b> l'utente amministratore vuole poter gestire gli utenti registrati, monitorare l'andamento dell'applicazione, i suoi contenuti, la sua posizione nel mercato e tutto ciò che compete al monitoraggio strategico e operativo del sistema
>> - <b> Role: </b> amministratore
>> - <b> Action: </b> analizzare dati e andamenti relativi all'applicazione e alla sua community
>> - <b> Benefit: </b> miglior ascolto delle necessità degli utenti, delle problematiche, reattività in caso di guasti o calo di posizione e importanza nel mercato, data analysis
> - <b> CoS: </b> dashboard e cruscotti lato amministrazione per analizzare tutti gli aspetti di interesse; l'utente non deve sentirsi "spiato", ma ascoltato in modo il più anonimo possibile, se non tramite richieste di supporto esplicite

<iframe width="768" height="432" src="https://miro.com/app/live-embed/uXjVNFH3fUg=/?moveToViewport=-1417,-347,2622,883&embedId=909947665965" frameborder="0" scrolling="no" allow="fullscreen; clipboard-read; clipboard-write" allowfullscreen></iframe>