# PLACEHOLDERS — sourdough-sign demo (must resolve BEFORE commissioning)

Prospect: **Sourdough Sign Service LLC**, Wasilla, Alaska (Mat-Su Valley).
Live demo: https://mrjcarrazco.github.io/sourdough-sign-demo/
Repo: https://github.com/MrJCarrazco/sourdough-sign-demo

## Verified facts used on the page (do not change without a new source)

| Fact | Value | Source |
|---|---|---|
| Legal name | Sourdough Sign Service LLC | Alaska business registry (new registration) |
| Phone | 907-830-0301 | prospect record |
| Address | 8860 W Angel Dr, Wasilla, AK | prospect record |
| USDOT # | 8287021 | FMCSA / SAFER public carrier record |
| Operating status | ACTIVE | FMCSA / SAFER |
| Drivers | 4 | FMCSA / SAFER |
| Cargo classification | Construction | FMCSA / SAFER |
| Website | none exists | pitch angle — this demo IS the asset |

## Placeholders / unverified content ON the page

| # | Item | Current state on page | Action before live |
|---|---|---|---|
| 1 | **Service list (6 cards)** | Generic sign-industry menu: illuminated/channel letters, monument & post, vehicle & fleet graphics, banners/yard/event, interior+ADA+wayfinding, install/repair/service. Explicitly labelled as a PLACEHOLDER menu in a visible note under the grid. | Owner keeps / cuts / rewords each card |
| 2 | **Photo gallery (6 tiles)** | Empty dashed tiles reading `[ photo of your work here ]` with a sub-label (storefront sign, monument, vehicle lettering, install, banner, interior). No stock photos used. | Owner supplies 6 real job photos |
| 3 | **Business hours** | Three rows reading `[ your hours ]` — Mon–Fri / Sat / Sun | Owner supplies real hours |
| 4 | **ZIP code** | Shown as **99623** with a visible note "owner to confirm the correct Wasilla ZIP" | Confirm (Wasilla uses 99623 / 99629 / 99654) |
| 5 | **Map pin** | OSM embed of the Wasilla area with **NO marker**. Nominatim returned zero results for 8860 W Angel Dr, so no pin was invented. Visible note explains why. | Owner drops the pin, or replace map with a text service-area block |
| 6 | **Service area town list** | 9 suggested Mat-Su chips (Wasilla, Palmer, Big Lake, Houston, Meadow Lakes, Willow, Sutton, Talkeetna, Anchorage) with a PLACEHOLDER note | Owner trims to real coverage |
| 7 | **4-step process copy** | Site visit → design & quote → build → install & service. Labelled PLACEHOLDER; also flags that in-house permitting is NOT claimed. | Owner confirms, incl. whether they pull sign permits |
| 8 | **"Locally owned & operated"** | In hero pin line and trust band | Defensible (AK LLC at a Wasilla address) but owner should confirm the wording |
| 9 | **Headline / tagline copy** | "Your business, impossible to miss" + Alaska-weather durability angle | Owner's call — easy swap |
| 10 | **Quote form** | Disabled, fires an alert. Comment in source shows the one-line swap to `formsubmit.co/OWNER_EMAIL`. | Wire to owner's email on commission |
| 11 | **Logo / brand colors** | Text-only wordmark; amber-neon + aurora palette invented for the demo | Ask owner for logo + colors |
| 12 | **Insurance / bonding / license #** | NOT claimed. Trust-band footnote says these are "to be added by the owner". | Owner supplies if they want them shown |
| 13 | **`robots: noindex, nofollow`** | ON | Remove ONLY after commissioning + owner approval |

## Explicitly NOT on the page (anti-fabrication guardrails)

- No testimonials, no review quotes, no star ratings, no review counts.
- No years-in-business / "since 19xx" (company is brand new on the registry).
- No certifications, licenses, bonding or insurance claims.
- No client logos, no stock photography, no borrowed project photos.
- No owner/person name anywhere in the copy.
- No agency human byline. Only footer credit: "A Digital Consulting Studios demo".
- Claim that they do any specific service is hedged — the services block is openly a menu to choose from.

## Deploy gate

Deployed per the pre-approved demos pattern (same model as `master-auto-repair`).
GitHub Pages, public repo `MrJCarrazco/sourdough-sign-demo`, branch `main`, path `/`.
