# Subharaj Nandi — Portfolio Website

A dark-themed, multi-page personal portfolio built with plain HTML, CSS, and JavaScript — no frameworks, no build step, no backend.

## 🔗 Live Preview
Open `index.html` directly in your browser, or deploy the folder to any static host (GitHub Pages, Netlify, Vercel).

## 📁 Folder Structure

```
portfolio/
├── index.html          # Home page
├── about.html           # About / education / skills
├── projects.html        # Featured projects
├── experience.html      # Work experience
├── contact.html         # Contact info + frontend-only form
├── styles.css           # Shared design system (colors, type, layout)
├── main.js               # Shared JS (nav toggle, scroll reveal)
└── assets/
    ├── profile.jpeg      # Profile photo
    └── sky.jpeg          # Hero background image
```

> ⚠️ **Important:** The `assets` folder must sit in the same directory as the HTML files for images to load. If you move or copy this project, always move the whole folder together — never just the `.html` files.

## 🎨 Design

- **Theme:** Dark, techy, AI/ML-inspired — built around a "training run" motif (an animated loss-curve graphic on the homepage).
- **Colors:** Near-black base (`#0a0e14`) with a neon green/cyan accent (`#39ff8f`).
- **Fonts:** Space Grotesk (headings), Inter (body text), JetBrains Mono (labels/code-style text) — loaded via Google Fonts.
- **Navigation:** Terminal-style breadcrumb (`~/subharaj/about`) reflecting the active page.

## 🛠️ How to Edit

All content lives directly inside the `.html` files as plain text — open any of them in a text editor (VS Code, WebStorm, Notepad, etc.) and edit the text between the HTML tags. No rebuild needed; just save and refresh the browser.

Common edits:
| Want to change... | Edit this file |
|---|---|
| Bio, headline, hero text | `index.html` |
| Education, skills | `about.html` |
| Projects | `projects.html` |
| Work experience | `experience.html` |
| Email, social links, contact form | `contact.html` |
| Colors, fonts, spacing | `styles.css` |
| Mobile menu / scroll animations | `main.js` |

## 📬 Contact Form

The contact form on `contact.html` is **frontend-only** — it validates input and shows a confirmation message, but does not actually send emails anywhere. To make it functional, connect it to a service like:
- [Formspree](https://formspree.io/) — easiest, no backend needed
- [EmailJS](https://www.emailjs.com/) — sends via your own email account
- A custom backend endpoint, if you build one later



## 📄 License

@2026 SUBHARAJ NANDI | All rights reserved | Feel free to use the code structure and Styling without using the jpeg of mine.