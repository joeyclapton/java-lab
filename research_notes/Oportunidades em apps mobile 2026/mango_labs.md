# Mango Labs as a mobile app publisher (state as of 13 Nov 2026)

Research-access note for the report writer (applies to every section): from this session, `apps.apple.com`, `itunes.apple.com`, `play.google.com`, `sensortower.com`, `appfollow.io`, `techcrunch.com` and `mangolabs.com.br` could NOT be fetched directly (network allowlist), and the shared web-search budget ran out mid-research. Store-page facts below therefore come from search-engine result snippets of those pages (lower fidelity, undated crawl), while facts about the Brazilian Mango Labs come mostly from a primary source that WAS readable: the company's own public GitHub organisation (`github.com/mangolabsbr`), which contains the source code of its website. Anything not sourced is listed under Gaps, not asserted.

## 1. Which distinct "Mango Labs" entities publish apps on the App Store / Google Play?

### Takeaway
Two unrelated entities actually publish mobile apps under this name: (A) **Mango Labs Ltda**, a small Brazilian indie studio (mangolabs.com.br) that started shipping in Jan 2026 and now lists 8 iOS/Android apps plus 2 web products; and (B) **Mango Labs, LLC**, a San Francisco publisher account owned by influencer-marketing firm JetFuel (acquired by Vungle in 2021) that fronted viral subscription apps such as Fontmaker. **(A) is the most likely match for "a friend's studio" of a Brazilian requester — confidence high (roughly 85-90%) but NOT confirmed**; nothing found links (A) and (B), and they must not be merged.

### Cited Findings

**Candidate A — Mango Labs Ltda (Brazil) — most likely match**
- The App Store seller name on "Currency Converter - Xchanger" is "Mango Labs Ltda" (search snippet of the US App Store page) — [App Store](https://apps.apple.com/us/app/currency-converter-xchanger/id6757408534)
- On Google Play the same apps appear under the developer name "MANGO LABS LTDA" (search snippet) — [Google Play](https://play.google.com/store/apps/details?id=com.mangolabs.xchanger&hl=en_US)
- Website is mangolabs.com.br; its own copy describes it as an "independent app studio", tagline "Apps for daily life. Crafted by humans.", "made in Brazil", building mobile apps and digital services for everyday needs (currency conversion, route planning, bill splitting) — [website source, messages/en.json](https://github.com/mangolabsbr/mango-website/blob/main/messages/en.json); [mangolabs.com.br](https://www.mangolabs.com.br/)
- The studio also sells services: mobile app development, cross-platform (iOS/Android/web) development, UI design and full-stack web products — [messages/en.json](https://github.com/mangolabsbr/mango-website/blob/main/messages/en.json)
- GitHub organisation "Mango Labs" (@mangolabsbr): location Brazil, website mangolabs.com.br, email hello@mangolabs.com.br, no public members, 3 public repos (mango-website, expo-game-services, xchanger-currency-flags) — [GitHub org](https://github.com/mangolabsbr)
- Contact emails used: hello@mangolabs.com.br (company, Splitte, SunRouter support) and contato@mangolabs.com.br (the puzzle games) — [messages/en.json](https://github.com/mangolabsbr/mango-website/blob/main/messages/en.json); [mwm.ai SunRouter mirror](https://mwm.ai/apps/route-planner-sunrouter/6758227443)
- Governing law in the terms of Proportion, Splitte and all five puzzle games is Brazil — [messages/en.json](https://github.com/mangolabsbr/mango-website/blob/main/messages/en.json)
- All 60 commits of the website repository are authored by GitHub user `tchesa`; first commit ("v1") is dated 5 Dec 2025 — [commit history p.1](https://github.com/mangolabsbr/mango-website/commits/main/); [commit history p.2](https://github.com/mangolabsbr/mango-website/commits/main?after=e417285a643603ab1ddec7dd396e787dce1c3dac+34)
- `tchesa`'s public GitHub profile: display name Cesar Olimpio, bio "Front-end developer. Game developer on my spare time.", location Belo Horizonte, Brazil, website field mangolabs.com.br, 95 repositories, 21 followers — [GitHub profile](https://github.com/tchesa)
- Social/company links hard-coded in the website footer: LinkedIn `linkedin.com/company/mangolabsbr`, X `x.com/mangolabsbr`, a Facebook page ("Mango-Labs", id 61592320798007) and GitHub; no Instagram, TikTok or YouTube link is present — [footer source](https://github.com/mangolabsbr/mango-website/blob/main/components/footer/index.tsx)
- Developer-page URLs: the site links each app directly (no developer-page URL is stored); App Store app IDs and Google Play package IDs are listed in section 2 — [lib/apps.ts](https://github.com/mangolabsbr/mango-website/blob/main/lib/apps.ts)

**Candidate B — Mango Labs, LLC (San Francisco, USA) — JetFuel/Vungle publisher account**
- TechCrunch (1 Sep 2021) reported that "Mango Labs, LLC" was an iTunes developer account owned by mobile growth company JetFuel, recently acquired by Vungle; the handwriting-font app Fontmaker, charging a weekly subscription, was published under it and reached the top of the App Store — [TechCrunch](https://techcrunch.com/2021/09/01/how-a-vungle-owned-mobile-marketer-sent-fontmaker-to-the-top-of-the-app-store/)
- A Vungle spokesperson said apps under the Mango Labs LLC name "were in fact developed by other companies, and Mango Labs has only acted as a publisher" — [TechCrunch](https://techcrunch.com/2021/09/01/how-a-vungle-owned-mobile-marketer-sent-fontmaker-to-the-top-of-the-app-store/)
- Takeoff Labs' site listed a portfolio (Celeb, Litstick, FontKey) that was published by Mango Labs on the App Store; Takeoff Labs' LLC application was signed by Tim Lenardo (JetFuel) — [TechCrunch](https://techcrunch.com/2021/09/01/how-a-vungle-owned-mobile-marketer-sent-fontmaker-to-the-top-of-the-app-store/)
- Tim Lenardo's personal site says he co-launched Takeoff Labs in 2019 and that the studio sold the Takeoff app portfolio in 2022 — [timl.xyz](https://www.timl.xyz/works)
- JetFuel (influencer marketing platform) was acquired by Blackstone-owned Vungle in July 2021 — [AdExchanger](https://www.adexchanger.com/mobile/vungle-is-acquiring-influencer-platform-jetfuel-to-reach-those-gen-z-eyeballs/)
- AppFollow lists iOS apps under "Mango Labs LLC" including Caption Pro, Stickered, Celebs - Celebrity Look Alike and Color Meme — [AppFollow](https://appfollow.io/ios/mango-labs-llc?country=us&developer=Mango%20Labs%20LLC)
- Google Play has a developer page "Mango Labs LLC" with a San Francisco address and a social app called "Mango" (package `com.mangolabs.mango`) — [Google Play developer page](https://play.google.com/store/apps/developer?id=Mango+Labs+LLC); [Google Play app](https://play.google.com/store/apps/details?id=com.mangolabs.mango)
- Sensor Tower has a publisher page for it (iOS publisher id 1289530365); the figures are behind login and were not visible — [Sensor Tower](https://app.sensortower.com/ios/publisher/mango-labs-llc/1289530365)

**Other "Mango Labs"-named entities found that are NOT confirmed mobile app-store publishers**
- Mango Labs (East Brunswick / New Brunswick, New Jersey): in-game advertising company founded 2013, marked permanently closed on Crunchbase — [Crunchbase](https://www.crunchbase.com/organization/mango-labs); [Dealroom](https://app.dealroom.co/companies/mango_labs)
- "Mango Labs, Inc" (San Francisco): a business-directory profile with a third-party revenue estimate of $315,683/yr and a named CEO; not shown to be an app-store publisher and possibly unrelated to the LLC — [Buzzfile](https://www.buzzfile.com/business/Mango-Labs,-Inc-650-646-1003)
- "Mango Labs" design studio (Framer site, design-subscription offering at $4,895/month) — a design-services page, not an app publisher — [Framer site](https://optimistic-tour-006101.framer.app/)
- mangolabs.ch — a Swiss startup with the same name, unrelated — [mangolabs.ch](https://www.mangolabs.ch/)
- "Mango Lab Studio" (X account @mangolab, location Brazil, site mangolabstudio.com) — a game studio with a similar name; no confirmed link to Mango Labs Ltda — [X](https://x.com/mangolab)
- An X account @Mango_Labs exists; which entity owns it was not verified — [X](https://x.com/mango_labs)
- Similarly named but different App Store developers that searches surface (do not confuse): Mango Umbrella LLC (Mango Baby etc.), MangoApps Inc., Mango Mobile S.r.l., Mango Technologies Inc. — [App Store developer page, Mango Umbrella](https://apps.apple.com/developer/508676284); [appgoblin, Mango Mobile](https://appgoblin.info/developers/772211887)

### Inferences
- "Ltda" (Sociedade Limitada) is a Brazilian legal form, and the site says "made in Brazil", governing law Brazil, GitHub location Brazil: Candidate A is clearly a Brazilian company. Combined with the requester being Brazilian and describing it as a friend's company, A is the best match. B is a US corporate marketing vehicle, not something one would normally call "a friend's studio".
- Cesar Olimpio (`tchesa`, Belo Horizonte) is the only visible committer and links mangolabs.com.br from his profile, so he is very probably the founder or the lead/sole developer; his role as founder is an inference, not a stated fact. The team size appears to be one or very few people.
- Founding date of A is not public in sources read; the observable start of activity is Dec 2025 (website v1) with first app release Jan 2026, so the studio is roughly 11 months old as of Nov 2026.
- Both A and B use the `com.mangolabs.*` Android package prefix (`com.mangolabs.xchanger` vs `com.mangolabs.mango`); this is a naming collision, not evidence of a link.
- The Solana/"Mango Markets" Mango Labs mentioned in the assignment is a crypto protocol team, not an app-store publisher; no source on it was collected in this session.

### Gaps
- CNPJ, registered address, incorporation date and partners of Mango Labs Ltda: not found (the site footer has no legal block; Receita Federal/CNPJ lookups were not reachable).
- The LinkedIn company page and X/Facebook accounts of A could not be opened, so follower counts, team list and posting activity are unknown.
- Apple developer-page URL / developer ID for Mango Labs Ltda and the Google Play developer-page URL were not retrieved.
- Current (2026) status of Candidate B's apps is unknown: the newest source on it is from 2021-2022; whether Fontmaker, Celebs, etc. are still live was not verified.
- No confirmation from the requester of which entity is meant; if the friend's studio is not the Brazilian one, this profile targets the wrong company.

## 2. Candidate A (Mango Labs Ltda): full app list, categories, launch dates, updates, ratings, localization, rankings

### Takeaway
The Brazilian studio lists 11 products: 8 mobile apps on both stores (3 utilities launched Jan-Mar 2026, 5 casual puzzle games added Sep-Nov 2026), 1 Android-only calculator, and 2 web products (Menoodo SaaS, Xchanger API). Visible traction is minimal: ~10 months after launch the flagship Xchanger still showed "not enough ratings" on the US App Store, and no chart rankings were found.

### Cited Findings
- The website's app registry (`showcasedAppSlugs`, "ordered by prominence") lists exactly these 11 entries, in this order — [lib/apps.ts](https://github.com/mangolabsbr/mango-website/blob/main/lib/apps.ts):

| # | Product | Type / niche | iOS App Store ID | Google Play package | Web |
|---|---|---|---|---|---|
| 1 | Xchanger ("Currency Converter - Xchanger") | Finance utility: fiat + crypto converter | id6757408534 | com.mangolabs.xchanger | — |
| 2 | SunRouter ("Route Planner - SunRouter") | Navigation: multi-stop route planner for delivery drivers | id6758227443 | com.mangolabs.sunrouter | — |
| 3 | Splitte ("Splitte - Bill Splitter") | Utility/finance: item-by-item bill splitting with AI receipt scan | id6760258397 | com.mangolabs.splitte | — |
| 4 | Menoodo | Web SaaS: QR-code digital menus for restaurants | — | — | menoodo.com |
| 5 | Sudoku | Puzzle game | id6815376814 | com.mangolabs.sudoku | — |
| 6 | Mathdoku | Puzzle game (KenKen-style) | id6818647148 | com.mangolabs.mathdoku | — |
| 7 | Words Infinity | Word game (Wordle-style, endless) | id6819404698 | com.mangolabs.wordsinfinity | — |
| 8 | Word Search Infinity | Word-search game | id6821736206 | com.mangolabs.wordsearchinfinity | — |
| 9 | Sudoku Colors | Puzzle game (colours instead of digits) | id6815864434 | com.mangolabs.sudokucolors | — |
| 10 | Proportion | Rule-of-three / proportion calculator, Android only | — | com.mangolabs.proportion | — |
| 11 | Xchanger API | Web/API: REST exchange-rate API for developers | — | — | xchangerapi.com |

- The home page showcases only the first four (Xchanger, SunRouter, Splitte, Menoodo) — [lib/apps.ts](https://github.com/mangolabsbr/mango-website/blob/main/lib/apps.ts)
- Xchanger iOS: version 1.0 released 15 Jan 2026; a later snapshot shows latest version 1.0.4 (third-party mirror) — [mwm.ai](https://mwm.ai/apps/currency-converter-xchanger/6757408534)
- Xchanger iOS (search snippet of the US App Store page, crawl date unknown): Free with in-app purchases, requires iOS 15.1+, size 55.3 MB, most recent update "adds support for cryptocurrency exchange rates", privacy label "developer does not collect any data", and "this app hasn't received enough ratings or reviews to display an overview" — [App Store](https://apps.apple.com/us/app/currency-converter-xchanger/id6757408534)
- Xchanger Google Play listing snippet dated 6 Jun 2026 announces "Exchange rate alerts are here"; listing copy: 100+ world currencies, 200+ cryptocurrencies, real-time rates, smart rate alerts, offline mode — [Google Play](https://play.google.com/store/apps/details?id=com.mangolabs.xchanger&hl=en_US)
- SunRouter iOS: first release 10 Mar 2026 per third-party mirror, which also shows "User Rating 1.0/5, 0" (looks like a placeholder for an unrated app, not a real average) — [mwm.ai](https://mwm.ai/apps/route-planner-sunrouter/6758227443)
- SunRouter features: up to 25 stops, waypoint reordering/optimisation, avoid tolls/highways/ferries, bulk address import, car/bicycle/walking/two-wheeler modes, hand-off of turn-by-turn navigation to Google Maps, Apple Maps or Waze; "no cloud accounts, no data sharing" — [Google Play](https://play.google.com/store/apps/details?id=com.mangolabs.sunrouter); [messages/en.json](https://github.com/mangolabsbr/mango-website/blob/main/messages/en.json)
- Splitte: splits bills item by item including tax and tip, scans receipts with AI (Google Gemini), saves frequent participants, local SQLite storage, no cloud sync; App Store subtitle "Split bills with friends" — [messages/en.json](https://github.com/mangolabsbr/mango-website/blob/main/messages/en.json); [App Store "More by" section](https://apps.apple.com/us/app/currency-converter-xchanger/id6757408534)
- Sudoku: four difficulty levels, notes, up to three hints per game, fully offline, 19 languages, light/dark mode; terms/privacy dated 23 Sep 2026 — [messages/en.json](https://github.com/mangolabsbr/mango-website/blob/main/messages/en.json)
- Sudoku Colors: colours replace numbers, colour-assist palettes, 19 languages; terms dated 23 Sep 2026 — [messages/en.json](https://github.com/mangolabsbr/mango-website/blob/main/messages/en.json)
- Mathdoku: 336 puzzles from 3x3 to 9x9, offline, 19 languages, "No ads", puzzle generator derived from the MIT-licensed Gengen; terms dated 2 Oct 2026 — [messages/en.json](https://github.com/mangolabsbr/mango-website/blob/main/messages/en.json)
- Words Infinity: endless word-guessing, six tries, 4/5/6-letter difficulties, score multiplier up to 3x, 13 languages, offline, optional Game Center / Google Play Games leaderboards; terms dated 5 Oct 2026 — [messages/en.json](https://github.com/mangolabsbr/mango-website/blob/main/messages/en.json)
- Word Search Infinity: endless levels, 23 themes, three hints per level, 13 languages, no timer, offline, optional leaderboards and achievements; terms dated 14 Oct 2026 — [messages/en.json](https://github.com/mangolabsbr/mango-website/blob/main/messages/en.json)
- Proportion: direct/inverse proportion solver, one-tap copy, 20 languages, no ads, no sign-up, Android only; terms carry the date 22 Feb 2025 while the privacy policy is dated 1 Aug 2026 — [messages/en.json](https://github.com/mangolabsbr/mango-website/blob/main/messages/en.json); [lib/apps.ts](https://github.com/mangolabsbr/mango-website/blob/main/lib/apps.ts)
- Release cadence visible in website commits (legal/landing pages are added when an app is about to ship): Xchanger pages 11 Jan 2026; SunRouter privacy/terms 8 Feb 2026; Proportion terms 2 Mar 2026; Splitte pages 13 Mar 2026; Proportion listed 2 Aug 2026; Menoodo added 2 Sep 2026; Sudoku and Sudoku Colors terms 23-27 Sep 2026; Mathdoku legal pages 2 Oct 2026; Words Infinity terms 7 Oct 2026; Word Search Infinity pages 14 Oct 2026; Word Search Infinity app page and Xchanger API article 3 Nov 2026 — [commits p.1](https://github.com/mangolabsbr/mango-website/commits/main/); [commits p.2](https://github.com/mangolabsbr/mango-website/commits/main?after=e417285a643603ab1ddec7dd396e787dce1c3dac+34)
- The website itself is localised in English (default), Spanish and Portuguese — [CLAUDE.md](https://github.com/mangolabsbr/mango-website/blob/main/CLAUDE.md)
- The home page displays headline numbers "12K+" downloads, "4.9" rating, "1K+" active users and "11" apps, but a code comment in the source labels these values as placeholders — [lib/metrics.ts](https://github.com/mangolabsbr/mango-website/blob/main/lib/metrics.ts)

### Inferences
- Portfolio pace: 3 utilities in Q1 2026, then a gap (Apr-Aug) with only maintenance, then 5 puzzle games in about six weeks (late Sep to early Nov 2026). The second wave is fast because the games share an engine/stack and reuse localisation (19 or 13 languages each).
- The website's "12K+ downloads / 4.9 rating / 1K+ active users" should be treated as unverified marketing copy (explicitly flagged as placeholder in code); it is inconsistent with the flagship app not having enough US ratings to display an average.
- Proportion's "22 Feb 2025" terms date is probably a typo for 2026 (its legal pages were committed on 2 Mar 2026), although an earlier Android-only release cannot be excluded.
- The SunRouter Google Play snippet was dated "about 250 days ago" (≈ early March 2026) in search results, which may indicate the Android listing has not been updated since launch; this is weak evidence because snippet dates can reflect crawl time.

### Gaps
- Per-app rating counts and averages, exact "last updated" dates, version histories, App Store category labels and the list of store-listing languages could not be read directly from the stores (hosts blocked).
- No App Store or Google Play chart rankings by country were found for any Mango Labs Ltda app; no third-party tracker page with rank history was reachable.
- Google Play install-count buckets (e.g. "100+", "1K+") were not retrievable.
- Exact store release dates for Splitte and the five games are not confirmed; only website-commit dates are known. Whether all five games are already live on both stores (versus pending review) was not verified.

## 3. Monetization (free vs paid, IAP price points, trials, ads)

### Takeaway
Candidate A uses a freemium subscription model on the two core utilities at very low price points (Xchanger: US$1.99/month, US$14.99/year via RevenueCat), keeps Splitte, Proportion and (apparently) the puzzle games free, and is diversifying into non-store revenue: a restaurant SaaS (Menoodo, US$12-29/month via Paddle) and a developer API (US$10/month). Candidate B used aggressive weekly subscriptions on viral novelty apps.

### Cited Findings
- Xchanger US App Store in-app purchases: Monthly Subscription $1.99, Annual Subscription $14.99; app is free to download (search snippet) — [App Store](https://apps.apple.com/us/app/currency-converter-xchanger/id6757408534)
- Xchanger paywall logic: free users get accurate rates with a 1-hour delay; Premium gets rate updates every 10 minutes and offline access to downloaded rates; subscriptions are monthly or annual, auto-renewing — [Google Play](https://play.google.com/store/apps/details?id=com.mangolabs.xchanger&hl=en_US); [messages/en.json](https://github.com/mangolabsbr/mango-website/blob/main/messages/en.json)
- SunRouter Premium (monthly and annual subscriptions, prices not found) unlocks route optimisation, unlimited routes and up to 25 stops per route — [messages/en.json](https://github.com/mangolabsbr/mango-website/blob/main/messages/en.json); [Google Play](https://play.google.com/store/apps/details?id=com.mangolabs.sunrouter)
- Subscriptions in Xchanger and SunRouter are handled through RevenueCat — [messages/en.json](https://github.com/mangolabsbr/mango-website/blob/main/messages/en.json)
- Splitte's terms state "Splitte is free to use" even though each receipt scan calls the Google Gemini API — [messages/en.json](https://github.com/mangolabsbr/mango-website/blob/main/messages/en.json)
- Proportion: privacy policy says no purchases or subscriptions; described as no ads — [messages/en.json](https://github.com/mangolabsbr/mango-website/blob/main/messages/en.json)
- Puzzle games: Mathdoku is explicitly "No ads"; the legal texts of Sudoku, Sudoku Colors, Mathdoku, Words Infinity and Word Search Infinity name only Sentry, Vexo and Expo EAS Update as third parties (no RevenueCat, no ad network) — [messages/en.json](https://github.com/mangolabsbr/mango-website/blob/main/messages/en.json)
- The website serves an `app-ads.txt` with one Google (AdMob/AdSense) publisher line (`google.com, pub-4949895159484773, DIRECT`), added on 4 Feb 2026 — [app-ads.txt](https://github.com/mangolabsbr/mango-website/blob/main/public/app-ads.txt); [commits p.2](https://github.com/mangolabsbr/mango-website/commits/main?after=e417285a643603ab1ddec7dd396e787dce1c3dac+34)
- Menoodo pricing: Hobby free forever (1 restaurant, 1 language, 30-dish cap, small Menoodo banner); Pro $12/month; Max $29/month; annual billing cheaper; 30-day free trial on paid plans; Paddle is merchant of record; prices vary by country — [Menoodo comparison article](https://github.com/mangolabsbr/mango-website/blob/main/content/articles/best-digital-menu-platforms-for-restaurants/en.mdx); [Menoodo launch article](https://github.com/mangolabsbr/mango-website/blob/main/content/articles/menoodo-digital-menus-for-restaurants/en.mdx)
- Xchanger API pricing: Free 1,000 requests/month (no card); Pro $10/month (about $100/year) for 1,000,000 requests; Enterprise on request; 30-day money-back guarantee; rates refresh every 10 minutes on every plan — [Xchanger API article](https://github.com/mangolabsbr/mango-website/blob/main/content/articles/best-currency-and-crypto-exchange-rate-apis/en.mdx)
- Price context for the route-planner niche (competitors, not Mango Labs): MyWay Route Planner $9.99/month and $79.99/year with a reported 4.8/5 from 2,271 reviews; inRoute Pro $6.99/month and $49.99/year; enRoute $9.99/month with 3-day trial or $49.99/year — [Adapty paywall library](https://adapty.io/paywall-library/route-planner-delivery-myway/); [App Store, inRoute](https://apps.apple.com/app/id703796787); [App Store, enRoute](https://apps.apple.com/us/app/id1582408861)
- Candidate B: Fontmaker (published under Mango Labs, LLC) charged a weekly subscription — [TechCrunch](https://techcrunch.com/2021/09/01/how-a-vungle-owned-mobile-marketer-sent-fontmaker-to-the-top-of-the-app-store/)

### Inferences
- Xchanger's $1.99/month and $14.99/year are far below what the adjacent utility niches charge (route planners at $6.99-9.99/month and $49.99-79.99/year). Low price plus low volume implies very small revenue per app; the studio prices like a hobbyist tool rather than like a subscription business.
- The gating choice in Xchanger (data freshness: 1-hour delay vs 10 minutes) is a weak paywall for casual travellers, who rarely need sub-hour rates; the stronger gates are offline mode and alerts.
- An `app-ads.txt` exists but no privacy policy read mentions an ad SDK and two apps are explicitly ad-free, so ads are either limited to one app/platform not covered in the texts read, planned, or abandoned. Ad monetisation is therefore unconfirmed.
- The five puzzle games appear to have no monetisation at all at launch (no IAP SDK, no ads named). They may be audience/ASO experiments or a base for later ads/IAP.
- Splitte carries a variable AI cost (Gemini calls) with no revenue, a negative-margin feature unless usage stays tiny.
- Menoodo and Xchanger API signal a deliberate move toward B2B/web revenue outside the stores (no 15-30% store fee, Paddle billing, higher price points) and reuse of assets built for the apps (the rates backend).

### Gaps
- SunRouter subscription prices, any lifetime unlocks, and whether any Mango Labs Ltda app offers a free trial: not found.
- Brazilian storefront (BRL) price points: not retrieved.
- IAP lists for Splitte and the five games as shown on the App Store: not retrieved (legal texts suggest none).
- Whether any app actually shows ads: unconfirmed.
- Candidate B's exact price points and trial structures: not retrieved (TechCrunch page not fetchable; only the "weekly subscription" fact surfaced).

## 4. Estimated downloads and revenue (third-party sources)

### Takeaway
No third-party download or revenue estimate was obtained for any Mango Labs Ltda app, and the indirect signals (no displayable US rating average on the flagship after ~10 months, no chart presence found) point to very low volume. For Mango Labs, LLC a Sensor Tower publisher page exists but its numbers are gated.

### Cited Findings
- Sensor Tower lists a publisher page for "Mango Labs" (LLC, iOS publisher id 1289530365) with top apps, revenue and download estimates, but the figures require login and were not visible — [Sensor Tower](https://app.sensortower.com/ios/publisher/mango-labs-llc/1289530365)
- The Xchanger US App Store page showed no rating overview because the app "hasn't received enough ratings or reviews" (snippet; crawl date unknown) — [App Store](https://apps.apple.com/us/app/currency-converter-xchanger/id6757408534)
- A third-party mirror shows SunRouter with "1.0/5" and "0" (ratings/downloads field), i.e. effectively no rating data — [mwm.ai](https://mwm.ai/apps/route-planner-sunrouter/6758227443)
- The studio's own site shows "12K+ downloads", "4.9 rating", "1K+ active users", flagged in the source code as placeholder values (self-reported, unverified, not an estimate from a data provider) — [lib/metrics.ts](https://github.com/mangolabsbr/mango-website/blob/main/lib/metrics.ts)
- Candidate B: TechCrunch reported Fontmaker reaching the top of the App Store in 2021 (chart position, not a download estimate) — [TechCrunch](https://techcrunch.com/2021/09/01/how-a-vungle-owned-mobile-marketer-sent-fontmaker-to-the-top-of-the-app-store/)
- A business directory gives a third-party ESTIMATE of $315,683 annual revenue for "Mango Labs, Inc" in San Francisco; it is unclear that this is the same entity as the LLC and the methodology is unknown — [Buzzfile](https://www.buzzfile.com/business/Mango-Labs,-Inc-650-646-1003)

### Inferences
- With the evidence available, Mango Labs Ltda should be treated as pre-traction: there is no sign that any of its apps is profitable. It is useful as a case study of an indie "ship many small apps" approach in its first year, not as a proven revenue model.
- If the studio's "12K+ downloads" were real across the portfolio, at typical freemium utility conversion rates and a $14.99/year plan the implied subscription revenue would still be small (order of hundreds to low thousands of USD per year); this is a reasoning-based bound, not a sourced estimate.

### Gaps
- Sensor Tower, AppMagic, Appfigures, AppBrain, data.ai, Similarweb and Apptopia pages for Mango Labs Ltda apps were not reachable or not found; no per-app download or revenue estimate exists in these notes.
- Google Play install buckets were not retrievable.
- Candidate B's download/revenue figures (2021 or current) were not retrievable.

## 5. Product strategy patterns (niches, portfolio model, design, AI, tech)

### Takeaway
Mango Labs Ltda runs a small "app portfolio/factory" on one shared stack (React Native + Expo, RevenueCat, Sentry, Vexo, OTA updates): it clones well-established commodity categories (currency converter, route planner, bill splitter, sudoku, word games) with a privacy-first, offline, no-account angle, broad localisation, and light AI features, then spins internal assets into B2B products. Mango Labs, LLC was a different kind of factory: a publishing shell for third-party viral apps driven by influencer marketing.

### Cited Findings
- Niches targeted: finance utility (currency/crypto converter), navigation for delivery drivers and field agents, bill splitting, proportion calculator, and classic puzzle/word games — [lib/apps.ts](https://github.com/mangolabsbr/mango-website/blob/main/lib/apps.ts); [Google Play SunRouter](https://play.google.com/store/apps/details?id=com.mangolabs.sunrouter)
- Tech stack shown on the home page includes React Native, Expo and PostgreSQL (list of eight technologies with a TODO to confirm) — [lib/metrics.ts](https://github.com/mangolabsbr/mango-website/blob/main/lib/metrics.ts)
- Shared SDK set across apps: RevenueCat (subscriptions), Sentry (crash reporting), Vexo Analytics (including session replays and tap heatmaps in Proportion), Expo EAS Update (over-the-air updates in the games), Expo SecureStore and local SQLite storage — [messages/en.json](https://github.com/mangolabsbr/mango-website/blob/main/messages/en.json)
- Privacy-first, local-first positioning: Xchanger collects no names/emails/location; SunRouter uses location on-device only with "no cloud accounts"; Splitte stores bills locally with no cloud sync; games work fully offline with no account — [messages/en.json](https://github.com/mangolabsbr/mango-website/blob/main/messages/en.json)
- AI features: Splitte scans receipts via Google Gemini; Menoodo uses AI menu import (PDF/spreadsheet/website to editable menu) and AI auto-translation with owner approval across about 120 languages — [messages/en.json](https://github.com/mangolabsbr/mango-website/blob/main/messages/en.json); [Menoodo launch article](https://github.com/mangolabsbr/mango-website/blob/main/content/articles/menoodo-digital-menus-for-restaurants/en.mdx)
- Heavy localisation as a default: Proportion 20 languages; Sudoku, Sudoku Colors and Mathdoku 19 languages; Words Infinity and Word Search Infinity 13 languages; Menoodo dashboard in 8 languages — [messages/en.json](https://github.com/mangolabsbr/mango-website/blob/main/messages/en.json); [Menoodo launch article](https://github.com/mangolabsbr/mango-website/blob/main/content/articles/menoodo-digital-menus-for-restaurants/en.mdx)
- Reusable internal components are open-sourced: `@mangolabs/expo-game-services` (Game Center + Google Play Games leaderboards/achievements for Expo SDK 54+, MIT, 4 commits, updated 6 Oct 2026) and `xchanger-currency-flags` (154 PNG / 161 SVG fiat flags and 1,322 crypto icons) — [expo-game-services](https://github.com/mangolabsbr/expo-game-services); [xchanger-currency-flags](https://github.com/mangolabsbr/xchanger-currency-flags)
- Spin-off pattern: Xchanger API is described as the app's rates backend offered to other developers (172 fiat currencies, 514 cryptocurrencies) — [Xchanger API article](https://github.com/mangolabsbr/mango-website/blob/main/content/articles/best-currency-and-crypto-exchange-rate-apis/en.mdx)
- AI-assisted production: the website repo contains a `CLAUDE.md`, a `.claude/skills/article-writing` skill and at least one commit co-authored with Claude — [mango-website repo](https://github.com/mangolabsbr/mango-website); [commits p.1](https://github.com/mangolabsbr/mango-website/commits/main/)
- Unfinished polish: the Xchanger and SunRouter terms still contain bracketed placeholders such as "[Jurisdiction]" for governing law — [messages/en.json](https://github.com/mangolabsbr/mango-website/blob/main/messages/en.json)
- Candidate B's model: a publisher account fronting apps "developed by other companies" (Fontmaker, Celeb, Litstick, FontKey, Caption Pro, Stickered, Color Meme), run by an influencer-marketing company — [TechCrunch](https://techcrunch.com/2021/09/01/how-a-vungle-owned-mobile-marketer-sent-fontmaker-to-the-top-of-the-app-store/); [AppFollow](https://appfollow.io/ios/mango-labs-llc?country=us&developer=Mango%20Labs%20LLC)

### Inferences
- Yes, Candidate A looks like a portfolio/factory model at solo-developer scale: 9 store apps in ~10 months on one cross-platform codebase pattern, every app on both stores, shared analytics/billing/legal templates, and a single website generating landing + legal pages per app.
- The category choices are all "evergreen search demand" utilities and games, i.e. niches with huge keyword volume but entrenched incumbents with thousands of ratings; none of the apps has an obviously unique wedge except SunRouter's delivery-driver audience (a user group with real willingness to pay) and Splitte's AI receipt scan.
- The shift from utilities (Q1 2026) to casual games (Q4 2026) and to B2B web products (Sep-Nov 2026) suggests the first utilities did not gain enough traction to justify doubling down on them; this is an interpretation of release timing, not a statement by the studio.
- No evidence of widgets, Live Activities, Apple Watch apps or other platform-native features was found (Expo cross-platform approach makes these costlier). Design quality could not be assessed because store screenshots were not viewable.

### Gaps
- Screenshots, icons and UI quality were not viewable; no judgement on design quality is possible from the sources read.
- Whether apps include home-screen widgets or other native extensions is unknown.
- The remaining items of the eight-item tech-stack list (beyond React Native, Expo, PostgreSQL) were not captured.

## 6. Distribution patterns (ASO, social, paid ads, press, founder posts)

### Takeaway
Mango Labs Ltda's distribution is almost entirely organic and low-intensity: keyword-first store titles ("Currency Converter - Xchanger", "Route Planner - SunRouter"), a trilingual SEO blog with vendor-authored "best X in 2026" comparison posts, open-source repos that link back to the apps, and basic company pages on LinkedIn, X and Facebook; no paid acquisition, press, Product Hunt launch or build-in-public revenue posts were found. Mango Labs, LLC is the opposite playbook: TikTok/influencer-driven virality engineered by a marketing company.

### Cited Findings
- Store titles follow a "generic keyword - brand" pattern: "Currency Converter - Xchanger" (iOS), "Currency converter - Xchanger" (Android), "Route Planner - SunRouter", "Splitte - Bill Splitter" — [App Store](https://apps.apple.com/us/app/currency-converter-xchanger/id6757408534); [Google Play Xchanger](https://play.google.com/store/apps/details?id=com.mangolabs.xchanger&hl=en_US); [Google Play SunRouter](https://play.google.com/store/apps/details?id=com.mangolabs.sunrouter)
- Website SEO work was done in a burst on 17-23 Jul 2026 (redesign, SEO, articles section, sitemap, RSS feeds, Open Graph images, Vercel Analytics, Sentry) — [commits p.1](https://github.com/mangolabsbr/mango-website/commits/main/); [CLAUDE.md](https://github.com/mangolabsbr/mango-website/blob/main/CLAUDE.md)
- Content strategy: MDX articles published in en/es/pt with per-locale RSS; five articles exist as of Nov 2026 — two news explainers for app developers (Apple's social-media age-rating question, 26 Jul 2026; Google Play catalog access opt-in, 26 Jul 2026), the Menoodo launch post (2 Sep 2026), and two "best of 2026" comparison posts (digital menu platforms, 14 Sep 2026; currency/crypto exchange-rate APIs, 3 Nov 2026) — [articles directory](https://github.com/mangolabsbr/mango-website/tree/main/content/articles); [CLAUDE.md](https://github.com/mangolabsbr/mango-website/blob/main/CLAUDE.md)
- The comparison posts disclose that the author makes one of the compared products, list its drawbacks, and end with a call to try it; the Apple article links to Xchanger and SunRouter as examples — [API comparison article](https://github.com/mangolabsbr/mango-website/blob/main/content/articles/best-currency-and-crypto-exchange-rate-apis/en.mdx); [menu comparison article](https://github.com/mangolabsbr/mango-website/blob/main/content/articles/best-digital-menu-platforms-for-restaurants/en.mdx); [Apple age-rating article](https://github.com/mangolabsbr/mango-website/blob/main/content/articles/apple-social-media-descriptor-13-plus/en.mdx)
- Menoodo offers a free, no-account QR-code generator at menoodo.com as a lead-generation tool — [Menoodo launch article](https://github.com/mangolabsbr/mango-website/blob/main/content/articles/menoodo-digital-menus-for-restaurants/en.mdx)
- The public `xchanger-currency-flags` asset repo links to the app's App Store and Google Play pages — [xchanger-currency-flags](https://github.com/mangolabsbr/xchanger-currency-flags)
- Social presence linked from the site: LinkedIn company page, X @mangolabsbr, a Facebook page and GitHub (Facebook and X links added 23 Jul 2026); no Instagram, TikTok or YouTube — [footer source](https://github.com/mangolabsbr/mango-website/blob/main/components/footer/index.tsx); [commits p.1](https://github.com/mangolabsbr/mango-website/commits/main/)
- Candidate B's distribution: Fontmaker was pushed to the top of the App Store by a Vungle-owned influencer-marketing company (JetFuel), whose business is reaching Gen Z through creators — [TechCrunch](https://techcrunch.com/2021/09/01/how-a-vungle-owned-mobile-marketer-sent-fontmaker-to-the-top-of-the-app-store/); [AdExchanger](https://www.adexchanger.com/mobile/vungle-is-acquiring-influencer-platform-jetfuel-to-reach-those-gen-z-eyeballs/)

### Inferences
- The blog topics chosen so far target developers and restaurant owners (B2B buyers of Xchanger API / Menoodo), not the consumers who would download the mobile apps; the content engine therefore does little for app installs.
- With no short-form video channel, no paid UA and commodity keywords, the consumer apps depend on App Store / Google Play search alone, where "currency converter", "route planner", "sudoku" and "word search" are among the most contested terms. This is consistent with the lack of ratings.
- Localising into 13-20 languages is the studio's main ASO lever (long-tail non-English keywords are cheaper to rank for), but its effect could not be measured.

### Gaps
- Subtitles, keyword fields and screenshot style of the store listings were not viewable.
- Meta Ad Library and TikTok Creative Center were not reachable; whether Mango Labs Ltda runs paid ads is unknown (nothing suggests it does).
- No press coverage, Product Hunt launch, Indie Hackers, Reddit or podcast mention of Mango Labs Ltda was found before the search budget ran out; absence is not proven.
- No founder posts about revenue or lessons learned were found; the X and LinkedIn accounts could not be opened.

## 7. Concrete lessons from the portfolio (what seems to work, what looks abandoned)

### Takeaway
Mango Labs Ltda is best read as an honest early-stage example of shipping velocity without distribution: the production system is replicable and cheap, but there is no evidence yet of meaningful downloads or revenue, so its lessons are mostly about process (worth copying) and about go-to-market gaps (worth avoiding). The only documented "what works at scale" under the Mango Labs name is Candidate B's influencer-led playbook, which belongs to a different company.

### Cited Findings
- Throughput: 9 store apps and 2 web products listed within about 11 months of the first website commit (5 Dec 2025 to 3 Nov 2026), apparently by a single committer — [lib/apps.ts](https://github.com/mangolabsbr/mango-website/blob/main/lib/apps.ts); [commits p.2](https://github.com/mangolabsbr/mango-website/commits/main?after=e417285a643603ab1ddec7dd396e787dce1c3dac+34)
- Maintenance signals: Xchanger kept receiving features after launch (crypto rates; rate alerts announced in a Google Play snippet dated 6 Jun 2026; version 1.0.4), and its privacy/terms were updated on 12 Apr 2026 — [Google Play](https://play.google.com/store/apps/details?id=com.mangolabs.xchanger&hl=en_US); [mwm.ai](https://mwm.ai/apps/currency-converter-xchanger/6757408534); [commits p.2](https://github.com/mangolabsbr/mango-website/commits/main?after=e417285a643603ab1ddec7dd396e787dce1c3dac+34)
- Traction signal: the flagship still lacked enough US ratings to show an average — [App Store](https://apps.apple.com/us/app/currency-converter-xchanger/id6757408534)
- Pricing signal: $1.99/month and $14.99/year for Xchanger versus $6.99-9.99/month and $49.99-79.99/year charged by route-planner competitors, one of which shows 2,271 reviews at 4.8 — [App Store](https://apps.apple.com/us/app/currency-converter-xchanger/id6757408534); [Adapty paywall library](https://adapty.io/paywall-library/route-planner-delivery-myway/); [App Store, inRoute](https://apps.apple.com/app/id703796787)
- Diversification signal: newest launches are a B2B SaaS with Paddle billing and 30-day trial, and a paid API with a free tier — [Menoodo launch article](https://github.com/mangolabsbr/mango-website/blob/main/content/articles/menoodo-digital-menus-for-restaurants/en.mdx); [Xchanger API article](https://github.com/mangolabsbr/mango-website/blob/main/content/articles/best-currency-and-crypto-exchange-rate-apis/en.mdx)
- Contrast case: a marketing-led operator took a simple novelty app (Fontmaker, weekly subscription) to the top of the App Store through creator campaigns, with the app itself built by a third party — [TechCrunch](https://techcrunch.com/2021/09/01/how-a-vungle-owned-mobile-marketer-sent-fontmaker-to-the-top-of-the-app-store/)

### Inferences
- Worth copying (process): one cross-platform stack (Expo/React Native) with a fixed kit (RevenueCat, Sentry, product analytics with session replay, OTA updates); legal/landing page templates per app; localisation into 13-20 languages from day one; local-first/no-account design that removes backend cost and simplifies privacy labels; extracting reusable modules (game services, rates backend) and turning internal infrastructure into sellable products (API); AI coding/content tooling to keep a solo studio's output high.
- Worth avoiding (go-to-market): entering the most saturated generic categories without a differentiated wedge or a distribution channel; relying on store search alone; pricing subscriptions at $1.99/month when the audience that pays (e.g. delivery drivers) tolerates $7-10/month; shipping AI features with per-use cost in a free app; launching five unmonetised games; spreading effort across 11 products before any one shows traction; leaving template placeholders in legal texts.
- What looks strongest in the portfolio: SunRouter (professional users, recurring job-to-be-done, competitors prove willingness to pay at 4-5x Mango's Xchanger price) and Menoodo (B2B, $12-29/month, outside app-store fees). What looks weakest or at risk of abandonment: Proportion (Android-only, no monetisation), the SunRouter Android listing if it has indeed not been updated since March 2026, and Splitte (free with AI costs).
- The gap between Candidates A and B illustrates the main lesson for a would-be profitable publisher: building is the cheap part; the profitable "Mango Labs" was the one that owned a distribution engine (creator marketing) and paired it with aggressive weekly-subscription monetisation, while the technically productive indie studio shows no revenue evidence after ~10 months.
- For someone planning a launch: validate one niche with real willingness to pay, pick one acquisition channel before building, set price by competitor benchmarks rather than by modesty, and only then replicate the factory.

### Gaps
- No revenue, download, retention or conversion data exists in these notes for Mango Labs Ltda, so "what works" cannot be evidenced with outcomes; the assessments above are inferences from public signals.
- The founder's own view (goals, whether the studio is a side project, whether client services fund it) is unknown; an interview with the friend would resolve most gaps in this profile, including real installs, revenue per app and which apps are being discontinued.
- The network restrictions of this session mean the store pages should be re-checked directly (ratings, IAP lists, update dates, rankings) before publishing any firm claim about traction.
