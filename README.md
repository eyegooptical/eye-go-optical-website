# Eye Go Optical website

Static multi-page website. Open index.html from a local web server or deploy this folder to Netlify. Styles are in styles.css and multi.css; shared browser behavior is in script.js.

## Pages

Home, About, Services, Accessibility, School Screenings, Eye Go International, Eyewear & Brands, Insurance, Financing, Book Appointment, Contact, and Google Reviews.

## Integrations

- Cherry financing and Setmore scheduling retain the owner-provided embeds.
- Contact messages use the Netlify function at /api/contact and Resend; configure RESEND_API_KEY and a verified CONTACT_FROM_EMAIL. The recipient is info@eyegooptical.com.
- Google reviews are fetched server-side from Google Places. Configure GOOGLE_PLACES_API_KEY and GOOGLE_PLACE_ID. Until configured, the reviews page links to the Google business profile.
- No public invoice feature is included.

Contact delivery and live Google review retrieval are inactive until the hosting environment has the required credentials.
