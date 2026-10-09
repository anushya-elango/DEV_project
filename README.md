# Data Exploration and Visualization - Capstone (Assignment II)

Exploratory analysis and visualization of an OpenStreetMap (OSM) facility summary by country
(116 countries, 4,800 facilities). Covers Units 1-5 of the syllabus.

**Author:** Anushya - KGiSL Institute of Technology

## Contents
- `data/` - original CSV and cleaned CSV
- `notebooks/Capstone_EDA_OSM_Facilities.ipynb` - executed notebook (start Jupyter from the project root so `data/` paths work)
- `src/analysis.py` - same analysis as a script (creates `figures/`, `interactive/`, `results.json`)
- `figures/` - 27 figures used in the report
- `interactive/` - Plotly and Bokeh HTML plots (open in a browser)
- `report/` - final report (Word)

## Run
    pip install -r requirements.txt
    python src/analysis.py

## Dataset note
The CSV has no embedded source URL. Context/licence: https://www.openstreetmap.org/copyright (ODbL).
