# Intelligence Notes & Strategic Recommendations

## Systemic Finding — March 2026

### The Core Problem

**80%+ of web design orders on mainstream freelance platforms (Upwork, PeoplePerHour,
Freelancer.com) explicitly require WordPress, Shopify, Squarespace, or Wix.**

The team delivers vanilla HTML/CSS/JS static sites. This is not a search quality problem.
It is a positioning and channel mismatch. No amount of additional searching on these
platforms will change the ratio.

After reviewing 40+ listings across 11 platforms, only 7 (17.5%) were technically
compatible with the team's output. Of those 7, only 3 were strong unqualified recommends.

---

## Competitive Advantages the Team Has (That Most Clients Don't Know to Ask For)

These are real advantages the team's static HTML/CSS/JS output has over WordPress/Shopify:

| Advantage | Proof Point |
|-----------|-------------|
| Google-indexable immediately | IBT site replaced a JS-injected SPA that was invisible to search bots |
| Faster load times | No plugin overhead, no database queries, pure static files |
| No hosting cost inflation | Runs on Surge.sh, Netlify, Vercel, GitHub Pages — often free |
| No maintenance overhead | No WordPress updates, no plugin conflicts, no hack surface |
| Live preview in hours | DEPLOYER ships to Surge.sh within the same day |
| Custom design system | Not a template — built from scratch per client |
| SEO-optimized by default | Semantic HTML, meta tags, alt text, structured headings |

**The pitch:** Clients who've been burned by slow WordPress sites, plugin bloat, or
JS-injected site builders (Wix, Lovable, Squarespace) are the natural audience.

---

## High-Priority Client Profiles to Target

### Profile 1 — Lovable / Wix / Bubble Migration Clients
**Signal:** Has an existing AI-generated or no-code site that's slow, ugly, or invisible to Google.
**Why they're ideal:** They already have content. SCOUT can analyze the existing site.
BUILDER rebuilds it properly. The pitch is concrete: "Your current site is invisible to
Google because it's JS-injected. Here's what it looks like rebuilt properly."
**Where to find them:** Upwork ("Convert Lovable to HTML" type queries), Reddit r/webdev

### Profile 2 — Service Businesses with No Website
**Signal:** Construction companies, contractors, clinics, law offices, restaurants — no website or a terrible one.
**Why they're ideal:** No CMS preference. They just want to exist online.
SCOUT researches the business, BUILDER builds a professional 5-page site.
**Where to find them:** Upwork (Frontier Groundworks is the model), local business directories

### Profile 3 — SaaS / Startup Marketing Sites
**Signal:** "I need a landing page for my app" or "our marketing site looks outdated"
**Why they're ideal:** Tech-adjacent clients understand static sites and appreciate
performance. Often willing to pay more. No CMS expectations.
**Where to find them:** Upwork, Hacker News "Who is Hiring?" threads, Twitter/X #buildinpublic

### Profile 4 — B2B Companies with Invisible Websites
**Signal:** Company has a website but it's a JS SPA or outdated HTML — not ranking on Google.
**Why they're ideal:** SCOUT can identify the problem precisely. The pitch has immediate
business impact: "Your site isn't indexed. Here's what it looks like fixed."
**Where to find them:** Proactive outreach (see below)

---

## Channel Strategy Recommendations

### Continue Using (High Value)
- **Upwork** — primary platform, best public indexing of listings
- **PeoplePerHour** — secondary, some listings accessible without auth

### Add to Next Cycle
- **Hacker News "Ask HN: Freelancer? Seeking Freelancer?" threads** — Monthly thread,
  tech-literate clients, high static-site acceptance rate
- **Hacker News "Who is hiring?" threads** — Less relevant but surfaces startup needs
- **Product Hunt "need a landing page" searches** — Founders often post in comments

### Requires Account Access
- **Freelancer.com** — Budget data locked behind auth. All Freelancer leads are currently
  "Honorable Mentions" only. An active account unlocks 20+ additional listings per cycle.
- **Reddit r/forhire direct browsing** — Real-time posts not indexed. Browse directly and
  filter by [Hiring] + "website" / "landing page" keywords.

### The Highest-ROI Untapped Channel: Proactive Outreach

Instead of bidding on posted orders (reactive), the team can originate demand:

**Method:**
1. SCOUT identifies businesses with broken/invisible/ugly websites (search for niche + "website" in Google → find ugly sites on page 2+)
2. BUILDER generates a quick preview mock (a few hours)
3. Reach out with: "I redesigned your website — here's a live preview: [surge.sh URL]. Want to talk?"

**Why this works:**
- Zero competition (no other bidders)
- Client sees proof before paying
- Directly demonstrates the team's value proposition
- Targets the exact segment (businesses that need help but haven't posted a job)

**Target niches for proactive outreach:**
- Local construction / contracting companies
- Dental / medical practices
- Law firms with outdated sites
- Small B2B distributors / importers (proven by IBT project)
- Independent restaurants with Flash-era websites

---

## Next Cycle Priorities

1. Run proactive outreach on 2–3 local service businesses (construction, dental, legal)
2. Set up Reddit r/forhire direct monitoring (bookmark + daily check)
3. Open Freelancer.com account to unlock budget data on 8 unverified listings
4. Add Hacker News Freelancer thread search to platform coverage
5. Search specifically for "Lovable to HTML" / "Wix to HTML" / "SPA to static" conversion jobs
6. Consider writing a short post on r/webdev or r/forhire offering the "JS SPA → SEO-clean static site" service

---

## Reference: The IBT Project (Proof of Capability)

The team's established proof-of-work is the IBT International Brands Trading website:

- **Company:** B2B food distributor, 37 employees, 35M PLN revenue, Warsaw + Mannheim
- **Problem:** Existing site was a JS SPA — completely invisible to Google search bots
- **Delivered:** 7-page static site (HTML/CSS/JS), 1,362-line CSS design system, 10 JS modules
- **Pages:** Homepage, interactive product catalog, two audience landing pages (brands + retailers), about, news, contact
- **Time:** ~1 day for BUILDER to complete full build
- **Live URL:** ibt-preview.surge.sh (deployed Feb 28, 2026)
- **Key feature:** All content rendered in HTML — Google indexes every page and every product

This is the template to reference when pitching clients who have a JS-only or CMS-bloated site.
