# TEYZIX_CORE_TASK-03
# Pulsewave — Interactive SaaS Landing Page

**One-line description:** Pulsewave is a real-time API observability
platform that traces, scores, and alerts on request anomalies before they
become customer-facing incidents. This project is its marketing landing
page, built to demonstrate modern frontend development skills.

---

## 🎯 Purpose Alignment

This project was built to satisfy an assignment that asked for an
**Interactive SaaS Landing Page & Product Experience Platform**. Here is
how each requirement was met:

| Assignment asked for | What this project delivers |
|---|---|
| Modern responsive UI | Fully responsive layout — desktop, tablet, mobile |
| Component-based thinking | Clearly separated sections (hero, pricing, FAQ, etc.), each self-contained and reusable |
| Interactive UX | Pricing toggle, expandable table, carousel, accordion, form validation |
| Smooth animations | Scroll reveals, hover states, animated counters, animated waveform |
| Accessibility | Keyboard focus states, semantic HTML, reduced-motion support |
| Performance | No frameworks, no build step, no external images — loads instantly |
| Clean code structure | One well-commented, logically organized file |
| Production-level design | A real visual identity (custom palette, type, and a signature motif) instead of a generic template look |

Rather than build a generic "SaaS landing page," a specific fictional
product (**Pulsewave**, an API monitoring tool) was invented first. This
gives every design choice a *reason*: for example, the scroll-progress bar
at the top of the page is drawn as a waveform/pulse line — because that's
literally what the product shows its own users. This is what "purpose
alignment" means here: the design serves the product's story, not just
decoration.

---

## 🧩 What's Inside (Easy Overview)

Think of the page as a stack of sections, top to bottom:

1. **Navbar** — sticky menu, dark/light mode switch, mobile menu
2. **Hero** — big headline + a live "request trace" preview card
3. **Product Showcase** — 4 feature cards explaining what Pulsewave does
4. **Stats** — animated counters (numbers count up when you scroll to them)
5. **Pricing** — 3 plans, with a toggle to switch monthly ⇄ yearly
6. **Comparison Table** — click a row to expand and see more detail
7. **Testimonials** — auto-sliding customer quotes carousel
8. **FAQ** — click a question to expand the answer
9. **Blog Preview** — 3 sample articles
10. **Contact Form** — validates your input and shows a success message
11. **Footer** — links, social icons, company info

Everything is on one page — just scroll down (or click a nav link to jump
to a section).

---

## 🛠️ Tech Stack (Simple Explanation)

- **HTML, CSS, and JavaScript only** — no React, no npm install, no build
  step. Just open the file and it works.
- **Why no framework?** So anyone — including a non-technical reviewer —
  can open `index.html` directly in a browser with zero setup.
- **Icons/graphics:** hand-drawn using inline SVG, so there are no image
  files to load or go missing.
- **Fonts:** Space Grotesk (headings), Inter (body text), JetBrains Mono
  (numbers/data) — loaded from Google Fonts.

> In a real production team, this would likely be rebuilt with React/Next.js
> and Tailwind so each section becomes a reusable component. The single-file
> version here is intentional: it keeps the demo simple to open, read, and
> deploy anywhere.

---

## 📁 Project Structure

```
pulsewave/
├── index.html     → the entire website (structure + styling + behavior)
└── README.md      → this file
```

---

## 🚀 How to Run It

**Option 1 — Just open it:**
Double-click `index.html` and it opens in your browser. That's it.

**Option 2 — Deploy it for free:**
- **Vercel / Netlify:** drag the `pulsewave` folder into their dashboard
- **GitHub Pages:** push the folder to a GitHub repo, then turn on Pages in
  the repo settings

No build commands, no environment variables, no dependencies to install.

---

## ✅ Accessibility & Performance Notes

- All interactive elements (buttons, links, form fields) are keyboard
  reachable and show a visible focus outline
- Respects the `prefers-reduced-motion` setting for users sensitive to
  animation
- No external JavaScript libraries — keeps the page fast and lightweight
