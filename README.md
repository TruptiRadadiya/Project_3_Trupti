# Interactive Visualization of the Schools in Western Australia

## Schools in WA Dashboard

This project involves creating an interactive dashboard to explore the distribution and characteristics of schools in Western Australia. The dashboard includes visualizations such as maps, bar charts, pie charts, and searchable tables, allowing users to interact with and analyze the data effectively.

### File structure

```
project_3_trupti/
├── data_cleaning/
│   └── data_cleaning.py            # Python script for cleaning the data
├── mongoDB/
│   └── schools_WA.ipynb            # Jupyter notebook for handling MongoDB operations and analysis for WA schools
├── source_data/
│   └── WA_schools_data.xlsx        # Source data file containing information about WA schools
├── static/
│   ├── plots.js                    # JavaScript file for data processing and visualization
│   └── style.css                   # CSS file for styling the dashboard
├── data.json                       # JSON file containing processed data for the dashboard
├── index.html                      # Main HTML file for the dashboard
└── README.md                       # This README file explaining the project structure and usage
```

### What Do You Need?

- D3.js
- Leaflet.js
- Chart.js
- HTML/CSS
- JavaScript
- Python (for data preprocessing if needed)

### How to Use the Code?

1. Clone this repository to your local machine.
2. Navigate to the project directory and install the required dependencies.

### Summary of Features

- Interactive Map:

  - Displays the locations of schools using latitude and longitude.
  - Each marker on the map represents a school. Clicking on a marker shows a tooltip with the school name and other details.

- Data Table:

  - Searchable and sortable table displaying the school information.
  - Columns include: Code, School Name, Suburb, State, Phone, Education Region, Broad Classification, Classification Group, Total Students.

- Graphs/Charts:

  - Bar chart showing the number of students by year (KIN, PPR, Y01, etc.).
  - Pie chart showing the distribution of schools by broad classification.

### Deployment

- Deployed the dashboard to GitHub Pages for easy access and sharing:

```
https://truptiradadiya.github.io/Project_3_Trupti/
```
