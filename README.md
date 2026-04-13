# Fatima Zohra Hligue — Personal Portfolio

Personal portfolio website reflecting my professional profile, technical projects, and social engagement work.

**[Live Site →](https://hligue-fatimazohra.vercel.app/)**

---

## About

I'm a multilingual professional based in Tangier, Morocco, working at the intersection of AI quality evaluation, full stack development, and human rights advocacy. This site is my full picture — not just a CV.

It covers:

- **Professional experience** — AI annotation & evaluation, business operations, compliance, sales, and remote work across US and Moroccan companies
- **Technical skills** — Full stack development, AI/NLP tools, multilingual systems, and three deployed projects
- **Social engagement** — Human rights activism, gender equality advocacy, NGO co-founding, UN civil society contribution, and youth leadership
- **Personal side** — The person behind the work

---

## Projects Featured

| Project | Stack | Live |
|---------|-------|------|
| Smart Budget & Life Planner | React 18 · Supabase · Groq API · PWA · 8 languages | [smart-budget-app-mu.vercel.app](https://smart-budget-app-mu.vercel.app/login) |
| CV × JD Reviewer | Vanilla JS · Groq API | [c-vx-jd.vercel.app](https://c-vx-jd.vercel.app/) |
| Darija & Arabic Annotator | Vanilla JS · Groq API | [darija-arabic-nlp-annotator.vercel.app](https://darija-arabic-nlp-annotator.vercel.app/) |

---

## Tech

- Pure HTML, CSS, and JavaScript — no framework, no build step, no dependencies
- Google Fonts — Cormorant Garamond + Poppins
- Fully responsive — mobile, tablet, desktop
- Single file deployment — open `index.html` directly or push to any static host

---

## File Structure

```
/
├── index.html
└── assets/
    └── images/
        ├── profile.jpg           # Hero photo (3:4 ratio recommended)
        ├── hiking.jpg            # Personal — Jbel Tizirane, 2106m
        ├── sea.jpg               # Personal — Tangier coast at sunset
        ├── travel.jpg            # Personal — travel
        ├── food.jpg              # Personal — food
        ├── erasmus.jpg           # Social impact — Erasmus+ Marrakech 2022
        ├── hackathon.jpg         # Social impact — Hackathon Khmiset 2023
        ├── cinema-women.jpg      # Social impact — Cinema & Women Larache 2023
        ├── embassy.jpg           # Social impact — Netherlands Embassy Feb 2024
        ├── bootcamp.jpg          # Social impact — Young Leaders Bootcamp 2023
        ├── feministes.jpg        # Social impact — Féministes Press Conf. Rabat 2024
        ├── youth-awareness.jpg   # Social impact — Youth Awareness Larache 2024
        └── red-crescent.jpg      # Social impact — Red Crescent volunteer work
```

Drop images into `assets/images/` using the exact filenames above. No code changes needed — the site picks them up automatically.

---

## Sections

1. **Hero** — Name, bio, LinkedIn / GitHub / Smart Budget App links, stats (3+ years, 4 languages, 15+ social actions, 95%+ AI accuracy)
2. **Experience** — 8 professional roles, most recent two pinned in dark cards with ongoing indicator
3. **Skills** — Technical stack, currently learning, AI & data annotation, business & operations, leadership & advocacy, language proficiency bars, three credential callout boxes
4. **Education** — 5 entries including ALX VA certification (98.43%) and two international baccalauréats
5. **Social Engagement** — 13 activism entries, 5 Larache youth empowerment sessions, "In the Field" photo grid
6. **Projects** — 3 live deployed tools with descriptions, tags, and live links
7. **Personal** — Bio and 4-photo gallery (hiking, sea, travel, food)
8. **Contact** — Red strip with email, LinkedIn, GitHub

---

## Deployment

No build step needed. Options:

**Vercel:**
```bash
npm i -g vercel
vercel
```

**GitHub Pages:**
Push to a repo → Settings → Pages → select branch → save.

**Netlify:**
Drag and drop the project folder at [app.netlify.com/drop](https://app.netlify.com/drop).

**Local:**
Just open `index.html` in any browser.

---

## Customisation

All content is in `index.html`. To update:

- **Profile photo** — replace `assets/images/profile.jpg` (3:4 ratio)
- **Social links** — search for `linkedin.com` and `github.com` and update the hrefs
- **Instagram links** — uncomment the `ig-tag` lines inside social engagement cards and add your handles
- **Project cards** — find the `#projects` section and update title, description, tags, and href
- **Coming soon card** — one placeholder slot remains for a future project

---

## Colour Palette

| Variable | Hex | Usage |
|----------|-----|-------|
| `--black` | `#080808` | Background, dark cards, nav |
| `--black-2` | `#111111` | Hover states |
| `--red` | `#c8102e` | Accents, labels, bars, CTAs |
| `--red-lt` | `#e8294a` | Hover on red elements |
| `--white` | `#ffffff` | Body background, text on dark |
| `--off` | `#f4f4f4` | Alternate section backgrounds |
| `--grey` | `#888888` | Muted text |
| `--border` | `#e0e0e0` | Dividers, card borders |

---

## Author

**Fatima Zohra Hligue**
- [LinkedIn](https://www.linkedin.com/in/fatima-zohra-hligue/)
- [GitHub](https://github.com/Jenniyaa)
- fatimazohrahligue@gmail.com
- Tangier, Morocco · Open to Remote

---

## License

MIT
