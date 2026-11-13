# Non-game, non-camera App Store niches: saturation vs. opportunity map (state as of November 2026)

*Research limitations (read first).* The shared web-search budget for this session ran out after about 30 searches, and page fetches worked only for `developer.apple.com` (fetches to `www.revenuecat.com`, `a16z.com`, `techcrunch.com` and `dev.to` failed at DNS level and would need to be allowed in the session's network settings). Consequences: (1) platform and policy findings are strong, because they come from Apple primary pages; (2) revenue figures come from search-result summaries of third-party estimators and were not checked on the original pages; (3) most of the "less obvious niches" (trades, hobbies, exam prep, travel, caregiver, Vision Pro, etc.) could not be searched at all, and are listed under Gaps with clearly labelled unverified background knowledge. All revenue numbers are third-party estimates unless marked self-reported. Estimator buckets such as AppGoblin's "$10K+" are floors, not point estimates.

## 1. Common, heavily exploited areas: how saturated in 2026, who dominates, is there room?

### Takeaway
Every mainstream consumer category checked is dominated by one or two scaled players plus a long tail of clones, and 2026 added a supply shock: new iOS app releases were up about 80% year over year in Q1 2026. Room remains mainly in sub-segments (a vertical, a life stage, a language, a denomination) and in categories where policy keeps casual cloners out; generic AI chat, calorie scanning, cleaners, meditation and AI companions are poor entry points for a solo developer.

### Cited Findings

**Market backdrop**
- Worldwide app releases in Q1 2026 were up 60% YoY across both stores and up 80% on iOS alone; April 2026 was trending +104%. Games were the largest share of new releases and Health & Fitness was in the top five categories (Appfigures data) — [TechCrunch, 18 Apr 2026](https://techcrunch.com/2026/04/18/the-app-store-is-booming-again-and-ai-may-be-why/)
- Consumers spent more in non-game apps than in games for the first time in 2025 (Sensor Tower) — [Sensor Tower press release, 21 Jan 2026](https://tools.prnewswire.com/en-us/live/20813/release/20260121EN66586)
- RevenueCat's 2026 report (primarily 2025 data from apps on its platform): 27.1% of subscription apps are classified as AI-powered; the share of apps using trials of four days or less rose from 42.1% to 46.5%; Travel and Business have the highest median annual-plan renewal (40%), Productivity and Photo & Video the lowest (23%); Business apps take a median 113 days to reach $1K MRR versus 32 days for games — [RevenueCat State of Subscription Apps 2026](https://www.revenuecat.com/state-of-subscription-apps-2026/); [RevenueCat benchmarks post](https://www.revenuecat.com/blog/growth/subscription-app-trends-benchmarks-2026)
- Secondary coverage of the same report says AI apps earn 41% more per user but churn 30% faster, and that subscription growth is concentrating at the top — [PPC Land](https://ppc.land/ai-apps-earn-41-more-per-user-but-churn-30-faster-revenuecat-finds/); [Subscription Insider](https://www.subscriptioninsider.com/article-type/news/revenuecat-data-shows-subscription-app-growth-concentrating-at-the-top)
- One indie author called Q3 2026 "the hardest indie iOS quarter in 5 years" and advised narrower niches and one-time purchases by default (single-author opinion) — [dev.to forecast](https://dev.to/snake_sun/indie-ios-q3-2026-forecast-where-the-indies-will-win-and-where-they-will-not-1ige)
- Apple's own review guideline 4.3(b) names the categories it considers saturated: "dating, flashlight, sound effects, wallpaper, simple timers, and fortune telling", and says new submissions are refused unless meaningfully different (guidelines last updated 16 Oct 2026) — [App Review Guidelines](https://developer.apple.com/app-store/review/guidelines/)

**AI chatbot wrappers / "AI assistant" apps — saturated, winner-take-most**
- ChatGPT became the fastest mobile app to reach 1 billion monthly active users (May 2026); AI-app in-app revenue was projected to pass $4B in H1 2026, +36% versus H2 2025 (Sensor Tower estimates, store IAP only) — [Sensor Tower State of AI 2026 press release](https://sensortower.com/press/sensor-tower-state-of-ai-2026-report-global-time-spent-on-generative-ai-apps-projected-to-more-than-double-year-over-year)
- April 2026: ChatGPT, Gemini and Claude were the top three App Store apps by downloads (15.5M, 15.4M, 10.9M; Appfigures estimates) — [Appfigures, April 2026](https://appfigures.com/resources/insights/most-downloaded-highest-earning-apps-april-2026)
- Grok had its best month in January 2026 at about $17M net revenue (Appfigures estimate) — [Appfigures This Week in Apps, 13 Feb 2026](https://appfigures.com/resources/this-week-in-apps/20260213)
- The a16z ranking's 7th edition (5 Oct 2026) added a spending ranking; 29 of the top 50 products by spend appear on neither the web nor the mobile traffic list — [a16z Top 100, 7th edition](https://a16z.com/100-gen-ai-apps-7/). The March 2026 mobile list was led by ChatGPT, CapCut, Gemini, Canva and AI Gallery — [The Decoder](https://the-decoder.com/new-top-100-ai-list-shows-a-market-where-chatgpt-leads-but-no-one-is-loyal/)
- A low-reliability secondary site says 200,000+ apps now reference AI in their store descriptions and three apps capture 90% of attention — [appsops.store](https://appsops.store/news/sensor-tower-state-of-ai-2026-mobile-revenue-app-builders)

**AI calorie / food scanners — saturated; the breakout was bought by the incumbent**
- MyFitnessPal announced its acquisition of Cal AI on 2 Mar 2026 (deal closed Dec 2025; terms undisclosed). Cal AI revenue was reported at "over $30M" annually by MyFitnessPal and at "more than $40M" by other outlets; it had about 15M downloads in two years; it stays a standalone app — [eWeek](https://www.eweek.com/fr/news/myfitnesspal-acquires-cal-ai-teen-founders/); [Athletech News](https://athletechnews.com/myfitnesspal-cal-ai-acquisition); [Pulse 2.0](https://pulse2.com/myfitnesspal-acquires-cal-ai-to-expand-ai-powered-nutrition-tracking-portfolio)
- A price above $100M was rumoured but is unconfirmed — [stork.ai](https://www.stork.ai/blog/this-teens-ai-app-sold-for-100-million)
- Cal AI is now connected to MyFitnessPal's database, reported at 20 million foods — [RaftLabs teardown](https://www.raftlabs.com/blog/cal-ai-product-teardown)

**Meditation / sleep content — declining demand, entrenched brands**
- Calm revenue was about $210M in 2025, down 24% YoY; Headspace about $140M and down 300,000 paid subscribers to about 2M (Business of Apps figures relayed by a secondary site) — [Voxbooster](https://voxbooster.com/blog/mental-health-app-statistics-2026)
- Store-billed revenue for Headspace was only about $39M in 2025 (AppMagic via Udonis; excludes web and B2B, so not comparable with the figure above) — [Udonis](https://www.blog.udonis.co/statistics/headspace)
- Calm downloads fell 61% and Headspace 74% between 2018 and 2024 — [Statista](https://statista.com/statistics/1243022/headspace-app-downloads-worldwide/); Appfigures titled its May 2024 analysis "Demand for Mental Health Apps is at an All-Time Low" — [Appfigures](https://appfigures.com/resources/insights/20240510/3-demand-for-mental-health-apps-is-at-an-all-time-low)
- Insight Timer grew while Calm and Headspace monthly revenue roughly halved from the January 2021 peak to March 2026 (Chinese trade press) — [Baijing](https://www.baijing.cn/article/55298)

**Language learning — one giant, AI tutors growing**
- Duolingo: FY2025 revenue about $1.04B (+39%); 2026 guidance is 15–18% revenue growth; Q1 2026 revenue $292M (+26.5%) — [MarketBeat Q4 call](https://www.marketbeat.com/instant-alerts/duolingo-q4-earnings-call-highlights-2026-02-26/); [Barchart Q1 deep dive](https://www.barchart.com/story/news/1701016/duol-q1-deep-dive-product-investments-and-ai-content-drive-user-growth-amid-margin-pressure)
- Speak is listed at about $150M ARR as of January 2026 by an aggregator citing unnamed trackers (unverified); it raised $78M at a $1B valuation in December 2024 — [EnterpriseDNA directory](https://enterprisedna.co/resources/ai-map/company/duolingo)
- Apple's 2025 App of the Year for China was CapWords, which turns photos of objects into vocabulary stickers — [App Store Awards 2025](https://developer.apple.com/app-store/app-store-awards-2025/)

**Period tracking / women's health — dominated by Flo**
- Flo reported about $275M in annual subscription revenue by 2025 and about 77M monthly active users in 2026; Sifted reported about $200M for 2024; valuation above $1B in July 2024 — [Bridgehead profile](https://bridgeheadcommunications.com/healthtech-index/flo-health); [Sifted](https://sifted.eu/articles/flo-health-unicorn-raise-news)

**Budgeting — crowded at the top, high prices hold**
- Monarch reached an estimated $100M ARR in September 2026, up from $60M at end-2025 (Sacra estimate) — [Sacra](https://sacra.com/c/monarch-money/)
- YNAB is estimated at about $49M ARR and Rocket Money above $100M ARR (secondary industry analysis) — [Luminix report](https://www.useluminix.com/reports/industry-analysis/competitive-landscape-personal-finance-and-budgeting-apps-2026)
- Copilot's weekly store revenue peaked near $114K in the last week of 2025 (Sensor Tower) — [Sensor Tower Q4 2025](https://sensortower.com/blog/2025-q4-ios-top-5-personal-finance-budgeting-and-planning-revenue-us-63e363f0e1714cfff1979caa)
- Prices in September 2026: Monarch $14.99/month or $99.99/year; YNAB about $109/year; Copilot $13/month or $95/year — [Toolradar](https://toolradar.com/guides/best-ynab-alternatives)

**Cleaners, VPN, scanners — lucrative, paid-acquisition-driven, policy-gated**
- Appfigures counted 161 cleaner apps grossing at least $1,000 in a month, 42 above $100K and 7 above $1M; leaders include Cleanup, Cleaner Guru, AI Cleaner, Cleaner Kit and Swipewipe (insight dated June 2025; the search summary described the data month as February 2026, so the date is uncertain) — [Appfigures](https://analytics.appfigures.com/resources/insights/20250606?f=1)
- May 2026 top-grossing Utilities included Cleanup, Blink Home Monitor, Cleaner Guru, NordVPN and Norton 360 — [AppPricingLab](https://www.apppricinglab.com/reports/UTILITIES)
- Adobe Scan is estimated at about $2.3M per month (undated, low-confidence estimator; the exact Screensdesign page was not identified in the search summary, so the link is to its app directory) — [Screensdesign directory](https://screensdesign.com/discover/apps/)
- VPN apps must use NEVPNManager, may only be offered by developers enrolled as an organization, and may not sell or disclose data (guideline 5.4) — [App Review Guidelines](https://developer.apple.com/app-store/review/guidelines/)

**Identifier apps (plant, coin, rock, insect) — two publishers own it**
- Monthly consumer spending on identifier apps hit $27M; plant identifiers were 78% of category revenue and coin identifiers alone grossed $3.5M in a month (Appfigures, May 2025) — [Appfigures](https://appfigures.com/resources/insights/20250509/1-monthly-consumer-spending-in-this-niche-just-hit-27m)
- PictureThis (Glority) is estimated at about $6M monthly App Store revenue and about 400K monthly downloads (AppSprint estimate, 11 Oct 2026) — [AppSprint](https://appsprint.app/picturethis-plant-identifier-monthly-recurring-revenue)
- CoinSnap (Next Vision) is estimated at 17.2M installs, 2.1M MAU and more than $200K monthly revenue (AppGoblin, March 2026); another estimator says $400K–$550K per month — [AppGoblin](https://appgoblin.info/apps/1634551626); [Screensdesign](https://screensdesign.com/apps/coinsnap-coin-identifier/)

**Screen-time blockers — one clear leader, many "earn your screen time" clones**
- Opal is estimated at $500K–$600K monthly revenue and 200K installs per month (Screensdesign estimate, 2025–2026) — [Screensdesign](https://screensdesign.com/discover/apps/opal-screen-time-control/)
- Brainrot estimates range from "$10K+" per month with about 82.5K MAU (AppGoblin) to $55K–$65K per month (Screensdesign); its founder reported $26K in the first month (self-reported) — [AppGoblin](https://appgoblin.info/apps/6744338972); [Screensdesign](https://screensdesign.com/apps/brainrot-screen-time-control/); [We Are Founders](https://www.wearefounders.uk/he-built-an-app-to-fix-his-phone-addiction-it-made-26k-in-30-days/)
- New clones keep appearing in 2026, e.g. FitRot and DoerPal — [AppGoblin FitRot](https://appgoblin.info/apps/6761732041); [AppGoblin DoerPal](https://appgoblin.info/apps/6760669409)
- Focus Friend won a 2025 App Store Cultural Impact award for fighting digital distraction — [App Store Awards 2025](https://developer.apple.com/app-store/app-store-awards-2025/)
- The Family Controls entitlement requires a permission request to Apple before App Store submission — [Family Controls documentation](https://developer.apple.com/tutorials/data/documentation/familycontrols.json)
- Apple added first-party "Time Allowances" in iOS 27 for Entertainment, Games and Social Media categories — [Apple developer news, 8 Jun 2026](https://developer.apple.com/news/?id=0d2gpmml)

**Faith apps — Hallow far ahead, AI "Bible chat" rising, strongly seasonal**
- Hallow earned about $40M net in 2025; post-Lent peaks were $10M (March 2024) and $9.7M (April 2025), a flat trend; February 2026 tracked at about $1.3M (Appfigures estimates) — [Appfigures](https://appfigures.com/resources/insights/hallow-lent-surge-prayer-app-revenue)
- Bible Chat had earned $6.3M net cumulatively by April 2025, with a best month of $750K in March 2025; Appfigures called it the highest-earning Bible app at that time — [Appfigures, April 2025](https://appfigures.com/resources/insights/20250418?f=5)
- Glorify is estimated at about 1.6M MAU and "$100K+" monthly revenue, 73% from ads (AppGoblin) — [AppGoblin](https://appgoblin.info/apps/1490587079)

**AI companions — real money, highest policy risk**
- Romantic/NSFW companion apps took $162.8M in H1 2026 across both stores and "PG" companions $164.8M (Appfigures via Decrypt); 337 revenue-generating companion apps were tracked in 2025 — [Decrypt](https://decrypt.co/373395/how-much-your-boyfriend-spending-ai-girlfriends); [TechCrunch, Aug 2025](https://techcrunch.com/2025/08/12/ai-companion-apps-on-track-to-pull-in-120m-in-2025)
- Apple's new "Dating and Relationships" descriptor covers "a virtual companion that engages a user in sexual or romantic content" and forces a minimum 18+ rating; declarations open 16 Nov 2026 and are mandatory by 12 Jan 2027 — [Apple developer news, 2 Nov 2026](https://developer.apple.com/news/?id=yxkh08us)
- Guideline 5.1.2(i) requires explicit permission before sharing personal data with third-party AI (added 13 Nov 2025); the 16 Oct 2026 update strengthened rules against AI-generated nonconsensual intimate imagery — [Apple developer news](https://developer.apple.com/news/)
- California SB 243 took effect 1 Jan 2026 (AI disclosure, crisis referrals, safeguards for minors), per secondary coverage — [Cybernews](https://cybernews.com/ai-news/apple-app-store-ai-companions/)

**AI therapy-style and mood apps — regulation is tightening state by state**
- Illinois (August 2025) bars offering AI mental-health therapy without a licensed professional, with fines up to $10,000; Nevada has a similar ban with fines up to $15,000 — [eWeek](https://www.eweek.com/news/illinois-bans-ai-mental-health-therapy/); [Bloomberg Law](https://news.bloomberglaw.com/health-law-and-business/ai-therapy-chatbots-spur-states-to-act-over-patient-safety-fears)
- Five more states enacted restrictions in 2026 (including Maine, Tennessee, Vermont and Rhode Island); Utah regulates through disclosure and data protection instead — [Becker's](https://www.beckersbehavioralhealth.com/?p=11726); [Quartz guide, Jul 2026](https://qz.com/state-laws-restricting-ai-mental-health-care-guide-072826)
- The FDA has authorized about 1,200 AI-enabled devices, none for generative mental health — [AP via WCAX, Sep 2025](https://www.wcax.com/2025/09/29/regulators-struggle-keep-up-with-fast-moving-complicated-landscape-ai-therapy-apps/)

**AI homework / study helpers — owned by ByteDance, Google and Quizlet**
- Gauth (ByteDance) is estimated at about 2.3M MAU and "$100K+" per month (AppGoblin) or about $600K per month (Screensdesign); its Plus tier is $11.99/month. Photomath (Google) and Quizlet (about $2.3M per month on one estimator) are the other leaders — [AppGoblin Gauth](https://appgoblin.info/apps/1542571008); [Screensdesign Gauth](https://screensdesign.com/apps/gauth-ai-study-companion/); [Screensdesign Photomath](https://screensdesign.com/apps/photomath/)
- Apple's 2025 Mac App of the Year was Essayist, an academic-writing tool for sources and formatting — [App Store Awards 2025](https://developer.apple.com/app-store/app-store-awards-2025/)

**Book summaries / micro-learning — well funded incumbents**
- Headway projects passing $1B in annual revenue and an IPO by 2029 (company forward-looking claim) — [Headway/Web Summit document](https://websummit.com/wp-media/2025/11/Headway_Inc_Emerges_as_One_of_the_Worlds_Fastest-Growing_EdTech_Companies.pdf.pdf)
- Blinkist claims 26M users; annual plans work out to about $8.33/month for Blinkist and $7.50/month for Headway (Blinkist's own comparison) — [Blinkist](https://www.blinkist.com/learn/blinkist-vs-headway-which-book-summary-app-is-better-in-2026)
- One estimator lists Headway at $550K, Imprint at $250K and Nibble at $100K per month (method unstated) — [Screensdesign](https://screensdesign.com/apps/blinkist-book-summaries-daily/?vs=56303)

**Short-drama apps — a $3B category, not an indie game**
- Short-drama apps generated $2.98B in in-app revenue in 2025; in Q1 2026 the category had 850M+ downloads (+140% YoY) and about $750M revenue, with DramaBox and ReelShort near $140M each (Sensor Tower) — [Sensor Tower](https://sensortower.com/blog/state-of-short-drama-apps-2026-report); [Marketing Dive](https://www.marketingdive.com/news/microdrama-apps-stand-on-mobile-heres-what-the-numbers-say/812610)

**AI note takers / transcription — large, venture-scale leaders**
- Plaud reached an estimated $250M annualized revenue in September 2025 (+83% YoY) and said its software business passed $100M ARR after shipping 2M devices (June 2026); plans cost $99.99 and $239.99 per year — [Sacra](https://sacra.com/research/plaud)
- Otter announced $100M ARR in late 2025 — [Gladia market overview](https://www.gladia.io/blog/ai-notetaker-market-funding-and-acquisitions)
- Granola raised at a $250M valuation in May 2025 and reportedly at $1.5B in May 2026 (the latter from a secondary site) — [TechCrunch, May 2025](https://techcrunch.com/2025/05/14/ai-note-taking-app-granola-raises-43m-at-250m-valuation-launches-collaborative-features); [EntrepreneurLoop](https://entrepreneurloop.com/granola-ai-meeting-notes-unicorn-series-c-2026/)

**Looksmaxxing / face-rating — faded hit, weak resale values**
- Umax was reported at 7M+ downloads and about $500K per month in July 2024 (Fortune, relayed secondhand); Umax-branded listings now show under $10K per month on AppGoblin (possibly different listings) — [Plisio](https://plisio.net/ai/looksmax-ai); [AppGoblin](https://appgoblin.info/apps/6478508605)
- A looksmaxxing app listed for sale shows only a few hundred dollars of verified monthly revenue — [TrustMRR](https://trustmrr.com/startup/facemax-ai-face-rating-plam?metric=mrr)

**Fitness — Apple keeps rewarding incumbents and craft**
- Strava was Apple Watch App of the Year 2025; Ladder was an iPhone App of the Year finalist; GO Club was a Watch finalist — [App Store Awards 2025](https://developer.apple.com/app-store/app-store-awards-2025/)

### Inferences
- Saturation ranking, most to least crowded for a new solo entrant (judgment based on the evidence above): generic AI chat > phone cleaners/VPN > AI calorie scanners > meditation > short drama > AI companions > identifier apps (plants/coins) > book summaries > language learning > budgeting > screen-time blockers > faith apps.
- The Cal AI outcome shows two things at once: a small team can still build a $30M+ app in a crowded category, and the exit was the incumbent buying it. The post-acquisition category now combines the fastest follower with the largest food database, which raises the bar for a new scanner.
- Categories where demand is falling at the top (meditation) leave room only for narrow products; Insight Timer's growth suggests the opportunity moved to community and free tiers rather than new paid content libraries.
- Policy is now the main moat-or-trap variable: companions (18+ floor), AI therapy (state bans), VPN (organization accounts), screen time (entitlement), health (medical-device declaration). A solo developer benefits where the gate is paperwork (entitlement requests) and loses where the gate is legal exposure (therapy, companions).
- Faith and budgeting show that users pay $95–$110 per year for products that touch identity or money; both support annual plans better than novelty AI apps do.

### Gaps
- No data was gathered this session on: habit trackers and to-do apps (a search summary mentioned HabitKit at about $13.6K MRR in mid-2024 without an identifiable source), walking apps, QR/translator/voice-recorder utilities, widgets/wallpapers/themes/keyboards, bird/rock/insect identifiers specifically, "rizz" dating helpers, astrology/tarot/numerology, Muslim Pro, quit-addiction apps (one estimator listed Quittr at $50K–$85K with no stated period), skin/hair analysis, parenting/baby trackers (Huckleberry), pet apps, journaling, recipe/meal planning, sleep/snoring, white noise. The search budget ran out before these could be queried.
- Per-category RevenueCat benchmarks (trial conversion, revenue per install, price medians) exist in the full report and its category pages (e.g. [Productivity](https://www.revenuecat.com/state-of-subscription-apps-2026-productivity), [Utilities](https://www.revenuecat.com/state-of-subscription-apps-2026-utilities/), [Education](https://www.revenuecat.com/state-of-subscription-apps-2026-education)) but could not be fetched.
- No verified 2026 revenue for the leading AI-wrapper publishers (e.g. Codeway's "Chat & Ask AI") was found.
- Estimator disagreement is large (Gauth $100K+ vs $600K per month; Brainrot $10K+ vs $65K), so individual app figures should be treated as order-of-magnitude only.

## 2. Less obvious or emerging niches with evidence of demand and weaker competition

### Takeaway
The best-evidenced emerging areas are GLP-1 companions (huge demand, but already flooded with 568 new apps in 2026), collectibles scanning and pricing, neurodivergent-friendly planning, women's mid-life health, and in-person transcription for non-desk workers. Most other niches on the brief's list could not be researched this session and are flagged below.

### Cited Findings

**GLP-1 / weight-loss-medication companions**
- AppMagic tracked at least 568 new apps with "GLP-1" in the title since January 2026; these apps show download and revenue spikes on weekends (injection days) — [Benzinga](https://www.benzinga.com/node/62011321)
- Shotsy is estimated at about 1.8M installs and 153.7K MAU, with a 4.83 rating from 35.3K ratings; revenue is shown only as "$10K+" per month (AppGoblin floor bucket); its monthly plan is $19.99 on one storefront — [AppGoblin](https://appgoblin.info/apps/6499510249); [App Store listing](https://apps.apple.com/mk/app/id6499510249)
- MeAgain is estimated at about 905K installs and 75.1K MAU; Pep at 41.1K installs and declining (AppGoblin) — [AppGoblin MeAgain](https://appgoblin.info/apps/6744178534); [AppGoblin Pep](https://appgoblin.info/apps/6504788281)
- HealthKit has let apps read medications and logged doses from the Health app since June 2025 — [HealthKit updates](https://developer.apple.com/documentation/updates/healthkit)
- Guideline 1.4.2 restricts drug dosage calculators to manufacturers, hospitals, universities, insurers, pharmacies or FDA-approved entities — [App Review Guidelines](https://developer.apple.com/app-store/review/guidelines/)

**Collectibles and TCG scanners / price trackers**
- Collectr is estimated at about 2.7M installs and 200.7K MAU, revenue "$10K+" per month (AppGoblin) — [AppGoblin](https://appgoblin.info/apps/1603892248)
- A newer entrant, "TCG Card Scanner & Value – Foloy", is estimated at $250K per month and 150K installs per month (single estimator, unverified) — [Screensdesign](https://screensdesign.com/discover/apps/tcg-card-scanner-value-foloy/)
- More than a dozen near-identical Pokémon scanner apps launched in 2025–2026; most are estimated under $10K per month — [AppGoblin example](https://appgoblin.info/apps/6743204900)
- Pokémon TCG Pocket was Apple's iPhone Game of the Year 2025, a demand driver for card apps — [App Store Awards 2025](https://developer.apple.com/app-store/app-store-awards-2025/)
- Coin identification alone grossed $3.5M in one month (Appfigures, May 2025) — [Appfigures](https://appfigures.com/resources/insights/20250509/1-monthly-consumer-spending-in-this-niche-just-hit-27m)

**Neurodivergent / ADHD-friendly planning**
- Tiimo, a visual planner, was iPhone App of the Year 2025; Structured was an iPad finalist — [App Store Awards 2025](https://developer.apple.com/app-store/app-store-awards-2025/)
- Structured was again a 2026 Apple Design Award finalist for a planner that "pre-fills tasks for neurodivergent users" — [Apple Design Awards 2026](https://developer.apple.com/design/awards/)

**Women's mid-life health (menopause)**
- HealthKit added a menopause and perimenopause API in June 2026 (menopausal state, bleeding after menopause) — [HealthKit updates](https://developer.apple.com/documentation/updates/healthkit); [watchOS 27 what's new](https://developer.apple.com/watchos/whats-new/)

**In-person transcription, captions and accessibility**
- Sacra describes Plaud as a "$250M/year Granola for plumbers", i.e. recording for in-person, non-desk work — [Sacra](https://sacra.com/research/250m-year-granola-for-plumbers); Pocket, another recorder, is at about $27M annualized — [Sacra](https://sacra.com/research/pocket-at-27m-annualized-revenue/)
- Hearing Buddy, by a solo developer, was a 2026 Apple Design Award finalist for on-device real-time captions and summaries — [Apple Design Awards 2026](https://developer.apple.com/design/awards/)
- Be My Eyes won a 2025 Cultural Impact award — [App Store Awards 2025](https://developer.apple.com/app-store/app-store-awards-2025/)

**Hobby and outdoor data utilities (Apple-recognized, small teams)**
- 2026 Apple Design Award winners include Tide Guide (tides and weather), Moonlitt (moon phases) and Guitar Wiz (solo developer; guitar toolkit); finalists include The Outsiders (training readiness) and Harvee (Apple Watch recovery guidance, on-device) — [Apple Design Awards 2026](https://developer.apple.com/design/awards/)
- 2025 recognition included StoryGraph (reading tracker), Yuka (food scanner), Whoscall (caller ID) and Under My Roof (home management, Mac finalist) — [App Store Awards 2025](https://developer.apple.com/app-store/app-store-awards-2025/)

**Small-business and B2B on mobile**
- Organizations can buy app subscriptions in volume through Apple Business and Apple School Manager since 22 Oct 2026; multiseat purchasing is on by default; Group Purchases arrive in winter — [Apple developer news, 16 Sep 2026](https://developer.apple.com/news/?id=likeohx4)
- Business apps have the joint-highest median annual renewal (40%) but are slowest to $1K MRR (113 days) — [RevenueCat 2026](https://www.revenuecat.com/state-of-subscription-apps-2026/)

**New device surfaces**
- iPhone Duo, a foldable iPhone, went on sale 23 Oct 2026; optimized apps get a product-page badge and Duo screenshots become mandatory in April 2027 — [Apple developer news, 5 Oct 2026](https://developer.apple.com/news/?id=kkphp5qo)
- Apple is preparing developers for "MacBook Pro with Touch" — [Apple developer news, 28 Oct 2026](https://developer.apple.com/news/?id=i9boeiqc)
- CarPlay now accepts voice-based conversational apps and video apps (parked only), and shows widgets and Live Activities — [CarPlay developer page](https://developer.apple.com/carplay/)
- The developer agreement now covers iOS widgets and CarPlay apps on "Apple HomeView" — [Apple developer news, 13 Oct 2026](https://developer.apple.com/news/?id=17mwd36z)
- Vision Pro: two solo developers were recognized (Explore POV, Vision Pro App of the Year 2025; Caradise, 2026 finalist) — [App Store Awards 2025](https://developer.apple.com/app-store/app-store-awards-2025/); [Apple Design Awards 2026](https://developer.apple.com/design/awards/)

### Inferences
- GLP-1 has the strongest raw demand but is no longer under-served: 568 new titles in ten months means keyword competition is brutal, and the leaders' estimated revenue is modest relative to their user counts. Remaining angles are speculative: the maintenance/off-medication phase, protein and muscle preservation, and deeper use of the HealthKit medications API.
- Collectibles is a repeatable template (scan, identify, price, portfolio). The Pokémon keyword set is flooded, but the same template for less-served collectibles is likely less contested. That last point is an inference; no data on non-Pokémon verticals was gathered.
- Apple's awards two years running point to a consistent editorial preference: accessible, calm, single-purpose apps from small teams (Tiimo, Structured, Guitar Wiz, Hearing Buddy, Tide Guide, Moonlitt). Featuring is a realistic distribution channel for a craft-focused solo developer in these niches.
- The menopause API is the clearest "new HealthKit data type, few native apps yet" opening of 2026; Flo's scale shows willingness to pay in women's health, though Flo itself is the likely competitor.
- Volume Purchasing plus the high renewal of Business apps makes small vertical B2B tools more viable on the App Store than before, but the slow ramp implies distribution through direct outreach rather than search.

### Gaps
- Not researched (search budget exhausted): apps for contractors/estimators, real-estate agents, nurses, truckers and pilots; fishing, golf, pickleball/padel, running clubs, birding, sneakers, wine, coffee, knitting and gardening; ADHD revenue figures, migraine, diabetes/CGM, longevity/biomarkers and blood-test analysis; elderly/caregiver; home maintenance; car/EV; eSIM, flight trackers and itinerary apps; creator tools; invoicing/receipts/CRM; HOA/community; legal-document helpers; immigration/visa prep; driving-test and certification exam prep; kids education; AAC apps; iPad pro tools; Mac menu-bar apps.
- Unverified background knowledge (researcher's memory, not checked this session; treat as leads only): Flighty and Tripsy in flight/itinerary tracking; Airalo, Holafly and Saily in eSIM; ForeFlight in aviation; Fishbrain and onX in outdoors; 18Birdies, Hole19 and TheGrint in golf; DUPR in pickleball; Runna (acquired by Strava in 2025) in running plans; Merlin (free, Cornell) in birding; Vivino in wine; Invoice Simple, Joist and Jobber in trades invoicing; Pocket Prep and UWorld in exam prep; Proloquo2Go and TD Snap in AAC (high one-time prices); Tessie for Tesla owners; Migraine Buddy; Inflow for ADHD; Balance and Stella for menopause; Function Health and Superpower for blood biomarkers; Levels and Signos for CGM.
- No revenue or user data was found for any Vision Pro, CarPlay-first, Watch-first or Mac menu-bar app.
- Vendor blogs name pet diet planners, home management and profession-specific AI utilities as under-served, without data — [dev.to app-ideas post](https://dev.to/tobby_scraper/top-app-ideas-for-2026-and-how-to-validate-them-before-writing-a-single-line-of-code-3i0l)

## 3. Platform-driven openings (iOS 18, iOS 26, iOS 27) and who benefited from earlier shifts

### Takeaway
iOS 27 changes app economics more than app surfaces: small developers get Apple's server-side models free, any LLM can plug into the Foundation Models framework, and Siri AI can call app actions (App Store submissions open in spring 2027). The newest untapped surfaces are AlarmKit, the menopause and medications HealthKit APIs, CarPlay conversational apps, the foldable iPhone Duo and touch on Mac.

### Cited Findings

**AI on the platform**
- iOS 27's Foundation Models framework works with Apple's on-device model, cloud models such as Claude and Gemini, or any provider conforming to the Language Model protocol; it adds image input, on-device OCR and barcode tools, and Dynamic Profiles — [iOS 27 what's new](https://developer.apple.com/ios/whats-new/)
- App Store Small Business Program members with fewer than 2 million first-time downloads can use Apple Foundation Models on Private Cloud Compute at no cloud API cost — [Small Business Program](https://developer.apple.com/app-store/small-business-program/)
- The on-device model has a 4,096-token context window; the Private Cloud Compute model offers more reasoning and a larger context — [Foundation Models updates](https://developer.apple.com/documentation/updates/foundationmodels)
- Core AI is a new framework for running your own models on-device with "zero server dependencies and zero token costs" — [iOS 27 what's new](https://developer.apple.com/ios/whats-new/)
- Generative-AI apps can request an entitlement to sell expiring consumables (credits/tokens, minimum 12-month expiry) through In-App Purchase — [App Store what's new](https://developer.apple.com/app-store/whats-new/)
- Siri AI Developer Preview (iOS 27.3 beta, 3 Nov 2026): apps expose content and actions through App Intents, "skills" combine several actions, and Siri can surface any entity in the Spotlight semantic index. It is unavailable in the EU on iOS, iPadOS and watchOS and for users under 13; App Store submission opens "in the spring" — [Apple developer news, 3 Nov 2026](https://developer.apple.com/news/?id=gdk2umrf)
- The View Annotations API lets people act on on-screen app content conversationally — [iOS 27 what's new](https://developer.apple.com/ios/whats-new/)
- `ImageCreator` (Image Playground API) stops working in iOS 27 — [Apple developer news, 11 Jun 2026](https://developer.apple.com/news/)

**Surfaces: widgets, controls, Live Activities, alarms**
- iOS 18 (June 2024): Controls for Control Center, the Lock Screen and the Action button; Live Activities in the watchOS Smart Stack; broadcast push for Live Activities — [WidgetKit updates](https://developer.apple.com/documentation/updates/widgetkit); [ActivityKit updates](https://developer.apple.com/documentation/updates/activitykit)
- iOS 26 (June 2025): Live Activities appear automatically in the Mac menu bar and CarPlay and can be scheduled for a future time; widgets come to CarPlay and Vision Pro; controls come to watchOS and macOS; widgets can be reloaded by push — [ActivityKit updates](https://developer.apple.com/documentation/updates/activitykit); [WidgetKit updates](https://developer.apple.com/documentation/updates/widgetkit)
- AlarmKit (iOS 26) lets third-party apps schedule "prominent alarms and countdowns" with snooze and a system-managed Live Activity — [AlarmKit documentation](https://developer.apple.com/tutorials/data/documentation/alarmkit.json)
- iOS 27: widgets can be customized through App Intents and dynamic styling; a new NowPlaying framework connects playback to the Lock Screen, Dynamic Island and CarPlay — [iOS 27 what's new](https://developer.apple.com/ios/whats-new/)
- Other iOS 26 additions: Liquid Glass, Declared Age Range, PermissionKit, Wi-Fi Aware, EnergyKit, PaperKit, SpeechAnalyzer, Visual Intelligence integration, Accessibility Nutrition Labels — [WWDC25 updates](https://developer.apple.com/tutorials/data/documentation/updates/wwdc2025.json)

**Health**
- June 2024: State of Mind, PHQ-9 and GAD-7 assessment data. June 2025: workout sessions on iPhone and the medications/dose API. June 2026: workout zones and the menopause API — [HealthKit updates](https://developer.apple.com/documentation/updates/healthkit)
- watchOS 27 brings the Foundation Models framework and Vision framework to the watch — [watchOS what's new](https://developer.apple.com/watchos/whats-new/)
- Since 26 Mar 2026, new apps in Health & Fitness or Medical (or with frequent medical references) must declare regulated-medical-device status to distribute in the EEA, UK and US; existing apps have until early 2027 or lose the ability to update — [Apple developer news, 26 Mar 2026](https://developer.apple.com/news/?id=nyqbfz1y)

**Calls, translation, default apps, payments**
- CallKit can hand a call to system translation (`CXSetTranslatingCallAction`, June 2025) — [CallKit updates](https://developer.apple.com/documentation/updates/callkit)
- User-selectable defaults now include browser, mail, calling, messaging, dialer and carrier messaging (June 2025), translation (2025), contactless/NFC (iOS 18.1), navigation (EU 2025, Japan December 2025) and app marketplaces (EU 2024, Japan December 2025) — [Default apps updates](https://developer.apple.com/tutorials/data/documentation/updates/defaultapps.json)
- Alternative distribution expanded to Japan (iOS 26.2, December 2025) and Brazil (iOS 26.5, June 2026); the EU moved to a 5% Core Technology Commission on 1 Oct 2026 — [Apple developer news](https://developer.apple.com/news/)
- FinanceKit (June 2024) gives apps on-device access to Wallet financial data with a transaction picker — [FinanceKit updates](https://developer.apple.com/tutorials/data/documentation/updates/financekit.json)

**Age assurance and child safety**
- Texas SB 2420 enforcement resumed 4 Jun 2026; Apple points developers to the Declared Age Range API, a Significant Change API and consent-revocation notifications; Utah, Louisiana, Brazil, Australia and Singapore requirements were addressed in February 2026 — [Apple developer news](https://developer.apple.com/news/)
- Age ratings gained 13+, 16+ and 18+ tiers (July 2025); a Social Media descriptor with a minimum 13+ rating became mandatory in September 2026 — [Apple developer news, 9 Jul 2026](https://developer.apple.com/news/?id=tlur8uvi)

**Monetization and distribution mechanics**
- New in 2026: monthly subscriptions with a 12-month commitment (not in the US or Singapore), subscription Bundles and Suites, retention messages in the cancellation flow (4 Nov 2026), and custom product pages raised to 70 with their own keywords (October 2025) — [App Store what's new](https://developer.apple.com/app-store/whats-new/); [Apple developer news](https://developer.apple.com/news/)
- Uploads have required the iOS 26 SDK since 28 Apr 2026 and will require the iOS 27 SDK from April 2027 — [Apple developer news](https://developer.apple.com/news/)
- The Small Business Program commission is 15% for developers under $1M in annual proceeds — [Small Business Program](https://developer.apple.com/app-store/small-business-program/)

**Early movers in previous shifts**
- iOS 14 widgets: the top 20 home-screen customization apps passed 13.7M installs in the first week; Widgetsmith, Color Widgets and Photo Widget took about 92% of them, and Widgetsmith (a solo developer) earned about $370K in the launch period (Sensor Tower) — [Sensor Tower](https://sensortower.com/blog/ios-14-home-screen-app-downloads)
- Widgetsmith reached $3M cumulative net revenue by December 2021 (Appfigures) and about 131M downloads by its fifth anniversary (developer's own post) — [Appfigures](https://appfigures.com/resources/insights/20211224/amp?f=5); [David Smith](https://www.david-smith.org/blog/2025/09/18/widgetsmith-at-five/)
- iOS 16 Lock Screen widgets produced a much smaller wave: downloads were "a fraction" of the iOS 14 surge — [Appfigures, Sep 2022](https://analytics.appfigures.com/resources/insights/20220923?f=3)
- Liquid Glass adopters Tide Guide and Moonlitt won 2026 Apple Design Awards — [Apple Design Awards 2026](https://developer.apple.com/design/awards/)
- Apple named Day One as an early Foundation Models adopter and Etsy for visual intelligence at WWDC25 — [Apple Newsroom, June 2025](https://www.apple.com/newsroom/2025/06/apple-supercharges-its-tools-and-technologies-for-developers/)

### Inferences
- Free Private Cloud Compute plus on-device models removes the main variable cost of AI features for a developer under 2M downloads. That undercuts wrapper apps that must charge weekly subscriptions to cover API bills, and it makes one-time-purchase or low-priced AI utilities viable. This is the single biggest structural change for solo developers in 2026.
- The Widgetsmith pattern (a new system surface, a visible user desire, day-one availability) recurs only when the surface is user-visible and personal. The iOS 16 result shows the second wave of the same idea pays far less. The closest 2026–2027 analogues are Siri AI actions (spring 2027), iPhone Duo layouts and AlarmKit.
- AlarmKit opens product types that were previously unreliable for third parties (medication alarms, prayer-time alarms, wake-up challenges, cooking and parking timers). Note that "simple timers" are on Apple's saturated list, so an AlarmKit app needs a specific job.
- Siri AI is absent in the EU and for under-13s, so Siri-first products have a smaller addressable market in Europe and no role in kids' apps for now.
- The medical-device declaration and age-rating questionnaires add fixed compliance work for every health or social app; they slightly favour developers who already document their claims carefully.

### Gaps
- HealthKit data types for sleep apnea, hypertension and hearing were not listed on Apple's HealthKit updates page, so their availability to third-party apps is unconfirmed here.
- Call screening as a third-party API, Live Translation APIs beyond the CallKit action, Tap to Pay changes after 2024, Wallet pass changes in 2025–2026 and CarPlay Ultra opportunities for non-automaker apps were not documented on the pages fetched.
- Apple does not explain the new "Live Assistance API" or "App Replacement Entitlement" in its public news post.
- No sourced data on which apps benefited from Live Activities, Dynamic Island, StandBy, interactive widgets or Controls. Unverified background knowledge: Flighty and sports-score apps for Live Activities, Pixel Pals for Dynamic Island, Lock Launcher-type apps for Lock Screen widgets.
- iPhone Duo sales volume and screen specifications are unknown, so the size of the foldable opportunity is speculative.

## 4. Demand-side evidence (search terms, trends, community requests)

### Takeaway
Hard keyword data could not be collected this session. The usable demand signals are supply counts by niche, Apple's editorial choices, and aggregate market data, all of which show demand shifting to AI utilities, health-adjacent tracking and short-form entertainment.

### Cited Findings
- 568 new "GLP-1" titled apps since January 2026 is the clearest single-keyword rush on record this year — [Benzinga](https://www.benzinga.com/node/62011321)
- Generative AI was reported as the fastest-growing spending category, +108% (data provider not identified in the article; 11 Aug 2026) — [Apfelpatient](https://www.apfelpatient.de/en/news/app-store-ai-apps-drive-sales-games-lose)
- Short-drama installs grew 238% YoY in Q1 2026 (Adjust with Sensor Tower data); FreeReels reached 21M downloads in February 2026 — [Adjust](https://www.adjust.com/blog/short-drama-apps-report/); [Appfigures, Feb 2026](https://appfigures.com/resources/insights/most-downloaded-highest-earning-apps-february-2026)
- Social listening: Brandwatch logged more than 806,000 mentions of "looksmaxxing" between September 2025 and early 2026 (relayed secondhand) — [Plisio](https://plisio.net/ai/looksmax-ai)
- Faith-app demand is seasonal and predictable around Lent — [Appfigures](https://appfigures.com/resources/insights/hallow-lent-surge-prayer-app-revenue)
- Homework-helper demand rides the back-to-school season — [Appfigures, Sep 2024](https://appfigures.com/resources/insights/20240920/2-the-ai-study-helper-thats-riding-the-back-to-school-wave)
- One guide argues that the real competitive set is the 50–200 apps in a specific keyword niche, not the whole store — [FoxData](https://foxdata.com/en/blogs/solo-developer-crowded-store-how-to-find-your-edge-in-a-market-of-189-million-apps/)
- Custom product pages can now carry their own keywords (up to 70 pages), which lets one app target many long-tail terms — [Apple developer news, 29 Oct 2025](https://developer.apple.com/news/)
- Appfigures publishes a Mobile Market Index tracking download and revenue growth by category and country — [Appfigures help](https://help.appfigures.com/en/article/the-mobile-market-index-1t2rv7/)

### Inferences
- A fast rise in the number of apps on a keyword (GLP-1, TCG scanner, "earn screen time") is a lagging indicator: by the time hundreds of titles exist, search ads and ranking difficulty have already risen. The useful signal is the next adjacent keyword, not the one in the news.
- Seasonal categories (faith at Lent, study tools in August–September, fitness in January) let a small developer concentrate marketing spend into a few weeks.

### Gaps
- No keyword popularity or difficulty scores (Astro, AppTweak, Appfigures), no Google Trends series, no TikTok trend data and no Reddit "is there an app for" threads were collected. These need a follow-up pass once search is available.
- Appfigures' category-level growth indices for late 2026 were not retrieved.

## 5. For each promising niche: price, willingness to pay, retention, build complexity, regulation, main risk

### Takeaway
Observed prices cluster at $10–$20 per month or $95–$110 per year for products tied to health, money or work, and willingness to pay is highest where the app replaces a professional or a paid service. The binding constraints are mostly regulatory (health declarations, state AI-therapy laws, age ratings) and data licensing, not engineering.

### Cited Findings
- Observed price points: Shotsy $19.99/month (one storefront) — [App Store](https://apps.apple.com/mk/app/id6499510249); Gauth Plus $11.99/month — [AppGoblin](https://appgoblin.info/apps/1542571008); Plaud $99.99 or $239.99/year — [Sacra](https://sacra.com/research/plaud); Monarch $99.99/year, YNAB about $109/year, Copilot $95/year — [Toolradar](https://toolradar.com/guides/best-ynab-alternatives); Blinkist about $100/year equivalent — [Blinkist](https://www.blinkist.com/learn/blinkist-vs-headway-which-book-summary-app-is-better-in-2026)
- Retention benchmarks: median annual renewal is 40% for Travel and Business and 23% for Productivity and Photo & Video; nearly half of apps now use trials of four days or less — [RevenueCat 2026](https://www.revenuecat.com/state-of-subscription-apps-2026/)
- Subscriptions must last at least seven days and provide ongoing value (3.1.2) — [App Review Guidelines](https://developer.apple.com/app-store/review/guidelines/)
- Health claims: apps claiming to measure blood pressure, glucose, temperature or blood oxygen with device sensors alone are rejected; accuracy claims need disclosed methodology (1.4.1); health data may not be used for advertising (5.1.3) — [App Review Guidelines](https://developer.apple.com/app-store/review/guidelines/)
- Medical-device status declaration is mandatory for health apps in the EEA, UK and US — [Apple developer news, 26 Mar 2026](https://developer.apple.com/news/?id=nyqbfz1y)
- Kids Category apps may not include third-party analytics or advertising and must gate purchases behind a parental gate (1.3) — [App Review Guidelines](https://developer.apple.com/app-store/review/guidelines/)
- Financial apps: trading apps must come from the licensed institution; loan apps are capped at 36% APR — [App Review Guidelines](https://developer.apple.com/app-store/review/guidelines/)
- Screen-time apps need Apple's approval for the Family Controls entitlement — [Family Controls documentation](https://developer.apple.com/tutorials/data/documentation/familycontrols.json)
- CarPlay apps need a category entitlement requested from Apple — [CarPlay developer page](https://developer.apple.com/carplay/)
- Excessive refund requests or negative reviews can count against a developer under the Code of Conduct (5.6.4) — [App Review Guidelines](https://developer.apple.com/app-store/review/guidelines/)

### Inferences
The table below is the researcher's assessment. Price ranges are extrapolated from the observed points above; retention, build effort and risk columns are judgment, not measured data.

| Niche | Likely paywall and price | Retention profile | Build effort (solo) | Data, licensing, regulation | Main risk |
|---|---|---|---|---|---|
| AlarmKit specialty alarms (medication, prayer, wake-up) | Freemium; $15–$30/year or $10–$20 one-time | Daily habit | Low | Medication reminders trigger the medical-device declaration question | Apple improves its own Clock/Health reminders |
| Menopause / perimenopause companion | Annual subscription $40–$80 | Multi-year life stage | Low to medium | Health claims rules; device-status declaration; sensitive data | Flo and Clue add the same API |
| Neurodivergent planner / routines | Annual $30–$60; lifetime option | Daily habit, but Productivity renews worst (23%) | Low to medium | None specific | Tiimo and Structured own Apple's attention |
| Hobby data utilities (tides, moon, sport-specific) | $10–$30/year or one-time | Seasonal, loyal | Low to medium | Data-source licences (tide, weather, course maps) | Small market per hobby |
| Vertical on-device transcription | $10–$20/month or $100/year | Weekly to daily for workers | Medium | Recording-consent laws vary; health contexts add privacy duties | Otter, Plaud, Granola and Apple's own transcription |
| Collectibles scanner and portfolio | $5–$10/month or $30–$60/year | Bursty around releases | Medium | Price-data and image licences; trademark use | Dependence on third-party price feeds; clone floods |
| Foldable-first (iPhone Duo) utilities | One-time $5–$20 or low annual | Depends on utility | Low to medium | None specific | Unknown device volume |
| Faith apps for under-served traditions or languages | Annual $40–$70; donations | Daily habit, seasonal peaks | Low to medium (content heavy) | Content rights for translations and audio | Doctrinal sensitivity; Hallow and Bible Chat expansion |
| Trades micro-SaaS (estimate, invoice) | $20–$40/month per seat | High once embedded in work | Medium to high | Payments, tax rules, document accuracy | Slow, sales-led growth; Jobber-class incumbents |
| GLP-1 companion (new angle only) | $5–$20/month | 6–18 months per user | Low | Dosage-calculator ban (1.4.2); device declaration; no medical advice | 568+ competitors; drug-market shifts |

### Gaps
- No sourced prices for Cal AI, Opal, Flo, Tiimo, Structured, Hallow or Bible Chat were collected.
- No category-specific trial-conversion or revenue-per-install benchmarks were retrieved; the RevenueCat category pages hold them.
- COPPA/GDPR-K specifics for kids apps, recording-consent law by state, and FDA general-wellness guidance were not researched.

## 6. A defensible way to rank niches, and a top-10 shortlist

### Takeaway
A multiplicative score across six factors (demand, monetization, competitive headroom, build feasibility, distribution fit, risk safety) penalizes any fatal weakness and puts platform-enabled, low-regulation niches ahead of the headline categories. On current evidence the top of the list is AlarmKit-based specialty alarms, menopause tracking and hobby data utilities; the scores are subjective and several rest on thin evidence.

### Cited Findings
- Evidence used for scoring is cited in sections 1–5. Key anchors: iOS releases +80% YoY — [TechCrunch](https://techcrunch.com/2026/04/18/the-app-store-is-booming-again-and-ai-may-be-why/); renewal by category — [RevenueCat 2026](https://www.revenuecat.com/state-of-subscription-apps-2026/); free Private Cloud Compute for small developers — [Small Business Program](https://developer.apple.com/app-store/small-business-program/); 568 GLP-1 apps — [Benzinga](https://www.benzinga.com/node/62011321); Apple's saturated-category list — [App Review Guidelines](https://developer.apple.com/app-store/review/guidelines/); 18+ floor for companions — [Apple developer news](https://developer.apple.com/news/?id=yxkh08us)

### Inferences
**Method (researcher's proposal).** Score each niche 1–5 on six factors and take the geometric mean, so a 1 on any factor drags the result down:
- Demand: evidence of users searching or paying now.
- Monetization: observed price points and renewal behaviour.
- Competitive headroom: 5 = few credible apps, 1 = hundreds of clones or a dominant giant.
- Build feasibility: 5 = one developer, weeks; 1 = content library, hardware or licences needed.
- Distribution fit: can a solo developer reach users through search, Apple featuring or a community without large ad spend?
- Risk safety: 5 = no policy or legal exposure; 1 = likely removal, lawsuits or regulation.

**Shortlist (scores are judgment calls; D/M/C/B/F/R in that order).**

| Rank | Niche and angle | D | M | C | B | F | R | Score |
|---|---|---|---|---|---|---|---|---|
| 1 | AlarmKit specialty alarms and timers (medication, prayer times, wake-up) | 3 | 3 | 4 | 5 | 4 | 4 | 3.8 |
| 2 | Menopause / perimenopause companion on the new HealthKit API | 4 | 4 | 3 | 4 | 3 | 3 | 3.5 |
| 3 | Hobby data utilities with widgets and Liquid Glass (tides, moon, sport-specific) | 3 | 3 | 3 | 4 | 4 | 4 | 3.5 |
| 4 | Neurodivergent planner / routines with alarms, Live Activities and Siri actions | 4 | 3 | 2 | 4 | 4 | 4 | 3.4 |
| 5 | Foldable-first (iPhone Duo) and touch-Mac utilities | 2 | 3 | 5 | 4 | 4 | 3 | 3.4 |
| 6 | Vertical on-device transcription and captions (field work, appointments, hearing) | 4 | 4 | 3 | 3 | 3 | 3 | 3.3 |
| 7 | Collectibles scanner and portfolio for under-served verticals | 4 | 3 | 3 | 3 | 4 | 3 | 3.3 |
| 8 | Faith and devotional apps for under-served traditions or languages | 4 | 4 | 2 | 4 | 3 | 3 | 3.2 |
| 9 | Trades micro-SaaS with multiseat purchasing | 3 | 5 | 3 | 2 | 2 | 4 | 3.0 |
| 10 | GLP-1 companion with a differentiated angle | 5 | 3 | 1 | 4 | 3 | 2 | 2.7 |

**Reference scores for saturated categories, same method:** generic AI chatbot wrapper 2.3 (5/3/1/5/1/2); AI calorie scanner 2.7 (5/4/1/3/2/3); AI companion 2.2 (4/5/2/3/1/1); phone cleaner 2.1 (4/4/1/3/1/2); meditation library 2.1 (2/3/1/2/2/4).

**Reading the list.**
- Ranks 1, 2 and 5 are platform-timing bets, strongest in the 6–12 months after the enabling API or device ships. Rank 5 is the most speculative because foldable volume is unknown.
- Ranks 3 and 4 depend on Apple featuring and craft; Apple's 2025 and 2026 awards support that route.
- Ranks 6 and 9 have the best monetization but need distribution outside App Store search.
- Rank 10 stays on the list only because demand is exceptional; without a distinct angle it scores like a saturated category.
- A cross-cutting multiplier applies to every item: use on-device or free Private Cloud Compute models to keep AI cost at zero, and ship Siri AI intents before App Store submission opens in spring 2027.

### Gaps
- Scores are not calibrated against measured keyword difficulty, cost per install or conversion data; a follow-up with Astro or Appfigures keyword scores should replace the Demand and Competition columns.
- Niches that could not be researched (exam prep, eSIM/travel, caregiver, AAC, golf, fishing, pickleball, invoicing) are absent from the ranking for lack of evidence, not because they scored poorly. Exam prep and travel utilities in particular deserve a second pass.
- No evidence was gathered on realistic revenue ceilings for ranks 1, 3 and 5, so their monetization scores are the least certain.
