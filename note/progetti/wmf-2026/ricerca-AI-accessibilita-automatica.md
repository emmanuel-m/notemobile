# Ricerca: AI e valutazione automatica dell'accessibilità web

**Data:** 2026-04-19
**Tag:** #AI #accessibilità #WCAG #testing-automatico #ricerca
**Categoria:** appunti

---

## 1. Il dato storico: quanto trovano i tool automatici tradizionali?

Il dato comunemente citato è che i tool automatici trovano solo il **20-30% dei problemi** di accessibilità. Questo numero si riferisce alla percentuale di *criteri di successo WCAG* che possono essere verificati automaticamente.

Tuttavia, Deque nel 2021 ha contestato questa metrica con uno studio su larga scala:
- **2.000+ audit**, 13.000+ pagine, quasi 300.000 issue analizzate
- Risultato: axe-core identifica il **57% delle issue di accessibilità** per volume
- La differenza sta nella metrica: non "quanti criteri WCAG si possono testare" ma "quante issue reali si trovano"
- Alcuni tipi di errori sono molto più frequenti di altri (es. contrasto insufficiente), quindi in termini di volume il dato sale

Secondo Accessible.org, la situazione per criteri WCAG è:
- **~13%** dei criteri WCAG può essere verificato automaticamente con alta affidabilità
- **~45%** dei criteri può essere parzialmente verificato (ma serve conferma umana)
- **~42%** dei criteri non può essere rilevato automaticamente — richiede giudizio umano su qualità, appropriatezza, accuratezza o esperienza utente

**Fonti:**
- [Deque: Automated Testing Identifies 57% of Issues](https://www.deque.com/blog/automated-testing-study-identifies-57-percent-of-digital-accessibility-issues/)
- [Accessible.org: Automated Scans Flag 13% of WCAG Criteria](https://accessible.org/automated-scans-wcag/)

---

## 2. Cosa cambia con gli LLM? La ricerca accademica

### Studio López-Gil e Pereira (Springer, 2024)
Studio chiave: "Turning manual web accessibility success criteria into automatic: an LLM-based approach"
- Testati **3 criteri WCAG che richiedono valutazione manuale:**
  - 1.1.1 Contenuto non testuale
  - 2.4.4 Scopo del link (nel contesto)
  - 3.1.2 Lingua delle parti
- Risultato: detection rate complessivo dell'**87,18%**
- Conclusione: gli LLM possono essere integrati con i tool automatici esistenti, migliorando la capacità di rilevare issue che i tool automatici attualmente non trovano

**Fonte:** [Springer: LLM-based approach](https://link.springer.com/article/10.1007/s10209-024-01108-z)

### Studio ScreenAudit (CHI 2025)
- 6 esperti di accessibilità hanno analizzato 14 schermate di app mobile indipendentemente
- ScreenAudit (tool basato su LLM) ha trovato il **69,2%** di 163 errori identificati dagli esperti
- Precisione: **71,3%**
- Forte correlazione tra valutazioni degli esperti e report generati dall'AI

**Fonte:** [ScreenAudit paper (CHI 2025)](https://faculty.washington.edu/wobbrock/pubs/chi-25.02.pdf)

### Studio ACM 2025 — LLM per validazione accessibilità web
- "How an LLM Can Improve Automatic Web Accessibility Validation"
- Presentato alla 16ª conferenza biennale del SIGCHI italiano
- Conferma che gli LLM possono migliorare la validazione automatica

**Fonte:** [ACM: LLM Web Accessibility Validation](https://dl.acm.org/doi/10.1145/3750069.3750310)

### Studio ACM 2025 — Assessment LLM-Based
- "An Assessment of LLM-Based Auditing and Validation for Web Accessibility"
- Ulteriore conferma del potenziale, con limiti da indagare

**Fonte:** [ACM: LLM-Based Auditing Assessment](https://dl.acm.org/doi/10.1145/3748699.3749805)

---

## 3. LLM e produzione di codice accessibile

La ricerca sulla capacità degli LLM di *generare* codice accessibile mostra risultati misti:

- **Carnegie Mellon:** l'82% delle label ARIA generate da AI soddisfano i requisiti WCAG senza modifiche quando testate con screen reader
- **Pattern base vs complessi:** accuratezza dell'83% sui pattern base, ma calo al **47%** per widget interattivi complessi senza intervento umano
- **Tabelle ordinabili:** solo il **34%** delle tabelle ordinabili generate da AI comunicano correttamente lo stato di ordinamento agli screen reader (studio 2024)

**Fonte:** [TestParty: LLMs and Accessible UI Code Generation](https://testparty.ai/blog/emerging-accessibility-research-llms-accessible-ui-code-generation)

---

## 4. Lo stato dell'accessibilità web oggi — WebAIM Million 2026

Il report WebAIM Million 2026 offre un quadro preoccupante:
- **95,9%** delle homepage ha almeno un errore WCAG rilevato (in aumento dal 94,8% del 2025)
- Media di **56,1 errori per pagina** (+10,1% rispetto al 2025)
- Inversione del trend di miglioramento degli ultimi 6 anni
- Complessità delle pagine aumentata del 22,5% in un anno (1.437 elementi medi per pagina)

### Errori più comuni:
- Contrasto insufficiente: **83,9%** delle homepage
- Alt text mancante: **53%**
- Input form senza label: **51%**
- Link vuoti: **46%**
- Pulsanti vuoti: **31%**

### Dato rilevante per lo speech:
WebAIM suggerisce che l'aumento degli errori potrebbe essere correlato all'**uso crescente di framework, librerie di terze parti e pratiche di coding assistite da AI** — un dato provocatorio che merita riflessione.

**Fonte:** [WebAIM Million 2026](https://webaim.org/projects/million/)

---

## 5. Strumenti open source e AI

### axe-core (Deque)
- Oltre **3 miliardi di download**, standard de facto
- Open source, integrabile con Playwright, WebdriverIO, CI/CD
- axe-core 4.5: prime regole WCAG 2.2 (touch target, focus appearance)
- Versione Pro (non open): Intelligent Guided Tests (IGTs) — workflow AI-assistiti per issue che l'automazione non copre
- Zero false positive come principio di design

**Fonte:** [axe-core GitHub](https://github.com/dequelabs/axe-core)

### Previsioni: AI Hybrid Audits
- Accessible.org prevede audit WCAG ibridi AI per il **Q1 2027**
- L'idea è combinare scansione automatica, analisi LLM e revisione umana in un flusso integrato

**Fonte:** [Accessible.org: AI Hybrid WCAG Audits](https://accessible.org/ai-hybrid-wcag-audits/)

---

## 6. Il dibattito: overlay vs assessment automatico

### Overlay (accessiBe, UserWay, AudioEye) — TEMA SEPARATO
- **FTC ha multato accessiBe** per 1 milione di dollari (aprile 2025) per pubblicità ingannevole
- La claim del "95% di compliance" è stata esplicitamente vietata
- Oltre **600 esperti** di accessibilità hanno contestato le claim degli overlay
- Il 22% delle cause di accessibilità digitale nel primo semestre 2025 ha coinvolto siti con overlay
- Gli overlay **confliggono con le tecnologie assistive** degli utenti, peggiorando l'esperienza
- The A11Y Project li definisce "attivamente dannosi"

### La voce della comunità disabile
- Le persone con disabilità riportano che gli overlay **riducono la funzionalità** e **aumentano la frustrazione**
- Gli overlay sovrascrivono le configurazioni personalizzate delle tecnologie assistive
- Vice ha riportato testimonianze dirette: "questo strumento AI sta peggiorando il web per noi"

**Fonti:**
- [Vice: People With Disabilities Say This AI Tool Is Making the Web Worse](https://www.vice.com/en/article/people-with-disabilities-say-this-ai-tool-is-making-the-web-worse-for-them/)
- [ACM: Promise and Pitfalls of Overlays for Blind Users](https://dl.acm.org/doi/fullHtml/10.1145/3663548.3675650)
- [Accessibility.Works: Overlay Widgets Attract Lawsuits](https://www.accessibility.works/blog/avoid-accessibility-overlay-tools-toolbar-plugins/)

---

## 7. Sintesi: cosa può e cosa non può fare l'AI nell'assessment

### Cosa l'AI/LLM MIGLIORA rispetto ai tool tradizionali:
- Valutazione della **qualità** dell'alt text (non solo presenza/assenza)
- Comprensione del **contesto semantico** (es. scopo di un link)
- Analisi della **lingua** delle parti di pagina
- Detection rate su criteri "manuali" fino all'**87%** (vs 0% dei tool tradizionali)
- Analisi di **screenshot** per problemi visivi (ScreenAudit: 69% detection)

### Cosa l'AI NON PUÒ ancora fare:
- Testare l'**esperienza reale** con tecnologie assistive
- Valutare la **navigabilità** complessiva di un'interfaccia
- Giudicare se un **percorso alternativo** è equivalente
- Verificare la coerenza dell'**esperienza utente** attraverso flussi complessi
- Sostituire il **testing con utenti reali** con disabilità

### Il quadro numerico riassuntivo:
| Approccio | Copertura criteri WCAG | Note |
|-----------|----------------------|-------|
| Tool automatici tradizionali | ~13% affidabile, ~45% parziale | axe-core: 57% per volume di issue |
| LLM su criteri "manuali" | 87% detection su 3 criteri testati | Studio accademico, campione limitato |
| ScreenAudit (LLM su mobile) | 69% delle issue trovate dagli esperti | Precisione 71% |
| Testing manuale esperto | ~100% | Lento, costoso, non scalabile |

---

## 8. Implicazioni per lo speech e per il lavoro di Giuseppe

1. **L'AI non è il sacro graal** ma sposta significativamente il confine dell'automazione
2. **Il dato WebAIM 2026 è provocatorio:** l'AI nel coding potrebbe star *peggiorando* l'accessibilità, non migliorandola
3. **La combinazione tool automatici + LLM + esperto umano** è il modello emergente (audit ibridi previsti per 2027)
4. **Gli overlay sono un fallimento conclamato** — distinguere nettamente dall'assessment automatico
5. **Giuseppe potrebbe sperimentare:** far valutare a un LLM dei criteri manuali su un sito reale e confrontare con la propria valutazione esperta
