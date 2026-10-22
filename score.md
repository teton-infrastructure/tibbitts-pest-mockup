# Website Score: Tibbitts Pest Services (tibbittspestservices.com)

Audited: Oct 22, 2026 (MDT). Live pages fetched with curl and screenshotted with headless Chrome (Playwright) at 1280px and 390px.

> **Location verified: Idaho Falls, Idaho.** The site says "Born and raised in Idaho Falls" and "Serving Idaho Falls and surrounding areas", and its Areas page lists **Idaho Falls, Rigby, Ammon, Shelley, Iona and Ucon**. Google-derived directory listings (exa.ai, pestcontrolbusinesses.com, Birdeye, BestProsInTown, HomeSpotHQ) all place the business in Idaho Falls, ID 83401 with the same phone, (208) 360-7941.

**Hosting / platform:** **Wix.** The `<meta name="generator">` tag reads "Wix.com Website Builder". DNS: nameservers `ns10/ns11.wixdns.net`, `www` is a CNAME to `cdn3.wixdns.net`, the apex resolves to Wix IPs (185.230.63.x), and responses carry `x-wix-request-id` behind Wix's Cloudflare edge (`server: cloudflare`). No MX records, so the business email is a Gmail address.

## Overall: **49 / 100**: honest, useful content, but it hides the phone number and the 62 five-star reviews

| Category | Score | Notes |
|---|---|---|
| Mobile & tap-to-call | 7 / 15 | Wix serves a separate mobile layout locked to `width=320` (`<meta name="viewport" content="width=320, user-scalable=yes">`), so everything is scaled down on a modern phone. There is **one** `tel:` link, and it sits in the footer at the very bottom of the page. The hero has only "GET A QUOTE", which goes to a form on another page. `format-detection: telephone=no` is set, so iPhones won't auto-link the number either. A floating Wix "Let's Chat!" widget covers part of the content. |
| Clear headline & offer | 9 / 15 | The H1 is the generic "Premium Pest Control Services" with no city and no pests named. The supporting lines are good ("10+ years of experience", "Residential & Commercial", "Serving Idaho Falls and surrounding areas"). The strongest selling points are buried on subpages: **"Starting as low as $95 per treatment"** and "4 total treatments from Spring through Fall" are only on /services-3, and **"No contracts or commitments!"** only appears in the contact page's meta description. |
| Trust (reviews, licensing) | 5 / 15 | The Google Business Profile shows **5.0 stars from 62 reviews** (per Google-derived directory listings), but there are **zero reviews, stars or testimonials on the site**. No licensing or insurance is mentioned. Positives: a real owner story (Logan Tibbitts, 10+ years) and a clear guarantee (free service if pests show up between treatments). |
| Speed / tech | 6 / 10 | The edge is fast (TTFB about 0.16 s), but the home page is about **1.3 MB over ~140 requests, ~96 of them JavaScript**, with about 800 KB of HTML (870 KB for mobile) and 62 inline `<script>` tags. That's heavy for a five-section page. |
| SEO / local basics (title, meta, schema, NAP) | 7 / 15 | Good: the title is "Pest Control In Idaho Falls \| Tibbitts Pest Services" and the meta description is solid. Bad: the only schema is `{"@type":"WebSite","name":"Tibbitts"}`, with **no LocalBusiness/PestControl schema**. There's no `og:image` (link previews show no picture), `og:site_name` is just "Tibbitts", and there are no towns on the home page. The sitemap lists **11 leftover Wix template pages** (`/product-page/i-m-a-product`, `-1` … `-11`), plus a `copy-of-privacy-policy` page. URLs are template slugs like `/services-3` and `/areas-we-service-1`. The footer social bar in the code links to **Wix's own** Facebook, Instagram and LinkedIn (`facebook.com/wix`). |
| Readable by Google AI / ChatGPT | 4 / 10 | Text is server-rendered, which helps. But there's no structured data saying what the business is, where it serves, its phone or its rating. The phone number is marked up as an `<h2>`. There's no FAQ, and price, service area and contract terms are spread across separate pages, so an AI answer to "pest control in Ammon, how much?" has little it can quote. |
| Design | 6 / 10 | A consistent brand (black + green spider logo) and clean icons. However, body text is set in bright green `#0ABF67` on white, which has a **contrast ratio of 2.4:1** (WCAG needs 4.5:1), so it's hard to read in sunlight. The services box is a heavy black-bordered block with small text. |
| Calls to action | 5 / 10 | There are two "GET A QUOTE" buttons and a chat widget, but no "Call" button anywhere above the footer. The quote form lives on a separate page. |
| **Total** | **49 / 100** | |

### Top 5 problems (with evidence)
1. **No tap-to-call where it counts.** The only `tel:` link is in the footer (`<a href="tel:(208)360-7941">`, inside an `<h2>`), and phone auto-linking is disabled with `format-detection: telephone=no`. The hero has no call button.
2. **62 five-star Google reviews, none on the site.** No stars, quotes or Google link anywhere.
3. **No LocalBusiness/PestControl schema and no og:image.** The only JSON-LD is `WebSite` named "Tibbitts", so Google and AI tools get no structured phone, area, rating or services.
4. **The best offer is buried.** "$95 per treatment", "4 treatments Spring–Fall", "free re-treat between visits" and "no contracts" never appear together, and the price only shows on a subpage.
5. **Dated mobile build and template leftovers.** The mobile layout is fixed at 320px, body text is low-contrast green (2.4:1), the sitemap contains 11 "I'm a product" Wix placeholder pages, and the social links point to Wix's own accounts.

### What's good (honestly)
- Clear list of what each treatment includes (inspection, foundation barrier, window wells, wasp nests, spider webs, lawn pests) plus add-ons (voles/mice, mosquitoes).
- A real guarantee: "If you see any pests between treatments, we will take care of it free of charge."
- Useful local content: a Bug Guide (hobo spiders, pavement ants) and eight Helpful Tips.
- HTTPS, a good `<title>` and meta description, and the city in the title.

## Business facts (from tibbittspestservices.com unless noted)
- **Name:** Tibbitts Pest Services (Birdeye also shows an older listing name, "Tibbitts Lawn & Pest, LLC"; one reviewer says Logan used to do lawn care as well)
- **Owner:** Logan Tibbitts. Locally owned and operated, born and raised in Idaho Falls, and "worked in the pest control industry for over 10 years".
- **Phone:** 208-360-7941
- **Email:** tibbittspestservices@gmail.com
- **Service area:** Idaho Falls, Rigby, Ammon, Shelley, Iona, Ucon (Idaho)
- **Customers:** residential and commercial
- **Plan / price:** 4 total treatments from spring through fall, "Starting as low as $95 per treatment"
- **Treatment includes:** inspection, foundation barrier, window well treatment, wasp nest removal, spider web removal, lawn pests (lawn spiders, gnats, other insects)
- **Add-ons:** vole & mice control, mosquito control
- **Guarantee:** free service if pests appear between treatments
- **Quotes:** quick quote using satellite imaging; "No contracts or commitments!" (contact page meta description)
- **Common pests listed:** wasps, ants, earwigs, box elder bugs, centipedes, crickets, springtails, snails, slugs, hobo/black widow/wolf/black lawn/jumping/house/cat-faced spiders, daddy long legs, scorpions, voles, mice, mosquitoes, fleas, ticks, gnats, grasshoppers, billbugs, aphids
- **Google rating:** 5.0 from 62 reviews per exa.ai and pestcontrolbusinesses.com (Google-derived). Birdeye shows 4.9 / 62, HomeSpotHQ shows 5.0 / 52 (older snapshot). I could not load Google Maps directly from the box.
- **Address in directories:** 4138 Orwell Ave, Idaho Falls, ID 83401. This is **not on their website** and looks residential, so I left the street out of the mock-up.

### Not verified / left out
- **Licensing / insurance:** not stated on the site. The ISDA applicator lookup didn't return a result through a scripted search. Ask Logan for his ISDA license number to add as a trust badge.
- **Hours:** directories conflict (Mon–Sat 9–7 on Birdeye vs. 9–10 PM on exa/BestProsInTown), so they're omitted.
- **Founding year:** only "10+ years" in the industry; no business start date found.
- **Social profiles:** none found (the site's social links are Wix template defaults).
- **Bed bug service:** a directory quotes an old bed-bug line "from the company website", but the current site doesn't offer it, so it's left out.
