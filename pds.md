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
- Design accessibile per permettere a tutti di usufruire del sistema (COULD)

## Login e registrazione utente

Etichetta MoSCoW: <b>MUST</b>

Aspetti tecnici:
- API gateway per gestire meglio l'inoltro di richieste derivate dall'utilizzo delle API di accesso (SHOULD)
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
- Link condivisibile per invitare amici (COULD)

## Creazione di un gruppo di viaggio

Etichetta MoSCoW: <b>MUST</b>

Aspetti tecnici:

## Suggerimento idee da visitare

Etichetta MoSCoW: <b>SHOULD</b>

## Votazione e approvazione idee dei partecipanti

Etichetta MoSCoW: <b>MUST</b>

## Creazione del viaggio in automatico

Etichetta MoSCoW: <b>MUST</b>

## Modifica del viaggio proposto apportando rifinimenti manuali

Etichetta MoSCoW: <b>SHOULD</b>

## Modifica del viaggio proposto apportando rifinimenti manuali

Etichetta MoSCoW: <b>SHOULD</b>

## Integrazione con servizi di mappe e routing

Etichetta MoSCoW: <b>COULD</b>

## Integrazione con servizi di mappe e routing

Etichetta MoSCoW: <b>COULD</b>

## Integrazione pubblicità

Etichetta MoSCoW: <b>MUST</b>

## Inizio campagna pubblicitaria al cliente (B2C)

Etichetta MoSCoW: <b>COULD</b>

## Profilo a pagamento (diversi profili)

Etichetta MoSCoW: <b>WOULD</b>
