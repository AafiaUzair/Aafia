
# Aafia Uzair | Portfolio Website

A dark-themed, animated personal portfolio showcasing my resume, work experience, projects and certificates. Built with plain HTML, CSS and JavaScript in a single file, with no frameworks or build step.

**Live site:** https://your-portfolio-link.vercel.app *(replace with your deployed link)*

## About

I'm Aafia Uzair, a web developer and BS Cloud Computing & Information Sciences student at SSUET, Karachi. This site brings together my experience, projects, certificates and creative work in one place.

## Features

- **Animated hero:** letter-by-letter name reveal, a typing effect for my roles, a floating profile photo and a cursor-following glow
- **Experience timeline:** a line that fills in as you scroll
- **Project showcase:** 11 projects with category filters (Web, AI, Python, Networks, Design), browser-style previews and **Visit live site** and **GitHub** buttons
- **3D tilt and spotlight** effects on project cards
- **Certificates and awards** section, including the Alibaba Cloud AI Hackathon Top 10 recognition
- **Scrolling skills marquee** that pauses on hover
- **Scroll progress bar** and active-section highlighting in the navbar
- **Fully responsive** with a mobile menu
- **Accessible:** visible keyboard focus and `prefers-reduced-motion` support

## Tech stack

| Area     | Tools                                                        |
| -------- | ------------------------------------------------------------ |
| Markup   | HTML5                                                        |
| Styling  | CSS3 (custom properties, grid, flexbox, keyframe animations) |
| Behavior | Vanilla JavaScript (IntersectionObserver, Pointer Events)    |
| Fonts    | Bricolage Grotesque and Instrument Sans (Google Fonts)       |

## Getting started

1. Clone the repository:
   ```bash
   git clone https://github.com/AafiaUzair/<your-repo-name>.git
   cd <your-repo-name>
   ```
2. Open `index.html` in your browser. For live reload in VS Code, install the **Live Server** extension, then right-click the file and choose **Open with Live Server**.

> Rename `aafia-portfolio.html` to `index.html` so hosting platforms pick it up automatically.

An internet connection is needed the first time so the Google Fonts load.

## Customizing

- **Projects:** edit the `const P=[...]` list in the `<script>` section. Each entry has a title, description, tags, category, live link and GitHub link.
- **Experience, certificates and education:** edit the matching blocks in the HTML.
- **Colors:** change the variables at the top of the `<style>` section (`--bg`, `--orchid`, `--peach`, `--mint`).
- **Photo:** replace the image in the hero with your own, either as an `images/` file or an embedded data URI.

## Deployment

**Vercel**

1. Push the repository to GitHub.
2. Import it at [vercel.com/new](https://vercel.com/new) and deploy. No build settings are needed.

**GitHub Pages**

1. Go to **Settings → Pages**.
2. Set the source to the `main` branch and the root folder, then save.

## Featured projects

| Project                                             | Live                                             | Code                                                   |
| --------------------------------------------------- | ------------------------------------------------ | ------------------------------------------------------ |
| Settlr.ai (Top 10, Alibaba Cloud AI Hackathon 2026) | [Visit](https://settlr-ai.vercel.app)             | [GitHub](https://github.com/AafiaUzair/Settlr.ai)       |
| HR Hiring System                                    | [Visit](https://hr-hiring-system.vercel.app)      | [GitHub](https://github.com/AafiaUzair/HR-HiringSystem) |
| AuraTech E-Commerce Store                           | [Visit](https://aura-tech-store-mauve.vercel.app) | [GitHub](https://github.com/AafiaUzair/aura-tech-store) |
| WeCloud                                             | [Visit](https://we-cloud-mu.vercel.app)           | [GitHub](https://github.com/AafiaUzair/we-cloud)        |

## Contact

- Email: [aafiauzair1@gmail.com](mailto:aafiauzair1@gmail.com)
- LinkedIn: [linkedin.com/in/aafia-uzair](https://www.linkedin.com/in/aafia-uzair)
- GitHub: [github.com/AafiaUzair](https://github.com/AafiaUzair)
- Design portfolio: [Canva](https://graphic-portfolio-aafia.my.canva.site/)

## License

© 2026 Aafia Uzair. All rights reserved. Please don't copy this site's content or photos without permission.
