# Casi studio super app: Asia, Occidente, Europa (note di dettaglio)

**Data:** 2026-11-01 16:45
**Tag:** #superapp #wechat #satispay #revolut #casistudio #fonti
**Categoria:** progetti

> Materiale di contesto per la consulenza UX su REBELL. Indice: [report di sintesi](00-report-completo.md).


Method note: 17 web searches (search-engine summaries of primary and press sources). No full-page fetches were done, so figures come from search-result extracts and should be spot-checked against the linked primaries before going in client material. Items marked [UNVERIFIED-BACKGROUND] come from prior knowledge and were not confirmed with a source in this session. They are listed under Gaps only, never as findings.

## 1. Definitions and typologies of "super app"

### Takeaway
There are two working definitions. Gartner's is architectural: core features plus independently built mini-apps, the "Swiss Army knife". a16z/Connie Chan's is behavioral: many unrelated services mashed into one high-frequency app, with "apps within an app" as WeChat's key innovation. Typologies by anchor use case (messaging, payments, mobility, retail, bank) are an analyst convention and not a formal standard.

### Cited Findings
- Gartner: a superapp "provides end-users (customers, partners or employees) with a set of core features plus access to independently created miniapps". It is "like a Swiss army knife… a range of component tools (miniapps) that the user can use and remove as needed." — [Gartner, "What is a superapp" (Sep 28, 2022)](https://gcom.pdo.aws.gartner.com/en/articles/what-is-a-superapp); [TechTarget](https://techtarget.com/whatis/definition/super-app)
- Gartner forecast (2022): by 2027, more than 50% of the world's population will be daily active users of multiple super apps. Some secondary sources drop the "more than". — [Ionic blog citing Gartner Top Tech Trends 2023](https://ionic.io/blog/2023-will-be-all-about-superapps); [Joget citing Gartner webinar, Feb 21, 2023](https://joget.com/superapps-in-the-enterprise-up-up-and-away/?llm_view=1)
- Gartner also counts enterprise/employee super apps, since the definition includes "customers, partners or employees". This matters for B2B and consultancy framing. — [Gartner](https://gcom.pdo.aws.gartner.com/en/articles/what-is-a-superapp)
- Connie Chan (a16z, 2018, "Rise of the Super App"): Chinese apps such as WeChat and Alipay show "what's possible when an entire country leapfrogs over the PC era directly to mobile". A super app "mixes and mashes a bunch of seemingly unrelated services together in one application". — [a16z](https://a16z.com/rise-of-the-super-app-mobile-first-product-ideas-from-china/); [Connie Chan newsletter, "What is a Super App?"](https://conniesnewsletter.substack.com/p/what-is-a-super-app)
- a16z credits WeChat's success to "apps within an app": official accounts and mini-programs that let third-party businesses live inside the chat interface. — [Antoine Buteau summary of Connie Chan (secondary)](https://www.antoinebuteau.com/lessons-from-connie-chan/)
- Chan contrasts WeChat's vertical approach (engagement and frequency) with the West's horizontal expansion for user numbers. She also identifies trust as integral to super app success. — [Buteau (secondary)](https://www.antoinebuteau.com/lessons-from-connie-chan/); [podcast description via podwise](https://podwise.ai/episodes/5284358)
- Emerging-market framing: super apps proliferate where infrastructure (payments, logistics) is missing and the app fills the gap. — [Afridigest](https://afridigest.substack.com/p/why-super-apps-are-proliferating)

### Inferences
- Proposed typology, synthesized from the cases below:
  - (a) Messaging-led: WeChat, LINE, KakaoTalk.
  - (b) Payments/wallet-led: Alipay, Paytm, Satispay, Twint, Vipps MobilePay.
  - (c) Mobility/delivery-led: Grab, Gojek, Rappi, Uber, Bolt, Glovo.
  - (d) Bank/neobank-led: Revolut, N26, Bunq, Kakao Bank.
  - (e) Retail/commerce-led: Amazon, Mercado Libre, Meituan.
  - (f) An emerging AI-assistant layer: ChatGPT apps, which would be a "super app without being an app".
- Gartner's definition is easy to meet technically (a mini-app container). The a16z definition sets a high bar: daily frequency plus trust. Most European "super apps" meet the first but not the second.
- For Switzerland and Europe, Gartner's employee super app concept is a separate, lower-risk opportunity: an internal app with mini-apps for HR, expenses, facilities and similar services.

### Gaps
- No peer-reviewed academic definition was retrieved in this session. Candidate literature [UNVERIFIED-BACKGROUND]: Steinberg, Mukherjee & Punathambekar, "Media power in digital Asia: Super apps and megacorps" (Media, Culture & Society, 2022); Chen & Qiu on WeChat platformization; Jia, Nieborg & Poell on platform ecosystems. Verify these before citing.
- McKinsey, BCG and Bain super app reports were not retrieved. [UNVERIFIED-BACKGROUND] BCG has written on "super apps" in banking, and McKinsey on "Asia's super apps" and on Western ecosystem plays.

## 2. Asian and LatAm cases: anchor, expansion sequence, ecosystem model, metrics

### Takeaway
The Asian winners all started from one very high-frequency anchor: chat (WeChat, Kakao, LINE), rides (Grab, Gojek) or payments (Alipay, Paytm). They then added payments as the connective tissue and opened to third parties only after reaching mass scale. Profitability came late. Grab reported its first full-year net profit only for 2025, and Rappi became EBITDA-positive in 2025. Paytm shows that regulatory failure in the financial layer can collapse the whole super app thesis.

### Cited Findings
**WeChat/Weixin (Tencent), messaging-led, open third-party mini-program model**
- Combined Weixin and WeChat MAU: 1,418 million at Dec 31, 2025 (+2% YoY), per Tencent's 2025 results released Mar 18, 2026. Mini Program GMV growth was described only as "double-digit". — [Coinlaw (aggregator quoting Tencent results)](https://coinlaw.io/wechat-statistics/); [SQ Magazine](https://sqmagazine.co.uk/wechat-statistics/)
- Mini Programs: about 764M DAU in 2025, up from about 689M in 2024 (QuestMobile via Statista); about 945M MAU and about 4.3M registered programs. One aggregator labels 945M as DAU, which conflicts. Treat it as MAU. — [99 Coupons Journal (aggregator)](https://blog.99coupons.ai/wechat-statistics); [Coinlaw](https://coinlaw.io/wechat-statistics/)
- Mini Program GMV is reported as "RMB 8 trillion" in a headline. This is aggregator-level and unconfirmed against Tencent. — [Coinlaw](https://coinlaw.io/wechat-statistics/)
- China's Android distribution runs largely through third-party OEM app stores rather than Google Play. This structural factor weakened the gatekeeper and allowed in-app ecosystems. — [Connie Chan-related summary](https://www.antoinebuteau.com/lessons-from-connie-chan/)

**Grab (SE Asia), mobility-led, now delivery, fintech and ads**
- FY2025: revenue $3.37B (+20% YoY), first full-year net profit of $200M (+$358M YoY), adjusted EBITDA $500M (+60%), adjusted FCF $290M. Q4 2025 On-Demand GMV was $6.1B (+21%). — [Grab Q4/FY2025 earnings release (SGX)](https://links.sgx.com/FileOpen/Grab%20-%20Q4%20Full%20Year%202025%20Earnings%20Release.ashx?App=Announcement&FileID=874808); [Grab IR PDF](https://s205.q4cdn.com/179588156/files/doc_financials/2025/q4/Grab-Q4-2025-Earnings-Release.pdf); [The Diplomat](https://thediplomat.com/2026/02/southeast-asias-grab-finally-turns-a-profit/)
- FY2025 On-Demand GMV per MTU was $513, up from $494. MTU reportedly rose from about 41M to about 47M; this comes from a secondary source and was not confirmed in Grab's release. — [Grab release](https://s205.q4cdn.com/179588156/files/doc_financials/2025/q4/Grab-Q4-2025-Earnings-Release.pdf); [Yahoo Finance call highlights](https://finance.yahoo.com/news/grab-q4-earnings-call-highlights-131945313.html)

**Paytm (India), payments-led, cautionary case**
- In January 2024 the RBI ordered Paytm Payments Bank (PPBL) to virtually halt core operations, after a March 2022 ban on onboarding new customers. The RBI cancelled the licence effective Apr 24, 2026. Court-supervised winding-up orders followed in July 2026. — [The Week (Apr 2026)](https://www.theweek.in/news/biz-tech/2026/04/25/paytm-payments-bank-license-cancelled-impact.html); [Gizmotimes](https://www.gizmotimes.com/business/paytm-payments-bank-shutdown/51092)
- Inc42: the bank suspension "dealt the lethal blow" and "more or less forced" CEO Vijay Shekhar Sharma to shelve the super app dream. The e-commerce revival was dropped, and the company is shedding parts of its super app empire. — [Inc42](https://inc42.com/features/how-paytms-super-app-machine-came-to-a-grinding-halt/)
- The Paytm app (One97 Communications) survives. QR, Soundbox, recharges and bill payments continue, and UPI is routed via partner banks (Axis, HDFC, SBI, YES). — [The Week](https://www.theweek.in/news/biz-tech/2026/04/25/paytm-payments-bank-license-cancelled-impact.html)

**KakaoTalk (Korea), messaging-led, UX backlash case**
- September 2025: the "biggest update in 15 years" turned the Friends tab into an Instagram-style feed. It triggered backlash over findability of the friends list and privacy. One UX firm's analysis found 42% dissatisfaction across more than 1,000 app store reviews. — [Korea Herald](https://www.koreaherald.com/article/10584551); [Wikipedia KakaoTalk](https://en.wikipedia.org/wiki/KakaoTalk)
- Kakao announced on Sep 29, 2025 that it would restore the friends list. On Oct 15 a VP said a technical rollback was "impossible". A staged fix from mid-December 2025 let users pick list or feed, and the feed was removed by Dec 2025. — [Korea Times, Sep 29 2025](https://www.koreatimes.co.kr/business/tech-science/20250929/kakao-to-restore-kakaotalks-friends-list-after-widespread-complaints); [Korea Times, Dec 16 2025](https://www.koreatimes.co.kr/business/companies/20251216/kakaotalk-removes-instagram-style-feed-after-user-backlash); [Seoul Economic Daily](https://en.sedaily.com/technology/2025/12/18/kakao-completes-kakaotalk-friend-tab-update-after-user); [JoongAng Daily](https://www.koreajoongangdaily.com/business/heres-how-the-new-kakaotalk-will-look-following-failed-update/12088063)

**Rappi (LatAm), delivery-led, then quick commerce (Turbo), RappiPay and travel**
- Colombian entity 2025 net profit: about COP 210.2B (about US$64.8M), +116% vs 2024 (COP 97.3B), from Superintendency of Companies filings. This was its second consecutive profitable year. — [Colombia One (Jul 2026)](https://colombiaone.com/2026/07/19/rappi-earned-us64-million-second-consecutive-profit-year/)
- CEO Simón Borrero: as of Dec 2025, Rappi had 4 consecutive quarters of positive EBITDA, reinvests 100% of profits and needs no new private funding. — [Rio Times](https://www.riotimesonline.com/rappi-profitable-colombia-super-app/); [Sacra](https://sacra.com/c/rappi/)
- Amazon invested in Rappi (reported Sep 2026). — [Colombia One (Sep 2026)](https://colombiaone.com/2026/09/19/colombia-amazon-invests-rappi-latin-america/)
- Turbo: a target to raise its share of grocery orders from 15% to 35% (an internal target, not a result). Colombian labor reform requiring social security contributions is a cost risk. — [Sacra](https://sacra.com/c/rappi/)

### Inferences
- The expansion sequence in successful cases is anchor (daily frequency), then a wallet/payments layer, then adjacent high-frequency services (food, bills, top-ups), then financial services (credit, insurance, investing), then third-party mini-apps and ads. Ads and fintech, not the anchor, drive late-stage profitability (Grab, Rappi).
- Two ecosystem models exist. The open third-party model (WeChat, Alipay mini-programs) needs a huge MAU base and weak OS gatekeepers. The in-house/curated model (Grab, Gojek, Rappi, Kakao) offers higher quality control but slower breadth.
- Kakao shows that once an app is critical infrastructure, users punish changes to the core anchor flow, even in a market used to super apps. UX lesson: never sacrifice findability of the core job (contacts and chats) for engagement surfaces.
- Paytm shows a single-licence dependency is an existential risk. In Europe and Switzerland (FINMA, EBA/ECB, PSD3), the regulated layer must be robust before breadth.

### Gaps
- No primary 2025 metrics were retrieved for Alipay/Ant, Gojek/GoTo, LINE (LY Corp) or Kakao financials.
- [UNVERIFIED-BACKGROUND] context, not confirmed here:
  - Gojek shut down GoLife (home services such as GoMassage and GoClean) in 2020 during COVID.
  - Grab and Gojek both retreated from some verticals and markets: Grab exited GrabFood in Vietnam? (uncertain), and Gojek exited Vietnam in 2024.
  - WeChat Pay took off via the 2014 Chinese New Year "red envelope" campaign.
  - Mini Programs launched in January 2017.
  - Alipay began in 2004 as Taobao's escrow.

## 3. Western attempts, why the West lacks a WeChat, and 2024-2026 developments

### Takeaway
Western "super app" efforts have converged on financial super apps (Revolut is the clear success: 68.3M customers and $2.3B pre-tax profit in 2025) or quietly reframed. PayPal moved from "super app" to "commerce platform". X Money only launched invite-only in mid-2026. The likeliest Western "super app layer" in 2025-2026 may be AI assistants (ChatGPT Apps SDK plus Instant Checkout) rather than a single consumer app. EU rollout of those features lagged.

### Cited Findings
**Revolut (bank-led, fintech super app)**
- 2025: revenue $6.0B (£4.5B, +46%); pre-tax profit $2.3B (£1.7B, +57%), its fifth consecutive profitable year. Net profit is reported variously as £1.3B (+65%) or $1.7B, depending on currency and source.
- 2025 customers: 68.3M retail (+30% YoY, 16M new) and about 767k business (+33%). Transaction volume was about £1.3T (+65%), deposits $67.5B (+66%).
- Target: 100M customers by mid-2027.
- Sources: [Revolut press release](https://www.revolut.com/en-AT/news/revolut_reports_record_profit_of_2_3bn_for_2025_as_revenue_surges_to_6bn/); [Annual Report 2025 PDF](https://assets.revolut.com/pdf/annualreport2025.pdf); [FinTech Futures](https://www.fintechfutures.com/challenger-banks/revolut-profit-jumps-57-to-1-7bn-for-2025); [Payment Expert](https://paymentexpert.com/2026/03/24/revolut-2025-annual-report/)

**PayPal**
- Under Dan Schulman, PayPal aimed to become a WeChat/Alipay-style "super app" (savings, crypto, shopping deals, bill pay, messaging). The goal of 750M users by 2025 was missed, at about 430M. Sources say the super app wallet plans "failed to materialize". — [The Investor's Podcast Network](https://www.theinvestorspodcast.com/intrinsic-value/paypal-pypl/)
- Alex Chriss (CEO from Sep 27, 2023) reframed PayPal: "going from… just a payments company to really being a commerce platform". — [Payments Dive](https://www.paymentsdive.com/news/paypal-ceo-alex-chriss-pushing-beyond-payments/733450/); [Payments Dive (appointment)](https://www.paymentsdive.com/news/paypal-intuit-exec-next-ceo-alex-chriss-dan-schulman/689511/)
- One source says Chriss was "jettisoning" non-core assets, including Venmo. This is dubious: Venmo remained a core PayPal growth focus. Do not use without verification. — [The Investor's Podcast Network](https://www.theinvestorspodcast.com/intrinsic-value/paypal-pypl/)

**X / "everything app"**
- Visa partnered with X in January 2025 for X Money (P2P and Visa Direct). — [Fortune, Jan 31 2025](https://www.fortune.com/2025/01/31/visa-is-partnering-with-x-to-launch-x-money-elon-musks-rival-to-venmo)
- Timeline: internal testing, then external beta invites from March 2026. As of Jul 28, 2026 (AP), X Money is invite-only, for paying X members only. It offers an X-branded Visa debit card, 6% yield on deposits of $1,000 or more, 3% cashback and real-time P2P, and runs on Cross River Bank. It holds money transmitter licences in 40 states plus DC.
- Sources: [AP via Washington Times](https://www.washingtontimes.com/news/2026/jul/28/elon-musk-launches-invite-x-money-visa-debit-card-6-yield-real-time/); [TechXplore](https://techxplore.com/news/2026-07-elon-musk-money-visa-debit.html); [Fortune](https://fortune.com/article/elon-musk-x-money-visa-partnership-impact)
- There is no confirmed international launch date. One explainer says none for Canada, LatAm or APAC (single source). — [explainx.ai](https://explainx.ai/blog/x-money-launch-digital-wallet-payments-2026)

**Klarna (BNPL-led, now neobank/"AI super app")**
- June 2025 (CNBC): CEO Sebastian Siemiatkowski outlined a plan to turn Klarna into a "super app" with AI, as a "digital financial assistant" for everyday banking. The pitch included deposit accounts, the Klarna Card (debit, US), cashback, budgeting and investment features. He said stocks and crypto were "not that far off".
- The CEO admitted an earlier super app attempt was "confusing for the customer". This is a direct post-mortem quote.
- "The U.S. is now our largest market by number of users."
- Users: about 100M (CNBC) vs 111M across 26 countries (other source), so the figures conflict.
- Sources: [CNBC, Jun 18 2025](https://www.cnbc.com/2025/06/18/klarna-ceo-outlines-plan-to-become-super-app-with-ai.html); [eMarketer](https://www.emarketer.com/content/klarna-leans-digital-banking-us); [The Digital Banker](https://thedigitalbanker.com/as-klarna-eyes-banking-bnpl-becomes-onramp-to-nextgen-neobank/)
- IPO status was not confirmed in the search results. [UNVERIFIED-BACKGROUND]: Klarna listed on NYSE in Sep 2025.

**OS gatekeeper shift: Apple Mini Apps Partner Program (Nov 13, 2025)**
- Apple offers a reduced 15% commission (vs the standard 30%) to host apps that carry third-party mini apps and games. This is an explicit opening of iOS to super app architectures.
- Requirements: the host app must support the Declared Age Range API and the Advanced Commerce API, and provide a manifest/metadata for every hosted mini app (Guideline 4.7.4). Mini apps must not be controlled by the host developer. Purchases shared across multiple mini apps do not qualify. Developers join via a request form, and Guideline 4.7 applies regardless.
- Bloomberg reported that an Apple–Tencent agreement on 15% for WeChat mini-apps preceded or underpinned the program. Apple says it is open to all qualifying developers.
- Sources: [MacRumors, Nov 13 2025](https://www.macrumors.com/2025/11/13/apple-announces-mini-apps-partner-program/); [MacStories](https://www.macstories.net/news/apple-introduces-a-mini-app-partner-program-featuring-a-reduced-commission/); [PYMNTS](https://www.pymnts.com/apple/2025/apple-launches-mini-apps-partner-program-halves-app-store-fees-to-15/); [RevenueCat](https://www.revenuecat.com/blog/engineering/apple-mini-apps-partner-program); [ppc.land](https://ppc.land/apple-mini-apps-program-breaks-commission-model-with-embedded-distribution/)
- Implication: the "gatekeeper" barrier to Western super apps has partly lowered since late 2025. A European host app (e.g., Twint, Satispay, Revolut) can now host third-party mini apps at 15% on iOS, subject to Apple's rules. No DMA-specific source was found.

**AI assistant as "super app layer" (2025-2026)**
- OpenAI launched "apps in ChatGPT" and the Apps SDK, which is open source and built on MCP. Apps were initially available to logged-in users outside the EU only, with EU availability promised "soon". — [Search Engine Journal](https://www.searchenginejournal.com/openai-launches-apps-in-chatgpt-releases-apps-sdk/557682/); [TestingCatalog](https://www.testingcatalog.com/openai-launches-chatgpt-apps-and-sdk-preview-outside-eu/); [OpenAI Help](https://help.openai.com/en/articles/12515353-build-with-the-apps-sdk)
- Instant Checkout and the Agentic Commerce Protocol: in-chat purchases, first single-item, for approved partners. The protocol is open. — [OpenAI, "Buy it in ChatGPT"](https://openai.com/index/buy-it-in-chatgpt/); [Agentic Checkout spec](https://developers.openai.com/commerce/specs/checkout); [AppsFlyer analysis](https://www.appsflyer.com/blog/measurement-analytics/chatgpt-os-app-commerce/)

### Inferences
- Why no Western WeChat (synthesis):
  1. OS gatekeepers (Apple App Store, Google Play) control distribution and in-app payments. In China, fragmented Android stores weakened this (cited above).
  2. Mature card rails, desktop/web habits and established best-of-breed apps leave no infrastructure gap to fill (cf. Chan's "leapfrog" point).
  3. Regulation: licensing per activity (EMI, bank, credit, insurance), GDPR limits on cross-service data use, and DMA scrutiny of gatekeepers' self-preferencing.
  4. Trust and user habits: users prefer specialist apps and are wary of one company holding chat, money and identity.
- AI assistants with tool/app protocols (MCP, Apps SDK) are the most credible "super app" vector in the West. They aggregate services by intent, not by icon grid, and sidestep the home-screen problem. In the EU, the lag in feature rollout is itself a design and strategy factor.
- Western successes are narrower "financial super apps" (Revolut) built around a money account, with product breadth (FX, stocks, crypto, travel, insurance) rather than third-party mini-apps.

### Gaps
- Not retrieved and therefore unconfirmed:
  - DMA effects on super apps and mini-apps (e.g., Apple's EU alternative distribution and mini-app rules in 2024-2025, and the "mini apps partner program").
  - Uber's "one app" consolidation (rides plus Eats, Uber One membership) and its 2025 metrics.
  - Klarna's 2024-2025 "AI shopping super app/neobank" push, its post-IPO (Sep 2025) status and its feature cuts.
  - Snapchat's mini-apps and Snap Minis.
  - Meta's WhatsApp Pay (Brazil, India) and Business messaging, and Meta AI.
  - Amazon's in-app services in India (Amazon Pay).
- [UNVERIFIED-BACKGROUND]: PayPal named Enrique Lores CEO in early 2026, replacing Chriss. Verify this.

## 4. Europe, Italy and Switzerland: Satispay and other EU attempts

### Takeaway
Europe's most credible "super app" candidates are payment-led, domestically dominant wallets (Twint in Switzerland, Bizum, Vipps MobilePay, Satispay). They expand into vouchers, bills, deals and benefits, and lately into banking, investing, e-ID and stablecoins. European sovereignty initiatives (Wero/EPI and the 2026 European Network for Payments interoperability entity) are creating shared rails that could become the base layer.

### Cited Findings
**Satispay (Italy), from P2P to merchants to services to bank**
- Users and merchants: about 6.5M users and 450k merchants (2026 press), up from about 5M and 380k in late 2024. Deposits were €670M at end of May. Annualized revenue is over €116M (+80% YoY), against about €45M net revenue projected for end-2024. It is gross-operating-profitable across core lines.
- The company is reportedly raising €120M to push into stock trading. It has about 500k users on investment products, with €140M AUM.
- BNPL launched in November 2025.
- Sources (press reports of a reported raise, not an audited report): [The Next Web](https://thenextweb.com/news/satispay-120-million-funding-round-italian-fintech-unicorn); [Tech Funding News](https://techfundingnews.com/revolt-challenger-italian-fintech-unicorn-satispay-to-raise-e120m-and-unlock-a-e1-27t-investing-opportunity/); [Dealroom](https://app.dealroom.co/news/note/satispay-plans-120m-raise-to-push-into-stock-trading)
- Meal vouchers (Buoni Pasto, from Sept 2023):
  - Fully digital, held in a separate wallet in the employee's app. One payment can combine a voucher with the personal balance.
  - The merchant pays no commission on vouchers up to €10 and €0.20 above that, with next-business-day settlement. This is a "fair-fee" positioning against traditional voucher issuers.
  - Validity is stated as 2 years in one Satispay page and 1 year in another, which conflicts.
  - Expanded into large retail (Lidl).
  - Sources: [Il Sole 24 Ore](https://www.ilsole24ore.com/art/satispay-entra-mercato-buoni-pasto-e-da-taglio-commissioni-AFP7u8z); [Satispay newsroom](https://www.satispay.com/it-it/newsroom/buoni-pasto-servizio-digitale/); [Satispay–Lidl](https://www.satispay.com/it-it/newsroom/satispay-lidl-buoni-pasto-grande-distribuzione/)
- Services: PagoPA notices (taxes, fines), car/motorbike road tax (bollo) and brand gift cards. — [Qualebroker review 2026](https://www.qualebroker.com/recensioni/conti-e-carte/satispay)
- July 2026: Satispay announced a plan to become a full bank, with Mastercard debit cards (physical/virtual), stock trading and expanded investments. — [Wikipedia IT (secondary)](https://it.wikipedia.org/wiki/Satispay)
- Local density example: Rome has more than 285k users. — [Satispay newsroom](https://www.satispay.com/it-it/newsroom/satispay-roma-provincia-utenti-attivita-convenzionate/)
- Background narrative: [EconomyUp history](https://www.economyup.it/fintech/satispay-storia-e-protagonisti-di-una-fintech-italiana-diventata-unicorno/); [Cosa Sposta, after the €500M raise](https://cosasposta.substack.com/p/come-sta-satispay-dopo-aver-raccolto)
- Unreliable figures (4.5M or 7.2M users, €3.2B volume, "€120M FY2025 revenue") come from SWOT and business-model blogs without primary sources. Do not use them. — e.g., [Canvas Business Model](https://canvasbusinessmodel.com/products/satispay-swot-analysis)

**Twint (Switzerland), bank-owned, payments-led, "platform for daily digital life"**
- 2025: 901M transactions (+17% vs 773M in 2024) and more than 6M users. Growth slowed noticeably vs prior years. Mix: 77% commercial, 23% P2P. Accepted at about 81% of physical stores and 86% of online shops. — [Twint media release](https://www.twint.ch/en/company/media/more-than-6-million-people-use-twint/); [finews](https://www.finews.com/news/english-news/71219-twint-2025-transaktionen-kunden-2)
- About 64% of Swiss mobile payment transactions, per the Swiss Payment Monitor (ZHAW/HSG), via a secondary source. — [payabl](https://payabl.com/news/what-is-twint-why-does-it-matter-for-merchants-entering-switzerland)
- The CEO calls Twint "more than just a payment app… a platform for daily digital life". Features include Super Deals, digital vouchers, subscription comparison, insurance, Spin & Win, parking/tickets and "Twint Prio Tickets".
- Oct 2025: Twint announced it will open the platform to new digital applications, including trusted stablecoins and the Swiss E-ID.
- Sources: [finews](https://www.finews.com/news/english-news/71219-twint-2025-transaktionen-kunden-2); [Twint media](https://www.twint.ch/en/company/media/); [Twint: payment infrastructure independence](https://www.twint.ch/en/company/media/twint-makes-switzerlands-payment-infrastructure-more-independent/)
- "6M" is described as active users in some sources and as users in others. — [Financial IT](https://financialit.net/news/payments/more-6-million-people-switzerland-use-twint)

**Bizum (Spain), Vipps MobilePay (Nordics), EuroPA, ENP**
- Bizum: more than 30.6M users, 111k merchants and 14k donation codes at end-2025, and more than 32M by Sep 2026. — [Invest in Spain](https://www.investinspain.org/en/news/2026/bizum); [The Paypers](https://thepaypers.com/payments/news/bancomat-bizum-epiwero-sibsmb-way-and-vipps-mobilepay-launch-a-european-interoperability-entity)
- Vipps MobilePay: about 12.5M users and close to 400k businesses (MobilePay in Denmark and Finland, Vipps in Norway and Sweden). This figure may be dated. — [The Paypers, EuroPA](https://thepaypers.com/payments/news/europa-joins-forces-with-epi)
- EuroPA cross-border interoperability (Bizum, Bancomat/Italy, MB WAY/Portugal) went live in March 2025 for P2P across Spain, Italy, Portugal and Andorra. — [Bancomat](https://bancomat.it/en/press-releases/europa-and-epi-towards-a-pan-european-hub-for-instant-payments)
- Feb 2026: Bancomat, Bizum, EPI/Wero, SIBS/MB WAY and Vipps MobilePay signed an MoU and created the European Network for Payments (ENP), headquartered in Madrid. It covers about 130M users in 13 countries. — [EPI press](https://european-payments-initiative-lux.prezly.com/bancomat-bizum-epiwero-sibs-mb-way-and-vipps-mobilepay-announce-the-creation-of-a-european-interoperability-entity-european-network-for-payments-to-connect-their-respective-solution-a-concrete-step-towards-european-sovereignty); [EPI Company](https://epicompany.eu/media-insights/bancomat-bizum-epi-sibs-and-vipps-mobilepay-sign-mou-to-accelerate-the-rollout-of-sovereign-pan-european-payment-solutions/); [Riksbank staff memo 2026](https://www.riksbank.se/globalassets/media/rapporter/staff-memo/engelska/2026/connecting-mobile-payment-solutions-in-europe.pdf)

**Lydia/Sumeria (France), deliberate unbundling of a would-be super app**
- In May 2024, Lydia (about 8M users across France, Spain and Germany) split into two apps:
  - Lydia keeps P2P payments and pooled collections.
  - Sumeria is a mobile-first bank account (IBAN and card) and absorbs advanced features (stock trading, savings, loans).
- About 2M users were on the banking features, which the company says are profitable. Sumeria planned €100M of investment and 400 hires over 3 years, with a target of 5M users by 2027.
- Sources: [TechCrunch, May 15 2024](https://techcrunch.com/2024/05/15/lydia-the-french-social-payment-app-with-8-million-users-launches-mobile-banking-app-sumeria/); [FinTech Futures](https://www.fintechfutures.com/digital-banking/french-fintech-lydia-launches-digital-banking-app-sumeria); [PaymentsJournal](https://www.paymentsjournal.com/french-p2p-app-lydia-spins-off-digital-banking/); [Sumeria About](https://sumeria.eu/en/about/); [ma-banque-en-ligne 2026 review](https://ma-banque-en-ligne.fr/neobanque/lydia/)
- Inference: this is the clearest European counter-case to the super app thesis. A social P2P brand and a banking brand served different mental models, so the company split them.

**Wero (EPI)**
- Users: about 58M (Sep 2026, Convera). Earlier figures were 52-53M.
- E-commerce live in Germany since Nov 2025, Belgium from Mar 2026. France is reported as April 2026 (Wikipedia) or pilot until autumn 2026 (Payplug), so the sources conflict.
- BPCE: 13M customers to be enabled online by summer 2026. N26 launched Wero in Germany and France (Aug 2026). In-store payments are planned for 2027.
- Sources: [Convera](https://convera.com/blog/cross-border-payments/european-payments-initiative-2026/); [Wikipedia Wero](https://en.wikipedia.org/wiki/Wero_(payment)); [Payplug](https://www.payplug.com/blog/payment-wero/); [Worldpay/Global Payments](https://www.worldpay.com/en/press-releases/worldpay-now-gp-joins-epi-to-enable-wero-payments-for-merchants); [BNP Paribas](https://group.bnpparibas/en/news/bnp-paribas-partners-with-wero-for-e-commerce-payment-solutions); [The Paypers](https://thepaypers.com/payments/news/wero-ecommerce-is-now-live-in-germany)

### Inferences
- The European "super app" pattern is a trusted domestic wallet plus daily-life services, not chat. Twint and Satispay follow the same playbook: P2P/merchant payments, then vouchers, deals and bills, then benefits (meal vouchers), then insurance and investing, then a bank licence or identity (E-ID).
- Satispay's UX and business differentiator is fee fairness and simplicity for merchants (no fee under €10). Its consumer anchor is the "Satispay at the bar" micro-payment habit.
- Twint's slowing growth (+17% in 2025) suggests payments saturation in Switzerland. Its next growth must come from services and platform opening (stablecoins, E-ID), which is exactly the super app question.
- For Swiss clients: Twint is the de-facto platform owner. Third parties are more likely to win as "mini-services inside Twint" or via partner integrations than by building a competing super app. Twint's opening to third-party apps (Oct 2025) is the relevant opportunity to monitor.
- ENP/Wero interoperability could allow national wallets to stay brands while sharing rails. That is a federated super app model, unlike Asia's single-owner model.

### Gaps
- Not retrieved: Bunq (users and 2025 profits; US licence attempts), N26 (2025 regulatory issues and leadership change), Lydia/Sumeria (the 2024 split into Lydia P2P plus Sumeria neobank, a key "unbundling" case), Glovo (Spain labor law changes in 2025, Delivery Hero) and Bolt (rides, scooters, food, Bolt Market).
- [UNVERIFIED-BACKGROUND] context:
  - Lydia split its banking product into Sumeria in 2024, an explicit move away from a single super app.
  - Glovo moved to an employee riders model in Spain in 2025.
  - Bolt shut down Bolt Market (dark-store grocery) in several markets.
- No Satispay audited 2025 annual figures were found. Satispay reports in Italian press (Il Sole 24 Ore, Corriere) around its funding rounds, so check those for confirmed figures.

## 5. Explicit failures, retreats and post-mortems

### Takeaway
Failures cluster into four types:
1. Regulatory collapse of the financial core (Paytm).
2. Unmet "super app" ambition reframed as narrower strategy (PayPal).
3. UX bloat or anchor disruption triggering user backlash and rollback (KakaoTalk 2025).
4. Unit-economics-driven vertical shutdowns (quick commerce, home services). This type is mostly unverified in this session.

### Cited Findings
- Paytm: the RBI actions of 2022-2024 led to licence cancellation (Apr 2026) and winding-up (Jul 2026). The super app vision was "shelved", e-commerce was dropped and the business refocused on payments/merchant core. — [Inc42](https://inc42.com/features/how-paytms-super-app-machine-came-to-a-grinding-halt/); [The Week](https://www.theweek.in/news/biz-tech/2026/04/25/paytm-payments-bank-license-cancelled-impact.html); [JJ Fintax compliance lessons](https://www.jjfintax.com/blogs/others/the-paytm-fallout)
- PayPal: the 750M-user super app target was missed (about 430M), followed by a pivot to a "commerce platform" under a new CEO. — [TIP](https://www.theinvestorspodcast.com/intrinsic-value/paypal-pypl/); [Payments Dive](https://www.paymentsdive.com/news/paypal-ceo-alex-chriss-pushing-beyond-payments/733450/)
- KakaoTalk: a feed-style Friends tab (Sep 2025) caused backlash, a restoration announcement (Sep 29), "rollback impossible" (Oct 15), then a staged choice/restore and feed removal (Dec 2025). — [Korea Herald](https://www.koreaherald.com/article/10584551); [Korea Times](https://www.koreatimes.co.kr/business/companies/20251216/kakaotalk-removes-instagram-style-feed-after-user-backlash)
- X Money: years after the "everything app" announcement (2022-2023), payments only reached invite-only US status in 2026, restricted to paying members. — [AP/Washington Times](https://www.washingtontimes.com/news/2026/jul/28/elon-musk-launches-invite-x-money-visa-debit-card-6-yield-real-time/)
- Gojek GoLife:
  - Dec 2019: Gojek closed most GoLife services as "stagnant". GoLife head Wesly Simatupang noted that GoClean and GoMassage produced most orders.
  - GoLaundry and GoDaily were to close by Dec 31, 2019, and GoFix and GoGlam by mid-January 2020.
  - June 2020: GoLife shut down entirely, with 430 layoffs (about 9% of staff, mostly GoLife and GoFood Festival). Gojek cited COVID-era wariness of physical interaction.
  - Sources: [Jakarta Post, Dec 17 2019](https://www.thejakartapost.com/news/2019/12/17/gojek-to-shut-down-several-golife-services.html); [Marketing-Interactive](https://www.marketing-interactive.com/gojek-ceases-several-golife-services-due-to-stagnant-business-performance/); [Coconuts, Jun 2020](https://coconuts.co/jakarta/news/gojek-to-shut-golife-lay-off-430-employees-as-pandemic-puts-brakes-on-super-app/); [DealStreetAsia](https://www.dealstreetasia.com/stories/indonesia-gojek-lifestyle-services-167242)
- Klarna: the CEO said the previous super app attempt was "confusing for the customer" (Jun 2025). — [CNBC](https://www.cnbc.com/2025/06/18/klarna-ceo-outlines-plan-to-become-super-app-with-ai.html)
- Lydia: split into Lydia (P2P) and Sumeria (bank) in May 2024, an unbundling. — [TechCrunch](https://techcrunch.com/2024/05/15/lydia-the-french-social-payment-app-with-8-million-users-launches-mobile-banking-app-sumeria/)
- The pandemic reshaped the super app race (Uber–Postmates, Asian players cutting verticals). — [CNBC, Jul 7 2020](https://www.cnbc.com/2020/07/07/from-uber-to-asia-pandemic-is-remaking-worlds-super-app-race.html)
- Rappi: dark kitchens and Turbo dark stores raise fixed costs and complexity, and labor reform adds cost risk. — [Sacra](https://sacra.com/c/rappi/)

### Inferences
- UX lessons for the consultancy:
  1. Protect the anchor job's speed and findability; Kakao is the textbook case.
  2. Add services where frequency or trust already exists (Twint deals and vouchers, Satispay meal vouchers) instead of distant verticals.
  3. Give users control (opt-in modules, customizable home), in line with Gartner's "use and remove as needed".
  4. Treat the regulated core as the foundation, not a feature (Paytm).
  5. In the West, aim for "super-service ecosystems" (federated rails, AI-agent integrations) rather than a WeChat clone.

### Gaps
- No post-mortems were retrieved for:
  - Gojek GoLife (2020).
  - Grab's vertical and market exits.
  - Facebook/Meta Pay and Novi/Diem shutdown (2022).
  - Twitter/X Payments delays.
  - Klarna's 2024-2025 app bloat criticism.
  - Snapchat's discontinued features (Snap Originals, Pixy).
  - Revolut's product closures (e.g., some crypto and stock features in certain markets).
- All of these are [UNVERIFIED-BACKGROUND] candidates the report writer should not state as fact without sources.
