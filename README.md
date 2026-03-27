# Unheard Needs, Unequal Burdens
### NYC Community Datathon 2026 · Team 10

> *Three years of community voices on health inequity in New York City*

**🏆 Submitted for: Best Digital Data Story — NYC Community Datathon, March 27, 2026**

---

## 🔗 Live Site

> Deploy via GitHub Pages (see instructions below)

---

## About This Project

This interactive data story analyzes **8,142 proposals** submitted to New York City's [People's Money Program](https://www.nyc.gov/site/civicengagement/index.page) across three years, tagged through the lens of **Social Determinants of Health (SDOH)**:

| Domain | Year 1 | Year 2 | Year 3 |
|---|---|---|---|
| Economic Stability | 334 | 153 | 1,099 |
| Healthcare Access & Quality | 737 | 341 | 1,092 |
| Neighborhood & Built Environment | 655 | 420 | 848 |
| **Total** | **2,202** | **1,945** | **3,995** |

### Key Findings
- 📈 Total proposals **nearly doubled** from Year 1 to Year 3
- 🏘️ **Bushwick** appears in the top 5 across all 3 years, across all 3 domains
- 🏥 **Jamaica** had the highest healthcare proposals of any single neighborhood in Year 1
- 💰 Economic Stability proposals surged **3×** from Year 1 to Year 3

---

## Team

**Preethi Sridhar, Samiha Akter & Soad Hossain**  
Team 10 · NYC Datathon 2026  
In partnership with the NYC Civic Engagement Commission

---

## Tech Stack

- Pure HTML5 / CSS3 / Vanilla JavaScript
- [Chart.js 4.4.1](https://www.chartjs.org/) — interactive data visualizations
- [Google Fonts](https://fonts.google.com/) — Playfair Display, Source Serif 4, DM Sans
- Zero dependencies, zero build tools — just open `index.html`

---

## 🚀 Deploy to GitHub Pages (Free Hosting)

### Option 1: GitHub.com (No Terminal Needed)

1. Go to [github.com](https://github.com) and sign in (or create a free account)
2. Click the **+** icon → **New repository**
3. Name it: `peoples-money-datathon` (or anything you like)
4. Set to **Public**, click **Create repository**
5. Click **uploading an existing file**
6. Drag and drop `index.html` and this `README.md`
7. Click **Commit changes**
8. Go to **Settings** → **Pages** (left sidebar)
9. Under **Source**, select `main` branch → `/ (root)` → click **Save**
10. Your site will be live at: `https://YOUR-USERNAME.github.io/peoples-money-datathon`

### Option 2: Terminal / Git

```bash
# Clone or create repo
git init peoples-money-datathon
cd peoples-money-datathon

# Add files
cp /path/to/index.html .
cp /path/to/README.md .

# Push to GitHub
git add .
git commit -m "Initial commit: NYC Datathon data story"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/peoples-money-datathon.git
git push -u origin main
```

Then enable GitHub Pages in repo **Settings → Pages → Source: main branch**.

---

## Rubric Alignment

| Criterion | How We Address It |
|---|---|
| **Narrative Impact & Storytelling** | Rosa's day-in-the-life opens the story; scrollytelling moves from problem → evidence → insight → action |
| **Community Voice & Representation** | Data framed around lived experience; Rosa humanizes systemic issues without tokenizing |
| **Visual & Interactive Design** | NYT-style typography, animated charts, scroll-triggered reveals, progress bar, tab navigation |
| **Analytical Foundation** | Python-parsed SDOH tagging methodology explained; data notes included |
| **Public Engagement & Usability** | Responsive design, high contrast, clear calls to action, accessible color choices |

---

## Data Source

NYC Civic Engagement Commission — People's Money Program, Years 1–3  
Parsed using Python with SDOH domain tagging via Impact Area classifications and keyword matching.

---

*Made with ❤️ for the communities of NYC who keep showing up, year after year.*
