---
title: Approccio Planning
layout: home
parent: Approccio
nav_order: 2
---
# Descrizione dell'approccio utilizzato per la fase di Planning
Subito dopo aver concluso la fase di scoping, si procede alla stesura della seconda fase di analisi che è il planning. Come primo step si completa lo schema di Event Storming realizzato organizzando i vari gruppi di dominio in differenti Bounded Context, che permettono di definire dei contesti indipendenti tra loro su cui i team lavorano in contemporanea (questa è solo una divisione a livello di dominio e non di piattaforme, in quanto backend o frontend rimangono team differenti).
Una User Story può coinvolgere più Bounded Context, quindi di fatto può coinvolgere più team, questo è il motivo del dividerli in task.

## Value Breakdown Structure
Analizzando alcune risorse online per cercare un metodo da utilizzare per adattare l'approccio User Story al WBS (Work Breakdown Structure) ci siamo imbattuti in una descrizione di un approccio alternativo, molto simile al classico WBS ma più in linea con le caratteristiche dell'Agile e Scrum.

<a> <i> https://andrew-40903.medium.com/forget-the-wbs-in-agile-you-need-a-vbs-c2d87fdc1f4e </i> </a>

Dato che negli approcci Agile non si parla esplicitamente di WBS, e per definizione la pianificazione non è un'attività con un solo ciclo di vita, in questo caso non riusciamo a modellare e pianificare in modo iterativo, dinamico e continuo, non conosciamo a priori tutta la quantità di lavoro da implementare per arrivare alla soluzione finale: in realtà neanche questa è ben definita inizialmente, può cambiare nel corso dello sviluppo anche a <i> scoping </i> definito.
L'approccio utilizzato in fase di Scoping (User Story Board) sfrutta le user story per catturare gli elementi essenziali di un requisito, utilizzato in sostituzione del classico RBS.
Così come la WBS amplia la RBS, la VBS fornisce un'ulteriore analisi e livello di dettaglio delle User Story, aggiungendo il concetto di task.

La Issue, nel caso di un approccio Agile, è fondamentale: la issue acquista quindi valore nella pianificazione, non solo in fase di una futura manutenzione: per questo motivo, essendo l'approccio Agile iterativo e incrementale, è necessario tener conto in fase di pianificazione e sviluppo nelle varie fasi anche delle issue aperte e non ancora chiuse, assimilabili come task della VBS.

I concetti che si vanno quindi ad aggiungere al VBS sono:
- Task: piccoli elementi che compongono una user story, che rappresenta un diario di bordo legato alla precisa storia, per definire quando essa può essere considerata come <it> Done </it>.
In questo modo riusciamo a definire, per ogni requisito, il ruolo di chi si impersona nella storia, un'azione e un beneficio garantito dal completamento di una determinata user story. Infine, troviamo una Condition of Satisfaction, ovvero come si ritiene completata una determinata user story.
- Issue: problema riscontrato al termine di ogni ciclo di sviluppo, che può essere uno sprint o il rilascio di un'Alpha release. La issue acquista quindi un valore nella pianificazione della futura quantità di lavoro, che potrebbe aumentare in vista della release successiva. Acquista anche valore per l'utente e la sua esperienza verso l'applicazione.

Task e Issue sono i mattoncini di base su cui si basa l'approccio Scrum, che altro non è che una implementazione Agile.

# Stima della complessità dei task in Agile
Per quantificare la complessità e l'<i> effort </i> necessario per portare a termine uno specifico task è stata utilizzata la stima in <b> Story Points </b>, ovvero una stima fortemente utilizzata in approccio SCRUM che non esprime il carico di lavoro in termini di giorni/uomo, ma appunto la complessità di sviluppo delle user story. Partendo quindi dai task individuati a partire dalle User Story (grazie alla scomposizione VBS) si assegnano un numero di story points concordato ad ogni task. Questi punteggi sono adimensionali, non indicano una quantità legata a tempo o spazio. Gli story points sono fondamentali per avere una più chiara idea sul lavoro richiesto da una specifica user story o una determinata epica per esser portata a termine, quindi aiutando in fase di planning l'organizzazione degli sprint e le relative review.
Ogni User Story avrà uno score di Story Points pari alla somma degli Story Points di tutti i task che ne fanno parte; ugualmente una epica avrà uno score pari alla somma degli Story Points delle User Story che ne fanno parte.

## Metodo di stima: Planning Poker
Per poter dare una stima di Story Points ad ogni task si è utilizzata la tecnica del Planning Poker: è una metodologia di tipo Consensus-based gamificata, ovvero una tecnica molto simile ad un gioco (utile a coinvolgere maggiormente i componenti) utilizzata per dare delle stime in modo anonimo. Più specificamente si utilizzano delle carte con dei numeri per assegnare un certo numero di Story Points ad un preciso task, coprendola e mischiandola insieme alle altre, così da garantire l'anonimato. Questo aiuta a creare un alto livello di discussione e evitare l'influenza degli altri partecipanti nello scegliere la stima. Si utilizzano anche in questo caso più round nel caso di un distaccamento troppo elevato tra i vari voti e, quindi, un basso livello di consenso.
Si è scelto di utilizzare un tool online che permette di realizzare sessioni di Planning Poker in modo totalmente condiviso e real-time, scegliendo di effettuare un'ulteriore round nel caso in cui la coesione, l'accordo, risulti inferiore al 75% (75% dei partecipanti hanno votato diversamente tra loro).
Si noti che si è scelto di utilizzare la sequenza numerica di Fibonacci per definire la scala di possibili valori da selezionare, ovvero le carte da scegliere per ogni round. Chiaramente il voto personale deve essere influenzato solo dalla propria esperienza e dal livello di conoscenza del dominio.

## Gestione Agile
Si è scelto di utilizzare il sistema software in-cloud <i> Jira </i> per poter gestire il progetto sfruttando la metodologia agile: essa infatti permette di individuare il cosiddetto Product Backlog, ovvero l'insieme delle epiche, user story e task da portare a termine, imporre dei vincoli di precedenza e priorità, assegnare task ai vari membri del progetto, associare descrizioni e story points e tanto altro. Inoltre per ogni task è presente una tabella riepilogativa che mostra la sessione di Planning Poker effettuata per quel preciso task e le considerazioni fatte su di esso.