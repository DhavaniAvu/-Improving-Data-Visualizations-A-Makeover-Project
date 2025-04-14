# Bad Graph 📉 to Good Graph 📈 - Improving Data Visualizations: A Makeover Project

This project focuses on identifying poor visualizations from public and redesigning them using principles of data storytelling, clarity, and accessibility. I worked with mortality data from 2015–2020, showcasing how better chart design can uncover meaningful patterns hidden in cluttered or misleading plots.

---

## 🎯 Project Goal

> **Bad graphs hide insights. Good graphs tell stories.**

The aim is to:
- **Spot misleading or ineffective graphs**
- **Redesign them** using R (`ggplot2`, `plotly`, `gganimate`)
- **Explain why the original visualizations failed**
- **Show how improved versions communicate insights clearly**

---

## 📌 Scope of Work

- Start with **raw or flawed visualizations** of gender-based mortality and disease-specific death counts.
- Redesign them by:
  - Choosing proper chart types
  - Fixing colors, labels, and scales
  - Making plots more readable and interpretable
- Add animations, interactivity, and maps for deeper exploration

---

## 🛠️ Tools & Techniques

- **Language**: R
- **Libraries**:
  - `ggplot2`, `plotly` for charting
  - `gganimate` for storytelling
  - `dplyr` for wrangling
  - `plot_geo` for map visualizations

---

## 📊 What We Fixed

| Original Issue | Fix Applied |
|----------------|-------------|
| Overloaded bar charts with hard-to-read labels | Rotated labels, simplified axis |
| Confusing color palettes | Switched to meaningful and colorblind-friendly schemes |
| Static charts lacking impact | Added animation and interactivity |
| No geographic context | Added choropleth maps for disease spread |
| Lack of story/narrative | Introduced titles, subtitles, tooltips, and annotations |

---

## 📈 Before & After Examples

- 🔹 **Grouped bar chart** → cleaner, gender-split chart with percentage labels inside bars  
- 🔹 **Static disease plot** → animated ranking by total deaths  
- 🔹 **Death rates across US states** → transformed into intuitive choropleth maps  
- 🔹 **Multi-disease trend over years** → polished line graph with distinct styles for each disease

---

## 📁 Project Structure

Graph-Makeover-Health/
- Badgraph_goodgraph_combined.Rmd : Complete analysis and all redesigns
- Badgraph_goodgraph_combined.pptx: Presentation slides with Before/after visualizations
- README.md                       : Project documentation (this file)


---

## 📌 Data Sources

- Mortality data (2015–2020) by disease, gender, and state — simulated or sourced from public records (you can link source if needed).

---

## 🧠 Lessons Learned

- Even accurate data can mislead when visualized poorly.
- Good graphs don’t just look pretty — they enhance comprehension.
- Tools like `gganimate` and `plotly` allow stories to unfold visually and interactively.

---

## 👩‍💻 Author

**Dhavani Avu**  

---

> ✨ This is a data storytelling and visualization cleanup project — showing how we can turn cluttered charts into compelling insights.

