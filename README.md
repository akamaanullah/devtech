## Devtech Website

Devtech is a marketing-focused static website that highlights professional IT services including web development, CRM solutions, cybersecurity, digital design, and more. The primary landing page (`index.html`) delivers a multi-section layout covering hero content, services, project highlights, testimonials, and contact information. Dedicated privacy and terms pages ship with the repository as well.

## Project Structure

- `index.html` – main landing page with navigation anchors (`#about`, `#services`, `#contact`).
- `privacy-policy.html` and `terms-and-conditions.html` – legal and compliance documentation.
- `assets/` – bundled CSS, JS, fonts, and images (Bootstrap, Swiper, Magnific Popup, custom styles, brand assets).
- `.gitignore` – standard ignore rules for environment-specific or build artifacts.

## Local Setup

1. Clone or download the repository:
   ```bash
   git clone git@github.com:akamaanullah/devtech.git
   cd devtech
   ```
2. Open `index.html` directly in your browser.

Because the project is entirely static, no build steps are required. If you prefer to serve it through a PHP-capable stack such as XAMPP, copy the folder into `htdocs` and browse to `http://localhost/devtech`.

## Customization Tips

- Update copy and branding within `index.html`; sections use clear classes and IDs for easy editing.
- Modify styling in `assets/css/main.css`; unique selectors keep CSS and JavaScript targeting straightforward.
- Replace imagery inside `assets/img/` while preserving filenames or adjusting the HTML accordingly.
- Bootstrap Icons are already included via `assets/css/all.min.css` for iconography needs.

## Deployment

You can deploy the site to any static hosting provider (Netlify, Vercel, GitHub Pages) or a conventional web server:

1. Skip build steps—upload the HTML files together with the `assets` directory.
2. Confirm `index.html` sits at the web root and relative asset paths remain intact.

## Contributing

1. Create a feature branch: `git checkout -b feature/<feature-name>`.
2. Implement changes, lint where applicable, and test in the browser.
3. Write descriptive commit messages and open a pull request for review.

For any database schema updates (if added later), maintain the convention of supplying separate SQL alter files.

