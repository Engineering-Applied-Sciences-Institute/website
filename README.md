# EASI — Engineering and Applied Sciences Institute

Website for the **Engineering and Applied Sciences Institute (EASI)** at [easinstitute.org](https://easinstitute.org). Static HTML, CSS, and a small amount of JavaScript so it can be hosted anywhere (GitHub Pages, Netlify, Vercel, or any web server) without a build step.

## Contents

- **Home** (`index.html`) — Hero, mission summary, featured research, support CTA
- **About** (`about.html`) — Mission, values, and story
- **Research** (`research.html`) — Research areas and publications
- **Team** (`team.html`) — Leadership and staff (placeholder bios)
- **Contact** (`contact.html`) — Contact form; emails use @easinstitute.org

## Customization

1. **Contact** — In `contact.html`, update the physical address (street, city, state, ZIP) with your real location.
3. **Form** — The contact form’s `action="#"` is a placeholder. Hook it up to a form service (e.g. Formspree, Netlify Forms) or your backend.
4. **Content** — Edit the copy on each page to match your research areas, team, and story. Add links to real reports and team bios/photos as needed.
5. **Colors/fonts** — In `css/style.css`, the `:root` variables control colors and fonts. Adjust `--color-primary`, `--color-accent`, and font families to match your brand.

## Running locally

Open `index.html` in a browser, or use a simple local server:

```bash
# Python 3
python -m http.server 8000

# Node (npx)
npx serve .
```

Then visit `http://localhost:8000` (or the port shown).

## Deployment

- **GitHub Pages** — Push the repo, enable Pages in repo Settings → Pages, and select the branch (e.g. `main`) and folder (e.g. `/` or `root`).
- **Netlify** — Drag the project folder into [Netlify Drop](https://app.netlify.com/drop), or connect the repo and use build command: *(leave blank)*, publish directory: `.`
- **Vercel** — Import the repo; set output directory to `.` and leave build command empty for a static site.

No build step or Node.js is required.

## License

Use and modify as needed for your organization.
