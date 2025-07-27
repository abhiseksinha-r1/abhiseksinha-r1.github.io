# Netflix Top 10: A Global Viewing Story

This project is a **narrative visualization** built using [D3.js](https://d3js.org/) that explores trends from Netflix's global Top 10 most-watched shows and films. It uses a **multi-scene interactive slideshow** structure to guide the user through key insights with options to explore.

## 🔍 Features

- 📊 Multiple data-driven scenes with annotations and transitions
- 🔄 Interactive filters for exploring different categories (TV, Films, English, Non-English)
- 📈 Visual elements include area charts, bar charts, scatter plots, and line graphs
- ✍️ Designed with clear narrative messaging and visual consistency
- 💡 Highlights cumulative trends, engagement metrics, and top titles
- 💬 Tooltips, labels, and annotations for user-friendly storytelling

## 📁 Files

- `index.html`: Main HTML file with embedded CSS and D3 setup
- `data.tsv`: The dataset used (cleaned from Netflix Top 10)
- `README.md`: This file
- *(Optional for your environment: additional `.js` or `.css` files if you separate them)*

## 📦 How to Use

1. **Download or Clone** this repository.
2. Open `index.html` in any modern browser (Chrome, Firefox, Edge).
3. Use the **Previous / Next** buttons to navigate the scenes.
4. Interact with **dropdown filters** to view trends by category.

> No server or build process required — this project is 100% client-side.

## 📊 Scenes Overview

1. **Weekly View Trends** – Stacked area chart with category filter
2. **Cumulative Viewing Hours** – TV vs. Films
3. **Top 15 Titles** – Filter by category with value labels
4. **Engagement Analysis** – Views per minute runtime (scatter plot)
5. **Category Trends** – Annotated line graph with trend line and peak highlight

## 🛠 Tech Stack

- [D3.js v7](https://d3js.org/)
- HTML5, CSS3
- Font: [Roboto](https://fonts.google.com/specimen/Roboto)
- Data Source: [Netflix Top 10 weekly viewing hours dataset (TSV)](https://top10.netflix.com/) *(archived locally as `data.tsv`)*

## ✍️ Author

Created by Abhisek Sinha as part of a narrative visualization project.
