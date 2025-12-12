# Take-Home Final: Teaching Data Science Concepts (INFO 7390)

This repository contains my take-home final for **INFO 7390: Advanced Data Science and Architecture**.  
The concept taught is **Storytelling with Data: Interactive Dashboards & Perception-Based Design**, implemented as a **Google Colab tutorial notebook** with interactive Plotly visualizations and exercises.

---

## Concept Summary
**Data storytelling** = **Data + Visualization + Narrative**

We use a simple three-act structure:
- **Act 1 (Setup):** Context, baseline patterns, KPIs
- **Act 2 (Conflict):** Insights, disparities, outliers, “why is this happening?”
- **Act 3 (Resolution):** Action steps, what to investigate next, impact framing

---

## Dataset
**Gapminder dataset** (bundled with Plotly: `plotly.express.data.gapminder()`)

Why this dataset:
- Works reliably in Google Colab (no broken download links)
- Clean schema for teaching visualization and storytelling
- Includes time, region (continent), population, GDP per capita, life expectancy

---

## Learning Outcomes
By the end of the tutorial, learners can:
- Choose appropriate charts based on relationship type (trend, distribution, correlation)
- Apply perception-based design (visual hierarchy, pre-attentive cues, log scaling)
- Build interactive Plotly visualizations and a dropdown-based mini-dashboard
- Identify outliers via residual reasoning (expected vs observed)
- Translate charts into clear, action-oriented insights

---

## Run in Google Colab
Open and run the notebook here:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kommurisi/Take-Home-Final-Teaching-Data-Science-Concepts/blob/main/notebooks/gapminder_storytelling_dashboard.ipynb)

> Run cells top-to-bottom. Plotly is installed in the first code cell.

---

## Repository Structure (Recommended)
```
Take-Home-Final-Teaching-Data-Science-Concepts/
├─ README.md
├─ requirements.txt
├─ .gitignore
├─ notebooks/
│  └─ gapminder_storytelling_dashboard.ipynb
├─ docs/
│  ├─ tutorial_documentation.pdf
│  └─ pedagogical_report.pdf
└─ assets/
   └─ (optional screenshots)
```

---

## Deliverables Included
- **Interactive Tutorial Notebook**: `notebooks/gapminder_storytelling_dashboard.ipynb`
- **Tutorial Documentation (PDF/Web)**: `docs/tutorial_documentation.pdf`
- **Pedagogical Report (PDF)**: `docs/pedagogical_report.pdf`
- **Video (10 min max)**: add your link below

### Video Link
- (Paste your unlisted YouTube / Drive link here)

---

## Local Setup (Optional)
```bash
pip install -r requirements.txt
```

---

## Notes
- This project avoids `ipywidgets` to reduce Colab rendering issues.
- Interactivity is implemented using Plotly dropdown menus for reliability.
