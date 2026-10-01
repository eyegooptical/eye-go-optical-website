# Eye Go Optical source audit and new architecture

Reviewed October 1, 2026. The existing website is the source for all business facts except the Setmore URL and Cherry widget supplied directly by the user.

## Existing website inventory

- Main navigation: Home, Booking, Cherry, Contact, Testimonial, Brands, and More.
- Logo: `eyegowithwords2.png` on the Eye Go Optical Wix CDN.
- Homepage: four Wix-hosted photo assets are referenced and retained in the new location galleries. The public text extraction did not identify which specific image depicts the storefront.
- Booking: user supplied the direct Setmore URL `https://eyegooptical4q07.setmore.com`.
- Cherry: user supplied the Cherry widget initialization code and configuration. It is included on the dedicated Financing page.
- Invoices: the business currently uses Wix Invoices. The public website does not expose invoice management or payment details. Staff can continue using Wix for invoice creation; customers should use the unique payment link sent with each invoice.
- Business name, address, and phone: Eye Go Optical, 989 Liberty Ave, Brooklyn, NY 11208; (718) 758-5155.
- Business email and hours are not published on the source site. The redesign tells customers to call for hours and does not invent an email.
- Services: the source site lists “Vision Screening”; the verified original storefront photograph also advertises “Eye Exams Available.” The user brief specifically identifies school vision screenings as a service, but does not provide screening methods, ages, pricing, equipment, or availability.
- Insurance (18): Aetna; Affinity; Amida Care; Avesis; Blue Cross Blue Shield; Davis Vision; EyeMed Vision; Fidelis; General Vision Services (GVS); Guardian Vision; HealthFirst; Local 100 - MTA; Local 1199; NYS Medicaid; MetroPlus; NVA; Spectera; United Health Care.
- Eyewear brands (25): BCBG; Carerra; Cazal; Celine; Dilli Dalli; DKNY; Dream Himax; Gucci; Jimmy Choo; Juicy Couture; Marc Jacobs; MCM Eyewear; Michael Kors; Miu Miu; Morel OGA; Moschino; Paul Vorsherant; Prada; Rag & Bone; Ray Ban; Steve Madden; Tom Ford; Tommy Hilfiger; Tory Burch; Versace. Spellings match the source list.
- The original Contact page has a Wix form, but the public site did not reveal a submission endpoint or email address. The redesign includes a clearly marked, disabled contact form placeholder until a verified email or secure form service is supplied; phone, directions, and booking actions remain available.

## New sitemap

- `index.html` — Concise homepage overview and primary actions.
- `about.html` — Confirmed business and location details.
- `services.html` — Vision screening and eyewear information.
- `accessibility.html` — Contact-first guidance; specific accommodations are flagged for confirmation.
- `school-screenings.html` — School screening inquiry and scheduling information without unsupported protocol claims.
- `eyewear-brands.html` — Searchable confirmed eyewear brands.
- `insurance.html` — Searchable insurance list and a linked brands section.
- `financing.html` — Cherry widget, with no stock photography.
- `book-appointment.html` — Setmore booking iframe, with no stock photography.
- `contact.html` — Accessible contact form placeholder, original photos, map, directions, phone, and booking link.
- `location.html` — Storefront, address, map, phone, and directions.
- `testimonials.html` — The customer story from the source site.
- `invoices.html` — Customer instructions for invoice-specific payment links; no public invoice search or card data collection.

## Design and image sources

- Red, black, and white design system; responsive menu and persistent mobile Book / Call / Directions actions.
- Original Wix logo and photo assets are retained.
- Jess Bailey, “eyeglasses with black frames on white surface,” Unsplash: https://unsplash.com/photos/eyeglasses-with-black-frames-on-white-surface-NtNBbiaqH1I. The photo page identifies the image as free under the Unsplash License. It is used as generic eyewear imagery, not as a depiction of the business.

Before production, confirm which original Wix asset is the storefront, verify published hours/email, and check the third-party embeds on the live domain.
