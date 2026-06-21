# Mohamed Yusuf Kathree — Portfolio Site

> Personal portfolio and CV site for Mohamed Yusuf Kathree, BSc Honours Computer Science candidate at the University of the Western Cape (graduating 2026). Built with pure HTML, CSS, and vanilla JavaScript — zero dependencies, zero build step, deployed on GitHub Pages.

**Live site:** [mohamed-kathree.github.io](https://mohamed-kathree.github.io)

---

## About

This site serves as a living CV and project showcase, targeting software engineering recruiters and hiring managers. It covers six shipped projects spanning reinforcement learning, quantitative finance, embedded systems, full-stack web development, databases, and scientific computing.

---

## Stack

| Concern | Solution |
|---|---|
| Markup | Semantic HTML5 |
| Styling | Vanilla CSS (custom properties, grid, flexbox) |
| Interactivity | Vanilla JavaScript (no frameworks) |
| Fonts | Google Fonts — Cormorant Garamond, Inter, JetBrains Mono |
| Hosting | GitHub Pages (auto-deploy from `main`) |
| Build step | None |

---

## Design

**Aesthetic:** Bone minimalism / quiet luxury. Restrained, typographically confident, monochrome throughout.

```
Background:   #F5F0E8  (warm bone/cream)
Surface:      #FFFFFF  (card backgrounds)
Primary text: #1A1A1A  (near-black ink)
Secondary:    #5C5C5C  (labels, dates, captions)
Borders:      #E0D9CE  (1px rules and card borders)
```

- Zero colour accents — monochrome only
- Sharp corners throughout (no border-radius)
- No box shadows — depth from 1px borders alone
- Display typeface: Cormorant Garamond (editorial serif)
- Body typeface: Inter
- Monospace: JetBrains Mono (terminal block and tech badges only)

---

## Sections

- **Hero** — name, typewriter terminal block, CTA buttons, quick stats
- **About** — professional summary
- **Projects** — six project cards with filterable tech tags
- **Skills** — grouped technical skills in a two-column table
- **Experience** — Senior Student Assistant (UWC) + YES Summit 2025
- **Education** — BSc Honours, BSc CS, NSC
- **Awards & Certifications** — achievements and completed courses
- **Contact** — email, LinkedIn, GitHub, CV download

---

## Featured Projects

| Project | Stack | Status |
|---|---|---|
| RL-Guided Fixed-Wing Glider | Python · JSBSim · Gymnasium (PPO) | Ongoing |
| Automated CFD Trading Bot | Python · MQL5 · Financial Modelling | Ongoing |
| F1 Database Management GUI | Python · MySQL · SQL | Complete |
| Peer-Review & Tutoring Platform | React · Next.js · HTML/CSS | Ongoing |
| Networked Security System | Raspberry Pi · UDP · Java | Complete |
| Physics & Maths Simulations | VPython · Python | Complete |

---

## Repo Structure

```
Mohamed-Kathree.github.io/
│
├── index.html               # Entire site — HTML, CSS, and JS in one file
├── Mohamed_Kathree_CV.pdf   # CV download (linked from Download CV button)
└── README.md                # This file
```

---

## Local Development

No build step required. Open directly in a browser:

```bash
git clone https://github.com/Mohamed-Kathree/Mohamed-Kathree.github.io.git
cd Mohamed-Kathree.github.io
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

Or use a local server for accurate GitHub Pages behaviour:

```bash
# Python
python -m http.server 8000

# Node
npx serve .
```

Then visit `http://localhost:8000`.

---

## Deployment

Every push to `main` triggers an automatic GitHub Pages deployment. The site is typically live within 2–5 minutes of a commit.

```bash
git add .
git commit -m "your message"
git push
```

No configuration required — GitHub Pages serves `index.html` from the repo root automatically.

---

## Contact

**Mohamed Yusuf Kathree**   
[linkedin.com/in/mohamed-kathree](https://www.linkedin.com/in/mohamed-kathree)  
Cape Town, South Africa
