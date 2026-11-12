# Studio Tejae — Luxury Interior Design Website

A mobile-responsive static website customized for Studio Tejae, Hyderabad.

## Contents
- `index.html`: premium homepage, about, services, filterable design portfolio, clearly labeled sample testimonials, project enquiry and appointment request forms.
- `config.js`: enter contact email, WhatsApp number, and optional webhook URL.
- `admin.html`: illustrative CRM dashboard and production integration checklist. This is a DEMO, not a secure CRM admin interface.

## Launch steps
1. Edit `config.js` with your actual email and WhatsApp number (international digit format, e.g. 919876543210).
2. Replace the inspiration images with actual Studio Tejae projects and get appropriate image usage rights.
3. Replace the explicitly labeled sample testimonials with permissioned authentic reviews.
4. Update About copy and real services, service area, and company details.
5. Upload all three files to the hosting service public folder (e.g. Hostinger `public_html`). Open `index.html` from your domain.
6. Test navigation, portfolio filters, email, WhatsApp and forms on desktop/mobile. Use HTTPS.

## Lead and appointment handling
- Default: Forms cannot submit without configured email or webhook.
- With `email`: Clicking submit opens a prefilled message in the visitor's email application; the visitor must send it. It is not an automatic submission or guaranteed delivery.
- With `webhookUrl`: The browser POSTs JSON to your configured HTTPS service. The service must support CORS and secure validation. No API secrets belong in config.js. Your backend can write the leads to a CRM. Ensure appropriate authentication design, spam prevention, user consent, retention and data protection.
- Appointment requests require manual confirmation. Actual booking availability and automated confirmations require calendar + backend integration.
- `admin.html` includes fictitious examples only. It does NOT store or retrieve actual submitted leads. Do not link this page as a real admin panel in a production site; remove its footer link after integrating your real secure CRM.

## Notes
The site references externally hosted Unsplash images and Google Fonts, so those resources need internet access. Business address, founder credentials, achievements and existing-client testimonials were not supplied and have not been invented.
