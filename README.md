The **Sea Level Predictor** project is designed to analyze and predict sea level changes over time using historical data. The project utilizes **Python**, **pandas** for data handling, **matplotlib** for visualization, and **scipy.stats.linregress** for linear regression analysis.

**How It Works:**
1. **Load Data**  
   - The dataset (`epa-sea-level.csv`) is read using **pandas**, which contains sea level measurements from **1880 onwards**.

2. **Scatter Plot of Observed Data**  
   - A scatter plot is created to visualize actual recorded sea levels over time.

3. **First Trend Line (1880 - 2050)**  
   - A linear regression model is applied to the entire dataset (1880-2020).  
   - Predictions are made up to **2050** based on this trend.  
   - The **red line** represents this trend.

4. **Second Trend Line (2000 - 2050)**  
   - A separate regression model is applied to recent data (from the year **2000 onwards**).  
   - This provides a more recent trend in sea level rise.  
   - The **green line** represents this trend.

5. **Plot Customization**  
   - Labels, titles, legends, and grid are added for better readability.

**Purpose of the Project**  
This project helps in understanding how sea levels are rising and predicting future changes. It provides a visual representation of historical and projected data, which is crucial for climate change studies and decision-making.
