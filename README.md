# Sabz Ali — Portfolio

A single-file, self-contained personal portfolio (operator-console theme) for
Sabz Ali, Azure Cloud Administrator & DevOps Engineer.

No build step, no frameworks, no internet required to render — all CSS, icons,
and scripts are inline.

## Files to upload

Upload **all of these together, in the same folder**:

```
index.html            ← the site (entry point — hosts load this automatically)
headshot.jpg          ← profile photo
Sabz-Ali-Resume.pdf   ← downloadable CV (the "Download CV" button links to it)
favicon.svg           ← browser-tab icon
```

## How to publish (pick one — all free)

### Option A — Netlify Drop (fastest, ~30 seconds)
1. Go to https://app.netlify.com/drop
2. Drag this whole folder onto the page.
3. You get a live URL instantly. (Optional: sign in to keep it / add a custom domain.)

### Option B — GitHub Pages
1. Create a new GitHub repository.
2. Upload these four files to the repo root.
3. Repo **Settings → Pages → Build and deployment → Source: Deploy from a branch**,
   pick `main` / `root`, Save.
4. Your site goes live at `https://<username>.github.io/<repo>/`.

### Option C — Azure Static Web Apps / Cloudflare Pages / Vercel
Point any of these at the repo (or drag-and-drop the folder). App location / root = `/`.

## Editing content later

Everything lives in `index.html`:

- **Text** (name, bio, experience, skills) — search the section comments like
  `<!-- ============ ABOUT ============ -->` and edit the visible text.
- **Accent color** — change `--accent` and `--accent-2` at the very top of the
  `<style>` block (`:root`) to re-skin the whole site.
- **Skill levels** — each tool has a badge: `<span class="lvl exp/adv/int">`.
- **Resume** — replace `Sabz-Ali-Resume.pdf` with an updated file of the same name.

## Features

Interactive terminal · Ctrl/⌘+K command palette · light/dark toggle ·
English/Urdu (EN/UR) · animated status console · collapsible experience ·
smooth scrolling · back-to-top · fully responsive (mobile drawer nav).

---
Contact: sabzalikhan333@gmail.com · https://www.linkedin.com/in/sabzalikhan/
