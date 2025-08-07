# Toronto_Traffic_Project
“A spatial-temporal analysis of vehicle collisions in Toronto (2021–2024).”

# Toronto Vehicle Collision Analysis (2021–2024)

This data project explores patterns in vehicle collisions across the city of Toronto using open police data from 2021 to 2024. It investigates **when** and **where** collisions most frequently occur, and how these patterns vary by neighbourhood, time of day, and day of the week.

> This is the first project in a multi-part series examining the relationship between weather, congestion, and traffic collisions in Toronto.

---

## Project Objectives

- Analyze trends in vehicle collisions over time
- Identify temporal risk patterns (by hour, weekday, and month)
- Map spatial hotspots and neighbourhood-specific dangers
- Compare severity rates across regions
- Lay the groundwork for weather-integrated risk modeling (coming next)

---

## Project Structure
|
├── Toronto_Traffic_Project.ipynb # Main analysis notebook
├── README.md # Project overview and instructions
└── traffic_collisions.csv # Toronto Police Service collision data (external)

---

## Key Insights

- **Collisions have increased sharply** since 2021, reaching nearly 70,000 incidents in 2024.
- **September through December** consistently show the highest collision counts.
- **Fridays between 2–5 PM** emerge as the most dangerous time window city-wide.
- **Wexford/Maryvale** and **West Humber-Clairville** lead in both volume and severity.
- **St. Lawrence** shows a high frequency but relatively low severity, indicating different risk dynamics.

Neighbourhood-specific trends revealed how some areas (e.g., student zones or downtown cores) have **unique collision rhythms** that aren't visible in city-wide averages.

---

## Data Source

Toronto Police Service Open Data Portal  
[Traffic Collisions Dataset](https://data.torontopolice.on.ca/datasets/TorontoPS::traffic-collisions-open-data-asr-t-tbl-001/about)

## How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/Toronto_Traffic_Project.git
2. Open the notebook in Jupyter
   jupyter notebook Toronto_Traffic_Project.ipynb

## Next Steps
In the next phase of this series, I will incorporate weather data (temperature, precipitation, and visibility) to examine how environmental conditions influence collision frequency and severity. This will help build a more predictive and actionable model for traffic risk in Toronto.

Thank you for reading!
<3
