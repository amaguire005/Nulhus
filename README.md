# Nulhus static website

This repository contains a minimalist, single‑file website for **Nulhus**, a consultancy providing behind‑the‑meter (BTM) solar PV and battery storage advisory services.

## Contents

- **index.html** – the main site content with inline styling and simple JavaScript to update the copyright year. Edit this file to update copy, services, case studies or the contact form endpoint.
- **logo.png** – the Nulhus logotype used in the header. Replace this with your high‑resolution logo if necessary.

## Editing

The site has been designed to be lightweight and easy to edit directly on GitHub. Simply open `index.html` in the GitHub web UI, click **Edit**, make changes and commit. The site will redeploy automatically via GitHub Pages.

### Updating the contact form

The form in the **Contact** section posts to [Formspree](https://formspree.io/) using a placeholder action URL (`https://formspree.io/f/your-form-id`). Sign up for a free Formspree account, create a new form and replace the action URL with your unique form ID to enable form submissions.

### Custom domain

Once the site is live on GitHub Pages, you can point your own domain to it. Go to **Settings → Pages** in this repository, set your custom domain (e.g. `www.nulhus.com`) and follow the provided DNS instructions.

## License

This project is provided without a license and is intended for internal use by the Nulhus team.