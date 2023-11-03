# Health Status Analysis in Developing Countries

## Project Overview

"Health" is a particularly sensitive issue in developing countries, where the challenges of hygiene, nutrition, and work-life balance significantly affect the population's well-being. There is a compelling body of research indicating a correlation between long working hours and an increased incidence of obesity, which in turn contributes to deteriorating health conditions among the working population. This project aims to explore the social and health status of individuals in developing countries through a data-driven approach.

Utilizing the Life in Transition Survey dataset provided by the European Bank for Reconstruction and Development in collaboration with the World Bank, this project offers an analysis of socio-economic and political factors affecting health outcomes in 31 countries. The dataset provides a rich source of information, allowing for an in-depth examination of the determinants of health within these populations.

## Contents of the Repository

- `Health_Status_Analysis.ipynb`: A Jupyter notebook containing all the data preprocessing steps, exploratory data visualization, and machine learning models applied to predict the Body Mass Index (BMI) variable.
The dataset can be accessed through this link: https://www.ebrd.com/what-we-do/economic-research-and-data/data/lits.html
## Data Preprocessing

The initial stage of the project involves cleaning and preparing the data for analysis. This includes handling missing values, encoding categorical variables, and normalizing the data where necessary.

## Data Visualization

With the data preprocessed, a series of visualizations are provided to offer insights into the distribution of various factors and their relationships with the health outcomes of the surveyed population.

## Machine Learning Models

Several machine learning models are implemented to predict BMI, a key indicator of health status. The models are evaluated based on their performance and the most effective model is identified.

## Getting Started

To run this project, you will need an environment capable of running Jupyter notebooks with Python 3. The following libraries are also required:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install these libraries using `pip`:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
