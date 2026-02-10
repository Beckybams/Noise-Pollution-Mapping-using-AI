Project Overview

This project demonstrates how Artificial Intelligence (AI) can be used to model and map environmental noise pollution. Using synthetic data, the system predicts noise levels (in decibels) across different geographic locations based on factors such as traffic density, industrial activity, and population density.

The project is suitable for academic research, environmental studies, and machine learning demonstrations.

Objectives

Simulate realistic noise pollution data

Train an AI model to predict noise levels

Evaluate model performance

Generate a spatial noise pollution map

Export results for analysis and visualization

Dataset Description

The dataset is synthetically generated and includes the following features:

Feature	Description
Latitude	Geographic latitude of location
Longitude	Geographic longitude of location
Traffic Density	Level of road traffic activity
Industrial Activity	Presence of industrial noise sources
Population Density	Number of people in the area
Noise Level (dB)	Measured noise pollution level (target)
Methodology

Data Generation – Synthetic environmental noise data is created using realistic assumptions.

Data Preprocessing – Features and target variable are separated.

Model Training – A Random Forest Regressor is trained to learn noise patterns.

Model Evaluation – Performance is assessed using Mean Squared Error (MSE) and R² score.

Noise Mapping – The trained model predicts noise levels across a spatial grid.

Technologies Used

Python

NumPy

Pandas

Scikit-learn

Random Forest Regression

How to Run the Project

Install required libraries:

pip install numpy pandas scikit-learn

Run the Python script:

python noise_pollution_mapping.py

View model performance metrics and predicted noise values.

Output

Trained AI model for noise prediction

Predicted noise pollution map

Excel file containing synthetic noise pollution data

Applications

Urban planning and smart cities

Environmental impact assessment

Traffic and industrial noise monitoring

Academic and educational projects

Disclaimer

This project uses synthetic data for demonstration purposes only and does not represent real-world measurements.

Author

Bamiekumo Becky Peremoboere
