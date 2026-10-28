# Jules On The Move Website

A fast, static, multi-page real estate lead-generation website for San Antonio search traffic and brand presentation. No framework, build command, database, or package installation is required.

## One-step deployment

Copy **all files and folders inside this directory** into the root of your GitHub repository, then deploy the repository as a static site. For Netlify, the included `netlify.toml` publishes the repository root. For GitHub Pages, enable Pages for the repository root.

## Required replacements before publishing

Use repository-wide search and replace:

- `YOUR-DOMAIN.com` → your production domain, without a trailing slash
- `PHONE_PLACEHOLDER` → your business phone
- `EMAIL_PLACEHOLDER` → your business email
- Replace the footer disclosure with brokerage-approved legal language and license information
- Connect the form handler in `assets/site.js` to your approved CRM, email, or form service
- Review `privacy/index.html` after analytics, advertising, CRM, and form tools are selected

Do not publish claims, awards, ratings, sales volume, testimonials, or service areas unless they are accurate, current, documented, and brokerage-approved.

## Architecture

- `/index.html` — branded conversion homepage
- `/buy-a-home-san-antonio/` — buyer-intent landing page
- `/sell-my-home-san-antonio/` — seller-intent landing page
- `/san-antonio-relocation-realtor/` — relocation landing page
- `/san-antonio-real-estate-investing/` — investor-intent landing page
- `/san-antonio-neighborhoods/` — neighborhood hub
- `/stone-oak-homes-for-sale/` — sample neighborhood landing page
- `/contact/` — lead conversion page
- `/privacy/` — privacy starter page
- `/assets/` — shared CSS, JavaScript, and portrait
- `sitemap.xml`, `robots.txt` — crawler discovery
- `netlify.toml` — static publishing and security headers

## SEO included

Each indexable page has a unique title, meta description, canonical URL, Open Graph metadata, semantic headings, internal links, descriptive URL slug, and `RealEstateAgent` JSON-LD. The site also includes a sitemap, robots file, responsive layout, image dimensions, and accessible navigation.

## Content expansion

Add only substantial local pages that answer a distinct search need. Duplicate a landing-page folder, rewrite the title, description, H1, body, FAQ, internal links, canonical URL, and schema description. Do not create thin pages by swapping only a neighborhood name. Add the new URL to `sitemap.xml`.

## Image

`assets/julie-professional.png` is used throughout the website. Replace it using the same filename to update every page automatically. Keep the image optimized and preserve the current dimensions or aspect ratio.
