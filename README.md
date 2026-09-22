# PJS Groups Website

A responsive 4-page static website designed for PJS Groups and ready for Cloudflare Pages, GitHub Pages, Netlify, or similar static hosting.

## Pages
- `index.html` — Home
- `about.html` — About Us
- `services.html` — Services / Products
- `contact.html` — Contact

## Before publishing
Search for these placeholders and replace them:
- `[X]`
- `[PHONE NUMBER]`
- `[EMAIL ADDRESS]`
- `[STREET ADDRESS]`
- `[CITY, STATE ZIP]`
- `[HOURS]`
- `[NAME]`
- `[SERVICE / PRODUCT NAME]`
- `[YOUR-EMAIL]`

Also replace the `#` social links and the Google Maps placeholder.

## Contact form
The example uses FormSubmit. In `contact.html`, replace:
`https://formsubmit.co/[YOUR-EMAIL]`
with your real receiving email address.

On first submission, FormSubmit may require email confirmation. For production, you can instead connect the form to a service such as Formspree, Basin, or a Cloudflare Worker.

## Cloudflare Pages
1. Put this folder in a GitHub repository.
2. Cloudflare Dashboard -> Workers & Pages -> Create -> Pages.
3. Connect the GitHub repository.
4. For a plain HTML site, no build command is required.
5. Set output directory to the repository root if prompted.
6. Deploy.
7. Add `mrpjs.com` under Custom Domains.
8. Follow Cloudflare's DNS instructions at GoDaddy.

## Local testing
Open `index.html` directly in a browser, or run:
`python -m http.server 8000`
Then visit:
`http://localhost:8000`
