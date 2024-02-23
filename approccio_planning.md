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
- Task: piccoli elementi che compongono una user story, che rappresenta un diario di bordo legato alla precisa storia, per definire quando essa può essere considerata come <it> Done </it>
In questo modo riusciamo a definire, per ogni requisito, il ruolo di chi si impersona nella storia, un'azione e un beneficio garantito dal completamento di una determinata user story. Infine, troviamo una Condition of Satisfaction, ovvero come si ritiene completata una determinata user story.
- Issue: problema riscontrato al termine di ogni ciclo di sviluppo, che può essere uno sprint o il rilascio di un'Alpha release. La issue acquista quindi un valore nella pianificazione della futura quantità di lavoro, che potrebbe aumentare in vista della release successiva. Acquista anche valore per l'utente e la sua esperienza verso l'applicazione.

Task e Issue sono i mattoncini di base su cui si basa l'approccio Scrum, che altro non è che una implementazione Agile.