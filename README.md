# Netflix Top 10: A Global Viewing Story

 This is a narrative visualization project that combines a clear message, a structured interactive slideshow, scene-specific visual designs, effective annotations, well-defined parameters, and intuitive triggers. It guides users from global patterns to local details, supporting both storytelling and exploration, and exemplifies best practices in narrative visualization design.

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

1. **Global Overview:** Introduces the worldwide context, showing which countries have the most prominent titles.
2. **Regional Favorites:** Highlights differences and similarities in top titles across countries, supporting regional comparison.
3. **Genre Trends:** Explores the balance between Films and TV, providing insight into content type preferences.
4. **Language Divide:** Examines the role of language, contrasting English and Non-English content.
5. **Country Explorer:** Allows users to select any country and see its unique viewing patterns, supporting deep, user-driven exploration.


## 🛠️ Built With

- [D3.js v7](https://d3js.org/)
- HTML5 & CSS3
- Data: [Netflix Top 10 weekly viewing hours](https://top10.netflix.com/) (archived as `all-weeks-global.tsv` and `country-weekly.tsv`)

## 👤 Author
Created by Abhisek Sinha for a narrative visualization project.
