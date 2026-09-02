# Complete WRMK website (NEW) — migrated from the WordPress export

This folder is **completely new** and was created in addition to the existing
`WRMK Homepage v3 (Website)` (the single-page homepage concept).
It contains the **entire old website** (content from `wrmk-wordpress-export`),
rebuilt in the **design/style of the v3 homepage** (same CSS classes,
colours, typography, header/footer, topbar).

## How can you tell something is new?

- **This whole folder** (`vollstaendige-website/`) is new — the original
  files in `WRMK Homepage v3 (Website)\index.html` and `assets\` were
  **not changed**.
- Every page has a **black banner** at the top: "Fully migrated version
  from the WordPress export · NEW added page …".
- Headings carry an **orange badge** ("Original content" or
  "NEW: …") indicating: the text/content genuinely comes from the WordPress
  export, only the look is new (v3 style).
- The additional stylesheet `assets/css/wrmk-v3-neu.css` contains exclusively
  new rules (prose typography, team tiles, breadcrumbs, badges,
  pagination) — `assets/css/wrmk-v3.css` (the original) was copied 1:1
  and left untouched.

## What was migrated (real content, no placeholders)

- 12 area-of-practice pages (`services/`)
- 4 office location pages with real addresses/teams (`offices/`)
- 56 real staff profiles with photos, bios, qualifications, contact details
  (`our-people/`)
- 327 news articles + paginated archive (`news/`)
- 208 real client reviews (`testimonials.html`)
- About us, Contact us, Careers, Community, Terms (root level, `legal/`)
- Do-it-online section with 11 self-service pages (`do-it-online/`)
- Guides for employers, employees, farmers, scholarships
  (`resources/`)
- `sitemap.html` — overview of all migrated pages

## Where does the data come from?

From `wrmk-wordpress-export\database.sql` (WordPress database dump) and
`wrmk-wordpress-export\wp-content\uploads` (images, mainly staff photos).
Page content was in Gutenberg block format and was cleaned up (WP block
comments removed, Kadence layout wrappers removed, internal links rewritten
to the new structure) and transferred into the v3 design language.

Not migrated: pure form/thank-you pages with no text content, image uploads
outside of staff photos (PDF downloads link to the original
domain wrmk.co.nz), WordPress admin functions/plugins.
