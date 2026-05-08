# Corso Marketing Comportamentale - Fonti Lezione B3

**Data:** 2026-05-08
**Tag:** #corso #enel #conflux #B3 #ai #bias #llm #fonti
**Categoria:** progetti

Lezione **B3 — AI come alleato e come "paziente": progettare con i bias e contro i bias delle macchine**.
Doppia direzione: usare l'AI per esplorare/documentare bias rilevanti per un brief; e leggere criticamente i bias delle macchine.

---

## Libri fondativi

- **Stuart Russell, *Human Compatible: Artificial Intelligence and the Problem of Control*** (Viking/Penguin, 2019). Edizione italiana **"Compatibile con l'uomo"** (Einaudi, 2025). Fonda il problema del controllo: macchine che deferiscono agli umani, agiscono con incertezza, accettano di essere spente. <https://people.eecs.berkeley.edu/~russell/hc.html>
- **Kate Crawford, *Atlas of AI: Power, Politics, and the Planetary Costs of AI*** (Yale UP, 2021). Edizione italiana **"Né intelligente né artificiale"** (Il Mulino, 2021). Smonta il mito dell'AI immateriale: estrazione, lavoro, classificazioni discriminatorie. <https://katecrawford.net/atlas>
- **Ethan Mollick, *Co-Intelligence: Living and Working with AI*** (Portfolio, 2024). Edizione italiana **"L'intelligenza condivisa"** (Luiss University Press, 2024, trad. P. Bassotti). Manuale pratico per usare l'AI come collega/coach/critico, con i suoi quattro principi.
- **Daniel Kahneman, *Pensieri lenti e veloci*** (Mondadori). Riferimento canonico Sistema 1/Sistema 2 da cui pesca tutta la letteratura sui bias.
- **Cathy O'Neil, *Armi di distruzione matematica*** (Bompiani). Per il filo "modelli opachi che fanno scelte che ricadono sulle persone".

## Paper accademici (2018-2025)

- **Bender, Gebru, McMillan-Major, Shmitchell (2021), *On the Dangers of Stochastic Parrots: Can Language Models Be Too Big?*** FAccT '21. Manifesto critico sui modelli linguistici come "pappagalli stocastici". <https://dl.acm.org/doi/10.1145/3442188.3445922> · PDF: <https://s10251.pcdn.co/pdf/2021-bender-parrots.pdf>
- **Mitchell et al. (2019), *Model Cards for Model Reporting***. FAT* '19. Schede di trasparenza per modelli ML. <https://arxiv.org/abs/1810.03993>
- **Buolamwini & Gebru (2018), *Gender Shades***. Bias intersezionale nei sistemi di gender classification (errori fino al 34,7% su donne dalla pelle scura). <https://proceedings.mlr.press/v81/buolamwini18a.html> · <http://gendershades.org>
- **Rahwan et al. (2019), *Machine behaviour***. *Nature* 568:477-486. Manifesto per uno studio interdisciplinare del comportamento delle macchine. <https://www.nature.com/articles/s41586-019-1138-y>
- **Rudin (2019), *Stop Explaining Black Box Machine Learning Models...***. *Nature Machine Intelligence*. Argomento contro la post-hoc explainability per decisioni high-stakes. <https://arxiv.org/abs/1811.10154>
- **Sharma et al. / Anthropic (2023), *Towards Understanding Sycophancy in Language Models***. ICLR 2024. RLHF spinge i modelli ad assecondare l'utente. <https://arxiv.org/abs/2310.13548> · <https://www.anthropic.com/research/towards-understanding-sycophancy-in-language-models>
- **Hicks, Humphries, Slater (2024), *ChatGPT is bullshit*** (Ethics & Information Technology). Argomenta che le "allucinazioni" sono meglio descritte come bullshit nel senso di Frankfurt: indifferenza alla verità. <https://link.springer.com/article/10.1007/s10676-024-09775-5>
- **Huang et al. (2024), *A Survey on Hallucination in Large Language Models***. Tassonomia, cause, mitigazione. <https://arxiv.org/abs/2311.05232>
- **Hubinger et al. / Anthropic (2024), *Sleeper Agents: Training Deceptive LLMs that Persist Through Safety Training***. <https://arxiv.org/abs/2401.05566>

## Risorse in italiano

- **Luciano Floridi, *Etica dell'intelligenza artificiale. Sviluppi, opportunità, sfide*** (Raffaello Cortina, 2022, a cura di M. Durante). Riferimento accademico italiano sull'etica dell'AI.
- **Nello Cristianini, *La scorciatoia*** (Il Mulino, 2023) e ***Machina sapiens*** (Il Mulino, 2024). Spiegazione divulgativa rigorosa di come funzionano davvero gli LLM, scritta da uno dei pochi italiani che lavorano nel cuore tecnico del campo.
- **Tiziano Bonini, "IA: né intelligente, né artificiale"**, *doppiozero*. Recensione/sintesi italiana di Crawford. <https://www.doppiozero.com/ia-ne-intelligente-ne-artificiale>
- **"Atlas of AI", Agenda Digitale**: <https://www.agendadigitale.eu/cultura-digitale/atlas-of-ai-quellintreccio-di-potere-politica-e-costi-collettivi-celati-nellintelligenza-artificale/>
- **Podcast *DataKnightmare* di Walter Vannini** ("L'algoritmico è politico"). Critico, lucido, tecnico-divulgativo. <https://pod.link/1163697417>
- **Podcast *Il Disinformatico* di Paolo Attivissimo** (RSI). Episodi recenti sul lavoro nascosto dietro l'addestramento dei modelli.
- **Carmilla, "Scenari di intelligenza condivisa"**: lettura critica italiana di Mollick. <https://www.carmillaonline.com/2025/05/04/scenari-di-intelligenza-condivisa/>

## Video, podcast, talk

- **Stuart Russell, *3 principles for creating safer AI*** (TED 2017). <https://www.ted.com/talks/stuart_russell_3_principles_for_creating_safer_ai>
- **Joy Buolamwini, *How I'm fighting bias in algorithms*** (TED). Origine del concetto di "coded gaze". <https://www.ted.com/talks/joy_buolamwini_how_i_m_fighting_bias_in_algorithms>
- **Andrej Karpathy, *Intro to Large Language Models*** (1h, nov 2023). <https://www.youtube.com/watch?v=zjkBMFhNj_g>
- **Andrej Karpathy, *Deep Dive into LLMs like ChatGPT*** (3h31, feb 2025). Tratta esplicitamente "LLM Psychology": allucinazioni, conoscenza vs memoria di lavoro, jagged intelligence, "models needing tokens to think". <https://www.youtube.com/watch?v=7xTGNNLPyMI>
- **Emily M. Bender**, sito ufficiale "Stochastic Parrots" con paper, audiopaper, talk. <https://faculty.washington.edu/ebender/stochasticparrots/>
- **Kate Crawford, conversazione USC Annenberg sul libro**. <https://annenberg.usc.edu/news/critical-conversations/kate-crawford-maps-world-extraction-and-exploitation-atlas-ai>
- **Ethan Mollick, blog *One Useful Thing***. La lettura settimanale più utile su uso pratico/serio degli LLM. <https://www.oneusefulthing.org>

## Casi reali (perfetti per la lezione)

- **Amazon hiring tool (2014-2018)**: penalizzava CV con "women's", privilegiava verbi tipici dei CV maschili. <https://www.reuters.com/article/world/insight-amazon-scraps-secret-ai-recruiting-tool-that-showed-bias-against-women-idUSKCN1MK0AG/> · <https://www.technologyreview.com/2018/10/10/139858/>
- **COMPAS / ProPublica (2016)**: bias nel rischio di recidiva, falsi positivi sproporzionati su imputati neri. <https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing>
- **Riconoscimento facciale - Gender Shades**: errori fino al 34,7% su donne dalla pelle scura vs 0,8% su uomini chiari. <http://gendershades.org>
- **Google Translate / bias di genere**: traduzione da lingue gender-neutral (turco, ungherese) verso inglese che assegna "he is a doctor / she is a nurse". <https://blog.google/products/translate/reducing-gender-bias-google-translate/>
- **Chatbot sycophancy / "yes-machine"**: utile mostrare in vivo durante la lezione un esempio di assecondamento dell'utente.

## Risorse pratiche su LLM nel design/marketing

- **Anthropic, *Prompt engineering overview***: <https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview>
- **OpenAI, *Best practices for prompt engineering with the API***: <https://help.openai.com/en/articles/6654000-best-practices-for-prompt-engineering-with-the-openai-api>
- **Prompt Engineering Guide (DAIR.AI)**: open, copre few-shot, chain-of-thought, ToT, scaffolding. <https://www.promptingguide.ai>
- **Ethan Mollick, post operativi sul blog** (es. "co-intelligence" workflows, "the four rules"): <https://www.oneusefulthing.org>
- **IDEO + altri studi di design**: pattern d'uso degli LLM nelle fasi divergenti del design (brainstorming, persona generation, critic mode).

## Cognitive Bias Codex e Wikipedia

- **Lista Wikipedia dei bias cognitivi** (la fonte primaria che alimenta la skill Claude in demo). <https://en.wikipedia.org/wiki/List_of_cognitive_biases>
- **Buster Benson, *Cognitive bias cheat sheet***, Medium, 2016. L'articolo originale che organizza i ~175 bias in 4 macro-problemi (information overload, lack of meaning, need to act fast, what to remember). <https://buster.medium.com/cognitive-bias-cheat-sheet-55a472476b18>
- **John Manoogian III, *Cognitive Bias Codex***: il radial diagram di 188 bias derivato dallo schema Benson + lista Wikipedia. SVG ad alta risoluzione su Wikimedia Commons (CC). <https://commons.wikimedia.org/wiki/File:Cognitive_bias_codex_en.svg> · poster commerciale e making-of su <https://www.designhacks.co/pages/about-us>

## Voci critiche / tecniche su come funzionano davvero gli LLM

- **Anthropic system cards** (Opus 4, Opus 4.1, Sonnet 4.5, Opus 4.5, Haiku 4.5). Documentano test di bias politico/discriminatorio, sycophancy, comportamenti agentici. <https://www.anthropic.com/system-cards>
- **Anthropic Alignment Science Blog**: <https://alignment.anthropic.com>
- **Margaret Mitchell**, Hugging Face / model cards. Profilo: <https://huggingface.co/meg>
- **Timnit Gebru**, *Distributed AI Research Institute (DAIR)*. <https://www.dair-institute.org>
- **Cynthia Rudin**, Duke Prediction Analysis Lab. Posizione "non si scambia accuratezza con interpretabilità". <https://users.cs.duke.edu/~cynthia/>
- **Iyad Rahwan**, Max Planck, *Center for Humans and Machines*. <https://www.mpib-berlin.mpg.de/chm>
- **Karpathy, blog tecnico** e thread X. Il riferimento più diretto su "stocastic, jagged, hallucination as feature".

## Essential picks (3)

1. **Kate Crawford, *Atlas of AI / Né intelligente né artificiale*** + il TED-equivalent talk su Annenberg. Inquadra l'AI come *sistema socio-tecnico* con bias materiali, non solo statistici. Per il team Innovation Enel è il telaio politico-economico in cui infilare la lezione.
2. **Andrej Karpathy, *Deep Dive into LLMs like ChatGPT*** (cap. "LLM Psychology"). Spiega in modo operativo perché un LLM ha "memoria che non c'è, contesto che non c'è, conoscenza efficiente non certa". Ottimo da citare/clippare per la parte tecnica della lezione.
3. **Buster Benson, *Cognitive bias cheat sheet*** + **Manoogian, *Cognitive Bias Codex*** + **Wikipedia *List of cognitive biases***. Triade alla base della Claude skill in demo: una mappa visuale, una tassonomia narrativa, una fonte aggiornabile collettivamente. Nella lezione rendono tangibile la doppia direzione "AI per esplorare bias / AI vittima di bias".
