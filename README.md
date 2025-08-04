# Netflix Top 10: A Global Viewing Story

Explore global viewing trends with this **interactive narrative visualization** powered by [D3.js](https://d3js.org/). This project visualizes Netflix's Top 10 most-watched shows and films using data from both global and country-specific weekly rankings. Users can interactively explore patterns, compare categories, and gain insights through a multi-scene slideshow.

## 🚀 Features

- **Multi-scene narrative:** Step through key insights with smooth transitions and annotations.
- **Interactive filters:** Filter by category (TV, Films, English, Non-English) and by country.
- **Rich visualizations:** Includes area charts, bar charts, scatter plots, and line graphs.
- **Responsive design:** Works on modern browsers with tooltips, labels, and accessible controls.
- **No setup required:** 100% client-side—just open `index.html` in your browser.

## 📂 Project Structure

- `index.html` — Main HTML file with embedded CSS and D3.js logic.
- `all-weeks-global.tsv` — Global weekly Top 10 Netflix data.
- `country-weekly.tsv` — Country-level weekly Top 10 Netflix data.
- `README.md` — Project documentation.

## 🖥️ Getting Started

1. **Clone or download** this repository.
2. Ensure `index.html`, `all-weeks-global.tsv`, and `country-weekly.tsv` are in the same directory.
3. Open `index.html` in your web browser.
4. Use the navigation and filters to explore the data.

> No server or build tools needed.

## 📊 Scenes Overview

1. **Weekly Global Trends:** Stacked area chart with category and country filters.
2. **Cumulative Viewing Hours:** Compare TV vs. Films globally or by country.
3. **Top Titles:** Bar chart of the most-watched shows and films.
4. **Engagement Analysis:** Scatter plot of views per minute runtime.
5. **Category Trends:** Annotated line graph highlighting trends over time.

## 🛠️ Built With

- [D3.js v7](https://d3js.org/)
- HTML5 & CSS3
- [Roboto font](https://fonts.google.com/specimen/Roboto)
- Data: [Netflix Top 10 weekly viewing hours](https://top10.netflix.com/) (archived as `all-weeks-global.tsv` and `country-weekly.tsv`)

## 👤 Author

Created by Abhisek Sinha for a narrative visualization project.
