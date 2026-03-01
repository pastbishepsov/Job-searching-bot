# Search Strategy

## Platform Coverage

| # | Platform | Priority | Notes |
|---|----------|----------|-------|
| 1 | Upwork | PRIMARY | Google-indexed listings accessible publicly. Auth wall blocks full briefs on some posts. Best overall signal. |
| 2 | Freelancer.com | **PRIMARY** | **UPGRADED 2026-03-01**: Playwright + Google auth gives full descriptions, 54% qualifying hit rate. Budget amounts still hidden (Plus membership required). Scrape: /jobs/web-design/, /jobs/html5/, /jobs/css/, /jobs/landing-pages/ + keyword searches. |
| 3 | PeoplePerHour | SECONDARY | Many listings retrievable. Budgets often too low (£50–£150). High proposal counts on most open jobs. |
| 4 | Reddit r/forhire | TERTIARY | Ephemeral posts — not reliably indexed by search engines. Requires direct subreddit monitoring. |
| 5 | Reddit r/slavelabour | TERTIARY | Micro-tasks, lower budgets. Good for $40–$150 single-page work. Requires direct browsing. |
| 6 | Reddit r/webdev | TERTIARY | Occasional hiring threads. Low volume. |
| 7 | LinkedIn | TERTIARY | SMB job posts via hashtag search (#webdevelopment #freelance). Mostly employment not project orders. |
| 8 | Twitter/X | TERTIARY | Real-time "need a website" intent signals. Requires authenticated API for reliable search. |
| 9 | Dribbble Jobs | LOW | Full-time employment positions only. Not project orders. Skip. |
| 10 | Behance Jobs | LOW | Full-time employment positions only. Skip. |
| 11 | Telegram CIS | UNVERIFIED | веб заказы channels. Not accessible via public search. Requires channel membership. |

## Effective Search Queries (Upwork via Google)

### Primary high-yield queries:
```
site:upwork.com "website" "fixed price" posted 2026 web design
site:upwork.com "landing page" "fixed price" posted 2026
site:upwork.com "HTML" "CSS" website "fixed price" posted 2026
site:upwork.com "web design" "fixed price" "$[amount]" posted [month] 2026
```

### High-intent niche queries:
```
site:upwork.com "Convert Lovable" OR "Lovable to HTML" 2026
site:upwork.com "HTML website" OR "static website" "fixed price" 2026
site:upwork.com "from scratch" website "fixed price" 2026 design
site:upwork.com "no CMS" OR "custom coded" website 2026
```

### Business type queries (clients who rarely specify CMS):
```
site:upwork.com "construction company website" OR "contractor website" 2026
site:upwork.com "service company website" OR "local business website" 2026
site:upwork.com "portfolio website" "fixed price" posted 2026
```

### PeoplePerHour:
```
site:peopleperhour.com website "brand new" OR "new website" 2026
site:peopleperhour.com "landing page" 2026 budget open
```

### Reddit (direct browsing required):
```
reddit.com/r/forhire → filter by [Hiring] → search "website"
reddit.com/r/slavelabour → filter by [Hiring] → search "website" "landing page"
```

## What Doesn't Work (Tested)

- Reddit site: searches via Google → returns 0 results (Reddit not indexed at post level)
- WebFetch on Upwork URLs → 403 Forbidden
- WebFetch on Freelancer.com → returns CSS/font data only, no readable project content
- WebFetch on Reddit → blocked entirely
- Twitter/X real-time search → returns editorial content, not actual posts

## Authentication Requirements

To fully access these platforms, active accounts are needed:
- **Upwork** — full brief text, proposal counts, client history
- **Freelancer.com** — budget data, bid counts, project status
- **PeoplePerHour** — accessible without auth but limited detail
- **Reddit** — direct browsing, no API needed for reading

## Cadence Recommendation

- Run a full cycle every 48–72 hours (Upwork posts age quickly, competition builds fast)
- Immediately apply to any qualifying post under 24 hours old
- Posts over 7 days old on Upwork likely have 20+ proposals — still worth applying but less favorable
- Posts over 30 days old — verify still open before investing proposal time
