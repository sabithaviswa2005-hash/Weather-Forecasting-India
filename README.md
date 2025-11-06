# Weather-Forecasting-India
Exploratory Data Analysis and Machine Learning-based Forecasting of Temperature and Rainfall in India using Decision Tree and Linear Regression models.
# Objectives
- **Pattern Recognition:** Identify recurring weather patterns and anomalies.  
- **Trend Analysis:** Analyze long-term trends to assess climate change impacts.  
- **Predictive Modeling:** Develop predictive models for short-term and long-term weather conditions.  
- **Impact Assessment:** Assess effects of weather on agriculture, infrastructure, and settlements.  
- **Data Visualization:** Present weather data effectively for easy interpretation.

# Problem Statement
Current weather data analysis methods face challenges like:
- Scalability issues for large datasets.  
- Difficulty integrating multi-source data streams.  
- Limitations in real-time processing.  

This project addresses these challenges using **advanced analytical techniques**, **machine learning algorithms**, and **big data processing**, providing actionable insights from complex weather data.

## Dataset
The weather data used in this project was sourced from **Kaggle**. It includes:
1. **Mean Temperature of India (1901–2017)** – Monthly and seasonal temperature data.  
2. **Sub-divisional Rainfall Data (1901–2017)** – Average rainfall for various subdivisions.
> ⚠️ Note: The exact Kaggle dataset name/link is unavailable, but historical weather data from India was used.

## Methodology
1. **Dataset Acquisition:** Collected historical temperature and rainfall data from official sources.  
2. **Algorithm Selection:**  
   - Decision Tree Regressor – Captures nonlinear patterns and builds predictive models.  
   - Linear Regression – Models linear relationships between temperature and time.  
3. **Exploratory Data Analysis (EDA):**  
   - Visualizations using **matplotlib**, **seaborn**, and **plotly**.  
   - Trend analysis, correlation checks, and pattern recognition.  
4. **Forecasting:**  
   - Applied Decision Tree and Linear Regression for predictive modeling.  
   - Evaluated models using accuracy, R² scores, and visualization of results.

## Key Metrics
- **Accuracy:** Measures overall correct predictions.  
- **Precision:** Reliability of positive predictions.  
- **Recall (Sensitivity):** Ability to correctly identify actual positives.  
- **F1-Score:** Harmonic mean of precision and recall.  
- **R² Score:** Measures variance explained by regression models.

## Modeling & Results

### Decision Tree
- **Model:** Decision Tree Classifier  
- **Features:** Temperature, location, wind, humidity, air quality indices, etc.  
- **Output:** Predicts weather condition (clear, cloudy, rainy, etc.)  
- **Visualization:** Decision tree plots generated and saved.

### Linear Regression
- **Model:** Simple Linear Regression  
- **Features:** Temperature in Celsius  
- **Target:** Temperature in Fahrenheit  
- **Results:** Regression line, scatter plots, and R² score for model performance.

## Repository Contents
- `weatherdata.csv` – Raw dataset (temperature and rainfall)  
- `Weather_Data_Analysis.ipynb` – Colab notebook with Decision Tree and Linear Regression modeling  
- `outputs/` – Plots, Decision Tree visualizations, and results

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
> ⚠️ Note: Some portions of this project use reused code
