# Eye Go Optical site implementation notes

Static multi-page HTML/CSS/JavaScript site; no package manager or build step is present. Netlify Functions provide server-side contact and Google Reviews endpoints.

## Integrations and configuration

- Setmore appointment booking and Cherry financing remain embedded as supplied by the owner.
- Contact endpoint: /.netlify/functions/contact, routed through /api/contact. Configure RESEND_API_KEY and CONTACT_FROM_EMAIL in Netlify. Messages are sent to info@eyegooptical.com; sender address is used as reply-to. No success is shown unless Resend accepts the request.
- Reviews endpoint: /.netlify/functions/reviews, routed through /api/reviews. Configure server-side GOOGLE_PLACES_API_KEY and GOOGLE_PLACE_ID. No reviews are fabricated. Fallback links to https://maps.google.com/?cid=3089171725304475909.
- Catalog contains 48 brand entries and owner-provided prices.
- Public invoice help page and navigation are removed; this does not modify the owner’s Wix staff invoice account.

## Deployment

Deploy this folder to Netlify and configure the four environment variables to enable server-side integrations.
