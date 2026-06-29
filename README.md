# Ronin-do — Mansur Kohaku

The official website of **Mansur Kohaku** (Mansur Abdulmuslimov) — *Ronin-do*, the dojo of the
masterless samurai. Chechen Adat × Japanese Bushido.

A single self-contained static site: one `index.html`, vanilla JavaScript, zero build step,
zero dependencies. Bilingual (EN / RU). Assets in `assets/`.

## Hosting
Served as a static site (e.g. **GitHub Pages**) — no backend, no Rails, no database required.
To enable GitHub Pages: repo **Settings → Pages → Build from branch → `main` / root**.

## Course applications (email)
The "Apply" form posts to a form-to-email service (e.g. Formspree) which forwards each
submission to the chosen inbox. No server or private-room system — just email. The endpoint
is set in the form's `action` attribute in `index.html`.

## Structure
- `index.html` — the entire site
- `assets/` — artwork, hero images, and the with-masters photographs

---
*Local-authored. Personal project.*
