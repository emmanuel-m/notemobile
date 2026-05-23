# Strategie multicanale dei distributori di energia europei durante i blackout

**Data:** 2026-05-23
**Tag:** #enel #multicanale #blackout #distributori #energia #UX #accessibilità
**Categoria:** appunti

---

## Contesto

Analisi comparativa delle strategie di canale utilizzate da diversi distributori di energia europei (DSO) per la gestione delle comunicazioni durante i blackout. Lavoro in corso per Enel.

### La sfida dell'unbundling

In Europa, la liberalizzazione del mercato energetico ha separato (unbundling) la distribuzione dalla fornitura. Questo crea un problema ricorrente per gli utenti: **la confusione tra fornitore e distributore**. Quando manca la corrente, molti utenti non sanno a chi rivolgersi — chiamano il fornitore (con cui hanno il contratto) invece del distributore (che gestisce la rete). Ogni DSO deve quindi comunicare in modo chiaro il proprio ruolo e rendere facilmente accessibili i propri canali di segnalazione, in un contesto dove il brand del distributore è spesso meno noto di quello del fornitore.

Fonte: [Unbundling distribution and supply — Bain & Company](https://www.bain.com/contentassets/ea2e76d2bd134ef38dd036cba57e5610/unbundling_energy_distribution_supply.pdf)

---

## Distributori analizzati

| Distributore | Paese | Clienti |
|---|---|---|
| **E-REDES** | Portogallo | 6,4 milioni |
| **Enedis** | Francia | 36 milioni |
| **ESB Networks** | Irlanda | 2,5 milioni |
| **ČEZ Distribuce** | Repubblica Ceca | 3,7 milioni |

---

## Due filosofie di design a confronto

Non sono varianti dello stesso approccio, ma **due filosofie distinte** nella progettazione dell'esperienza utente durante un'emergenza.

### Filosofia A — "Designed for everyone" (Convergent design)
*Un flusso unico, ottimizzato per l'utente medio*

**Logica:** trovare il minimo denominatore comune. Un percorso che funzioni più o meno per tutti, facendolo bene. Meno canali, più focus.

**Esempio principale: Enedis (Francia)**

Flusso sequenziale:
1. **Web** → l'utente accede a enedis.fr, fa un'autodiagnosi per capire se il problema è in casa o sulla rete
2. **Telefono** → solo se la simulazione conferma un problema di rete, viene indirizzato a chiamare

**Canali attuali:**
- Sito web enedis.fr (ottimizzato mobile) con sezione "Panne et interruption"
- Account cliente online con tracking in tempo reale
- Telefono per segnalazione guasti

**Dato chiave:** Enedis ha dismesso l'app mobile "Enedis à mes côtés" il **7 luglio 2023**, nonostante buone recensioni. Tre ragioni dichiarate:
1. Il portale web è stato riprogettato per essere più completo e fruibile da qualsiasi browser
2. Duplicazione di funzionalità con le app dei fornitori di energia (monitoraggio Linky, consigli risparmio)
3. Costi di manutenzione di un'app nativa iOS/Android

La scelta è coerente con la filosofia: ridurre i canali, concentrare le risorse su quelli che restano, farli funzionare bene per tutti.

**Fonti:**
- [Enedis — Panne et interruption](https://www.enedis.fr/panne-et-interruption)
- [App Enedis supprimée en 2023](https://www.fournisseurs-electricite.com/enedis/appli-enedis-a-mes-cotes)
- [Enedis — Compte client](https://www.enedis.fr/presse/retrouvez-tous-vos-services-sur-votre-compte-client-enedis)

---

**Altro esempio convergente: ESB Networks (Irlanda)**

ESB Networks convoglia le segnalazioni principalmente su due canali:
- **PowerCheck** (portale web) — mappa in tempo reale delle interruzioni, segnalazione guasti online
- **Telefono** — linea guasti 1800 372 999

Canali secondari:
- SMS per notifiche su interruzioni pianificate (opt-in tramite account online)
- Nessuna app mobile dedicata per la segnalazione guasti

ESB Networks ha investito in tecnologie avanzate (digital twin con LiDAR per mappare l'infrastruttura), ma mantiene un approccio a canali limitati per l'interazione con il cliente.

**Fonti:**
- [ESB Networks — Report a Power Outage](https://www.esbnetworks.ie/power-outages/report-a-power-outage)
- [ESB Networks — PowerCheck](https://powercheck.esbnetworks.ie/)

---

### Filosofia B — "Tailored for each one" (Divergent design)
*Più canali paralleli, ciascuno autonomo e completo*

**Logica:** offrire diversi touchpoint indipendenti per la segnalazione, in modo che ogni utente scelga quello più adatto alle proprie capacità e preferenze. Riconosce che utenti diversi hanno bisogni diversi.

**Esempio principale: E-REDES (Portogallo)**

**Canali disponibili per segnalare un blackout (tutti autonomi):**
- **App mobile** — E-REDES Digital (iOS e Android), con funzione "Estou sem luz" (sono senza luce), tracking in tempo reale
- **Sito web** — Balcão Digital (sportello digitale) su balcaodigital.e-redes.pt
- **WhatsApp** — numero +351 913 846 398
- **Telefono** — Linha de Avarias 800 506 506 (gratuito, 24h)

Ogni canale consente di completare l'intero flusso di segnalazione in autonomia. L'utente non è costretto a passare da un canale all'altro.

**Fonti:**
- [E-REDES — Sono senza corrente, cosa fare?](https://www.e-redes.pt/en/i-am-without-power-what-should-i-do)
- [E-REDES App](https://www.e-redes.pt/en/e-redes-app)
- [E-REDES — Anomalie e guasti](https://www.e-redes.pt/en/node/27011)

---

**Altro esempio divergente: ČEZ Distribuce (Repubblica Ceca)**

**Canali disponibili:**
- **Telefono** — Linea gratuita 800 850 860 (24/7 per guasti)
- **App mobile** — per autolettura, informazioni su punti di connessione e guasti
- **Portale web** — distribuzione digitale con possibilità di connessione diretta tra sistemi
- **Centri fisici** — rete di centri di consulenza tecnica con personale dedicato
- **Notifiche elettroniche** — informazioni su interruzioni inviate via data box

**Fonte:**
- [ČEZ Distribuce — Hotline](https://www.cezdistribuce.cz/en/about-the-company/news-from-cez-distribuce-world/hotline)
- [ČEZ Distribuce — Segnalazione guasti](https://www.cezdistribuce.cz/cs/pro-zakazniky/nahlasit/chci-nahlasit-poruchu)

---

## Confronto sintetico

| | **"Designed for everyone"** | **"Tailored for each one"** |
|---|---|---|
| **Italiano** | Per tutti | Per ciascuno |
| **Logica** | Un flusso unico ottimale per l'utente medio | Più canali alternativi per utenti diversi |
| **Touchpoint** | Sequenziali e obbligati (prima web, poi telefono) | Paralleli e a scelta (ognuno è autonomo) |
| **Modello utente** | L'utente medio, il minimo denominatore | L'utente specifico, con le sue particolarità |
| **Accessibilità** | Rischio esclusione se un passaggio non è accessibile | Inclusivo per design: chi non può parlare usa il digitale, chi non può scrivere usa il vocale |
| **Efficienza** | Alta (meno canali da mantenere) | Minore (più canali da mantenere) |
| **Trend** | Enedis ha *ridotto* i canali (dismessa l'app) | E-REDES ha *aggiunto* canali (WhatsApp) |
| **Esempi** | Enedis, ESB Networks | E-REDES, ČEZ Distribuce |

---

## Brainstorm terminologico

Possibili formulazioni in inglese per i due approcci:
- **"Designed for everyone"** vs **"Tailored for each one"**
- **"One path for all"** vs **"Many paths for each"**
- **"Universal flow"** vs **"Adaptive access"**
- **"Lowest common denominator"** vs **"Highest individual fit"**
- **"Convergent design"** vs **"Divergent design"**

---

## Contesto di settore

### E.DSO e l'evoluzione della customer interaction
E.DSO (European Distribution System Operators, 37 DSO europei) ha pubblicato nel gennaio 2026 il paper "From Service Providers to Digital Partners: The Evolution of Customer Interaction in Europe's DSOs", che documenta come i DSO stiano ridefinendo il panorama del customer service in un'era di transizione energetica e digitalizzazione rapida.

I temi chiave:
- I DSO stanno passando da fornitori di servizi a **partner digitali**
- Maggiore comunicazione con i clienti sullo stato della rete
- Discussione su quali canali e tecnologie usare per **comunicare le crisi**
- Best practice per l'empowerment del cliente

**Fonti:**
- [E.DSO — Customer Interaction Paper (PDF, gennaio 2026)](https://www.edsoforsmartgrids.eu/content/uploads/2026/01/e.dso-joint-paper_from-service-providers-to-digital-partners-the-evolution-of-customer-interaction-in-europes-dsos.pdf)
- [E.DSO — Customer Service Overview](https://www.edsoforsmartgrids.eu/edso-publications/e-dso-customer-service-overview-paper/)
- [E.DSO — Best Practices DSOs Customer Empowerment](https://www.edsoforsmartgrids.eu/edso-publications/best-practices-dsos-enhancing-customer-empowerment/)
- [Sia Partners — Digitally Wired: DSOs Customer Experience](https://www.sia-partners.com/en/insights/publications/digitally-wired-how-dsos-are-reinventing-customer-experience)

---

## Da approfondire

- [ ] Leggere il paper E.DSO di gennaio 2026 sulla customer interaction
- [ ] Mappare i canali specifici di E-Distribuzione (Enel) per confronto
- [ ] Raccogliere dati su efficacia di ciascun approccio durante blackout reali (es. blackout Iberia aprile 2025)
- [ ] Collegamento con il tema accessibilità (EAA) per il contesto Enel
- [ ] Verificare se ci sono dati su quale approccio genera meno carico sul call center
