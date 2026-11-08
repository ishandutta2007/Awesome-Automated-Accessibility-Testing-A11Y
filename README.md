# Awesome Automated Accessibility Testing (A11Y)

A curated list of awesome automated digital accessibility testing platforms, dev tools, and frameworks to ensure WCAG, ADA, and Section 508 compliance.

---

## Sector Overview & Market Dynamics

The digital accessibility software and testing market is valued at approximately **$850 million to $930 million**, with the broader accessibility testing and remediation services ecosystem exceeding **$3.8 billion** and projected to surpass **$10 billion** by the early 2030s (expanding at a 7%–12% CAGR). The sector is **moderately fragmented**; while specialized pure-play platforms (such as Deque and Level Access) anchor enterprise governance alongside automated overlay providers, broad test-automation giants (like BrowserStack) and continuous dev-tool integrations ensure high competition across the software development lifecycle rather than a winner-take-all monopoly.

---

## SaaS Accessibility Platforms & Tools

The following table provides detailed pricing, free tier/trial limits, company size (valuation / revenue), and category for major SaaS accessibility solutions, sorted descending by company size / valuation:

| Platform | Category | Company Size (Valuation / Revenue) | Pricing (Starting Tier) | Free Tier / Trial Limits |
|---|---|---|---|---|
| **[BrowserStack Accessibility Testing](https://www.browserstack.com/)** | Cloud Testing & Scanning Suite | **$4B valuation** (~$230M ARR) | Starting at **$89/domain/month** (or bundled with Test Companion / Automate tiers from $29/mo) | **Free Trial:** Limited to 30 mins Live testing, 100 mins automated runs; Percy visual tester includes 5,000 free screenshots/month |
| **[Siteimprove](https://www.siteimprove.com/)** | Enterprise Digital Governance & QA | **$911M valuation** (acquired) / ~$100M ARR | Benchmark starting tier **~$15,000/year** (custom quote based on page count & modules) | **No full platform trial / permanent free tier.** Free single-page audit tool / extension limited strictly to 1 URL per manual scan |
| **[Evinced](https://www.evinced.com/)** | Enterprise CI/CD & Mobile A11Y | **$220M valuation** ($112M raised) / ~$34M ARR | Starting tier estimated at **$500–$2,000/month** (billed annually via custom enterprise quote) | **14-day Free Trial:** Site Scanner trial capped at 50,000 total URLs crawled/scanned and max 1,500 pages per scan (no credit card required) |
| **[Level Access](https://www.levelaccess.com/)** | Enterprise Compliance Platform | **>$100M ARR** (PE-backed by KKR & JMI) | Mid-market benchmark starting at **$75,000/year** (enterprise quote based on portfolio scope) | **No open free tier / free trial.** Access is demo-only; requires an enterprise contract |
| **[Deque Systems (axe DevTools)](https://www.deque.com/axe/devtools/)** | Developer Tooling & Scanning Platform | **~$40M–$100M revenue** (Privately held) | Pro browser extension starting at **$60/user/month** (or ~$45–$50/mo billed annually); Enterprise Monitor quote-based | **Free Forever Tier:** axe DevTools browser extension covers core automated checks (~57% of WCAG issues) on single pages. **14-day Free Trial** for Pro (IGT features, no credit card required) |
| **[UserWay](https://userway.org/)** *(acquired by Level Access)* | Accessibility Widget & Automation | **$98.7M acquisition valuation** (~$15M–$20M ARR) | Starting at **$490/year** (for sites up to 100K monthly page views) | **Free Forever Tier:** Basic client-side widget UI (contrast/text adjustments only; no automated AI fixes or legal compliance). **Free trial** available for Pro monitoring (capped at 50 pages) |
| **[accessiBe](https://accessibe.com/)** | AI Accessibility Widget & Scanning | **~$51M ARR** ($58M funding raised) | Starting at **$490/year** (Standard plan for sites under 1,000 pages) | **7-day Free Trial:** Full feature access for 1 domain (no credit card required). Includes free spot-check tool (accessScan) for single-page audit |
| **[Silktide](https://silktide.com/)** | Automated Web Governance & Scanning | **~$2.5M–$3M ARR** (Bootstrapped / Private) | Starting at **£5,000/year** (~$6,500/yr for up to 1,000 pages via UK G-Cloud rate card) | **No platform free trial.** Free standalone browser extension covers single-page manual WCAG checks; free homepage scan tool limited strictly to 1 homepage URL |
| **[Pope Tech](https://pope.tech/)** | Automated Scanning (WAVE Engine) | **~$800K–$1M ARR** (Bootstrapped / Private) | Team tier starting at **$25/month** (or Business Plus at $225/mo, Professional at $400/mo) | **Free Forever Tier:** Up to 25 pages/month for 1 website, 1 group, and 2 users with unlimited rescanning |
| **[Tenon.io](https://tenon.io/)** *(acquired by Level Access)* | API-first Accessibility Testing | **<$1M revenue** (acquired historical) | Starting at **$90/month** (priced on API scan request volumes) | **30-day Free Trial:** Includes limited initial API call credits for evaluation; historical single-page test console |

---

## Open-Source Frameworks & Developer Tools

| Project | What It Does | Stars / Adoption |
|---|---|---|
| **[AccessLint](https://github.com/accesslint)** | Continuous automated accessibility testing; monorepo providing CLI, Playwright, Storybook, and Vitest integrations. | Screenreaders repo (`VoiceOver.js`) has 183+ stars; active developer community |
| **[axe-core](https://github.com/dequelabs/axe-core)** | The accessibility engine for automated Web UI testing; powers Chrome DevTools, Lighthouse, and major automated test runners. | 6,500+ stars; industry-standard automated rules engine |
| **[pa11y](https://github.com/pa11y/pa11y)** | CLI and programmatic automated accessibility testing tool driven by HTML CodeSniffer and axe-core. | 4,200+ stars |
| **[lighthouse](https://github.com/GoogleChrome/lighthouse)** | Automated auditing tool for web quality, performance, and WCAG accessibility standards. | 28,000+ stars |
