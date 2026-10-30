# Eye Go Optical site implementation notes

Static multi-page HTML/CSS/JavaScript site deployed to GitHub Pages with a GitHub Actions workflow.

## Integrations and configuration

- Setmore appointment booking and Cherry financing remain embedded as supplied by the owner.
- The contact form uses a mailto link to prepare a message to info@eyegooptical.com. The visitor’s email app must be configured, and the visitor must press Send. This is static-site behavior; server-side delivery requires a separate host or form provider.
- Catalog contains 48 brand entries with prices removed.
- Public invoice and reviews pages and their navigation are removed.

## Deployment

GitHub Actions publishes the root HTML, CSS, JavaScript, robots.txt, and sitemap.xml files when changes are pushed to `main`.

