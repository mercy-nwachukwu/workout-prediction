# Workout Prediction from Motion Sensor Data

## Project Overview
This project aims to predict various workouts, including barbell lifts, squats, deadlifts, overhead presses, and rows, using data recorded from motion sensors. The core of the project involves a comprehensive machine learning pipeline that covers everything from data preprocessing to predictive modeling. Key steps include converting raw sensor data, visualizing time series data, outlier detection, feature engineering, predictive modeling, and counting repetitions with a custom algorithm.

### Key Features:
- **Data Preprocessing**: Converting raw data from sensors, reading CSV files, splitting data, and cleaning.
- **Data Visualization**: Plotting time series data for insightful analysis.
- **Outlier Detection**: Utilizing Chauvenet’s criterion and Local Outlier Factor (LOF) for identifying anomalies.
- **Feature Engineering**: Implementing techniques such as frequency analysis, low pass filtering, Principal Component Analysis (PCA), and clustering to enhance model inputs.
- **Predictive Modeling**: Applying various machine learning algorithms, including Naive Bayes, Support Vector Machines (SVMs), Random Forests, and Neural Networks, to predict workout types accurately.
- **Counting Repetitions**: Developing a custom algorithm to count repetitions accurately during workouts.

## Getting Started

## Environment Setup

This project uses Conda to manage its environment and dependencies. To set up the environment, you will need to have Conda installed on your system.

### Creating the Conda Environment

To create a Conda environment with all the necessary dependencies, follow these steps:

1. Open your terminal.
2. Navigate to the project directory where the `environment.yml` file is located.
3. Run the following command:

```bash
conda env create -f environment.yml

conda activate tracking-barbell-exercises

```
