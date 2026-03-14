# Indian_Election_Data_Analysis
🗳️ Interactive data analysis and geospatial visualization of the Indian General Election 2024. Features automated data cleaning with Pandas and dynamic mapping using Plotly to visualize party-wise performance and seat distributions.
# 🗳️ Indian Election 2024: Data Analysis

An interactive data science project focused on analyzing and visualizing the **2024 Indian General Election** results. This project transforms raw election data into actionable insights using Python's data stack.

## 🚀 Key Features
- **Data Wrangling:** Automated cleaning of election result CSVs using **Pandas**.
- **Interactive Geospatial Maps:** Visualizing constituency and state-wise results using **Plotly** and custom **GeoJSON** boundaries.
- **Party Performance Analysis:** Dynamic charts (Pie/Bar) showing "Top 4 Parties + Others" to simplify complex multi-party results.
- **Margin Analysis:** Insights into victory margins across different regions.

## 🛠️ Tech Stack
- **Language:** Python 3.x
- **Libraries:** Pandas, Plotly Express, NumPy
- **Environment:** Jupyter Notebook / VS Code

## 📊 Visualizations Included
1. **Interactive Choropleth Map:** Color-coded map of India showing party/alliance leads (NDA vs. INDIA vs. Others).
2. **Vote Share Distribution:** Pie charts representing the proportional strength of major political blocks.
3. **Winning Margins:** Statistical breakdown of how closely contested the seats were.

## 📁 Project Structure
```text
├── data/
│   └── election_results_2024.csv  # Raw data
├── maps/
│   └── india_states.json          # GeoJSON for mapping
├── notebooks/
│   └── election_analysis.ipynb    # Main analysis logic
└── README.md
