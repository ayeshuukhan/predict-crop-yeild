# 🌾 Crop Yield Prediction using Machine Learning

This project predicts crop yield using machine learning techniques based on soil characteristics, weather conditions, and crop data. The goal is to help farmers and policymakers make better data-driven decisions to improve agricultural productivity and food security.

---

## Table of Contents

- [About the Project](#about-the-project)
- [Datasets Used](#datasets-used)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [How to Run](#how-to-run)
- [Results](#results)
- [Future Work](#future-work)
- [Contributors](#contributors)

---

## 📖 About the Project

Agricultural yield is highly dependent on environmental factors and soil quality. This project uses supervised learning techniques to train models that can accurately predict the yield of crops based on input features like:

- Soil nutrients and composition
- Weather data (temperature, rainfall, humidity)
- Crop type and region

The project includes data preprocessing, feature engineering, training multiple models, and evaluating their performance using metrics like RMSE and R² score.

---

## Datasets Used

The following datasets were used in this project:

- `crop_and_yield.csv`: Contains crop types and corresponding yields by year and region.
- `soil_data.zip`: Contains files with soil test results and properties (like NPK levels).
- `weather_data.zip`: Historical weather data for various districts.

All datasets are placed in the working directory or extracted from ZIP files inside the Colab environment.

---

## Technologies Used

- Python
- Pandas & NumPy
- Scikit-learn
- XGBoost
- Matplotlib & Seaborn (for visualization)
- Google Colab / Jupyter Notebook

---

## Project Structure

```plaintext
├── crop_and_yield.csv
├── soil_data/
│   ├── sample_submission.csv
│   ├── test (1).csv
├── weather_data/
│   ├── [weather CSV files]
├── models/
│   ├── trained_model.pkl
├── notebooks/
│   ├── EDA_and_Preprocessing.ipynb
│   ├── Model_Training_and_Evaluation.ipynb
├── README.md
