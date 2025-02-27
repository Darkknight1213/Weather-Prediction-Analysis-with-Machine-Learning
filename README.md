# Weather Prediction & Analysis with Machine Learning

## Project Overview

This project is a machine learning-based weather data analysis completed as part of the Coursera course **Machine Learning with Python**. It involves data preprocessing, feature engineering, and predictive modeling to extract insights and make weather-related predictions.

## Features

- Data cleaning and preprocessing
- Handling missing values and inconsistencies
- Feature engineering (season categorization, transformations, etc.)
- Exploratory Data Analysis (EDA)
- Machine Learning model training and evaluation

## Technologies Used

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
- **Environment:** Jupyter Notebook (.ipynb)

## Dataset Description

The dataset contains the following columns:

- **Location:** Name of the region
- **MinTemp:** Minimum temperature recorded (°C)
- **MaxTemp:** Maximum temperature recorded (°C)
- **Rainfall:** Amount of rainfall (mm)
- **Evaporation:** Rate of evaporation (mm)
- **Sunshine:** Number of sunshine hours
- **WindGustDir:** Direction of strongest wind gust
- **WindGustSpeed:** Speed of strongest wind gust (km/h)
- **WindDir9am, WindDir3pm:** Wind direction at 9 AM and 3 PM
- **WindSpeed9am, WindSpeed3pm:** Wind speed at 9 AM and 3 PM (km/h)
- **Humidity9am, Humidity3pm:** Humidity percentage at 9 AM and 3 PM
- **Pressure9am, Pressure3pm:** Atmospheric pressure at 9 AM and 3 PM (hPa)
- **Cloud9am, Cloud3pm:** Cloud cover at 9 AM and 3 PM (octas)
- **Temp9am, Temp3pm:** Temperature at 9 AM and 3 PM (°C)
- **RainYesterday, RainToday:** Boolean indicating if it rained yesterday/today
- **Season:** Derived column categorizing the season based on date

## Installation & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/weather-ml-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd weather-ml-analysis
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook weather_analysis.ipynb
   ```

## Data Processing Steps

1. **Data Loading:** Read the dataset using Pandas
2. **Cleaning:** Handle missing values and inconsistencies
3. **Feature Engineering:** Convert the 'Date' column into a seasonal feature
4. **Machine Learning Modeling:** Train and evaluate predictive models
5. **Visualization:** Use Matplotlib and Seaborn to analyze weather trends

## Contribution Guidelines

- Fork the repository
- Create a feature branch (`git checkout -b feature-name`)
- Commit changes (`git commit -m "Add new feature"`)
- Push to the branch (`git push origin feature-name`)
- Create a Pull Request

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For queries, reach out to [your email] or create an issue in the repository.

---

*This project applies machine learning techniques to analyze and predict weather patterns.*

