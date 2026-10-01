# Eye Go Optical redesign

Open `index.html` in a browser. The static multi-page site uses `multi.css` and `script.js` and has no build step.

## Pages

Home, About, Services, Accessibility, School Screenings, Eyewear & Brands, Insurance, Financing, Book Appointment, Contact, Testimonials, and Invoice Help. See [SITE_AUDIT.md](SITE_AUDIT.md) for the source inventory, architecture, and licensed image credits.

## Integrations

- The dedicated Financing page loads the Cherry widget configuration supplied by the user.
- The dedicated Book Appointment page embeds `https://eyegooptical4q07.setmore.com` and includes a direct-link fallback.
- Wix Invoices remain the staff-side invoice workflow. The public Invoice Help page directs each customer to the unique link in their invoice message; it does not expose invoices or collect payment data.
- The Contact page and homepage include a responsive Google Maps embed and directions link.

Before launch, confirm which original Wix photo is the storefront, add verified hours and email if desired, and check that the Cherry and Setmore providers allow embeds on the production domain.
