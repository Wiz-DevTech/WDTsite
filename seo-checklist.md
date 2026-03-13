# WizDevTech — SEO Launch Checklist
Complete these steps after uploading to Cloudflare Pages.

---

## ① Google Analytics (required — 10 min)

1. Go to https://analytics.google.com
2. Create account → Property → "Web" data stream → enter `wizdevtech.com`
3. Copy your **Measurement ID** (format: `G-XXXXXXXXXX`)
4. In all 4 HTML files, replace `GA_MEASUREMENT_ID` with your ID:
   - index.html
   - careers.html
   - sales.html
   - policies.html
5. Re-upload the updated files to Cloudflare Pages

---

## ② Google Search Console (required — 15 min)

1. Go to https://search.google.com/search-console
2. Add property → URL prefix → `https://wizdevtech.com`
3. Verify via Google Analytics (instant if GA is already set up)
4. Submit sitemap: `https://wizdevtech.com/sitemap.xml`
5. Request indexing for each page:
   - https://wizdevtech.com/
   - https://wizdevtech.com/sales.html
   - https://wizdevtech.com/careers.html
   - https://wizdevtech.com/policies.html

---

## ③ Google Business Profile (optional but powerful — 20 min)

1. Go to https://business.google.com
2. Create profile for WizDevTech
3. Category: "Software Company" or "Information Technology Company"
4. Add website: wizdevtech.com
5. Add services matching your NAICS: programming, systems design, data processing
6. Verification: phone or postcard

---

## ④ Bing Webmaster Tools (5 min)

1. Go to https://www.bing.com/webmasters
2. Add site → `https://wizdevtech.com`
3. Import from Google Search Console (one click if GSC is set up)
4. Bing also powers DuckDuckGo and Yahoo indexing

---

## ⑤ Schema / Structured Data Validation

Test that Google reads your schema correctly:
- https://search.google.com/test/rich-results
- Paste each page URL and verify: Organization, Service, FAQ, JobPosting

---

## ⑥ OG Image (social sharing preview — 30 min)

Create a 1200×630px image named `og-image.png` and upload to your WDTsite folder.
All 4 pages reference `/og-image.png` for Twitter/LinkedIn link previews.
Suggested content: WizDevTech logo + "Embedded Execution" tagline on cream background.

Test previews at:
- https://www.opengraph.xyz — paste your URL
- https://cards-dev.twitter.com/validator — Twitter preview

---

## ⑦ Cloudflare Settings (in your dashboard)

- Enable **Always Use HTTPS**
- Enable **Auto Minify** → HTML, CSS, JS
- Enable **Brotli** compression
- Set SSL/TLS to **Full (Strict)**
- Enable **Early Hints** (speeds up font/CSS loading)

---

## ⑧ Directory Listings (ongoing — builds domain authority)

Submit to these free directories:
- https://clutch.co — IT services directory (high domain authority)
- https://www.sortlist.com — digital services marketplace
- https://www.goodfirms.co — software/IT companies
- https://www.crunchbase.com — company profile
- https://sam.gov — federal procurement (NAICS 541511 primary)
- https://www.dnb.com — confirm DUNS 144936954 profile is complete

---

## ⑨ Keywords to Target (priority order)

**High intent (people ready to buy):**
- "finish half-built software"
- "repair broken workflow"
- "stalled project rescue"
- "embedded execution services"
- "fixed scope IT engagement"

**Medium intent (research phase):**
- "fractional ops services"
- "productized IT services"
- "systems stabilization consultant"
- "data migration services small business"
- "automation repair services"

**Long tail (low competition, high conversion):**
- "who can finish my half-built app"
- "IT team left project unfinished help"
- "broken Zapier workflow fix"
- "stalled Notion setup completion"
- "data cleanup and migration service"

---

## ⑩ Monthly SEO Tasks

- Update `<lastmod>` dates in sitemap.xml when pages change
- Monitor Search Console for crawl errors weekly
- Check GA4 for top landing pages and conversion paths
- Request re-indexing in Search Console after any significant content update

