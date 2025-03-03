# Water Quality Analysis with Python, Pandas, and NumPy

## 📖 Overview
This project focuses on analyzing water quality using Python, Pandas, and NumPy. The analysis includes calculating the Water Quality Index (WAWQI), Groundwater Quality Index (WGWQI), and Overall Water Quality Index (OWQI) for nine different points over two years (2016 and 2017). The project leverages Pandas for data manipulation and NumPy for numerical calculations.

## 🛠 Technologies & Components Used
- **Python**: The programming language used for data analysis.
- **Pandas**: A powerful data manipulation and analysis library for Python.
- **NumPy**: A package for numerical computing in Python, used for mathematical operations on arrays.
- **Jupyter Notebooks** (optional): For interactive coding and visualizing the data.

## 📝 Key Features
1. **Data Collection**:
   - Water quality data for nine points across two years (2016 and 2017).
   - Includes various water quality parameters (e.g., pH, turbidity, dissolved oxygen).
   
2. **Calculation of Water Quality Indices**:
   - **WAWQI** (Water Quality Index): A composite index for assessing the overall water quality based on multiple parameters.
   - **WGWQI** (Groundwater Quality Index): A specific index for evaluating groundwater quality.
   - **OWQI** (Overall Water Quality Index): A holistic index that combines both WAWQI and WGWQI.
   
3. **Data Consolidation**:
   - Using Pandas to clean and consolidate data into a single DataFrame, adding calculated quality indices as new columns.
   
4. **Analysis and Reporting**:
   - Summarizing and visualizing the results for easier interpretation of water quality across different locations and years.
   
## 📊 Project Workflow

### 1. Data Preparation
- **Data import**: Load water quality data from CSV or Excel files into a Pandas DataFrame.
- **Data cleaning**: Handle missing values, incorrect data types, and outliers.
  
### 2. Calculation of Indices
- **WAWQI**: Compute the index using a weighted sum of water quality parameters.
- **WGWQI**: Similar to WAWQI but focused on groundwater quality parameters.
- **OWQI**: Combine the WAWQI and WGWQI to generate an overall water quality score.

### 3. Data Analysis
- Create new columns for WAWQI, WGWQI, and OWQI.
- Perform statistical analysis to identify trends and patterns in the data across different locations and time periods.

### 4. Reporting
- Generate a summary report presenting the calculated indices for all nine points, for both years (2016 and 2017).
- Use visualizations (e.g., bar charts, line plots) to highlight key insights.
