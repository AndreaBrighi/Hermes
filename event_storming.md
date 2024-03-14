---
title: Event Storming
layout: home
parent: Scoping
nav_order: 9
---

# Conclusione scoping
Per concludere la fase di scoping e prima di procedere nel successivo step di planning, abbiamo organizzato un meeting per delineare a grandi linee i concetti principali da sviluppare seguendo l'approccio di Event Storming.

## Event Storming
Cos'è l'Event Storming? E' un framework collaborativo per esplorare un dominio complesso sfruttando una lavagna (nel nostro caso virtuale) e post-it colorati, ognuno con il proprio significato e semantica.
Questo approccio favorisce il design di un sistema pulito e ben manutenibile, event-driven e per supportare un business evolutivo, come nel nostro caso essendo una startup: questo lo troviamo nella capacità di identificare opportunità e possibili hotspot, i quali rappresentano un primo segnale di eventuali problematiche che potrebbero occorre e a cui si dovrebbe fare attenzione. Inoltre aiuta anche a definire processi interni, relazioni e vincoli, anche di natura esterna come dipendenze da terze parti.

Significato post-it in base al colore:
- Attore (giallo): colui che intende effettuare un'operazione sul sistema
- Azione (blu): l'azione che l'utente vuole effettuare
- Domain Event (arancio): il risultato dell'azione a livello di logica di dominio
- Hotspot (rosa): possibile problematica che potrebbe scaturire
- Sistema (rosso): sistema che rientra come collaboratore
- Opportunità (azzurro): eventuale opportunità che scaturisce dallo sviluppo di un particolare evento

<iframe width="768" height="432" src="https://miro.com/app/live-embed/uXjVNqQPB28=/?moveToViewport=32,-1053,923,668&embedId=31021021664" frameborder="0" scrolling="no" allow="fullscreen; clipboard-read; clipboard-write" allowfullscreen></iframe>