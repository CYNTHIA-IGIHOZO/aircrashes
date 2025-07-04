# Aircrash Data Analysis Project
This project explores and visualizes global aircraft crash data using Python. It provides insights into crash frequency, fatalities, survival rates, aircraft types, operator breakdowns, and more.

## Project Structure

Aircrash/
│
├── Data/
│   ├── Raw/           # Original unprocessed CSV files
│   └── Processed/     # Cleaned and transformed data files
│
├── Docs/              # Project documentation or references
│
├── Notebooks/         # Jupyter Notebooks for analysis and visualizations
│
├── Results/           # Saved charts, figures, and export files
│
└── README.md          # Project overview (this file)

### Key Insights Covered
Crashes over time (yearly trends)

Distribution by continent and region

Aircraft and operator breakdowns (military, commercial, unknown)

Fatalities vs. survivors

Most deadly incidents and ground death cases

Interactive maps of crash locations

Survival rates and crash severity

### Tools & Technologies
Python

Pandas & NumPy (data wrangling)

Plotly (interactive charts & dashboards)

Ipywidgets (Jupyter-based interactivity)

Geopy / Nominatim (geolocation)

### How to Run
Open the Notebooks/ folder in Jupyter Notebook or JupyterLab.

Start with the main analysis notebook (e.g., aircrash_analysis.ipynb).

#### Make sure required packages are installed:

pip install pandas plotly ipywidgets pycountry pycountry-convert geopy
Run the cells to explore interactive graphs and insights.

## Notes
Location names were geocoded using OpenStreetMap. Unknown locations are marked as NaN.

The dataset includes crash info from early 1900s to modern day.

This project is designed for both static analysis and interactive filtering in Jupyter.
