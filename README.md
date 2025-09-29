
# YourAIStartup — Static Website (Student Project)

This is a simple, professional one-page static website template built for a student-led AI startup. It uses Tailwind CSS via CDN and plain HTML/JS so it's easy to understand and deploy.

## What's included
- `index.html` — One page site (Hero, About, Product, Team, Contact).
- No build tools required. Just a static site.

## How to run locally
1. Extract the zip.
2. Open `index.html` in your browser.

## How to deploy (3 easy options)

### 1) GitHub Pages
1. Create a new GitHub repository and push the files.
2. In repository settings -> Pages -> Source -> `main` branch (or `gh-pages`) -> Save.
3. Your site will be available at `https://<your-username>.github.io/<repo-name>/`.

### 2) Vercel (recommended for simplicity)
1. Create a Vercel account at https://vercel.com
2. Import the GitHub repository and deploy (it detects a static site automatically).
3. Vercel gives you a live URL immediately.

### 3) Netlify
1. Create a Netlify account.
2. Drag-and-drop the site folder in the Netlify dashboard or connect your GitHub repo.
3. Deploy and get a live URL.

## Contact form
- The contact form in this demo saves messages to `localStorage` (demo mode).
- To enable real email, sign up at Formspree (https://formspree.io) or Netlify Forms and replace the demo handler with your form action endpoint.
- Example (Formspree): Replace the `handleSubmit` script with a normal form `action="https://formspree.io/f/your-id"` and `method="POST"`.

## Customize
- Replace company name in the header and footer.
- Update team member names and bios.
- Replace hero text with your startup idea — use ChatGPT to polish content.

---
Good luck! If you want, I can also generate a README in Hindi, or create a GitHub-ready `index.html` with metadata and SEO tags.
