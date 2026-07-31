# Cybersecurity Portfolio

Live site: [swetha0175.github.io](https://yourusername.github.io)

A single-page portfolio built to showcase my skills, hands-on projects, and certifications for recruiters and hiring teams — in place of a static PDF resume. Designed around a terminal/SOC-dashboard aesthetic to reflect a security-focused background.

## Sections

- **Home** — intro terminal panel with name, role, and quick links
- **About** — background, current focus, and certifications in progress
- **Skills** — grouped by Defensive, Offensive, Systems & Networking, and Scripting
- **Projects** — SOC investigations, threat hunts, automation builds, and personal dev projects, each with a short summary and a link to a full writeup
- **Certifications** — completed and in-progress certs with verification links
- **Experience** — professional work history with detailed, bullet-point responsibilities
- **Education** — degree, coursework, and final year project
- **Contact** — email, LinkedIn, GitHub, and downloadable resume (PDF)

## Project writeups

Full writeups for select projects live in [`/writeups`](./writeups), each as a standalone page matching the main site's design:

- `writeups/phishing-remediation.html` — True-Positive Phishing Email Analysis & Remediation

More writeups will be added here as projects are documented in full.

## Built with

- HTML5 / CSS3 (no framework, no build step)
- Vanilla JavaScript (hamburger navigation menu)
- Hosted for free on [GitHub Pages](https://pages.github.com/)

## Project structure

```
├── index.html              # main portfolio page
├── resume.pdf              # downloadable resume
└── writeups/
    └── phishing-remediation.html
```

## Running locally

No build process required — clone the repo and open `index.html` directly in a browser:

```bash
git clone https://github.com/yourusername/yourusername.github.io.git
cd yourusername.github.io
open index.html   # or just double-click the file
```

## Notes

This repo is the source for my live portfolio site, not a general-purpose template — but feel free to fork it if you'd like a starting point for your own.
