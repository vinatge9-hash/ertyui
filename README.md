# VerifyNow - SaaS API Website

This repository contains static HTML pages for a dark-themed, neon-accent SaaS product named VerifyNow. The site is designed to be mobile-responsive with subtle scroll animations, a consistent navigation bar, and a well-structured footer across all pages.

Pages included:
- index.html (Home)
- pricing.html
- api.html
- contact.html
- login.html
- README.md (this file)

Key design notes:
- Theme: Dark background with neon blue/cyan accents for buttons and highlights.
- Typography: Two fonts loaded as placeholders:
  - Inter (sans-serif) for body/content
  - Merriweather (serif) for brand/textmark
- Location placeholder: Hyderabad, India used on the Contact page for the address.
- Footer: 3-column layout on desktop with a brand/socials, Quick Links, and Newsletter. Includes a centered © 2025 VerifyNow.
- Content placeholders: Images use the provided placeholder syntax src="https://images.pexels.com/photos/226123/pexels-photo-226123.jpeg?auto=compress&cs=tinysrgb&h=650&w=940".
- All icons are inline SVGs styled with Tailwind classes.

How to run:
- This is a static HTML site using Tailwind CSS via CDN. No build step required.
- Open any of the HTML files in a browser to view.

Notes:
- The HTML files include placeholders for fonts and images. In production, replace font-face URLs with actual font files and update image sources accordingly.
- For full site-wide styling, you can later convert to a React/Vite project or similar if dynamic behavior is required.