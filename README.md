# PathfinderX: Resilient GPS Prediction using Machine Learning

PathfinderX is a machine learning project designed to predict aircraft positions during brief GPS outages, ensuring reliable navigation in aviation. By leveraging historical flight data, it provides accurate predictions using models such as Random Forest, LightGBM, and XGBoost.

## Features
- **Accurate Predictions**: Predicts aircraft position (latitude, longitude, and altitude) during GPS outages.
- **Machine Learning Models**: Implements Random Forest, LightGBM, and XGBoost for robust predictions.
- **Seamless Integration**: Designed for minimal changes to existing aviation systems.
- **Real-time Performance**: Suitable for real-world aviation scenarios with efficient computation.

## Dataset
The project uses a simulated flight dataset with features such as:
- Flight number
- Latitude, longitude, and altitude
- Heading and timestamp
- Derived parameters like speed, acceleration, and bearing changes

## Methodology
1. **Data Preprocessing**: Cleaning, interpolation, and feature engineering for enriched insights.
2. **Feature Engineering**: Generating time-series inputs for models using flight dynamics.
3. **Model Training**: Training separate models for latitude, longitude, and altitude predictions.
4. **Visualization**: Interactive maps and detailed plots to evaluate predictions and errors.

## Key Results
- Achieved R² scores > 0.95 for latitude and longitude predictions.
- Errors consistently below 5 km for position and 500 ft for altitude during GPS outages.
- Demonstrated scalability and high performance with multiple machine learning models.

## Contributions
- Shashank A Bhat
- Tejas Mohandas Patil
- Abhijith D Pai
