# Data Analysis on Electric Vehicle

## Project Overview

This project provides a detailed analysis and visualization of electric vehicle (EV) sales trends across the United States. By leveraging various data analysis and visualization techniques, we were able to extract meaningful insights into the EV market trends.

## Features

- **Choropleth Map of EVs by State**: Visualizes the distribution of electric vehicles across U.S. states.

  ![ChoroplethMap](https://github.com/user-attachments/assets/71546741-ad54-4781-8ae2-e1cd8a0f49d0)

- **Racing Bar Chart of EV Sales by Manufacturer**: Shows the changing landscape of top EV manufacturers over the years through an animated racing bar chart.

  https://github.com/user-attachments/assets/5adf5863-4960-4ff3-8efe-75302c175919
  
## Methodology
1. **Data Understanding**
2. **Data Cleaning**
3. **EDA - Univariate Analysis (Non Visualization)**
4. **EDA - Univariate Analysis (Visualization)**
5. **EDA - Bivariate Analysis (Non Visualization)**
6. **EDA - Bivariate Analysis (Visualization)**
7. **Choropleth Map to display the number of EV vehicles based on location**
8. **Racing Bar Chart to display the animation of EV Make and its count each year**

## Technologies Used

- **Python**: Programming language for data analysis and visualization.
- **pandas**: Data manipulation and analysis.
- **matplotlib & seaborn**: For Exploratory Data Analysis (Univariate and Bivariate)
- **plotly**: For generating the choropleth map.
- **bar_chart_race**: To create racing bar charts.

## Dataset
This dataset provides insights into the distribution of electric vehicles across different states, counties, and cities, and offers detailed information on their range and eligibility for fuel incentives.


| Column                                      | Description                                                                 |
|---------------------------------------------|-----------------------------------------------------------------------------|
| `'VIN (1-10)'`                              | The first 10 characters of the Vehicle Identification Number (VIN)          |
| `'County'`                                  | The county where the vehicle is registered                                  |
| `'City'`                                    | The city where the vehicle is registered                                    |
| `'State'`                                   | The state where the vehicle is registered (represented by a 2-letter code)  |
| `'Postal Code'`                             | The postal code of the vehicle's registration area                          |
| `'Model Year'`                              | The model year of the electric vehicle                                      |
| `'Make'`                                    | The manufacturer or brand of the vehicle (e.g., Tesla, Toyota)              |
| `'Model'`                                   | The specific model name of the vehicle                                      |
| `'Electric Vehicle Type'`                   | The type of electric vehicle (e.g., Battery Electric Vehicle (BEV), Plug-in Hybrid Electric Vehicle (PHEV)) |
| `'Clean Alternative Fuel Vehicle (CAFV) Eligibility'` | Indicates whether the vehicle is eligible for CAFV benefits                 |
| `'Electric Range'`                          | The electric-only driving range of the vehicle (in miles)                   |
| `'Base MSRP'`                               | Manufacturer's suggested retail price (MSRP) for the vehicle (in USD)       |
| `'Legislative District'`                    | The legislative district where the vehicle is registered (if available)     |
| `'DOL Vehicle ID'`                          | A unique ID assigned to the vehicle by the Department of Licensing          |
| `'Vehicle Location'`                        | The geographic coordinates of the vehicle registration location (longitude and latitude) |
| `'Electric Utility'`                        | The electric utility company serving the location where the vehicle is registered |
| `'2020 Census Tract'`                       | The 2020 Census Tract where the vehicle is located                          |

## Requirements
- Python 3.x
- Libraries: `pandas`, `matplotlib`, `seaborn`, `plotly`, `bar_chart_race`

## Installation
To run this project, ensure you have the required libraries installed. You can do this by running:

```bash
pip install pandas matplotlib seaborn plotly bar_chart_race
```

## Thank you
If you enjoyed this notebook, please consider sharing it.

Author: `Sri Charan Thoutam`

- 👉Shoot me mails : thoutamsricharan@gmail.com
- 👉Connect on LinkedIn: [linkedin.com/in/codewithcharan](https://www.linkedin.com/in/codewithcharan/)
- 👉Explore my Portfolio: [codewithcharan.github.io/My-Portfolio](https://www.codewithcharan.github.io/My-Portfolio)
- 👉Explore my GitHub: [github.com/CodeWithCharan](https://www.github.com/CodeWithCharan)