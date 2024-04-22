---
title: Monitoring details
layout: home
parent: Monitoring
nav_order: 1
---

# Gestione dei rischi
Il piano di monitoraggio e controllo dei rischi ha lo scopo di identificare, valutare e gestire i rischi elencati nel documento di Risk Management già stilato (<a href="./risk_management.html">link</a>). Il Risk Log sarà utilizzato come strumento per registrare e monitorare i rischi nel corso del progetto. Le decisioni chiave per il monitoraggio e controllo dei rischi sono le seguenti:
- Durante le riunioni di organizzazione preliminare per ogni nuovo sprint, si cercano tra i task da assegnare quali possono avere uno o più dei rischi identificati, inoltre si applicano le <i>mitigation</i> pianificate
- Durante la review dei task si aggiorna lo stato dei rischi (Risk Log) con le nuove informazioni raccolte
- Si valuta e analizza l'efficacia delle azioni di <i>mitigation</i> e si adattano, se necessario, o si aggiornano in modo da avere una miglior gestione dei rischi e un minor impatto
- Preparazione di report periodici con riassunti e informazioni significative sullo stato dei rischi, le azioni intraprese e il loro andamento

# Sprint Review
Al termine di ogni Sprint viene discussa e analizzata la qualità e quantità del lavoro svolto e si verifica di essere nei tempi previsti dalla schedula principale. Si ricorda che in caso di divergenza, è ammessa la modifica della pianificazione generale in favore all'approccio dinamico e agile che incoraggia un riadattamento del planning o della schedula, cercando di rispettare sempre le deadline delle varie release.
Un altro step che aiuta a capire le esigenze del pubblico di riferimento è l'uso di Focus Group: si prevede una sottomissione più o meno periodica di demo funzionanti al fine di comprendere se si è centrata l'usabilità dell'app e le sue funzionalità.

# Monitoraggio Release
A seguito della prima release, ci si accerta che i commenti ricevuti sull'applicazione attraverso le piattaforme di Store, siano in linea con quelle ricevute dai Focus Group. Si valutano i suggerimenti ricevuti al fine di migliorare l'applicazione e la sua fruibilità. Ci si accerta inoltre che le nuove funzionalità suggerite dagli utenti siano già previste tra le funzionalità individuate in fase di Scoping, ed eventualmente si aggiornano con le nuove idee non presenti (se possibile).
Questa fase può ovviamente essere estesa per l'individuazione e risoluzione di problemi riscontrati dagli utenti e non verificati durante lo sviluppo.

# Issue Log
Come già evidenziato in fase di Planning, l'uso delle Issue è fondamentale per il planning e il conseguente monitoraggio post-release, includendo tutti quei problemi riscontrati dagli utenti che necessitano di un'aggiornamento in release o patch minori. Sarà necessario uno strumento per la segnalazione dei problemi da parte degli utenti, che verranno convertiti in Issue in <i>Jira</i>, in modo da integrare i due strumenti per avere la lista completa dei problemi riscontrati da risolvere.

# Monitoraggio dei costi
Essendo una startup, il budget disponibile per l'avvio del progetto è particolarmente ridotto e tutte le risorse fondamentali devono essere acquisite per la prima volta. Nel tentativo di spendere il meno possibile si cerca di ridurre la quantità di spesa necessaria per ogni risorsa ed eventualmente di tempo di utilizzo (come le consulenze). Bisogna tenere in conto le licenze necessarie per lo sviluppo e i componenti hardware necessari sempre per sviluppo e testing dell'applicazione, creando un inventario di tutta l'infrastruttura (hardware e software) presente.
Al fine di ridurre le spese necessarie si crea un account per un servizio di Cloud hosting che verrà ampliato nel numero di servizi e livello di qualità nel tempo in base alle esigenze, ai fondi disponibili e allo stato di avanzamento del progetto.

# Gestione dei report di controllo
Lo strumento principale utilizzato in fase di pianificazione e di sviluppo degli Sprint è <i>Jira</i>. A seguito di uno Sprint Meeting si può estendere la descrizione di ciascun task ed eventualmente realizzare una scaletta sotto forma di checklist, da assegnare poi ai membri del team, per aiutarli nel completamento del task. Questo strumento rende possibile visionare lo stato di avanzamento di ciascun task, e più in generale la presenza di task permette di comprendere lo stato di avanzamento dello sprint in sviluppo.
Lo stato dei task viene espresso tramite etichetta:
- To Do: il task è in attesa di essere assegnato e quindi ancora da iniziare
- In Progress: il task è stato assegnato è in attesa di esser portato a termine
- Done: il task è da considerare completato
Come già descritto, è possibile creare una serie di dipendenze tra task, mentre una User Story si considera completata quando tutti i suoi task sono portati a termine correttamente. La stessa cosa vale per le Issue.
Inoltre, se si ritiene necessario, è possibile aggiungere etichette custom per dare più espressività e significato allo stato di ciascun task.
