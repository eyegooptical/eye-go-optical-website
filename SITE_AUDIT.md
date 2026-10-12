# Eye Go Optical site implementation notes

Static multi-page HTML/CSS/JavaScript site; no package manager or build step is present. A Netlify Function provides server-side contact delivery.

## Integrations and configuration

- Setmore appointment booking and Cherry financing remain embedded as supplied by the owner.
- Contact endpoint: /.netlify/functions/contact, routed through /api/contact. Configure RESEND_API_KEY and CONTACT_FROM_EMAIL in Netlify. Messages are sent to info@eyegooptical.com; sender address is used as reply-to. No success is shown unless Resend accepts the request.
- Catalog contains 48 brand entries and owner-provided prices; prices appear below each brand in smaller type.
- Public invoice help page, reviews page, and associated navigation/API are removed.

## Deployment

Deploy this folder to Netlify and configure the two email environment variables to enable contact delivery.

