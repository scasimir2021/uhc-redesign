# Unlimited Healthcare — Responsive Redesign Preview

This is a self-contained front-end **design prototype**, built from an October 2026 review of https://uhcnursing.com/.

## Pages

- Home (`#/home`)
- Pediatric & Geriatric Care (`#/care`)
- Staffing Solutions (`#/staffing`)
- Patient Intake Process (`#/intake`)
- Employment (`#/careers`)
- Mission Statement (`#/mission`)
- Privacy & HIPAA (`#/privacy`)
- Contact (`#/contact`) — **proposed new page**, not present as a separate page in the reviewed navigation.

The navigation uses hash URLs (`#/...`) so deep linking works on static hosts such as GitHub Pages.

## Preview on your phone or computer

**Simplest:** use `uhc-redesign-standalone.html` provided separately. It embeds all images, requires no internet, and opens directly in a web browser. On Android, download the HTML and choose your browser from your file manager; on desktop, double-click it.

**Project version:** open `index.html` from this package or publish `index.html` and `assets/` to GitHub Pages. No build step and no external dependencies.

## Deploy to GitHub Pages

1. Create a repository (for example `uhc-redesign`).
2. Upload `index.html` and the entire `assets` folder to the root of your `main` branch.
3. In repository **Settings → Pages**, set **Build and deployment → Deploy from a branch**, select `main` and `/ (root)`.
4. Open the published `https://USERNAME.github.io/uhc-redesign/` URL and use the top navigation or the page-grid button to explore.

## Demo interactions

- All primary navigation routes work without a server.
- Service tabs switch content on the Care page.
- Employment roles show an interactive modal with source-supported requirements.
- All-page drawer works on desktop and mobile.
- Contact form supports local browser validation and displays a **preview only**. It does not send, persist or collect data on a server.

## Important before a public launch

- **Privacy:** Do not collect protected health information on a static GitHub Pages contact form. Use an approved secure intake system for sensitive information and have the legal policy reviewed by the healthcare organization's compliance contact.
- **Branding:** Proposed logo design and all illustrative images should be approved or replaced with licensed/approved assets. The images here were derived from AI-created design mockups, not actual employees or patients.
- **Truthfulness:** Verify published rates, hiring requirements, locations, clinical services, claims about AI-assisted coordination and company contact information before publishing.
- **Contact:** Add verified telephone number/email and connect actual form delivery to a secure provider before production.
- **Legal:** The Privacy page provides a short explanation and links to the **existing authoritative HIPAA policy**; it is not intended to replace the full notice.

## Existing pages reviewed

- https://uhcnursing.com/
- https://uhcnursing.com/employment/
- https://uhcnursing.com/intake-process/
- https://uhcnursing.com/home-health-hospice/
- https://uhcnursing.com/home-health-hospice-2/
- https://uhcnursing.com/mission-statement/
- https://uhcnursing.com/privacy-policy/
