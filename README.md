# Paw Haven Pet Care Centre — Part 3

## Project overview
Paw Haven Pet Care Centre is a five-page website project. The pages are Home (`_index.html`), About (`about.html`), Services (`services.html`), Contact (`contact.html`) and Enquiries (`enquiries.html`). 
## Part 3 enhancements
- Added page-specific SEO title tags, meta descriptions, meta keywords, viewport and robots metadata.
- Added descriptive image filenames and meaningful alternative text for content images.
- Added an accessible image lightbox. Activate a main-content image by clicking it or focusing it and pressing Enter/Space. Close with Escape, the close control or the backdrop.
- Added working service search and category filtering for all four service cards: grooming, sitting, walking and boarding. A result message is shown, including when no results match.
- Added two address-based Google Maps embeds on the Contact page, with descriptive iframe titles.
- Added native enquiry and contact forms with required fields, length limits, email validation and phone-number validation.
- Added client-side form validation and an email-draft response using `mailto:`.
- Added responsive styling, visible keyboard-focus indicators and reduced-motion support.
- Added `robots.txt` and `sitemap.xml` templates.

## Form process — important limitation
The forms validate the entered information and prepare an email addressed to `pawhaven@gmail.com` in the visitor's default email application. They do **not** send an email automatically and do not store submissions on a server. The visitor must review and send the email. A real automatic submission process requires a configured backend or form service.

## Changelog
### Part 3 — 31 October 2026
- Added meta keywords to all five pages and reviewed page-specific SEO titles and descriptions.
- Renamed image files to descriptive, web-safe filenames and updated HTML references and alt text.
- Corrected service-card classes and categories so search and filtering cover all four services.
- Improved lightbox keyboard operation, focus handling and accessible dialog attributes.
- Updated map embeds to search the two addresses already displayed on the Contact page; confirm both locations are correct before publishing.
- Improved responsive map, form, focus and reduced-motion styling.
- Updated project documentation and added a Part 2 feedback response table for completion.
- 
## REFERENCES - 
FOUR PAWS (2026) *About FOUR PAWS*. Available at: https://www.four-paws.org.za/about-us/about-four-paws (Accessed: 31 October 2026).
FOUR PAWS (n.d.) *Reports and resources*. Available at: https://www.four-paws.org.za/our-stories/reports-resources (Accessed: 31 October 2026).
People’s Dispensary for Sick Animals (PDSA) (n.d.) *Home*. Available at: https://www.pdsa.org.za/ (Accessed: 31 October 2026).
People’s Dispensary for Sick Animals (PDSA) (n.d.) *Services you can expect from the PDSA*. Available at: https://www.pdsa.org.za/services/ (Accessed: 31 October 2026).
South African Veterinary Council (SAVC) (n.d.) *Know your vet: How to ensure your pets receive the best medical care*. Available at: https://savc.org.za/know-your-vet-how-to-ensure-your-pets-receive-the-best-medical-care/ (Accessed: 31 October 2026).


## File structure
- `_index.html`, `about.html`, `services.html`, `contact.html`, `enquiries.html` — website pages
- `css.assets/myfirststyles.css` — site styling
- `js.assets/pawhaven.js` — lightbox, service filtering and form handling
- `_images/` — website image assets
- `robots.txt`, `sitemap.xml` — search-engine crawling templates
