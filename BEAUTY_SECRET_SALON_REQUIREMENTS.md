# Beauty Secret Salon --- Website Requirements Reference

> **Purpose:** Single source of truth for the AI coding agent building
> the Beauty Secret Salon website.
>
> **Project tier:** UGX 200,000 salon website.
>
> **Important:** This project is **Beauty Secret Salon**, not Levinah or
> any other salon project. Do not reuse another client's name, logo,
> address, contacts, copy, or branding.

------------------------------------------------------------------------

## 1. Business Identity

-   **Business name:** Beauty Secret Salon
-   **Business type:** Unisex hair and beauty salon
-   **Location:** Kisaasi--Kyanja Road, at the junction to Komamboga, opposite Prime Petrol Station, Kampala, Uganda
-   **Public map/listing reference:** 9HQV+J4X / 9HQV+J4V area,
    Kisaasi--Kyanja Rd, Kampala
-   **Verified public phone:** 0754 852 452
-   **Additional number visible in supplied salon artwork:** 0784 852
    452
-   **Public directory category:** Beauty Salon / Hair Salon

### Contact-data rule

Use **0754 852 452** as the primary public contact because it is both
present in supplied salon material and independently discoverable in a
current public directory.

The supplied promotional artwork also shows **0784 852 452**. Treat this
as a secondary number, but do not invent or replace contact details. If
WhatsApp ownership of either number is not confirmed, keep the WhatsApp
destination configurable in one central site-data/config location.

### Public-source verification

Google/web research located a Beauty Secret Salon listing on
Kisaasi--Kyanja Road, Kampala with phone **0754 852 452**. The public
directory result describes the location as:

`9HQV+J4X prime, 9HQV+J4V Opposite, Kisaasi - Kyanja Rd, Kampala, Uganda`

Source used during requirements preparation:
https://galego.cybo.com/UG/kasangati/sal%C3%B3ns-de-beleza?p=2

Do **not** copy information from unrelated businesses named "Beauty
Secret Salon" in other countries.

------------------------------------------------------------------------

## Client-confirmed business information

- **Official motto:** `Adding care to your beauty`
- **Confirmed directions:** `Kisaasi–Kyanja Road, at the junction to Komamboga, opposite Prime Petrol Station, Kampala, Uganda.`
- **Google-listed opening hours:** Monday–Sunday, 8:00 AM – 10:30 PM
- **Preferred website display:** `Open daily · 8:00 AM – 10:30 PM`
- **Service data priority:** Client-supplied services and prices take priority over service categories shown by Google.

These details are CLIENT-CONFIRMED and must not be replaced with guessed wording.

------------------------------------------------------------------------

## 2. Brand Direction

The site should visually follow the salon's existing physical branding
and supplied logo rather than introducing a new identity.

### Primary colors

-   **Salon Red:** `#E31B23`
-   **Deep Red:** `#B5121B`
-   **Black:** `#111111`
-   **Warm White:** `#FFF9F6`
-   **Soft Neutral:** `#F4F1EE`

### Usage

-   Red is the primary brand/accent color.
-   Black provides contrast for headings, navigation and premium-looking
    UI elements.
-   Warm white/soft neutral should dominate page backgrounds so the site
    does not become visually overwhelming.
-   Use red intentionally for CTAs, active states, highlights and small
    branded details.
-   Avoid introducing unrelated dominant colors such as purple, blue,
    berry/wine or green.

### Visual character

The website should feel: - modern; - clean; - lively; - welcoming; -
locally authentic; - professional without looking excessively luxurious.

The supplied salon interior uses strong **red, black and white**
elements. Preserve this character in the UI.

------------------------------------------------------------------------

## 3. Logo Requirements

The logo belongs to **Beauty Secret Salon**.

### Logo structure to preserve

The improved logo must preserve the identity and arrangement of the
original logo: - salon/barber tools at the top; - moustache element; -
arched composition; - the word **BEAUTY**; - the word **SALON positioned
below BEAUTY**; - lower scissor/tool-inspired curves; - no
woman/female-face icon; - no additional wording; - no unrelated symbols.

The redesign is an **appearance cleanup**, not a rebrand.

### Logo asset

Store/use the final logo from:

`assets/images/`

Recommended filename:

`assets/images/beauty-secret-logo.png`

If the existing project already uses another filename, the agent may
retain it rather than creating duplicate assets.

------------------------------------------------------------------------

## 4. Image Assets

All website imagery is stored under:

`assets/images/`

The agent must inspect the actual directory before wiring service cards.
Do not invent image paths.

### Image rules

-   Prefer the supplied/generated salon images over generic stock
    photography.
-   Service images should show Black Ugandan/East African clients where
    people are visible.
-   Service imagery should look like believable salon photography, not
    exaggerated AI advertising.
-   Maintain natural skin texture, realistic hair, realistic hands and
    ordinary salon equipment.
-   Salon interior backgrounds should reflect the supplied
    red/black/white Beauty Secret Salon environment.
-   Avoid excessively luxurious or obviously foreign-looking salon
    environments.
-   Use meaningful `alt` text.
-   Optimize images for web performance without visibly degrading them.
-   Use consistent aspect ratios within repeated card components.
-   Do not stretch images.

### Interior images

The project includes improved salon-interior visuals based on the
client's real premises. These can be used for: - hero/intro visual; -
About section; - gallery; - atmosphere/visit-us section.

Do not use all near-identical interior images on the same viewport.

------------------------------------------------------------------------

## 5. Services and Prices

**Currency:** Uganda Shillings (UGX).

Prices must be displayed clearly. Do not silently alter the client's
prices.

### Haircuts

  Service                  Price
  ----------------- ------------
  Men's Haircut       UGX 10,000
  Women's Haircut     UGX 15,000
  Kids Haircut         UGX 5,000

### Pedicure & Manicure

  Service                                                Price
  -------------------------------------- ---------------------
  Normal                                             UGX 10,000
  Foot Scrub                               UGX 20,000–25,000
  Gel Colors Only                                   UGX 20,000
  Gel Builder                                       UGX 35,000
  Artificial Nails + Gel Builder + Gel              UGX 70,000
  Artificial Nails + Normal Color                   UGX 25,000

### Hair Plaiting, Styling & Treatments

  Service                                       Price
  ----------------------------- ---------------------
  Wash & Blow Dry                          UGX 10,000
  Hair Ironing                             UGX 25,000
  Unplaiting                               UGX 10,000
  Natural Leave-in Treatments     UGX 30,000 / 25,000
  Other Leave-in Treatments                UGX 20,000
  Hair Steaming Treatments                 UGX 30,000
  Cornrows Plaiting                        UGX 20,000
  Cornrows with Braids                     UGX 30,000
  Natural Hair Styling                     UGX 20,000
  Kids Plaiting                            UGX 80,000
  Pencil Plaiting                          UGX 60,000
  Box Braids                               UGX 80,000
  Knotless Braids                         UGX 110,000
  Passion Twists                          UGX 150,000
  Weave Plaiting                          UGX 100,000
  Wig Installation                         UGX 50,000
  Dreadlocks Styling                       UGX 50,000
  Hair Coloring                            UGX 40,000
  Hair Retouching                        Price varies

### Wording normalization

The client's original list contains several spelling variants. For the
customer-facing UI use: - `Cornrows`, not `Conrows`; -
`Knotless Braids`, treating the supplied `Knowles braids` as the
intended service name; - `Hair Steaming Treatments`, treating the
supplied `Hair streaming Treatments` as a typo; - `Leave-in Treatment` /
`Leave-in Treatments` with consistent spelling.

Do not change the meaning or prices while correcting presentation
spelling.

### Variable/range prices

Do not convert ranges into a single fixed price.

Examples: - Foot Scrub → `UGX 20,000–25,000`
`UGX 15,000 / 25,000` - Natural Leave-in Treatments → preserve
`UGX 25,000 / 30,000` unless the client later explains the variants. -
Hair Retouching → `Price varies` or `Ask for price`.

------------------------------------------------------------------------

## 6. Service Image Coverage

Dedicated or relevant visual coverage has been prepared for the supplied
service list. The agent should map the available images in
`assets/images/` to the closest exact service rather than generating new
imagery.

Important service visuals include: - Men's Haircut - Women's Haircut -
Kids Haircut - Normal Pedicure/Manicure - Foot Scrub - Gel Colors - Gel
Builder - Artificial Nails - Wash & Blow Dry - Hair Ironing -
Unplaiting - Natural Leave-in Treatment - Other Leave-in Treatment -
Hair Steaming Treatment - Cornrows - Cornrows with Braids - Natural Hair
Styling - Kids Plaiting - Pencil Plaiting - Box Braids - Knotless
Braids - Passion Twists - Weave Plaiting - Wig Installation - Dreadlocks
Styling - Hair Coloring - Hair Retouching

If multiple closely related services share one suitable visual, reuse
intelligently rather than introducing a mismatched image.

------------------------------------------------------------------------

## 7. Recommended Site Structure

Keep the scope appropriate for the **UGX 200,000 tier**. This should be
a polished salon website, not an oversized web application.

### Header / Navigation

Recommended navigation: - Home - Services - Gallery - About - Contact

Include a clear **Book / WhatsApp** CTA.

On mobile: - navigation must be compact; - menu must be easy to tap; -
CTA must remain prominent without covering content.

### Hero

The hero should immediately communicate: - Beauty Secret Salon; - unisex
hair and beauty services; - Kampala/Kisaasi--Kyanja location; - primary
booking/contact action.

Use a strong real/improved salon visual or a suitable service image.

Suggested direction for copy:

**Headline:** `Adding care to your beauty`

**Supporting copy:** A concise line explaining that Beauty Secret Salon
offers professional hair, plaiting, nail and beauty services in
Kisaasi/Kyanja, Kampala.

**CTAs:** `View Services` and `Book / WhatsApp`

This copy is proposed website copy, not a verified historical business
slogan.

### Services

Services are the most important content section.

Requirements: - organize by category; - show service name; - show
price; - show image where appropriate; - make categories easy to scan; -
avoid presenting 25+ identical giant cards in one endless wall.

Recommended categories: 1. Haircuts 2. Nails & Pedicure 3. Hair
Treatments & Styling 4. Braids & Plaiting

A category-tab or filter interface is acceptable if it remains simple
and reliable.

### Gallery

Use the client's real salon/interior and service imagery.

The gallery should: - use a responsive grid; - avoid duplicate-looking
images; - support sensible cropping; - optionally use a lightweight
image preview/lightbox if already supported by the project.

### About

Keep the About section grounded. Do not invent: - years in business; -
number of clients; - awards; - staff qualifications; - ratings; -
branches; - guarantees.

Safe positioning: Beauty Secret Salon is a unisex salon on
Kisaasi--Kyanja Road offering haircuts, plaiting, hair
styling/treatments, manicure and pedicure services.

### Contact / Visit

Include: - primary phone: `0754 852 452`; - secondary supplied number:
`0784 852 452`; - location: `Kisaasi–Kyanja Road, Kampala, Uganda`; -
call CTA; - WhatsApp CTA once the WhatsApp number is
confirmed/configured; - map/directions link where practical.

Use the CLIENT-CONFIRMED Google-listed opening hours: Monday–Sunday, 8:00 AM – 10:30 PM. Display them on the website as `Open daily · 8:00 AM – 10:30 PM`.

------------------------------------------------------------------------

## 8. Booking / Enquiry Behaviour

For this tier, keep booking lightweight.

Recommended flow: 1. Customer selects a service or taps Book. 2. Site
opens WhatsApp/contact flow. 3. Pre-filled message contains the service
name and displayed price where applicable.

Example message:

`Hello Beauty Secret Salon, I would like to enquire about Knotless Braids (UGX 110,000). Please let me know the available time slots.`

For Hair Retouching:

`Hello Beauty Secret Salon, I would like to enquire about Hair Retouching. Please let me know the price and available time slots.`

Do not build: - customer accounts; - payment gateway; - complex
appointment database; - admin dashboard; - automated slot-management
backend;

unless separately approved as a scope upgrade.

------------------------------------------------------------------------

## 9. UI / UX Requirements

### Desktop

-   Use the available width well.
-   Avoid narrow mobile-like columns centered inside large empty desktop
    space.
-   Keep sections visually structured with clear hierarchy.
-   Use responsive card grids.
-   Maintain comfortable content width and spacing.

### Mobile

Mobile quality is critical.

-   No horizontal page overflow.
-   No clipped headings or buttons.
-   Service tabs, if used, must remain usable on small screens.
-   Cards should not feel cramped.
-   Floating CTA must not block content.
-   Touch targets should be comfortable.
-   Navigation must close correctly after selection.

### Motion

Use subtle modern motion only: - gentle reveal-on-scroll; - small card
hover transitions on desktop; - subtle CTA feedback; - smooth section
navigation.

Avoid: - excessive parallax; - continuous distracting animation; -
marquee-like text; - heavy animation that harms mobile performance.

------------------------------------------------------------------------

## 10. Design System Guidance

### Typography

Use a clean, readable web font or the project's existing typeface.

Recommended approach: - expressive but readable display style for major
headings; - clean sans-serif for body copy, prices and controls.

Do not use difficult-to-read script fonts for service names/prices.

### Cards

Service cards should include: - image; - service name; - price; -
optional short descriptor only when useful; - enquiry/book action if the
layout supports it.

Keep price visually prominent.

### Buttons

Primary: - red background; - strong contrast; - clear hover/focus state.

Secondary: - neutral/outlined treatment.

Use consistent border radius, spacing and icon style.

------------------------------------------------------------------------

## 11. SEO Requirements

Use semantic HTML and create useful metadata.

### Suggested homepage title

`Beauty Secret Salon Kampala | Hair, Braids, Nails & Beauty`

### Suggested meta description

`Beauty Secret Salon on Kisaasi–Kyanja Road, Kampala offers haircuts, braids, hair treatments, styling, manicure and pedicure services. View services and prices.`

### SEO implementation

-   one clear `<h1>`;
-   logical heading hierarchy;
-   descriptive image `alt` attributes;
-   canonical URL once production domain is known;
-   Open Graph metadata;
-   mobile viewport;
-   meaningful page title and description;
-   LocalBusiness/BeautySalon structured data once final
    contact/location details are confirmed;
-   sitemap and robots configuration if appropriate to the deployment
    setup.

Never fabricate reviews, ratings, opening hours or geo-coordinates for
structured data.

------------------------------------------------------------------------

## 12. Accessibility & Performance

-   Maintain readable color contrast.
-   Provide keyboard-visible focus states.
-   Use semantic buttons/links.
-   Add `alt` text to meaningful images.
-   Decorative imagery should not create noisy screen-reader output.
-   Lazy-load below-the-fold images.
-   Serve appropriately sized images.
-   Avoid unnecessarily large JavaScript dependencies.
-   Respect `prefers-reduced-motion` where animations are used.
-   Keep layout stable while images load.

------------------------------------------------------------------------

## 13. Technical Content Architecture

Keep editable business information centralized rather than scattering it
through HTML/components.

Recommended structure concept:

``` text
siteData
├── business
│   ├── name
│   ├── phones
│   ├── location
│   └── whatsapp
├── brand
│   └── colors
├── services
│   ├── haircuts
│   ├── nails
│   └── hairPlaiting
└── socialLinks
```

If the project is plain HTML/CSS/JS, use an equivalent central JS object
or clearly documented data section.

The agent must follow the existing stack instead of unnecessarily
rebuilding the project in another framework.

------------------------------------------------------------------------

## 14. Scope Guardrails

### Included

-   Responsive salon website
-   Business branding
-   Service catalogue with supplied prices
-   Service imagery
-   Salon gallery
-   About section
-   Contact/location information
-   Call/WhatsApp enquiry CTA
-   Basic SEO
-   Modern responsive UI

### Do not add without approval

-   Online payments
-   Customer login/accounts
-   Admin dashboard
-   Database-backed bookings
-   Staff scheduling system
-   Inventory/e-commerce
-   Loyalty system
-   Complex animations
-   Paid third-party services
-   Features that materially change the agreed 200k-tier scope

------------------------------------------------------------------------

## 15. Information Still Requiring Client Confirmation

The coding agent must **not invent** these:

-   Exact WhatsApp number if different from the primary phone
-   Opening/closing hours
-   Confirmed social-media profile URLs
-   Final website/domain URL
-   Exact Google Maps link
-   Whether `0784 852 452` remains active
-   Any business slogan
-   Staff names/details
-   Any testimonials/reviews to display

Keep these configurable so they can be inserted later without
restructuring the site.

------------------------------------------------------------------------

## 16. Final Agent Checklist

Before considering the site complete:

-   [ ] Branding says **Beauty Secret Salon** everywhere.
-   [ ] No Levinah branding or content remains.
-   [ ] Red/black/white brand direction is consistent.
-   [ ] Correct Beauty Secret logo is used.
-   [ ] Every supplied service is represented.
-   [ ] Every price matches the supplied client list.
-   [ ] Hair Retouching is shown as variable price.
-   [ ] Service images resolve from `assets/images/`.
-   [ ] No broken/missing image paths.
-   [ ] No fabricated business claims.
-   [ ] Phone/location information is consistent.
-   [ ] WhatsApp message generation includes service details.
-   [ ] Desktop layout is intentionally designed.
-   [ ] Mobile layout has no overflow or overlapping UI.
-   [ ] Images are optimized and appropriately cropped.
-   [ ] Basic SEO metadata is present.
-   [ ] Accessibility basics are implemented.
-   [ ] No out-of-scope backend/payment features were introduced.
-   [ ] Site has been checked at common mobile, tablet and desktop
    widths.

------------------------------------------------------------------------

## 17. Agent Priority

When requirements conflict, use this priority:

1.  Client-supplied business information and prices in this document.
2.  Actual assets present in `assets/images/`.
3.  Beauty Secret Salon's supplied branding/logo/interior references.
4.  Verified Kampala public business information.
5.  Sensible UI/UX implementation decisions.

**Never replace client-supplied information with assumptions from
another similarly named business found online.**
