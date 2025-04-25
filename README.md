# Relocation Support using Data Science Techniques for Optimized District Selection

## Project Overview
This project was completed as part of the IBM Applied Data Science Capstone.  
It aims to assist families and relocation service providers in identifying the best districts in São Paulo, Brazil, based on rental affordability and proximity to important venues (schools, parks, metro stations, etc.).  
The project uses data scraping, SQL-based exploratory data analysis, interactive visualizations, and predictive clustering techniques.

## Main Steps
- **Data Collection**: Scraped rental price data and venue information from public websites and APIs (Geopy, Foursquare).
- **Data Wrangling**: Cleaned, filtered, and standardized datasets for analysis.
- **Exploratory Data Analysis (EDA)**: Used SQL and Python visualizations to uncover key insights about district characteristics.
- **Interactive Visualization**: Created Folium maps and a dynamic Plotly Dash dashboard.
- **Predictive Analysis**: Applied DBSCAN clustering to identify optimal districts based on relocation criteria.

## Repository Structure
- `notebooks/`: Contains all Jupyter notebooks for different stages of the project.
- `scripts/`: Python scripts for reusable code (data cleaning, SQL queries, clustering).
- `presentation/`: Final project presentation PDF.
- `requirements.txt`: List of Python libraries needed to run the notebooks.

## Installation
Clone the repository:
```bash
git clone https://github.com/your-username/Relocation-Support-DataScience-Project.git
```

Install dependencies:
```bash
pip install -r requirements.txt
```

## How to Run
Open each notebook inside the `notebooks/` folder sequentially.  
Each notebook is labeled according to the project phase.

To run the Plotly Dash dashboard:
```bash
python scripts/plotly_dash_dashboard.py
```

## Project Results
- Districts satisfying relocation requirements were successfully identified.
- Created interactive maps and dashboards for easier district exploration.
- Used clustering to prioritize neighborhoods for families based on their preferences.

## Future Improvements
- Extend to other cities or countries.
- Include more venue categories (healthcare, shopping, entertainment).
- Automate the rental ad fetching for faster real-world application.

## Author
- Vikranth, 2025
