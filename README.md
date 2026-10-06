# Abubakar Jalil — Personal Portfolio

A responsive single-page developer portfolio built with HTML, CSS and vanilla JavaScript. Showcases projects, skills, process, and contact form with subtle animations, an interactive hero canvas background, and GSAP scroll/entrance animations.

Live demo: Open `index.html` in any browser (or deploy to GitHub Pages).

## Features

- Clean, responsive single-page layout (Home, About, Skills, Projects, Process, Contact)
- Animated hero particle background (canvas)
- GSAP-powered scroll and entrance animations
- Project cards with links to GitHub repositories
- Contact form demo (static, shows success message on submit)
- Progressive, accessible-friendly UI with Google Fonts and Font Awesome icons

## Tech / Libraries

- HTML, CSS, JavaScript
- Google Fonts — Poppins & Inter
- Font Awesome (CDN) for icons
- GSAP (CDN) for animations
- No build step required (static site)

## Quick start

1. Clone the repository
   ```
   git clone https://github.com/M-Abu-bakar-71/My-Portfolio.git
   cd My-Portfolio
   ```

2. Open locally
   - Option A: Open `index.html` directly in your browser.
   - Option B: Serve with a simple HTTP server (recommended for some browsers):
     ```
     # Python 3
     python3 -m http.server 8000
     # then open http://localhost:8000 in your browser
     ```

## Customize

- Update your name, headline, description and links in `index.html`.
- Replace the avatar image: currently uses your GitHub avatar URL — change the `<img src="...">` inside the About section.
- Edit projects: update the projects list inside the Projects section (`<section id="projects">`) with your latest repos, descriptions and links.
- Change skills: adjust the progress `data-level` attributes on `.progress-bar` elements to reflect your expertise.

## Deployment (GitHub Pages)

1. Push your changes to the `main` branch.
2. In the repository settings → Pages, set the source to the `main` branch and the site root (`/`).
3. Save and visit the provided GitHub Pages URL after a minute.

## Accessibility & performance notes

- The site is a static HTML page with semantic sections and keyboard-focusable links/buttons.
- For better performance and privacy, consider bundling or self-hosting critical fonts and reducing external CDN requests if desired.

## Contributing

This repository is a personal portfolio; contributions are optional. If you'd like to suggest a change:
- Open an issue describing the change.
- Or send a pull request with a small, focused diff.

## Credits & assets

- Fonts: Poppins & Inter — Google Fonts
- Icons: Font Awesome (CDN)
- Animations: GSAP (CDN)
- Particle background: custom canvas script included in `index.html`

## License

This project is available under the MIT License. See `LICENSE` (add one if you want to include it).

## Contact

- GitHub: https://github.com/M-Abu-bakar-71  
- LinkedIn: https://www.linkedin.com/in/m-abubakar-jalil-a2b671353/  
- Fiverr: https://www.fiverr.com/s/e6pzXmm
