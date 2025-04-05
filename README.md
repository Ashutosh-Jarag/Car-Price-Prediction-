# Car Price Prediction

## Description
This project is a simple machine learning model designed to predict car prices based on various attributes. The pipeline includes data cleaning, exploratory data analysis (EDA) to uncover relationships between car models and features like fuel type, model, and distance traveled, and the application of a linear regression model. The dataset is preprocessed using one-hot encoding for categorical variables like fuel type, achieving a 92% accuracy on the test set.

## Required Tools and Libraries
- **Python 3.8+** - Core language for data processing and model building
- **Pandas** - Data manipulation and cleaning
- **NumPy** - Numerical operations
- **Scikit-learn** - Linear regression model and one-hot encoding (via `OneHotEncoder` or `pandas.get_dummies`)
- **Matplotlib/Seaborn** - Visualization for EDA
- **Jupyter Notebook** - For data exploration and model training

## Features
- Data cleaning to handle missing or inconsistent values
- Exploratory data analysis (EDA) to identify relationships between car price and attributes (e.g., fuel type, model, distance traveled)
- One-hot encoding for categorical variables like fuel type
- Simple linear regression model with 92% accuracy on the dataset

## Installation
1. Clone the repository: `git clone https://github.com/Ashutosh-jarag/Car-Price-Prediction-.git`
2. Install dependencies(python, numpy, matplotlib, seaborn, scikit-learn)
3. Place the dataset (e.g., `quikr_car.csv`) in the project’s root directory
4. Open the Jupyter Notebook (`Car_Price_Prediction.ipynb`) to run the analysis and model

## Usage
1. Launch the Jupyter Notebook (`Car_Price_Prediction.ipynb`) to:
   - Load and clean the dataset
   - Perform EDA to visualize relationships between car attributes and price
   - Apply one-hot encoding to categorical features like fuel type
   - Train and evaluate the linear regression model
2. Run the notebook cells to predict car prices and view the model’s performance (92% accuracy)

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
MIT License
