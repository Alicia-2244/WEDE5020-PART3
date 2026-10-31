# Paw Haven Pet Care Centre — Part 3

## Project overview
Paw Haven Pet Care Centre is a five-page website project. The pages are Home (`_index.html`), About (`about.html`), Services (`services.html`), Contact (`contact.html`) and Enquiries (`enquiries.html`). Open `_index.html` in a browser to start.

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

## Part 2 feedback and response — complete before submission
The actual lecturer/marker feedback was not included in the website ZIP, so it must not be invented. Complete this section using the feedback you genuinely received:

| Feedback received in Part 2 | Change made in Part 3 | How the change improved the website |
|---|---|---|
| [Insert the exact feedback] | [Describe the change you made] | [Explain the improvement] |
| [Insert the exact feedback] | [Describe the change you made] | [Explain the improvement] |

If no formal feedback was provided, state that honestly and describe the improvements you identified yourself. Do not claim that a marker requested a change unless that happened.

## Changelog
### Part 3 — 31 October 2026
- Added meta keywords to all five pages and reviewed page-specific SEO titles and descriptions.
- Renamed image files to descriptive, web-safe filenames and updated HTML references and alt text.
- Corrected service-card classes and categories so search and filtering cover all four services.
- Improved lightbox keyboard operation, focus handling and accessible dialog attributes.
- Updated map embeds to search the two addresses already displayed on the Contact page; confirm both locations are correct before publishing.
- Improved responsive map, form, focus and reduced-motion styling.
- Updated project documentation and added a Part 2 feedback response table for completion.

## References — complete before submission
Add the sources you actually used while researching and developing the website. Use the referencing style required by your lecturer. Do not submit invented sources or URLs. Include image sources where required by your assignment brief.

## Before publishing / submission checklist
1. Replace `YOUR-DEPLOYED-DOMAIN.example` in `robots.txt` and `sitemap.xml` with the final public website domain. If the site is not publicly deployed, do not claim it is deployed.
2. Confirm that the two Contact page addresses and map pins are the intended Paw Haven locations. The address text was retained from the supplied project files.
3. Confirm the phone number, email address, opening hours and all business details are correct and approved for publication.
4. Complete the Part 2 feedback table with genuine feedback and add your actual references.
5. Test all five pages, navigation links, all four service filters, image lightbox, both forms and maps on desktop and mobile.
6. Push the project to GitHub and make several meaningful commits (for example: `Add responsive page layout`, `Add service search and filters`, `Add form validation and email draft`, `Improve SEO and accessibility`). Only use commit messages that accurately describe work you performed.
7. Publish the website using your required hosting platform and test the live URL. GitHub commit history and deployment cannot be created by this ZIP alone.

## File structure
- `_index.html`, `about.html`, `services.html`, `contact.html`, `enquiries.html` — website pages
- `css.assets/myfirststyles.css` — site styling
- `js.assets/pawhaven.js` — lightbox, service filtering and form handling
- `_images/` — website image assets
- `robots.txt`, `sitemap.xml` — search-engine crawling templates
