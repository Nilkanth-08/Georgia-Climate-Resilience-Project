# Georgia Climate Resilience Project

## Overview
This repository contains all the data, scripts, and analysis results for the Georgia Climate Resilience Project. The project leverages Geographic Information Systems (GIS) for spatial mapping of climate projections, facilitating effective strategic planning and community engagement. It involves analyzing downscaled climate data from the National Climate Assessment #5 (NCA5) using ArcGIS, supplemented by statistical modeling to enhance data interpretation for regional impact assessments.

## Software and Tools Used
- **ArcGIS**: Used for spatial mapping and data visualization.
- **Python**: Utilized for advanced statistical analysis and data processing.
- **R**: Employed for statistical modeling and data validation.

## Python Libraries
The project uses several Python libraries, each serving specific functions in data handling, analysis, and visualization:
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical data processing.
- **Matplotlib** and **Seaborn**: For creating static, interactive, and animated visualizations.
- **Statsmodels**: For conducting statistical tests and time series analysis.
- **Scikit-learn**: For machine learning and predictive modeling.

## Time Series and Trend Analysis
This project involves extensive time series analysis to identify trends and patterns in climate data over time. Using Statsmodels, the project performs:
- **Decomposition of time series data**: This separates the time series into trend, seasonal, and residual components, helping to understand underlying patterns.
- **Trend Analysis**: To detect increasing or decreasing trends in climate variables over the years.
- **Forecasting**: To predict future climate conditions based on historical data.

## Repository Structure
- `/data`: Contains raw and processed climate data used in the analyses.
- `/Python Scripts`: Includes Python and R scripts used for statistical analysis and data validation.
- `/Time series`: Stores output files, including maps, graphs, and model outputs.
- `/documentation`: Contains project documentation and reports detailing the methodologies and findings.

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- ArcGIS

### Setup
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/Nilkanth-08/Georgia-Climate-Resilience-Project.git
