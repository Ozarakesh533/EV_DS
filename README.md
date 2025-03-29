## 🚀 Project Overview

This comprehensive analysis explores electric vehicle (EV) adoption trends across the United States, providing valuable insights into market dynamics, geographical distribution, and manufacturer competition through interactive visualizations and detailed analytics.

## ✨ Key Features

### 🌎 Interactive Choropleth Map
- Visualizes EV distribution across U.S. states with color gradients representing density
- Hover functionality reveals exact vehicle counts per state
- Responsive design for optimal viewing on any device

![ChoroplethMap](https://github.com/user-attachments/assets/71546741-ad54-4781-8ae2-e1cd8a0f49d0)

### 🏎️ Dynamic Racing Bar Chart
- Animated timeline of manufacturer market share evolution
- Tracks top EV brands from early adoption to current leaders
- Customizable time frame and display options

https://github.com/user-attachments/assets/5adf5863-4960-4ff3-8efe-75302c175919

### 📊 Additional Visualizations
- Time series analysis of EV adoption rates
- Range distribution by vehicle type and manufacturer
- Price segmentation analysis
- State-by-state adoption comparisons

## 🔍 Methodology

1. **Data Understanding & Exploration**
   - Comprehensive assessment of dataset structure and variables
   - Identification of key metrics and potential relationships

2. **Data Cleaning & Preparation**
   - Handling missing values and outliers
   - Standardization of categorical variables
   - Geocoding for spatial analysis

3. **Exploratory Data Analysis**
   - Univariate analysis (with and without visualization)
   - Bivariate analysis (with and without visualization)
   - Correlation studies between key variables

4. **Advanced Visualization**
   - Choropleth mapping for geographical distribution
   - Animated racing bar charts for temporal trends
   - Interactive dashboards for user exploration

## 💻 Technologies Used

| Technology | Purpose |
|------------|---------|
| Python 3.9+ | Core programming language |
| pandas | Data manipulation and analysis |
| NumPy | Numerical computations |
| matplotlib | Basic visualizations |
| seaborn | Statistical visualizations |
| plotly | Interactive visualizations |
| bar_chart_race | Animated bar chart creation |
| Geopandas | Geographical data handling |
| Jupyter Notebook | Interactive development environment |

## 📂 Dataset Overview

The dataset provides comprehensive information about electric vehicle registrations across the United States:

```markdown
| Column | Description | Key Insights |
|--------|-------------|--------------|
| VIN (1-10) | Vehicle Identification Number prefix | Unique vehicle identifier |
| County/City/State | Registration location | Geographical analysis basis |
| Model Year | Vehicle production year | Temporal trend analysis |
| Make/Model | Manufacturer and model | Brand performance tracking |
| Electric Vehicle Type | BEV or PHEV classification | Technology adoption trends |
| Electric Range | Miles per charge | Performance metrics |
| Base MSRP | Manufacturer's suggested price | Affordability analysis |
| CAFV Eligibility | Clean fuel vehicle status | Policy impact measurement |
```

## 🛠️ Installation Guide

1. Clone the repository:
```bash
git clone https://github.com/Ozarakesh533/EV-Sales-Analysis.git
cd EV-Sales-Analysis
```

2. Create and activate virtual environment:
```bash
python -m venv ev_env
source ev_env/bin/activate  # Linux/Mac
ev_env\Scripts\activate    # Windows
```

3. Install requirements:
```bash
pip install -r requirements.txt
```

Alternative manual installation:
```bash
pip install pandas matplotlib seaborn plotly geopandas bar_chart_race jupyter
```

## 🏆 Key Insights Discovered

1. **Geographical Trends**
   - Top 3 states for EV adoption: California, Washington, Florida
   - Emerging markets in Midwest showing rapid growth

2. **Manufacturer Analysis**
   - Tesla dominance in BEV market
   - Traditional automakers gaining PHEV market share

3. **Temporal Patterns**
   - 45% year-over-year growth since 2018
   - Seasonal purchasing patterns observed

4. **Price & Range Correlations**
   - Strong correlation between price and electric range
   - Market segmentation into affordable vs premium EVs

## 📈 Business Applications

1. **Market Strategy Development**
   - Identify high-potential geographical markets
   - Competitive benchmarking against industry leaders

2. **Policy Impact Assessment**
   - Evaluate effectiveness of state-level incentives
   - Model adoption rates under different policy scenarios

3. **Product Planning**
   - Optimal price positioning analysis
   - Range requirements by region and vehicle class

## 👨‍💻 About the Author

**Rakesh Oza** | Data Science & Analytics 

- 📧 Email: [ozarakesh533@gmail.com](mailto:ozarakesh533@gmail.com)
- 💼 LinkedIn: [linkedin.com/in/rakeshoza](https://www.linkedin.com/in/rakeshoza/)
- 🌐 Portfolio: [ozarakesh533.github.io](https://ozarakesh533.github.io/My_Portfolio_website/)
- 🔗 GitHub: [github.com/Ozarakesh533](https://github.com/Ozarakesh533)
