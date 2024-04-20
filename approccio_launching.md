---
title: Approccio Launching
layout: home
parent: Approccio
nav_order: 3
---

# Approccio Kick-Off
In seguito al primo <i>Kick-Off Meeting</i> si è discusso e anticipato anche alcuni aspetti riguardanti la fase successiva al planning, ovvero l'avviamento del progetto, la <b>launching phase</b>. Durante questo meeting si sono discussi in particolare i seguenti punti:
- Tecnologie che si vorrebbero utilizzare
- Eventuale training su tecnologie non conosciute a fondo
- Linee guida sulla divisione dei task e, in particolare, viene identificato un coordinatore di gruppo per ogni working team
- Precedenti esperienze di ogni membro, in modo da trovare task simili a lavori già svolti per recuperare conoscenza
- Come organizzare e assegnare il primo Sprint

# Figure e team necessari allo sviluppo e relative responsabilità
- Team Mobile
    - 1 responsabile
    - 1 sviluppatore junior
- Team Backend
    - 1 responsabile
    - 2 sviluppatore junior
- Cloud Expert
- Consulenza esterna
    - 1 collaboratore esterno
- Focus Group
    - numero di utenti deciso all'occorrenza sfruttando canali di beta test
- Designer Team
    - 1 collaboratore esterno esperto di Grafica e Design

## Ruoli Task
Una volta identificati i Team di sviluppo e i ruoli, procediamo a stilare una tabella indicativa sulla distribuzione e assegnazione delle responsabilità in base ai tipi di task. La tabella rimane indicativa, in quanto si preferisce adattare il personale al singolo task dello Sprint in base alle esigenze o disponibilità delle persone, in puro stile Agile.

Legenda:
- <b>R</b>esponsible: Responsabile dell’attività e del suo completamento con successo
- <b>A</b>ccountable: Incaricato dell’approvazione del risultato dell’attività
- <b>S</b>upport: Risorsa assegnata per supportare il responsabile
- <b>C</b>onsulted: Disponibile per assistere il responsabile
- <b>I</b>nformed: Membro che deve essere tenuto informato sullo stato di avanzamento

| Tipo di task                            | Project Manager | Designer Team | Responsabile Mobile | Sviluppatore Mobile | Cloud expert | Responsabile Backend | Sviluppatore Backend |
|:----------------------------------------|:----------------|:--------------|:--------------------|:------------------- |:-------------|:---------------------|:---------------------|
| <b> Architettura backend </b>           | I               |               | I                   | I                   | A - R        | R                    | I                    |
| <b> Backend </b>                        | I               |               | I                   | I                   | C            | A - R                | R                    |
| <b> Grafica mobile </b>                 | S               | R             | A                   | I                   |              | I                    |                      |
| <b> Implementazione mobile </b>         | I               |               | A - R               | R                   |              | C                    | I                    |
| <b> Test usabilità e accessibilità </b> | A               | I             | R                   | S                   | I            | I                    | I                    |

Si noti che i responsabili possono avere doppio ruolo nel caso siano anche sviluppatori e autori di un qualche task.
Nel caso del Cloud expert il doppio ruolo nasce dalla collaborazione col responsabile backend, sulla quale il Cloud expert ha l'ultima parola. 
