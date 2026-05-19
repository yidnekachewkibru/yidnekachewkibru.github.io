# Yidnekachew Kibru — Portfolio

A personal portfolio website showcasing my work as a Software Engineer and BSS Operations Manager. Built as a single static HTML file with vanilla CSS and JavaScript — no build step, no frameworks, no dependencies.

🌐 **Live site:** [yidnekachewkibru.github.io/Portfolio](https://yidnekachewkibru.github.io/Portfolio)

## About

I'm Yidnekachew Kibru Afework — a full-stack .NET developer and BSS Operations Manager based in Addis Ababa, Ethiopia. This site is where I introduce myself, list the services I offer, and share a snapshot of the systems I've worked on across telecom, finance, government, healthcare, and education sectors.

If you're here looking for someone to build software, automate a process, or help with a telecom integration, the contact section is the quickest way to get in touch.

## Services covered

- Website & web application development
- Custom software development
- AI & intelligent automation
- Business process automation
- Telecom systems consulting (BSS, CRM, UPC, SDP, Bulk SMS, Number Management)
- Enterprise systems operations & monitoring
- Digital marketing

## Tech stack

- **HTML5** — semantic markup, single-file structure
- **CSS3** — custom properties, grid, flex, transitions; no Tailwind or framework
- **Vanilla JavaScript** — theme toggle, scroll-aware navigation, modal, intersection-observer fade-ins
- **Plus Jakarta Sans** and **Source Serif 4** from Google Fonts

## Features

- 🌓 **Dark / light mode toggle** — remembers your preference, follows system setting on first visit
- 📱 **Fully responsive** — works on phones, tablets, and desktops
- ⚡ **Fast** — single HTML file, no build, no JS frameworks, no external dependencies beyond fonts
- ♿ **Accessible** — keyboard navigation, focus rings, ARIA labels, respects `prefers-reduced-motion`
- 🎨 **Custom favicon** — embedded as SVG, no separate file needed
- ✉️ **Custom contact modal** — animated success dialog instead of a default browser alert
- 🔝 **Smooth scrolling** with scroll-spy navigation and back-to-top button

## File structure

```
Portfolio/
├── index.html      # The entire site (HTML, CSS, JS all in one)
└── README.md       # This file
```

That's it. Everything is in `index.html`.

## Running locally

No build step needed. Either:

1. **Open directly** — double-click `index.html` to open it in your browser, or
2. **Serve locally** for a more realistic environment:
   ```bash
   # Python 3
   python -m http.server 8000

   # Node (if installed)
   npx serve
   ```
   Then visit `http://localhost:8000`.

## Deployment

This site is deployed via **GitHub Pages**. To deploy your own copy:

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Under "Build and deployment", set source to **Deploy from a branch**
4. Select the **main** branch and **/ (root)** folder
5. Save — GitHub will publish the site within 1–2 minutes

Any commit to the `main` branch automatically updates the live site.

## Customization

If you'd like to adapt this for your own portfolio:

- **Colors** — edit the CSS variables under `:root[data-theme="dark"]` and `:root[data-theme="light"]` at the top of the `<style>` block
- **Content** — all text is directly in the HTML; no separate data file to manage
- **Favicon** — replace the SVG inside the `<link rel="icon">` data URI in `<head>`
- **Sections** — each section (`#services`, `#projects`, etc.) is self-contained and can be added, removed, or reordered

## Contact

- **Email** — [yidnekibru@gmail.com](mailto:yidnekibru@gmail.com)
- **Phone / WhatsApp** — [+251 912 708 459](tel:+251912708459)
- **Location** — Addis Ababa, Ethiopia · Available globally for remote work

For project inquiries, the [contact form on the site](https://yidnekachewkibru.github.io/#contact) is the fastest way to reach me.

## License

The portfolio content (text, personal information, project descriptions) is © Yidnekachew Kibru Afework and not licensed for reuse.

The site's underlying HTML/CSS/JS structure is free for you to use as a template or learning resource — attribution appreciated but not required. If you build something nice with it, I'd love to see it.

---
