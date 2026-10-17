# STR General Trading and Projects (Pty) Ltd - Website

Corporate website for **STR General Trading and Projects (Pty) Ltd**, a South African multi-disciplinary company.

> Your Trusted Partner in Supply and Projects

A single-page static site (HTML, CSS and vanilla JavaScript). No database, no backend, no build step.

## Features

- Construction-company look built on the logo's navy and gold
- Hero, About, Vision, Mission, Core Values, 12-service grid and Contact sections
- Enquiry form that sends enquiries to WhatsApp (+27 63 549 4078) with no paid API
- Floating WhatsApp button and "Get a Free Quote" buttons
- Fully responsive (desktop, tablet, mobile)
- SEO ready: meta tags, Open Graph, JSON-LD, sitemap, robots.txt

## Project structure

```
index.html        The whole website (CSS, JS and logo are embedded)
404.html          Branded not-found page
robots.txt        Crawler rules and sitemap location
sitemap.xml       Sitemap for search engines
.htaccess         HTTPS, www redirect, compression, caching, security headers
favicon.ico       Browser icon
images/           Share image, favicons and logo source files
```

## Deploy to ReloHost (cPanel)

1. Make sure an SSL certificate is active for the domain (AutoSSL in cPanel).
2. Open **File Manager** and go to `public_html`.
3. Upload the project files (`index.html`, `404.html`, `robots.txt`, `sitemap.xml`, `.htaccess`, `favicon.ico` and the `images` folder).
4. Turn on "Show hidden files" to see `.htaccess`.
5. Open the domain and refresh with Ctrl+F5.

The site is designed and hosted by [ReloHost](https://www.relohost.com).

## How the enquiry form works

1. Required fields are validated in the browser.
2. A formatted message is built from the visitor's details.
3. WhatsApp opens via `https://wa.me/27635494078` with the message URL-encoded.
4. The visitor reviews the message and presses **Send in WhatsApp**.

The page never says "Enquiry Sent": the enquiry is only complete once the visitor presses Send in WhatsApp.

## SEO checklist

- [x] One `h1`, semantic landmarks and descriptive alt text
- [x] Title, meta description and canonical link
- [x] Open Graph and Twitter card tags with a 1200x630 share image
- [x] JSON-LD business data listing all 12 services
- [x] `sitemap.xml` and `robots.txt`
- [ ] Submit `https://strprojects.co.za/sitemap.xml` in Google Search Console
- [ ] Create a Google Business Profile
- [ ] Add a street address to the structured data if one is available

## Customise

- **Domain:** replace `https://strprojects.co.za` in `index.html`, `robots.txt` and `sitemap.xml`.
- **Colours:** edit the CSS variables at the top of the `<style>` block in `index.html`.
- **WhatsApp number:** search for `27635494078` in `index.html`.
- **Services:** the cards and the form dropdown are plain HTML in `index.html`.

## GitHub Pages (optional preview)

Push this repository to GitHub, then open **Settings > Pages**, choose the `main` branch and the root folder.
The `.nojekyll` file stops GitHub from processing the site with Jekyll. Production hosting stays on ReloHost.
