---
title: User Stories
parent: Scoping
layout: home
nav_order: 6
---
# Definizione User Stories
Definiamo di seguito le 

## Name: registrazione utente
> - Definizione: una persona si vuole registrare nella piattaforma, creando un nuovo utente nel sistema
>> - Role: futuro utente
>> - Action: registrazione nel sistema
>> - Benefit: creazione utente e raccolta informazioni personali e conseguente possibilità di accesso
> - CoS: il futuro utente deve avere un punto di accesso al sistema, che comprenda una pagina per registrarsi e una per autenticarsi. I dati devono essere salvati tenendo conto della privacy e dati sensibili, nonché sicurezza

## Name: login
> - Definizione: una persona vuole accedere alle funzionalità dell'applicazione e i servizi offerti
>> - Role: utente già registrato
>> - Action: accesso al sistema con autenticazione
>> - Benefit: autenticazione e sfruttamento dei servizi offerti dall'applicazione
> - CoS: è necessaria una pagina per il login, nella quale la password dell'utente deve essere mascherata, o eventualmente visibile su richiesta

## Name: creazione nuovo gruppo di viaggio
> - Definizione: un utente vuole creare un nuovo gruppo di viaggio da organizzare
>> - Role: utente
>> - Action: creazione di un nuovo gruppo di viaggio che comprenda un insieme di partecipanti (altri utenti) e un luogo di destinazione sotto forma di meta di partenza/meta finale
>> - Benefit: organizzazione tra utenti già registrati al fine di condividere un futuro viaggio
> - CoS: pagina relativa alla creazione di un nuovo viaggio e possibilità di aggiunta di altri partecipanti sotto forma di invito

## Name: utenti amici
> - Definizione: un utente vuole poter gestire una sua rete di amicizie all'interno dellìapplicazione
>> - Role: utente
>> - Action: cercare utenti e richiedere l'amicizia
>> - Benefit: creazione di una rete di contatti, semplificando la creazione di gruppi di viaggio
> - CoS: un utente vuole ricercare un altro utente mediante username o contatto memorizzato in rubrica (mail o numero di telefono) e richiedere l'amicizia. Un utente preferirebbe anche condividere il suo contatto mediante link o QR code

## Name: aggiunta partecipanti ad un gruppo di viaggio
> - Definizione: un capo viaggio vuole poter aggiungere partecipanti ad un gruppo di viaggio esistente
>> - Role: capo viaggio
>> - Action: aggiunta/modifica di utenti già registrati come partecipanti al gruppo di viaggio
>> - Benefit: condivisione del viaggio con più utenti amici
> - CoS: un utente vuole sfruttare una view opportuna per invitare un utente a partecipare ad un viaggio, mediante invito in-app (tramite amicizia) o invito condivisibile mediante altri mezzi

## Name: aggiunta idee
> - Definizione: un utente partecipante ad un gruppo di viaggio vuole poter proporre una propria idea, in modo facile ed intuitivo
>> - Role: utente partecipante ad un gruppo viaggio
>> - Action: un utente vuole poter proporre al gruppo di viaggio una propria idea, sotto forma di tappa o evento o altra idea inerente, da votare se inserire nell'itinerario di viaggio
>> - Benefit: miglior coordinazione tra utenti e organizzazione dell'itinerario. Storico delle idee proposte
> - CoS: pagina per poter aggiungere la propria idea, con descrizione, link e posizione della tappa/evento. 

## Name: visualizzazione delle idee
> - Definizione: un utente vuole poter visualizzare tutte le idee proposte in maniera ben strutturata e visibile a tutti, senza che siano trascurate alcune proposte
>> - Role: utente partecipante ad un gruppo viaggio
>> - Action: un utente vuole poter navigare con facilità tra le idee proposte e poter votare, mediante sondaggi real-time, per le idee preferite e accettate
>> - Benefit: miglior coordinazione tra utenti e organizzazione dell'itinerario
> - CoS: la visualizzazione deve favorire una chiara lettura di tutte le idee proposte e una valutazione di quelle che un utente vuole accettare, con una chiara visione sull'andamento delle proposte più in voga. La visualizzazione deve distinguere attrazioni turistiche da eventi stabiliti in una data fissa (idee proposte senza data e con data)

## Name: creazione trip di viaggio
> - Definizione: un capo viaggio vuole poter generare il trip in base alle scelte effettuate sulle idee proposte e accettare dai vari partecipanti
>> - Role: capo viaggio
>> - Action: generare il trip di viaggio una volta che i partecipanti sono d'accordo sulle attività da effettuare
>> - Benefit: generazione di un trip globalmente accettato dal gruppo, miglior condivisione dell'itinerario
> - CoS: il sistema deve poter proporre un itinerario coerente con le proposte e date accettate dai partecipanti e che sia il più corto possibile in termini di tempistiche/distanze (sempre nel rispetto del tempo di viaggio)

## Name: modifica del trip generato
> - Definizione: un capo viaggio vuole poter modificare l'itinerario 
>> - Role: capo viaggio
>> - Action: modifica itinerario già generato in caso di cambiamenti di qualsiasi tipo (ad esempio necessità o cambi di programma)
>> - Benefit: miglior flessibilità di organizzazione dell'itinerario
> - CoS: pagina che visualizzi l'itinerario generato e tool di editing per poter aggiungere, rimuovere o adattare l'ordine delle tappe

## Name: segnare le tappe già visitate
> - Definizione: un utente, durante il viaggio, vuole poter segnare le tappe già visitate o gli eventi a cui si è già partecipati, mantenendo aggiornata la lista TO-DO delle tappe da fare
>> - Role: capo viaggio
>> - Action: marking di una tappa/evento come visitata o effettuata
>> - Benefit: miglior tracciamento della progresssione dell'itinerario in corso
> - CoS: pagina per marcare le tappe/eventi visualizzabile solo per il capo viaggio, e visualizzarli chiaramente per tutti divisi tra effettuati e da fare

## Name: navigazione itinerario
> - Definizione: un utente vorrebbe poter specificare eventuali necessità di spostamento mediante mezzi pubblici
>> - Role: utente
>> - Action: specificare eventuali mezzi pubblici da utilizzare
>> - Benefit: miglior creazione dell'itinerario in base ai mezzi di trasporto disponibili
> - CoS: possibilità di poter indicare, per le varie città, come ci si intende spostare; possibilità di poter navigare su una mappa con vari filtri, per mostrare ad esempio le fermate di determinati mezzi pubblici proposti e altre informazioni utili

## Name: pubblicità e sponsorizzazioni
> - Definizione: il sistema deve poter dar risalto a servizi e aziende turistiche che sponsorizzano l'applicazione, in modo da consigliarli e pubblicizzarli se un gruppo organizza un viaggio affine ad essi
>> - Role: applicazione mobile
>> - Action: mostrare in primo piano consigli inerenti a servizi offerti da terze parti sponsor dell'applicazione e del suo sviluppo
>> - Benefit: maggior offerta all'utente, miglior rapporto con gli sponsor
> - CoS: l'utente non deve sentirsi troppo obbligato ad accettare proposte relative ad aziende sponsor

## Name: monitoraggio dell'applicazione
> - Definizione: l'utente amministratore vuole poter gestire gli utenti registrati, monitorare l'andamento dell'applicazione, i suoi contenuti, la sua posizione nel mercato e tutto ciò che compete al monitoraggio strategico e operativo del sistema
>> - Role: amministratore
>> - Action: analizzare dati e andamenti relativi all'applicazione e alla sua community
>> - Benefit: miglior ascolto delle necessità degli utenti, delle problematiche, reattività in caso di guasti o calo di posizione e importanza nel mercato, data analysis
> - CoS: dashboard e cruscotti lato amministrazione per analizzare tutti gli aspetti di interesse; l'utente non deve sentirsi "spiato", ma ascoltato in modo il più anonimo possibile, se non tramite richieste di supporto esplicite
