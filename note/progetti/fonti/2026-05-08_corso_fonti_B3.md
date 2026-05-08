# Corso Marketing Comportamentale - Fonti Lezione B3

**Data:** 2026-05-08
**Tag:** #corso #enel #conflux #B3 #ai #bias #llm #fonti
**Categoria:** progetti

Lezione **B3 — AI come alleato e come "paziente": progettare con i bias e contro i bias delle macchine**.
Doppia direzione: usare l'AI per esplorare/documentare bias rilevanti per un brief; e leggere criticamente i bias delle macchine.

---

## Libri

- **Stuart Russell, *Human Compatible: Artificial Intelligence and the Problem of Control*** (Viking/Penguin, 2019). Ed. it. *Compatibile con l'uomo* (Einaudi, 2025). Il problema del controllo: macchine che deferiscono, agiscono con incertezza, accettano di essere spente. <https://people.eecs.berkeley.edu/~russell/hc.html>
- **Kate Crawford, *Atlas of AI: Power, Politics, and the Planetary Costs of AI*** (Yale UP, 2021). Ed. it. *Né intelligente né artificiale* (Il Mulino, 2021). L'AI come tecnologia estrattiva: terra, lavoro, classificazioni. <https://katecrawford.net/atlas>
- **Ethan Mollick, *Co-Intelligence: Living and Working with AI*** (Portfolio, 2024). Ed. it. *L'intelligenza condivisa* (Luiss UP, 2024). Manuale pratico: AI come collega/coach/critico, le "quattro regole".
- **Cathy O'Neil, *Weapons of Math Destruction*** (Crown, 2016). Ed. it. *Armi di distruzione matematica* (Bompiani). Tre tratti dei modelli pericolosi: opachi, non regolati, scalabili.
- **Safiya U. Noble, *Algorithms of Oppression*** (NYU Press, 2018). Bias razziali nei motori di ricerca: il caso scuola pre-LLM.
- **Ruha Benjamin, *Race After Technology*** (Polity, 2019). "New Jim Code": il discriminatorio mascherato da neutralità tecnica.
- **Arvind Narayanan & Sayash Kapoor, *AI Snake Oil*** (Princeton UP, 2024). Distinzione critica AI predittiva vs generativa, debunking dell'hype. <https://press.princeton.edu/books/hardcover/9780691249131/ai-snake-oil>
- **Buster Benson, *Why Are We Yelling? The Art of Productive Disagreement*** (Portfolio, 2019). L'autore del Cognitive Bias Codex sulla pratica del disaccordo: utile per leggere bias di conferma in workshop e brief.
- **Reid Blackman, *Ethical Machines*** (HBR Press, 2022). Operativizzare etica AI in azienda: bias, spiegabilità, privacy. Taglio executive.
- **Meredith Broussard, *More than a Glitch*** (MIT Press, 2023). Il bias tecnologico come problema sistemico, non bug.
- **Daniel Kahneman, *Thinking, Fast and Slow*** (FSG, 2011). Sistema 1/2: substrato di tutta la letteratura sui bias.

## Paper recenti su LLM bias (2018-2026)

- **Bender, Gebru, McMillan-Major, Shmitchell (2021), *On the Dangers of Stochastic Parrots***. FAccT '21. Manifesto critico sui modelli linguistici come "pappagalli stocastici": costi ambientali, bias, illusione di comprensione. <https://dl.acm.org/doi/10.1145/3442188.3445922> · PDF: <https://s10251.pcdn.co/pdf/2021-bender-parrots.pdf>
- **Mitchell et al. (2019), *Model Cards for Model Reporting***. FAT* '19. Schede di trasparenza per modelli ML. <https://arxiv.org/abs/1810.03993>
- **Buolamwini & Gebru (2018), *Gender Shades***. Bias intersezionale nel gender classification (errori fino al 34,7% su donne dalla pelle scura). <https://proceedings.mlr.press/v81/buolamwini18a.html> · <http://gendershades.org>
- **Rahwan et al. (2019), *Machine behaviour***. *Nature* 568:477-486. Manifesto per uno studio empirico/etologico delle macchine. <https://www.nature.com/articles/s41586-019-1138-y>
- **Rudin (2019), *Stop Explaining Black Box Machine Learning Models for High-Stakes Decisions***. *Nature Machine Intelligence*. Argomento contro la post-hoc explainability. <https://arxiv.org/abs/1811.10154>
- **Rudin et al. (2021), *Interpretable ML: Fundamental Principles and 10 Grand Challenges***. <https://arxiv.org/abs/2103.11251>
- **Sharma et al. / Anthropic (2023), *Towards Understanding Sycophancy in Language Models***. ICLR 2024. RLHF spinge i modelli ad assecondare l'utente. <https://arxiv.org/abs/2310.13548>
- **Hicks, Humphries, Slater (2024), *ChatGPT is bullshit*** (Ethics & Information Technology). Le "allucinazioni" come bullshit nel senso di Frankfurt: indifferenza alla verità. <https://link.springer.com/article/10.1007/s10676-024-09775-5>
- **Huang et al. (2024-25), *A Survey on Hallucination in LLMs: Principles, Taxonomy, Challenges***. ACM TOIS. <https://dl.acm.org/doi/10.1145/3703155> · arXiv: <https://arxiv.org/abs/2311.05232>
- **Hubinger et al. / Anthropic (2024), *Sleeper Agents: Training Deceptive LLMs that Persist Through Safety Training***. <https://arxiv.org/abs/2401.05566>
- **"Towards Trustworthy LLMs: Debiasing and Dehallucinating"** (*AI Review*, Springer, 2024). Visione integrata bias+hallucination. <https://link.springer.com/article/10.1007/s10462-024-10896-y>
- **"Large Language Models Hallucination: A Comprehensive Survey"** (arXiv 2510.06265, 2025).
- **"User-reported LLM hallucinations in AI mobile apps reviews"** (*Scientific Reports* / Nature, 2025). 3M recensioni analizzate. <https://www.nature.com/articles/s41598-025-15416-8>

## Toolkit & risorse pratiche AI

- **Anthropic, *Prompt engineering overview***: <https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview>
- **Anthropic, *Effective Context Engineering for AI Agents*** (2025). Evoluzione del prompt verso il context engineering. <https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents>
- **Anthropic — Interactive Prompt Engineering Tutorial** (GitHub). XML tags, role assignment, chain-of-thought. <https://github.com/anthropics/prompt-eng-interactive-tutorial>
- **OpenAI, *Best practices for prompt engineering***: <https://help.openai.com/en/articles/6654000-best-practices-for-prompt-engineering-with-the-openai-api> · API guide: <https://developers.openai.com/api/docs/guides/prompt-engineering>
- **Prompt Engineering Guide (DAIR.AI)**: open, copre few-shot, chain-of-thought, ToT, scaffolding. <https://www.promptingguide.ai>
- **Claude skill — Behavioral Design** (V. Adiatullina, GitHub). Ciclo completo: define behavior → diagnose barriers → design interventions → check backfire. Behavior = Motivation × Ability × Prompt. <https://github.com/valeria-adiatullina/behavioral-design-claude-skill>
- **MCP Market — UI/UX Psychology & Behavior Design skill**. Bias, trigger comportamentali, leggi Gestalt. <https://mcpmarket.com/tools/skills/ui-ux-psychology-behavior-design>
- **awesome-claude-prompts** (langgptai, GitHub). Curatela di pattern di prompt riusabili. <https://github.com/langgptai/awesome-claude-prompts>
- **Ethan Mollick, *One Useful Thing*** (newsletter). La lettura settimanale più utile su uso pratico/serio degli LLM. <https://www.oneusefulthing.org>
- **IDEO + studi di design**: pattern di LLM nelle fasi divergenti (brainstorming, persona generation, critic mode).

## Cognitive Bias Codex & risorse

- **Lista Wikipedia dei bias cognitivi** — fonte primaria che alimenta la Claude skill in demo. <https://en.wikipedia.org/wiki/List_of_cognitive_biases>
- **Buster Benson, *Cognitive bias cheat sheet***, Medium, 2016. Articolo originale: ~175 bias in 4 macro-problemi (information overload, lack of meaning, need to act fast, what to remember). <https://buster.medium.com/cognitive-bias-cheat-sheet-55a472476b18>
- **John Manoogian III, *Cognitive Bias Codex***: il radial diagram di 188 bias derivato da Benson + Wikipedia. SVG high-res su Wikimedia Commons (CC). <https://commons.wikimedia.org/wiki/File:Cognitive_bias_codex_en.svg> · making-of e poster: <https://www.designhacks.co/pages/about-us>
- **Buster Benson — pile of cognitive biases**, versione "viva" mantenuta dall'autore. <https://busterbenson.com/piles/cognitive-biases/>
- **RiseVerse, *109 Cognitive biases to influence user decisions***. Database operativo per designer/marketer, ispirato a Benson. <https://riseverse.com/resources/cognitive-biases>
- **Nielsen Norman Group — Psychology for UX Study Guide**. Articoli su bias del designer e bias dell'utente. <https://www.nngroup.com/articles/psychology-study-guide/>

## Risorse in italiano

- **Luciano Floridi, *Etica dell'intelligenza artificiale. Sviluppi, opportunità, sfide*** (Raffaello Cortina, 2022, a cura di M. Durante). Riferimento accademico italiano sull'etica dell'AI.
- **Stefano Quintarelli (a cura di), *Intelligenza artificiale*** (Bollati Boringhieri, 2020). Sei voci esperte: tecnico, etico, giuridico, lavoro.
- **Nello Cristianini, *La scorciatoia*** (Il Mulino, 2023) e ***Machina sapiens*** (Il Mulino, 2024). Spiegazione divulgativa rigorosa di come funzionano davvero gli LLM, da uno dei pochi italiani nel cuore tecnico del campo.
- **Diletta Huyskes, *Tecnologia della rivoluzione*** (Il Saggiatore, 2024). Genere, potere, AI — voce critica italiana di nuova generazione.
- **Daniela Tafani, *L'imperatore è nudo? Per una critica filosofica dell'IA*** (Edizioni ETS, 2024). Critica filosofica all'hype AI.
- **Paolo Benanti, *Human in the loop*** (Mondadori, 2022) e ***Homo Faber*** (San Paolo, 2024). Etica AI dal tavolo italiano-vaticano.
- **Tiziano Bonini, *IA: né intelligente, né artificiale***, *doppiozero*. Recensione/sintesi italiana di Crawford. <https://www.doppiozero.com/ia-ne-intelligente-ne-artificiale>
- **Agenda Digitale, *Atlas of AI* (analisi)**: <https://www.agendadigitale.eu/cultura-digitale/atlas-of-ai-quellintreccio-di-potere-politica-e-costi-collettivi-celati-nellintelligenza-artificale/>
- **Podcast *DataKnightmare* (W. Vannini)**, "L'algoritmico è politico". Critico, lucido, tecnico-divulgativo. <https://pod.link/1163697417>
- **Podcast *Il Disinformatico* (P. Attivissimo, RSI)**. Episodi recenti sul lavoro nascosto dietro l'addestramento.
- **Carmilla, *Scenari di intelligenza condivisa***: lettura critica italiana di Mollick. <https://www.carmillaonline.com/2025/05/04/scenari-di-intelligenza-condivisa/>
- **Ma 'ndo AI** — podcast Roma Capitale, etica AI per cittadini. <https://podcasts.apple.com/us/podcast/ma-ndo-ai-un-podcast-sullintelligenza-artificiale/id1793598766>

## Video & Podcast

- **Stuart Russell, *3 principles for creating safer AI*** (TED 2017). <https://www.ted.com/talks/stuart_russell_3_principles_for_creating_safer_ai>
- **Joy Buolamwini, *How I'm fighting bias in algorithms*** (TED 2017). Origine del "coded gaze". <https://www.ted.com/talks/joy_buolamwini_how_i_m_fighting_bias_in_algorithms>
- **Joy Buolamwini, *How to protect your rights in the age of AI*** (TED 2024). <https://www.ted.com/talks/joy_buolamwini_how_to_protect_your_rights_in_the_age_of_ai>
- **Andrej Karpathy, *Intro to Large Language Models*** (1h, nov 2023). <https://www.youtube.com/watch?v=zjkBMFhNj_g>
- **Andrej Karpathy, *Deep Dive into LLMs like ChatGPT*** (3h31, feb 2025). "LLM Psychology": allucinazioni, conoscenza vs working memory, jagged intelligence, "tokens to think". <https://www.youtube.com/watch?v=7xTGNNLPyMI>
- **Kate Crawford, *The Trouble with Bias***, NIPS keynote, 2017. Classificazioni come atti di potere.
- **Kate Crawford, conversazione USC Annenberg sull'Atlas**. <https://annenberg.usc.edu/news/critical-conversations/kate-crawford-maps-world-extraction-and-exploitation-atlas-ai>
- **Emily M. Bender, sito *Stochastic Parrots*** (paper, audiopaper, talk). <https://faculty.washington.edu/ebender/stochasticparrots/>
- **Bender & Hanna, podcast *Mystery AI Hype Theater 3000*** (DAIR). <https://www.dair-institute.org/maiht3k/>
- **Diletta Huyskes, *Resistere all'inevitabile***, TEDxFerrara 2023. <https://www.youtube.com/watch?v=mH2OYUuww2k>
- **Ezra Klein Show**: episodi con Mollick (2024), Hassabis, Suleyman. Conversazioni sulla pratica AI.
- **Hard Fork (NYT)**: episodi su hallucination e bias laundering.

## Case study (AI in marketing / UX / behavior change)

- **Amazon hiring tool (2014-2018)**: penalizzava CV con "women's", privilegiava verbi tipici dei CV maschili. <https://www.reuters.com/article/world/insight-amazon-scraps-secret-ai-recruiting-tool-that-showed-bias-against-women-idUSKCN1MK0AG/>
- **COMPAS / ProPublica (2016)**: bias nel rischio di recidiva, falsi positivi sproporzionati su imputati neri. <https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing>
- **Riconoscimento facciale - Gender Shades**: errori fino al 34,7% su donne dalla pelle scura vs 0,8% su uomini chiari. <http://gendershades.org>
- **Google Translate / bias di genere**: turco → inglese che assegna "he is a doctor / she is a nurse". <https://blog.google/products/translate/reducing-gender-bias-google-translate/>
- **Tandfonline 2025, *Customer Responses to AI-Driven Personalized Journeys***. Tensione personalizzazione vs empowerment. <https://www.tandfonline.com/doi/full/10.1080/00913367.2025.2460985>
- **Medallia / Dynamic Yield case studies**: home improvement +89% acquisti da raccomandazioni; cosmetica DTC +4,2% ARPU; club sportivo +40% conversion. <https://www.dynamicyield.com/case-studies/>
- **Mosaikx, *Successful AI Marketing Campaigns 2024***: Coca-Cola "Create Real Magic", Heinz AI ketchup, Nutella Unica. <https://mosaikx.com/blogs/case-studies-successful-ai-marketing-campaigns-in-2024/>
- **DigitalDefynd, *AI in UX/UI Design: 8 Case Studies***. <https://digitaldefynd.com/IQ/impact-of-artificial-intelligence-on-ux-ui-design/>
- **MIT Sloan EdTech, *When AI Gets It Wrong***. Framework didattico-aziendale su hallucination e bias. <https://mitsloanedtech.mit.edu/ai/basics/addressing-ai-hallucinations-and-bias/>
- **Chatbot sycophancy / "yes-machine"**: utile mostrarlo dal vivo in lezione.

## Voci critiche

- **Bender & Hanna, *The AI Con*** (HarperCollins, 2025). Estensione "trade book" delle Stochastic Parrots: smontare l'hype.
- **Timnit Gebru — DAIR Institute**. Ricerca indipendente fuori da Big Tech. <https://www.dair-institute.org>
- **Margaret Mitchell** (Hugging Face, model cards). <https://huggingface.co/meg>
- **Cynthia Rudin** (Duke Prediction Analysis Lab). "Non si scambia accuratezza con interpretabilità". <https://users.cs.duke.edu/~cynthia/>
- **Iyad Rahwan** (Max Planck, Center for Humans and Machines). <https://www.mpib-berlin.mpg.de/chm>
- **Dan McQuillan, *Resisting AI*** (Bristol UP, 2022). "AI bias laundering" come dispositivo di potere.
- **Anthropic system cards** (Opus/Sonnet/Haiku 4.x). Test di bias politico, sycophancy, comportamenti agentici. <https://www.anthropic.com/system-cards>
- **Anthropic Alignment Science Blog**: <https://alignment.anthropic.com>
- **Yoav Goldberg, critica accademica a Stochastic Parrots** (per onestà del dibattito): <https://gist.github.com/yoavg/9fc9be2f98b47c189a513573d902fb27>

---

## Essential picks (3)

1. **Kate Crawford, *Atlas of AI / Né intelligente né artificiale*** + talk Annenberg. Inquadra l'AI come *sistema socio-tecnico* con bias materiali, non solo statistici. Per il team Innovation Enel è il telaio politico-economico in cui infilare la lezione.
2. **Andrej Karpathy, *Deep Dive into LLMs like ChatGPT*** (cap. "LLM Psychology"). Spiega in modo operativo perché un LLM ha "memoria che non c'è, contesto che non c'è, conoscenza efficiente non certa". Da clippare per la parte tecnica.
3. **Buster Benson, *Cognitive bias cheat sheet*** + **Manoogian, *Cognitive Bias Codex*** + **Wikipedia *List of cognitive biases***. Triade alla base della Claude skill in demo: mappa visuale, tassonomia narrativa, fonte aggiornabile collettivamente. Rende tangibile la doppia direzione "AI per esplorare bias / AI vittima di bias".

---

> **Possibili agganci con il pubblico Enel**
>
> - **Energia & sostenibilità AI:** Crawford (Atlas) e Bender (costi ambientali in Stochastic Parrots) parlano direttamente al core business Enel. Aggancio "specchio": l'AI consuma l'energia che voi producete — opportunità di posizionamento.
> - **Customer journey & nudging:** i case study di personalizzazione (Dynamic Yield, Medallia) e l'edizione finale di *Nudge* con il capitolo "sludge" sono leve concrete per ripensare flussi di acquisizione e customer care nell'energy retail.
> - **Ethics-by-design come vantaggio competitivo:** O'Neil + Rudin + Blackman offrono il quadro per posizionare le scelte AI di Enel come fiducia/brand value, non solo compliance regolatoria.
> - **AI come "paziente" — empatia tecnica:** la metafora "memoria che non c'è / contesto che non c'è" risuona con i marketer senior abituati a brief incompleti; trasforma frustrazione verso l'LLM in metodo (context engineering = brief writing rigoroso).
> - **Demo Claude skill su Cognitive Bias Codex:** durante la lezione, generare in vivo un "bias audit" di un brief Enel reale (es. campagna efficienza energetica → quali bias attivare/disinnescare per spostare il comportamento del cliente).
> - **AI Snake Oil come antidoto al cherry-picking interno:** la distinzione predittiva/generativa di Narayanan & Kapoor è utile per filtrare richieste interne ("usiamo l'AI per X") che mascherano un problema mal posto.
