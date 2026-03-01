# Team Capabilities

## The Three-Agent Pipeline

### SCOUT — Research & Intelligence

**Role:** Takes a target URL or company name and does deep research before the build begins.

**What it does:**
- Crawls the target website, LinkedIn, business registries (KRS, Aleo, BizRaport), industry directories
- Extracts company intelligence: legal structure, leadership, products, market position, financials
- Runs competitive analysis
- Identifies high-value "killer features" for the redesign
- Produces a structured briefing document + killer features document

**Tooling:** Playwright (for JS SPAs), WebSearch, WebFetch, public business registries

**Output:**
- `briefing.md` — comprehensive company + competitive intelligence
- `killer_features.md` — ranked feature recommendations with business case

---

### BUILDER — Website Construction

**Role:** Consumes SCOUT's briefing and builds a complete, production-ready static website.

**What it builds:**
- HTML5 (semantic, SEO-clean — no JS-dependent content)
- CSS (custom design system built from scratch per project — palette, typography, components)
- Vanilla JavaScript (progressive enhancement — all content visible without JS)
- Typically 5–10 pages per project

**Standard page types produced:**
- Homepage with animated hero, stats counters, social proof
- Product/service catalog with multi-dimensional JS filtering
- Audience-specific landing pages (e.g., B2B buyers vs. brand partners)
- About page with timeline, leadership, office locations
- News/blog feed
- Multi-step segmented contact/inquiry form

**JavaScript modules (standard set):**
- Sticky nav, mobile hamburger
- Count-up animations (IntersectionObserver-triggered)
- Scroll reveal with staggered delays
- Multi-dimensional filter chips with live count + URL params
- Multi-step form with branch logic, validation, Formspree submission
- Smooth scroll, active nav link detection
- Infinite ticker with pause-on-hover
- URL param pre-fill

**Design system standard:**
- CSS custom properties (colors, typography, spacing, radii, shadows)
- Mobile-first responsive (breakpoints: 1024px, 768px, 480px)
- Component library: nav, hero, ticker, grid cards, split CTA, stats, forms, timeline, filter bar

**Integrations:**
- Formspree (contact/inquiry form backend)
- Google Fonts (Sora + Inter standard; customizable per project)
- Surge.sh (preview deployment)
- i18n framework (Weglot-ready for multi-language)

**Output:**
- `/output/site/` — complete folder of HTML + CSS + JS files
- `handoff.md` — full technical handoff document
- `builder_notes.md` — running log of decisions per file

**Tech stack proof:** IBT International Brands Trading site — 7 pages, 1,362-line CSS design system, 10 JS modules, built in ~1 day.

---

### DEPLOYER — Deployment & Publication

**Role:** Takes BUILDER's `/output/site/` folder and publishes it live.

**What it does:**
- Runs pre-flight checklist (all pages present, links valid, no absolute paths, UTF-8 charset, no lorem ipsum)
- Installs Surge globally: `npm install --global surge`
- Deploys to Surge.sh subdomain
- Produces a live preview URL
- Creates `deploy_log.md` with checklist results and timestamps
- Can teardown on request

**Output:**
- Live URL on surge.sh (e.g., `clientname-preview.surge.sh`)
- `deploy_log.md`

**Turnaround:** Hours after BUILDER finishes.

---

## What the Team CAN Deliver ✅

| Deliverable | Notes |
|-------------|-------|
| Existing website redesigns | SCOUT researches existing site, BUILDER rebuilds it better |
| New websites from scratch | SCOUT researches the business, BUILDER builds |
| Landing pages | Single-page, high-conversion, responsive |
| SaaS marketing sites | Static marketing/product pages (not the app itself) |
| Portfolio / personal brand sites | Clean, fast, SEO-ready |
| B2B company brochure sites | Multi-page, dual-audience capable |
| Service business websites | Showcase + inquiry form |
| Static HTML sites replacing legacy CMS or SPA | Core strength — fixes SEO-invisible JS sites |
| Formspree-backed contact forms | No backend required |
| Multi-language sites | i18n framework built in, Weglot integration ready |
| Live preview URL on Surge.sh | Delivered as part of every project |

---

## What the Team CANNOT Deliver ❌

| Out of scope | Reason |
|-------------|--------|
| WordPress customization | No CMS work — team builds vanilla static |
| Shopify theme work | Platform-specific, not in toolchain |
| Webflow, Wix, Squarespace builds | Same — platform lock-in not supported |
| React / Vue / Angular apps | No JS framework — vanilla JS only |
| Server-side logic / APIs | No backend capability |
| Databases / authentication | Out of scope |
| E-commerce with cart / inventory / payments | Requires backend |
| Maintenance retainers | Build-and-handoff model only |
| Mobile apps | Not web |
| CMS admin panels | No backend |
| Complex integrations (Stripe, HubSpot, custom APIs) | No backend |

---

## Budget-to-Scope Reference

| Budget | Scope | Effort |
|--------|-------|--------|
| $40 – $150 | Single landing page or 1-pager | ~half day |
| $150 – $400 | 3–5 page small business site | 1–2 days |
| $400 – $800 | Full 5–7 page site with custom design | 2–3 days |
| $800 – $1,500 | Full 7–10 page site + animations + SEO | 3–5 days |
| $1,500 – $3,000 | Complex multi-page + extra iterations | 5–7 days |
