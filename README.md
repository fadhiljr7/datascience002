# M5 World Championship Data Analysis
This repository contains a comprehensive analysis of the M5 World Championship data. The analysis is performed using Python, specifically leveraging machine learning techniques to derive insights from the dataset. Below are the details of the contents and the steps undertaken during the analysis.

## Contents
- data hint.txt: This file provides explanations for the abbreviations used in the column names of the M5_World_Championship.csv file.
- M5_World_Championship.csv: The dataset containing various metrics related to hero picks, bans, and win rates during the M5 World Championship.
- Notebook.ipynb: The Jupyter Notebook containing all the code and analysis. This notebook covers data preprocessing, exploratory data analysis, machine learning model development (using XGBoost Regressor), model evaluation, and the generation of insights based on the model's predictions.
- Insight/Story.pdf: A PowerPoint presentation that summarizes the key insights and stories derived from the data analysis and the machine learning model. This presentation is intended to provide a clear and concise narrative of the findings..

## Project Overview
### Data Preprocessing
- Data Cleaning: Missing values were handled, particularly in the T_WinRate column where null values were replaced with 0, and then records with 0 were removed.
- Data Transformation: The column T_WinRate was converted to a float data type to ensure proper numerical operations.
### Exploratory Data Analysis (EDA)
- Descriptive Statistics: Basic statistics were calculated for numeric columns to understand the distribution of the data.
- Correlation Analysis: The relationship between different numeric features was analyzed to identify any significant correlations.
- Visualization: Box plots and scatter plots were used to visualize the distribution and relationships between various features.
### Machine Learning Model
- Model Used: XGBoost Regressor was selected due to the non-normal distribution of the data.
- Model Accuracy: The model achieved an accuracy of 85.91%, with an R-squared value of 0.86, indicating a strong fit.
- Error Metrics: The Mean Squared Error (MSE) and Root Mean Squared Error (RMSE) were used to evaluate the model's performance, showing low error rates.
### Insights and Story
- Hero Analysis: Insights include identifying heroes with the highest pick rates, the highest win rates, and those most frequently banned.
- Strategic Recommendations: Based on the model's predictions, strategies for hero selection in future games were suggested to maximize the chances of winning.

## How to Use
- Clone the Repository: Clone the repository to your local machine using git clone.
- Install dependencies: Ensure you have Python and Jupyter installed. You can install the required libraries by running: `pip install -r requirements.txt`
- Explore the Notebook: Open the Notebook.ipynb file in Jupyter Notebook or any other compatible environment to explore the code and results.
- Review the Insights: Open the Insight/Story.pptx file to review the key insights and stories derived from the analysis.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request to propose any changes.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
