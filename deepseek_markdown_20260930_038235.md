# CVForge

> **Beautiful CVs. Simple pricing.**

A fast, static CV builder that runs entirely in the browser. Live editing, 20 elegant templates, one-click PDF export, and local saving — no signup, no server, no subscription.

**Live demo:** https://yourusername.github.io/cvforge/

---

## ✨ Features

- **Live CV editor** — type on the left, watch the A4 preview update instantly on the right
- **20 professionally-designed templates** across 6 layout systems (split, single, centered, band, rail, sidebar)
- **Personal details, summary, experience, education, skills, projects, certifications** — all editable
- **Add / remove repeatable entries** for experience, education, and projects
- **Client-side PDF export** using `html2pdf.js` (A4, 300 DPI-equivalent, clean margins)
- **Zoom controls** — preview from 55% to 115%
- **Local persistence** — your draft is saved in `localStorage` and reloaded on your next visit
- **Print stylesheet fallback** — if the PDF library fails to load, `Ctrl/Cmd+P` prints only the CV
- **Responsive** — works on desktop, tablet, and mobile
- **Zero build step** — one HTML file, works from `file://` or any static host

---

## 🚀 Quick start

### Option 1 — Just open it

1. Download `index.html`
2. Double-click it — it opens in your browser
3. Click **Create CV**, fill in your details, download your PDF

No install, no server, no npm.

### Option 2 — Run a local server (recommended for dev)

```bash
# Python 3
python -m http.server 8000

# or Node
npx serve .