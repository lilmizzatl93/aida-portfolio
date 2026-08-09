# Aïda Mokube — Portfolio

Personal UX design portfolio. Built with plain HTML/CSS/JS — no build step.

## Structure
```
aida-portfolio/
├── index.html                        → Homepage (hero, 4 case study cards, stats, contact)
├── about.html                        → About Me page
├── case-studies/
│   ├── ai-writing.html               → AI Writing Companion
│   ├── next-best-action.html         → Next Best Action
│   ├── data-definitions.html         → Data Definitions (honest process framing)
│   └── onvation.html                 → Onvation Intelligent Washroom
├── css/
│   ├── shared.css                    → Design tokens, nav, footer, testimonials, buttons
│   └── case-study.css                → Case study page template (hero, principles, process, tensions)
├── js/
│   └── shared.js                     → Cursor + scroll-reveal animation, used on every page
├── images/                           → Drop all photos here
├── vercel.json                       → Vercel config
└── .gitignore
```

## Adding your photos
Several placeholder divs are still marked with "Add [photo] here" text — replace with:
```html
<img src="images/your-photo.jpg" alt="description">
```
Still needed: hero photo variant, Puerto Rico photo (about.html), Disney/Wakanda photo (about.html), and mockup screenshots for all 4 case study cards on the homepage and within each case study page.

## Content notes
- **Onvation case study** is built from established facts but is lighter on specifics than the other three (original research notes/screenshots from an earlier session weren't available in this rebuild) — see the HTML comment at the top of `case-studies/onvation.html` for what would deepen it.
- **Homepage stats bar** was rebuilt from scratch — the previous version (200+ feature ideas, 350+ bugs, 92% satisfaction) used unverifiable volume metrics. Current stats are all sourced and defensible.
- **About page "Career Transition" entry** was replaced with an honest, specific line (Graduate Studies, Dentistry, 2020–2022) rather than a vague placeholder.

## Deploying to Vercel
1. Push this folder to a GitHub repo
2. Go to vercel.com → New Project → Import your repo
3. No build settings needed — it's plain HTML
4. Hit Deploy. Done.

## Working with Claude going forward
- Design/content iteration happens in chat (or Claude Design, if you're testing that workflow)
- Bring the resulting files back here for integration and QA
- Push to GitHub → Vercel auto-deploys
