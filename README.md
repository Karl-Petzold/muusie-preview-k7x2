# muusie.com

Static website for Muusie, the AI lab building Ruums. Plain HTML, CSS and JS, no build step.

- Every page carries `noindex, nofollow`: search engines do not list the site. It is reachable only by its link.
- Do not add a robots.txt that blocks crawling: crawlers must be able to read the noindex tag.

## Structure
- `index.html`: home (hero, ruum vibes carousel, waitlist, footer parade)
- `about.html`, `privacy.html`, `terms.html`, `contact.html`
- `media/`: clips (540 x 810, H.264), posters, icons
- `assets/js/`: GSAP 3.12.5, ScrollTrigger, Lenis 1.1.13
- Fonts (Fraunces, Nunito, SIL OFL) are embedded in each page.

## Settings (`index.html`, search for `var CONFIG`)
- `testflightUrl`: public TestFlight link. Empty hides the beta button.
- `waitlistEndpoint`: form endpoint for waitlist emails (for example Formspree). Empty shows a preview message.
