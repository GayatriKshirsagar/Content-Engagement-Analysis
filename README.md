# 📺 Disney+ and Streaming Platforms TV Shows Analysis

This project leverages Python and data visualization libraries to analyze TV show offerings across major streaming platforms — **Netflix, Hulu, Prime Video, and Disney+** — using a dataset containing IMDb ratings, age suitability, and platform availability.

## 📊 Objective

To explore and compare content distribution, quality, and audience targeting strategies across leading streaming platforms, and identify:

- Platform with the most TV shows
- Platform offering the highest-rated shows
- Quality consistency across platforms
- Best shows on each platform
- Platform with the most children's content

## 🧰 Tools & Technologies

- **Python**  
- **Libraries**: pandas, numpy, seaborn, matplotlib  
- **Jupyter Notebook** for development and visual exploration

## 📁 Dataset

- **Source**: `tv_shows.csv`  
- **Columns include**: `Title`, `IMDb`, `Age`, platform availability (`Netflix`, `Hulu`, `Prime Video`, `Disney+`), and more.

## 📈 Key Analyses

- 📌 Total content count per platform (pie chart)
- ⭐ Platforms with most highly rated shows (IMDb > 8)
- ✅ Quality consistency ratio (highly rated per 100 shows)
- 🏆 Top 10 shows per platform by IMDb rating
- 🎯 Best platforms for children's content
- 📉 Ratio of kids' content vs total content

## 📌 Highlights

- Disney+ shows the highest concentration of children's content.
- Netflix leads in the volume of TV shows, but Prime Video has more consistent high-quality content.
- Custom visualizations were used to present insights through bar plots and pie charts.

## 🖼️ Visualizations

All visualizations are built using `matplotlib` and `seaborn` and include:
- Bar charts for top-rated shows
- Pie chart for market share by content
- Comparative plots for children's content across platforms

## 🚀 How to Run

1. Clone the repository  
2. Ensure dependencies are installed:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Run the Jupyter Notebook to explore insights:
   ```bash
   jupyter notebook
   ```

## 📬 Contact

Feel free to connect if you have any questions or feedback!

```

Let me know if you want to include a GIF or screenshot in the `README.md` as well.
