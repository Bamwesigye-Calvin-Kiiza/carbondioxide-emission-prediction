# Carbon Dioxide Emission Prediction

This repository contains code and resources for predicting carbon dioxide emissions based on vehicle attributes. The project includes data analysis, Principal Component Analysis (PCA), model selection, and more.

## Dataset

The dataset contains the following features:

- `MODELYEAR` (int): The year of the vehicle model.
- `MAKE` (str): The manufacturer of the vehicle.
- `MODEL` (str): The model name of the vehicle.
- `VEHICLECLASS` (str): The class/type of the vehicle.
- `ENGINESIZE` (float): The size of the vehicle's engine.
- `CYLINDERS` (int): The number of cylinders in the engine.
- `TRANSMISSION` (str): The type of transmission.
- `FUELTYPE` (str): The type of fuel used by the vehicle.
- `FUELCONSUMPTION_CITY` (float): The fuel consumption rate in the city (L/100km).
- `FUELCONSUMPTION_HWY` (float): The fuel consumption rate on the highway (L/100km).
- `FUELCONSUMPTION_COMB` (float): The combined fuel consumption rate (L/100km).
- `FUELCONSUMPTION_COMB_MPG` (int): The combined fuel consumption rate in miles per gallon (mpg).
- `CO2EMISSIONS` (target) (int): The carbon dioxide emissions of the vehicle (g/km).

The dataset is available in the `data` directory.

## Data Analysis

The `data_analysis.ipynb` notebook provides a detailed exploration of the dataset. It includes visualizations, summary statistics, and correlations to gain insights into the relationships between different variables and their impact on carbon dioxide emissions.

## Principal Component Analysis (PCA)

The `pca.ipynb` notebook implements Principal Component Analysis to reduce the dimensionality of the dataset while retaining important information. This technique helps in identifying the most significant features for predicting carbon dioxide emissions.

## Model Selection

The `model_selection.ipynb` notebook evaluates various machine learning models for predicting carbon dioxide emissions. It includes regression models such as Linear Regression, Decision Tree Regressor, Random Forest Regressor, and more. The notebook compares their performance and selects the best-performing model.

## Usage

To run the notebooks, ensure you have the necessary libraries installed. 

Open the notebooks using Jupyter Notebook or any compatible environment, and follow the instructions provided in each notebook.

## Results

The final selected model achieves an impressive accuracy in predicting carbon dioxide emissions. The results are discussed in detail in the `results.md` file.

## Conclusion

This project demonstrates the effectiveness of machine learning techniques in predicting carbon dioxide emissions based on vehicle attributes. The combination of data analysis, PCA, and model selection provides valuable insights for understanding and mitigating environmental impacts.

## Contributors

- Bamwesigye Calvin Kiiza(https://github.com/Bamwesigye-Calvin-Kiiza)

