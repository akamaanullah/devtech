## Devtech Website

Devtech ek static marketing site hai jo professional IT solutions, web development, CRM, cyber security aur digital design services ko highlight karta hai. Landing page `index.html` par multi-section layout hai jisme hero banner, services, projects, testimonials aur contact form shamil hain. Repository me privacy aur terms pages bhi included hain.

## Project Structure

- `index.html` – primary landing page with navigation anchors (`#about`, `#services`, `#contact`).
- `privacy-policy.html` aur `terms-and-conditions.html` – legal content pages.
- `assets/` – saari CSS, JS, fonts aur images (Bootstrap, Swiper, Magnific Popup, custom styles).
- `.gitignore` – common environment aur build outputs ignore karta hai.

## Local Setup

1. Repo clone ya download karein:
   ```bash
   git clone git@github.com:akamaanullah/devtech.git
   cd devtech
   ```
2. `index.html` ko browser me open karein.

Ye pure static site hai, koi build step required nahi hai. Agar aap PHP-ready environment use kar rahe hain (jaise XAMPP), to project folder ko `htdocs` me place karke `http://localhost/devtech` visit kar sakte hain.

## Customization Tips

- Branding aur copy ke liye `index.html` me relevant sections update karein.
- Styling ke liye `assets/css/main.css` modify karein; har UI element unique classes use karta hai jisse CSS/JS targeting asaan hoti hai.
- Images ko `assets/img/` ke andar same naming structure follow karte hue replace karein.
- Icons ke liye Bootstrap Icons already bundle hain (`assets/css/all.min.css`).

## Deployment

Static hosting platforms (Netlify, Vercel, GitHub Pages) ya kisi bhi standard web server par deploy kar sakte hain:

1. Build step skip karein, seedha `assets` aur HTML files upload karein.
2. Ensure karein ke root me `index.html` accessible ho, aur supporting assets relative paths maintain karein.

## Contributing

1. Nayi branch create karein: `git checkout -b feature/<feature-name>`.
2. Changes karein, lint aur browser testing karein.
3. Commit messages ko meaningful rakhein, phir pull request raise karein.

Agar kisi update me database schema me changes chahiye hon, to unke liye alag SQL alter file banane ka convention follow karein.

