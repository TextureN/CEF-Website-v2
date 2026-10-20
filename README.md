# CEF Website v2

Premium, responsive, public-facing website for Community Enterprise Fund (CEF).

## Pages
- `index.html` — Homepage and overview
- `about.html` — About CEF, purpose and principles
- `services.html` — Development finance, enterprise development, skills, implementation, agriculture and logistics
- `programmes.html` — Labour activation, agricultural skills, school nutrition logistics, small business support, community development and M&E
- `partnerships.html` — Partnership audiences and collaboration approach
- `contact.html` — Contact details and client-side email enquiry form

## Shared assets
- `assets/site.css` — Responsive design system, layout, animation and mobile navigation styles
- `assets/site.js` — Mobile navigation, scroll-reveal animation, current year and mailto form preparation
- `.github/workflows/pages.yml` — GitHub Actions workflow for GitHub Pages deployment

## Technology
Static HTML, CSS and JavaScript. No build step, server or website login is required.

## Deployment
The workflow deploys the repository to GitHub Pages when changes are pushed to `main`, or when manually triggered. In repository **Settings → Pages**, set the build and deployment source to **GitHub Actions**. Then check the **Actions** tab for the deployment result and the Pages settings for the published URL.

## Pre-launch review
Before public launch, confirm:
- Official CEF logo, brand assets, approved wording and legal entity details.
- Official email address, telephone number, physical address and website domain.
- All programme descriptions, accreditations, funding claims and figures.
- Privacy notice, POPIA considerations and any other required legal notices.
- Form behaviour and contact workflow. The current contact form prepares a message in the visitor's email application; it does not transmit data to a server.
- Accessibility, mobile layout and browser behaviour.

## Preview locally
Open `index.html` in a modern browser. Keep the folder structure intact so the shared CSS and JavaScript load correctly.
