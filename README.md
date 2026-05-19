# Lebron James Career Shot Chart & Heatmap

## Description
This project analyzes and visualizes the career shooting data of Lebron James (or any specified NBA player). Utilizing the `nba_api`, the Python script extracts detailed shot chart data, cleans it for analysis, and constructs two distinct visual representations:
1. **A Scatter Plot Shot Chart:** Differentiating between successful and missed shots.
2. **A Kernel Density Estimate (KDE) Heatmap:** Displaying the density and frequency of shot attempts across the court.

These visualizations are overlaid on a dynamically drawn representation of an NBA basketball court.

## Features
* **Automated Data Retrieval:** Uses `nba_api` to automatically fetch regular season and playoff shot data for a given player based on their full name.
* **Data Cleaning:** Preprocesses the data to accurately map court coordinates (converting to feet) and categorize shots by make/miss.
* **Custom Court Drawing:** Programmatically draws an accurate 2D representation of an NBA basketball court using `matplotlib.patches`.
* **Advanced Data Visualization:** Uses `matplotlib` for scatter plots and `seaborn` for generating smooth, continuous heatmaps of shot density.

## Prerequisites & Installation
Ensure you have Python installed. You can install the required libraries using pip:

```bash
pip install nba_api pandas matplotlib numpy seaborn
