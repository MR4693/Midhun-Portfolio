# Midhun Rajan — Manufacturing Digital Transformation Portfolio

Executive engineering portfolio for a Manufacturing & Process Engineer who led a digital
transformation programme across a live precision sheet metal environment — four ERP-integrated
systems, built with AI-assisted development under full engineering direction.

**Live site:** https://mr4693.github.io/Midhun-Portfolio/

Static HTML/CSS/JS — no build step, GitHub Pages ready.

## Pages
| File | Purpose |
|------|---------|
| `index.html` | Executive landing — positioning, ecosystem, executive architecture diagram, transformation journey |
| `showcase.html` | Project showcase — four live platforms, problem → solution → impact, with screenshots |
| `architecture.html` | System architecture, tech stack, data flow, AI integration |
| `intelligence.html` | Manufacturing Intelligence Platform — dashboards, KPIs, why each matters |
| `resume.html` | Résumé (with Download CV button) |
| `contact.html` | Contact + closing statement |
| `404.html` | Custom not-found page (root-relative links) |

## Structure
```
├── index.html  showcase.html  architecture.html  intelligence.html  resume.html  contact.html
├── 404.html
├── Midhun_Rajan_CV.pdf          # downloadable résumé
├── assets/                      # site.css, site.js, favicons, web manifest
├── screenshots/                 # application screenshots (customer/employee names redacted)
│   ├── sc-01..07 (Operations Platform)
│   ├── pi/   (Manufacturing Intelligence Platform)
│   ├── jpa/  (Digital Job Pack Platform)
│   └── dms/  (Document Intelligence Platform)
├── .nojekyll  robots.txt  sitemap.xml  .gitignore
```

## The four platforms
Manufacturing Operations Platform · Manufacturing Intelligence Platform · Digital Job Pack
Platform · Document Intelligence Platform. All share a single SQL Server data layer connected to
MIE Trak ERP. KPIs: 19 operators · 14 work centres · 4 systems live in production (2025).

## Privacy
Customer and employee names in the screenshots have been redacted for privacy and
data-protection reasons; an on-page note appears wherever redaction was applied.

## Deploy (GitHub Pages)
Repository: `MR4693/Midhun-Portfolio` (project site → served from a subpath).

1. Push the contents of this folder to the repo's `main` branch.
2. In GitHub: **Settings → Pages → Build and deployment → Deploy from a branch → `main` / `/ (root)`**.
3. The site goes live at **https://mr4693.github.io/Midhun-Portfolio/**.

`.nojekyll` disables Jekyll so every file is served as-is. `404.html` uses
`<base href="/Midhun-Portfolio/">` so its links resolve correctly under the subpath — if you
ever rename the repo, update that one line (and `sitemap.xml` / `robots.txt`).

> Tip: for a shorter root URL (`https://midhunrajan.github.io`), create a repo named
> `midhunrajan.github.io` instead and remove the `<base>` tag from `404.html`.
