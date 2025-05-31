# NYC Taxi Fare Prediction 🚕📊

This project applies a full data science pipeline to predict taxi fare amounts in New York City using TLC yellow taxi data from January 2024, integrated with NYC weather conditions.

## 📁 Included Files
- `NYCTaxi.ipynb` – The full notebook with preprocessing, EDA, feature engineering and model evaluation
- `NYC_Taxi_Fare_Analysis_Report.pdf` – Final project report 
- `NYC_TAXI_Presentation.pptx` – Project slides
- `nyc_weather_2024.csv` – Weather data used for integration
- `taxi_zone_lookup.csv` – Location ID to NYC zone mapping
- `trip_record_user_guide.pdf` – Official TLC user guide for trip data
- `data_dictionary_yellow.pdf` – Metadata for yellow taxi trip data fields

## 🧪 Dataset Info
Yellow taxi data can be downloaded from:
📎 https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

Note: We used **January 2024 data** (~1 million+ rows), filtered and preprocessed locally. Due to large file size, the raw dataset is **not included** in this repo.

## 📊 Models
- Decision Tree
- Random Forest
- Gradient Boosting

## 🔢 Evaluation Metrics
| Model            | MAE  | RMSE | R²   |
|------------------|------|------|------|
| Decision Tree    | 4.90 | 6.08 | 0.78 |
| Random Forest    | 2.79 | 3.68 | 0.93 |
| Gradient Boosting| 2.03 | 2.82 | 0.96 |


