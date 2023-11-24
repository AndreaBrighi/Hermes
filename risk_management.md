---
title: Risk Management
parent: Scoping
layout: home
nav_order: 4
---
# Rischi
Per analizzare i rischi relativi al progetto, faremo riferimento alla seguente tabella Risk Matrix, che indica la probabilità (likelihood) che il rischio accada e l'eventuale impatto (impact) sul progetto che ne potrebbe conseguire.
Si identificano 4 livelli:
- High Risk: alta probabilità di rischio e impatto di notevole gravità. In questo caso è consigliata un'azione di correzione preventiva e repentina per evitare il rischio, riducendone la gravità dell'impatto o la probabilità
- Medium High Risk: rischio di tipo medio alto. Può succedere che il rischio in oggetto possa risultare in un impatto e probabilità mediamente alto
- Medium Risk: un rischio con contenuto impatto sul sistema e sul progetto, con probabilità da prendere in considerazione ma non vincolante
- Low Risk: bassa probabilità e basso impatto sul progetto, tale da ignorarne l'esistenza ma comunque da evidenziare e accettarne il rischio

<center>
<img src="img/risk_matrix.jpg"/>
</center>

Iniziamo dividendo i fattori di rischio in 4 categorie, ovvero di tipo: 
- tecnico (TEC)
- gestione di progetto (PM)
- organizzazione (ORG)
- esterni (EXT)

Elenchiamo di seguito la valutazione dei rischi identificati per lo sviluppo del progetto:

{: .highlight }
> ## 
>
> <b> Descrizione: </b> 
>
> <b> Classificazione: </b> 
>
> <b> Likelihood: </b> 
>
> <b> Impact: </b> 
>
> <b> Score: </b> 
>
> <b> Risk mitigation: </b> 

{: .highrisk }
> ## Costi elevati
>
> <b> Descrizione: </b> uno dei rischi a cui sarà necessario fare attenzione è il possibile sforamento del budget nel costo del personale e delle risorse impiegate nello sviluppo del progetto. Essendo una startup in avviamento, con un budget limitato, sarà fondamentale fare economy nelle prime fasi del progetto, fino alla prima release
>
> <b> Classificazione: </b> ORG - PM
>
> <b> Likelihood: </b> 3
>
> <b> Impact: </b> 4
>
> <b> Score: </b> High risk
>
> <b> Risk mitigation: </b> una slow start per quanto riguarda le risorse umane, preferendo un graduale incremento dell'organico, cercando, per un breve intervallo di tempo iniziale, tirocinanti o figure da formare in pro bono. Per quanto riguarda le risorse computazionali necessarie, esse non verranno allocate se non al momento del bisogno, e sempre facendo attenzione alla disponibilità economica.

<!-------------------------------------------------------------------------------->

{: .mediumhighrisk }
> ## Sicurezza sui dati personali e sensibili
>
> <b> Descrizione: </b> data la natura dei flussi di dati generati e raccolti dal sistema sui vari utenti, il rischio è un'eventuale minaccia alla loro integrità e riservatezza da parte di esterni malintenzionati. Inoltre, sarà necessario applicare regolamenti europei e internazionali riguardanti la gestione della privacy (es. GDPR).
>
> <b> Classificazione: </b> TEC - EXT
>
> <b> Likelihood: </b> 3
>
> <b> Impact: </b> 3
>
> <b> Score: </b> Medium High risk
>
> <b> Risk mitigation: </b> 
> - applicazione delle normative sull'applicazione
> - gestione esclusivamente dei dati necessari
> - criptazione e anonimizzazione dei dati raccolti
> - ridondanza e backup dei dati per evitare eventuali ransomware e similari

<!------------------------------------------------------------------------------------->

{: .mediumhighrisk }
> ## Insufficenza di sponsorizzazioni o finanziamenti e guadagno tramite pubblicità
>
> <b> Descrizione: </b> la problematica è quella di non trovare una giusta visibilità nel mercato e lo stesso interesse verso il sistema sviluppato, rischiando di non trovare sponsorizzazioni o finanziamenti tali da permettere sviluppi futuri al progetto. Unito a questo c'è il rischio di non guadagnare a sufficenza da acquisti in app o pubblicità.
>
> <b> Classificazione: </b> EXT
>
> <b> Likelihood: </b> 2
>
> <b> Impact: </b> 4
>
> <b> Score: </b> Medium High risk
>
> <b> Risk mitigation: </b> l'unica mitigazione possibile individuata è il potenziamento del settore marketing in una fase avanzata del progetto, specialmente in una fase stabile per la startup, altrimenti si ferma il progetto per evitare di entrare in perdita economica

<!-------------------------------------------------------------->

{: .mediumrisk }
> ## Difficoltà nell'utilizzo
>
> <b> Descrizione: </b> un rischio è l'eventualità di riscontrare un certo livello di difficoltà, da parte degli utenti, nell'utilizzo dell'applicazione mobile, essendo la natura dell'applicazione stessa molto orientata all'interazione condivisa con altri utenti, nonché l'accessibilità a un più grande bacino di utenti
>
> <b> Classificazione: </b> TEC
>
> <b> Likelihood: </b> 2
>
> <b> Impact: </b> 2
>
> <b> Score: </b> Medium risk
>
> <b> Risk mitigation: </b> analisi preventiva mediante mockup e focus group unito a experience prototyping per analizzare e discutere le scelte UI e UX e aumentare il livello di usabilità e accessibilità

<!------------------------------------------------------------------------------>

{: .mediumrisk }
> ## Integrazione con sistemi esterni
>
> <b> Descrizione: </b> l'integrazione con eventuali sistemi esterni, come ad esempio l'accesso alle informazioni sui mezzi pubblici nelle grandi città, potrebbero portare a problematiche di livello tecnico ed esterno, in quanto l'integrazione prevede un adattamento a sistemi già esistenti
>
> <b> Classificazione: </b> TEC - EXT
>
> <b> Likelihood: </b> 2
>
> <b> Impact: </b> 2
>
> <b> Score: </b> Medium risk
>
> <b> Risk mitigation: </b> per mitigare questo tipo di rischi è necessario contattare direttamente i fornitori dei servizi e richiedere con anticipo documentazione e stipulare accordi di utilizzo

<!----------------------------------------------------------------------------------->

{: .mediumrisk }
> ## Ritardi nelle fasi progettuali e di sviluppo
>
> <b> Descrizione: </b> da tenere in considerazione è il rischio di non rispettare le scadenze degli obiettivi intermedi e di release, che potrebbero portare a un ritardo complessivo nello sviluppo e conseguentemente nei rilasci, impattando anche sul costo di implementazione e organizzazione interna del team (riduzione motivazione e conseguentemente livello di produttività).
>
> <b> Classificazione: </b> PM
>
> <b> Likelihood: </b> 2
>
> <b> Impact: </b> 2
>
> <b> Score: </b> Medium risk
>
> <b> Risk mitigation: </b> effettuare un buon planning nelle primissime fasi del progetto, mettendo in gioco le voci di ciascun membro del team, dai ruoli di management ai ruoli più tecnici, mediante stime il più accurate possibile (basate sull'esperienza dei membri). Tramite Product Backlog, inoltre, si potrebbe controllare al termine di ogni sprint il lavoro eseguito e stimolare discussioni collettive tramite sprint review.

<!-------------------------------------------------------------------------------->

{: .mediumrisk }
> ## Progetto che non risponde correttamente alle specifiche
>
> <b> Descrizione: </b> il rischio è che in una fase inoltrata dello sviluppo del sistema, esso potrebbe non soddisfare correttamente le specifiche definite in principio o le aspettative degli utenti sul sistema finale, sulla base delle funzionalità dichiarate in fase di marketing e promozione.
>
> <b> Classificazione: </b> TEC
>
> <b> Likelihood: </b> 1
>
> <b> Impact: </b> 3
>
> <b> Score: </b> Medium risk
>
> <b> Risk mitigation: </b> sicuramente un approccio Agile con Sprint Review di gruppo con gli utenti potrebbe tornare utile, sfruttando lo sviluppo iterativo di user stories e verifiche continuative con gli utenti o con gli alti membri del team.

<!-------------------------------------------------------------------------->

{: .lowrisk }
> ## Introduzione di bug nascosti o problemi di UX
>
> <b> Descrizione: </b> essendo un progetto informatico e tecnologico, con l'impiego di diverse tecnologie, è facile incorrere nell'introduzione di bug o problemi di UX per l'utente, cosa che potrebbe causare ritardi nei rilasci e lavoro extra per sistemare gli errori introdotti nello sviluppo.
>
> <b> Classificazione: </b> TEC
>
> <b> Likelihood: </b> 2
>
> <b> Impact: </b> 1
>
> <b> Score: </b> Low risk
>
> <b> Risk mitigation: </b> un modo per evitare la proliferazione di bug e specifiche UX non conformi è l'adozione di un approccio Test Driven Development, in quanto, non avendo nella prima fase di sviluppo Group Test di utenti, potrebbero verificarsi lo sviluppo di comportamenti non attesi o debiti tecnici trascurati. Inoltre, sarebbe utile disaccoppiare la logica applicativa dalle interfacce utente di input/output e l'integrazione con altri sistemi, sfruttando design architetturali noti.

<!-------------------------------------------------------------------------->

{: .lowrisk }
> ## Technology selection
>
> <b> Descrizione: </b> un fondamentale step preliminare allo sviluppo del progetto consiste nell'analisi delle proposte tecnologiche presenti nel mercato, quali utilizzare per sviluppare il software in-house e quali da usare in outsourcing (linguaggi, framework, tools, servizi cloud). Una loro errata valutazione e selezione potrebbe portare a problematiche in fase di sviluppo e ritardare i tempi di consegna
>
> <b> Classificazione: </b> TEC
>
> <b> Likelihood: </b> 1
>
> <b> Impact: </b> 2
>
> <b> Score: </b> Low risk
>
> <b> Risk mitigation: </b> un semplice modo per mitigare questa problematica in principio consiste nell'effettuare un'analisi preventiva dei prodotti disponibili nel mercato, le conoscenze presenti all'interno del team, necessità ipotizzate e budget disponibile

<!-------------------------------------------------------------------------->
