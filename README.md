# Ashvin Kumar — Personal Website

My one-page personal site — live at **[meet-ashvin.vercel.app](https://meet-ashvin.vercel.app/)**. A single static HTML file with inline CSS and JS — no build step, no dependencies.

## Structure

| File | What it is |
| --- | --- |
| `index.html` | The entire site (inline CSS + JS) |
| `Ashvin_Kumar_CV.pdf` | CV, linked from the site's **Résumé** button |
| `og-image.png` | Social share preview (1200×630), used by `og:image` / Twitter card |
| `robots.txt` | Allows all crawlers; points to the sitemap |
| `sitemap.xml` | Single-URL sitemap for search engines |

## Local preview

Open `index.html` in any browser. That's the whole thing.

## Deploy (Vercel)

Import this repo at [vercel.com](https://vercel.com) → **Add New → Project** → Framework preset **Other** → **Deploy**.

Vercel serves `index.html` at the root, and the CV is available at `/Ashvin_Kumar_CV.pdf`.

## Tech

Plain HTML / CSS / JS. Type set in Bricolage Grotesque, Hanken Grotesk, and JetBrains Mono (Google Fonts). Light and dark themes with a manual toggle (remembers your choice). Fully responsive.
