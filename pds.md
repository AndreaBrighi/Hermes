---
title: Project Definition Statement
layout: home
parent: Planning
nav_order: 2
---

# Project Definition Statement
Per dare un'ulteriore livello di dettaglio tecnico ai team di sviluppo, orientato anche al planning, si è scelto di estendere gli obiettivi da implementare per la Release #1 con aspetti più tecnici e di organizzazione.

Must: requisiti che <b>devono</b> essere soddisfatti nella soluzione finale per considerare il progetto concluso con successo.
Should: requisiti che <b>dovrebbero</b> essere inclusi nella soluzione se è possibile. Solitamente corrispondono a quei requisiti critici che in caso di necessità possono essere sostituiti con dei requisiti alternativi.
Could: requisiti che <b>potrebbero</b> essere inclusi nella soluzione ma non sono necessari. Questi requisiti saranno considerati solo se il tempo e le risorse lo permettono.
Would: requisiti che <b>sarebbero</b> da includere nella soluzione, ma che per decisioni nostre sono stati spostati in altre release successive. Rimane quindi a nostro giudizio l'eventuale anticipazione di tali requisiti.

## Facilità d’uso e intuitività dell’applicazione

Etichetta MoSCoW: <b>SHOULD</b>

Aspetti tecnici:
- Utilizzo di test A/B per capire i gusti e preferenze degli utenti
- Design reattivo per maggiore dinamicità con gli utenti
- Design accessibile per permettere a tutti di usufruire del sistema (<b>COULD</b>)

## Login e registrazione utente

Etichetta MoSCoW: <b>MUST</b>

Aspetti tecnici:
- API gateway per gestire meglio l'inoltro di richieste derivate dall'utilizzo delle API di accesso (<b>SHOULD</b>)
- Microservizio per effettuare login e registrazione (SHOULD, alternativa è il server monolitico)
- Dati criptati e anonimizzati lato server
- Utilizzo di connessioni criptate (e.g. HTTPS)

## Gestione profilo utente

Etichetta MoSCoW: <b>SHOULD</b>

Aspetti tecnici:
- API per modifica dei dati personali dell'utente
- Estensione microservizio logic per gestione utente

## Gestione legami di amicizie all’interno dell’app

Etichetta MoSCoW: <b>MUST</b>

Aspetti tecnici:
- Gestione amicizie con struttura dati tipo grafo efficiente
- Microservizio dedicato per la gestione delle amicizie
- Link condivisibile per invitare amici (<b>COULD</b>)

## Creazione di un gruppo di viaggio

Etichetta MoSCoW: <b>MUST</b>

Aspetti tecnici:
- Microservizio per gestione dei gruppi

## Suggerimento idee da visitare

Etichetta MoSCoW: <b>SHOULD</b>
Aspetti tecnici:
- Microservizio per gestione idee
- Aggiunta foto/link/puntatori a mappe per maggiore chiarezza (<b>COULD</b>)

## Votazione e approvazione idee dei partecipanti

Etichetta MoSCoW: <b>MUST</b>

Aspetti tecnici:
- Visualizzazione voti per ogni idea (<b>COULD</b>)
- Modifica voto e relativa memorizzazione

## Creazione del viaggio in automatico

Etichetta MoSCoW: <b>MUST</b>

Aspetti tecnici:
- Microservizio per gestione viaggio
- Creazione percorso
- Ottimizzazione percorso (<b>SHOULD</b>)

## Modifica del viaggio proposto apportando rifinimenti manuali

Etichetta MoSCoW: <b>SHOULD</b>

Aspetti tecnici:
- Integrazione col microservizio già presente
- Ottimizzazione ricalcolo viaggio (<b>COULD</b>)

## Integrazione con servizi di mappe e routing

Etichetta MoSCoW: <b>COULD</b>

Aspetti tecnici:
- Utilizzo di mappe e algoritmi in-cloud open source (e.g. OpenStreetMap e MapBox)
- Mappa custom con le informazioni principali facile da navigare (<b>WOULD</b>)

## Integrazione pubblicità

Etichetta MoSCoW: <b>MUST</b>

Aspetti tecnici:
- Integrazione con servizi esterni (e.g. Google ADS)
- Pubblicità non troppo invasiva

## Profilo a pagamento (diversi profili)

Etichetta MoSCoW: <b>WOULD</b>

Aspetti tecnici:
- Servizi di pagamento
- Per decisione di psicologia si sceglie di renderla disponibile in futuro, aggiungendo funzionalità aggiuntive a pagamento (mediante abbonamento o <i>pay only once</i>)

# Assunzioni/Rischi/Ostacoli
Sono definiti solo assunzioni/ostacoli per la Release #1, gli altri sono presenti nella seguente pagina: <a src="./assunzioni_rischi_ostacoli.html"> link </a>.
Stessa cosa vale per i rischi: <a src="./risk_management.html"> link </a>.
Di seguito sono elencati solamente quelli relativi ad aspetti tecnici di cui sopra.

## Rischi
- Gestione a microservizi potrebbe complicare il design lato server e l'interazione con l'utente
- Un cattivo design potrebbe portare a un degrado delle performance e peggiorare la manutenibilità
- Problematiche di sicurezza per gestione dei dati personali

## Assunzioni
- Creazione di un ambiente database distribuito che vada di pari passo ai microservizi
- Skill basilari degli utenti nell'utilizzo di un'applicazione (accesso, connessione a internet ecc...)

## Ostacoli
- Integrazione di servizi di terze parti