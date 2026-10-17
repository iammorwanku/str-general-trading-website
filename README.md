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
