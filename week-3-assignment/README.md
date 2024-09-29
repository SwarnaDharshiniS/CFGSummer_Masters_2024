
# Assignment 3 - Uncovering the Impact of Socio-Economic Factors on Life Expectancy Dashboard

This repository contains the necessary files and notebooks for **Assignment 3**, which focuses on analyzing life expectancy and its socio-economic factors across the globe.

---

## Table of Contents
- [Overview](#overview)
- [Files and Structure](#files-and-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Data Used](#data-used)
- [Project Highlights](#project-highlights)
- [Contributors](#contributors)
---

## Overview

This project leverages data visualizations and analysis to study the influence of socio-economic factors on life expectancy. The dashboard provides various insights through interactive graphs and charts built using Plotly and Dash. The analysis is carried out in a Jupyter Notebook.

---

## Files and Structure

The repository contains the following files and folders:

- **Task 2. Visualizations guide.docx**: A brief guide on how we decided which visualisations to use and
an interpretation of each of the figures presented.
- **Week-3-assignment.docx**: A report with conclusions and recommendations.
- **cleaned_life_expectancy_data.xlsx**: The cleaned dataset for socio-economic factors and life expectancy.
- **week_3_assignment_dashboard.ipynb**: The Jupyter notebook containing the dashboard.
- **README.md**: The current readme file.

---

## Getting Started

### Prerequisites

To run the notebook and the dashboard locally, you'll need the following installed:

- **Python 3.x**
- **Jupyter Notebook** or **JupyterLab**
- **pip** (Python package installer)

### Installation

1. **Clone the Repository**

   Clone this repository to your local machine using the following command:

   ```bash
   https://github.com/SwarnaDharshiniS/CFG_Masters_2024.git
   ```
   
2.  **Install required packages**

After cloning the repository, you will need to install the required Python libraries.

If you are running this in Google Colab or a local environment, install the necessary packages by running the following command:

```bash
pip install plotly dash dash-bootstrap-components pandas numpy
```

Required libraries include:

- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
- `plotly`: For creating interactive visualizations (both `express` and `graph_objects` modules are used).
- `dash`: For building web applications with interactive dashboards.
- `dash-bootstrap-components`: To style the dashboard using Bootstrap components.

3. **Import necessary libraries**

```python
import pandas as pd
import numpy as np
import plotly.express as px
import plotly.graph_objects as go
from dash import Dash, dcc, html
import dash_bootstrap_components as dbc
```

---

## Data Used

The project relies on a dataset that contains life expectancy data along with relevant socio-economic factors, such as:

- **Life Expectancy World Bank**: Life expectancy figures by country.
- **Socio-Economic Factors**: Includes indicators like education, sanitation, health expenditure, and prevalence of undernourishment.

The data is cleaned and stored in the `cleaned_life_expectancy_data.xlsx` file. These socio-economic factors are used to explore relationships and trends through the dashboard.

---

## Project Highlights

- **Interactive Global Life Expectancy Map**: A choropleth map showing life expectancy across countries.
- **Histograms and Correlation Heatmaps**: Visualizes the distribution of life expectancy and the relationships between life expectancy and socio-economic factors.
- **Scatter Plots**: Demonstrates relationships between life expectancy and key factors such as sanitation and undernourishment.
- **Hexbin and Box Plots**: Explore regional differences and trends.

---

## Contributors

Thanks to the following people who have contributed to this project:

- Swarna Dharshini S
- Rajindeep Pharwaha
- Marina Klepaci
- Priyanka S


