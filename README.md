Fire Weather Index Prediction:

Overview
This project aims to predict the Fire Weather Index (FWI) based on various meteorological and moisture-related factors. The FWI is a crucial metric in fire management and prevention, providing insights into fire behavior and risk.

Dataset Description

Observations:

Date: Format (DD/MM/YYYY) indicating the day, month (from June to September), and year (e.g., 2012).
Temp: Maximum temperature at noon in Celsius (range: 22 to 42).
RH: Relative Humidity in percentage (range: 21 to 90).
Ws: Wind Speed in km/h (range: 6 to 29).
Rain: Total daily rainfall in mm (range: 0 to 16.8).

FWI Components

Fine Fuel Moisture Code (FFMC): Index from the FWI system (range: 28.6 to 92.5).
Duff Moisture Code (DMC): Index from the FWI system (range: 1.1 to 65.9).
Drought Code (DC): Index from the FWI system (range: 7 to 220.4).
Initial Spread Index (ISI): Index from the FWI system (range: 0 to 18.5).
Buildup Index (BUI): Index from the FWI system (range: 1.1 to 68).
Fire Weather Index (FWI): Final Index (range: 0 to 31.1).

Classes
Fire: Indicates the presence of fire risk.
Not Fire: Indicates absence of fire risk.

Methodology

Data Preprocessing: Cleaning and formatting data to ensure quality and consistency.
Exploratory Data Analysis (EDA): Analyzing data distributions and relationships between variables.
Model Selection: Implementing linear regression to predict FWI based on independent variables.
Model Evaluation: Using metrics such as R-squared, MAE, and RMSE to assess model performance.

Requirements
Python 3.x
Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

Installation:
1.Clone the repository:
git clone https://github.com/thirumal/forestfire_predictions

2.Install required packages:
pip install -r requirements.txt

3.Usage
To run the model, execute the following command
python application.py

Results
The predicted Fire Weather Index (FWI) will be displayed alongside the actual values, allowing for a comparative analysis of the model's performance.

Contributing
Contributions are welcome! Please submit a pull request or open an issue for suggestions or improvements.






