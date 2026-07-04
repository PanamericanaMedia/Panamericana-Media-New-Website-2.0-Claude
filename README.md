# Panamericana Media Website — Launch Package

This is the new panamericana.media site, built on the same custom template
and design system as videocolorado.com so both brands share visual identity,
infrastructure, and code patterns. This README documents what's here, what
decisions were made, and what's still needed before going live.

## Revision log — Business track expansion

A second pass strengthened the business/brand pillar, which was thin in the
first version. Changes:

**Homepage.** Hero copy and core-service intro now explicitly mention
businesses alongside government and nonprofits. A new "Card 3" reframes
from "Trusted by Government & Community" to "A Bridge, Not a Gatekeeper" —
deliberately phrased so the subject of the sentence is the *gap businesses
have*, not anything implied about the Latino community itself. A new **Market
Opportunity stat section** sits right after the core services, with sourced
figures: U.S. Latino purchasing power at $4.1T (2025, Latino Donor
Collaborative) and Colorado's Latino population at 1.3M / ~20% of the state
(Pew Research / Colorado Public Radio, Nov. 2025). A new trust-us row adds
two cards: real cross-industry business experience, and real reach into
Spanish-language radio/TV/newspaper media (via your Conecta Colorado
relationship — see note below). The client swiper now includes Alpine Bank,
Westword, and Colorado Vizion alongside the government/nonprofit names.

**Services page.** The Business & Brands track was rebuilt from two thin
accordion items into four: Branded Content & Strategy, Event Coverage &
Media Partnerships, Spanish-Language Media Placement (new — this is your
distribution advantage, not just content creation), and the existing
hand-off to Video Colorado for full production. The section intro now
states the market data directly and names the range of industries you've
actually served (real estate, banking, hospitality, food brands, media,
construction, education).

**Our Work page.** Four new business case studies added after the existing
six government/nonprofit ones, under a "Business & Brand Work" divider:

- **Westword** — framed as a multi-year media partnership (Tacolandia, Out
  to Brunch, Westword Feast), which is a stronger story than treating each
  event as a separate one-off.
- **Alpine Bank — Hispanic Heritage Month 2024** — framed accurately as a
  multi-partner collaboration: produced by Panamericana Media, in
  partnership with Conecta Colorado, sponsored by Alpine Bank. Per your
  instruction, Conecta Colorado is referenced as a partner network ("a
  Spanish-language media network we work closely with") without disclosing
  your ownership of it.
- **Real estate cluster** — Colorado Vizion (bilingual branding video), Tu
  Realtor / Alfredo Salcedo (social + branding video, seminar marketing),
  Legacy Home / Megastar (headshots, social content).
- **Food, beverage & hospitality cluster** — Latin Supper Club / Hispanic
  Restaurant Association (podcast + event coverage), Mi Abuelo Organic
  Chile (brand storytelling).

A short line below these acknowledges the smaller-scope work too —
construction company branding videos and school training videos — framed
as proof the strategy-first approach scales down, without giving these the
same case-study weight as the larger relationships, per your call.

**Clients page.** Replaced the thin "Media & Other Collaborations" section
(which only had Westword) with a full "Business & Brand" sector group:
Westword, Alpine Bank, Colorado Vizion, Tu Realtor, Legacy Home, Latin
Supper Club, Mi Abuelo Organic Chile, and Conecta Colorado (listed as a
partner, not a client, since you own it — no public ownership disclosure).

**Language note on the "bridge" framing.** Per your concern about sounding
inclusive rather than extractive: the copy is deliberately built so
Panamericana Media is the bridge connecting two directions, not a vendor
granting businesses access to a market. The recurring construction is "help
[X] connect with Y authentically" paired with "without losing trust" — the
deficiency named is always on the institution/business side (no real way
to reach this audience) rather than anything about the audience itself.
"Anglo" is avoided throughout in favor of "mainstream" or no qualifier at
all. All population/purchasing-power statistics are cited with source and
date directly beneath the stat callout on the homepage.

## What's in this folder

```
index.html              Home
about.html               Our Roots (merged with The Panamericana Way)
services.html             Story + Strategy (organized by client type)
our-work.html            Crafted for Impact — 6 real case studies
clients.html             In Good Company — client list by sector
video-colorado.html      Bridge page explaining the two-brand structure
contact.html             Let's Create — contact form + FAQ
privacy-policy.html      PLACEHOLDER — see below
terms-conditions.html    PLACEHOLDER — see below
404.html                 Not found page
robots.txt
sitemap.xml
assets/                  Shared CSS/JS/fonts from the Video Colorado template,
                          plus Panamericana Media logos and a new pm-custom.css
                          for logo sizing and a few PM-specific components
```

## Navigation structure (locked in from our conversation)

Brand-voice labels in the nav, SEO-friendly URLs underneath, exactly as
agreed:

| Nav label (brand voice) | URL |
|---|---|
| Home | `/` |
| Our Roots | `/about.html` |
| Story + Strategy | `/services.html` |
| Crafted for Impact | `/our-work.html` |
| In Good Company | `/clients.html` |
| Video Colorado | `/video-colorado.html` |
| Let's Create | `/contact.html` |

## Key positioning decisions baked into the copy

- **Lead message, site-wide:** "We help organizations identify the
  communication gaps and challenges keeping them from truly connecting with
  their audiences" — this is now the homepage hero subhead and reappears as
  the throughline on About and Services. This was the sharper pitch language
  you said you've been using lately, and it's now the spine of the site.
- **Bicultural, not just bilingual** is stated explicitly multiple times
  (homepage core service cards, About, Services) rather than left implicit.
  The site doesn't carry a Spanish-language version — per our decision, the
  bilingual/bicultural positioning is communicated through the work itself
  (case studies, the two-version Aurora video) rather than a translated UI.
- **About page** merges "Our Roots" and "The Panamericana Way" per your
  call. Structure: organizational positioning → brief founder story (2–3
  sentences, not a full bio) → studio/collective model explanation → the
  four Panamericana Way principles as a visual block → CTA. No team roster
  page, since you confirmed there's no standing full-time team right now —
  the "lean, intentional studio" framing replaces it as a strength, not a
  gap.
- **Video Colorado relationship** is explicit and reciprocal. This site
  sends production-focused inquiries out to videocolorado.com (homepage
  bridge section, Services page accordion, dedicated `/video-colorado.html`
  page). The Video Colorado template already had a matching bridge section
  pointing back to panamericana.media — that link was already live in the
  template you shared, so the two sites now form a closed loop.

## Case studies (`our-work.html`)

Six case studies, in the priority order we agreed on, built from the details
you provided:

1. **City of Aurora — Office of International & Immigrant Affairs**
   (flagship). Built as two phases: the strategy consulting engagement, and
   the IRA Canopy Project, which is written in **present tense / "in
   progress"** per your note that the final video isn't done yet. It
   explicitly calls out that the bilingual video is two distinct versions
   with different creative approaches per language, not a translated
   script — this is your strongest differentiation proof point and it's
   surfaced prominently.
2. **Denver Mayor's Office** — 2025 Design Awards opening video.
3. **Juntos Community** — anniversary video, Run Club story, ongoing
   strategic storytelling support.
4. **Brothers Redevelopment** — documentary client stories, fundraising
   video, photography.
5. **Scholars Unlimited** — strategy consulting, gala video, LinkedIn
   content strategy.
6. **Latino Leadership Institute** — gala statement video.

I did **not** invent metrics, view counts, or fundraising totals for any of
these — none were provided, so none are claimed. If you get real numbers
later (funds raised at a gala, video view counts, etc.), those should be
added; they'll materially strengthen these case studies.

## Clients page (`clients.html`)

Grouped by sector (Government & Public Sector / Nonprofits & Community
Organizations / Media & Other) rather than the original site's blurred
auto-scrolling carousel. The six clients with full case studies link
through to `our-work.html`. Everyone else from your original brief
(Mountain Dreamers, Jefferson Center, El Grupo Vida, Conecta Colorado,
Westword, CDOT, DOTI) is listed as a name only, since you didn't provide
project details for those — easy to upgrade to full case studies later
using the same pattern as the six built ones.

These are currently **text-based cards, not logo images** — same honest
approach the Video Colorado README used for its client list, since I don't
have actual logo files for these organizations. Swap in real logos when
available; the `.client-logo-card` CSS class in `pm-custom.css` is built to
hold either text or an `<img>`.

## Founder story (`about.html`)

Per your call on weight and sequencing: it's two sentences, framed as
"founded by a first-generation Latino entrepreneur," used as a proof point
for the communication-gap thesis rather than a standalone biography. No
name is used in the copy — if you want it named, that's a one-line edit in
`about.html`.

## What's still placeholder and needs your input before launch

**Real photography and video.** Every image on this site is still a stock
dummy image from the template (`dummy-img-*.jpg`), same as the Video
Colorado site's known gap. This is the single biggest thing standing
between this site and feeling real — case study sections especially need
actual photos/stills from the Aurora, Juntos, Brothers Redevelopment, etc.
projects.

**Privacy Policy and Terms & Conditions.** Both pages are flagged
placeholders. Your live Wix site already has published versions of both at
`panamericana.media/privacy-policy` and `/terms-conditions` — those should
be reviewed and carried over, updated for the new contact form fields
(phone, organization, project type dropdown) and newsletter signup that
didn't exist on the old site.

**PHP hosting required.** Same as Video Colorado: the contact and
newsletter forms POST to `assets/php/submit-contact.php` and
`submit-newsletter.php`, which need PHP hosting (standard GoDaddy hosting
works; static hosts like Netlify/GitHub Pages without serverless functions
won't run them). Both files currently send to `info@panamericana.media` —
confirm that's the right inbox before launch.

**Domain.** `robots.txt` and `sitemap.xml` assume `panamericana.media` —
update if anything differs once DNS is pointed.

**Logo file format.** The navbar currently uses
`Panamericana_Media_Logo_Crop.png`, which has a white background — this
works fine against the site's dark navbar bg in testing, but a transparent-
background version of the same logo (if you have one) would render more
cleanly. Worth checking once it's live.

**Favicon source.** The favicon uses the orange/black grid "PM" mark
(`FavIcon_Mailchimp.png` from your project files), resized to 32×32 and
180×180. If that file was meant as a Mailchimp-specific asset rather than
the general brand mark, let me know and I'll swap in the right source file.

## Design system notes

Everything reuses `assets/css/main.css` and `assets/css/responsive.css`
unchanged from the Video Colorado template, so both sites stay visually
consistent and any future template-level fix benefits both. PM-specific
additions live entirely in `assets/css/pm-custom.css`: navbar logo image
sizing (Video Colorado uses a text wordmark, Panamericana Media uses an
actual logo file, so this needed separate handling), case study layout
components, the client logo grid, and a few small list/chip styles used on
About and Services. Brand colors, fonts, and spacing tokens are untouched —
`#F96500` orange, black/white, Anton + Inter — matching the brand manual
exactly.
