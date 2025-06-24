#  Weather Forecasting using Machine Learning Techniques

This project uses multiple machine learning models to forecast weather patterns such as temperature, humidity, wind speed, and rainfall based on historical data.

##  Overview

The project is inspired by academic research and applies real-world weather data to build and compare predictive models, including Support Vector Regression (SVR) and Recurrent Neural Networks (RNN).

##  Project Structure

- `forecast_model.py`: Main Python script containing preprocessing, model training, and evaluation code.
- `combined_dataset.csv`: Historical weather dataset used for training.
- `research_paper.pdf`: Source research paper that guided the methodology.

##  Models Used

| Model                          | Description |
|-------------------------------|-------------|
| **SVR (Support Vector Regression)** | Used to capture non-linear patterns in temperature and weather forecasting. |
| **RNN (Recurrent Neural Network)** | Deep learning model used for sequence prediction based on past weather conditions. |

## Techniques Applied

- Outlier removal using IQR method
- Feature scaling with `MinMaxScaler`
- Splitting dataset using `train_test_split`
- Model evaluation using **Mean Squared Error (MSE)**

## Results

Both models were evaluated using MSE. Results showed:
- SVR performed well on short-term forecasting
- RNN performed better on capturing sequential dependencies

*(Add exact MSE values here if available)*

##  Dataset

The dataset includes features like:
- Temperature
- Dew point
- Wind speed and gust
- Pressure and visibility
- Precipitation (Rain)

> Format: CSV (`combined_dataset.csv`) with timestamp and meteorological features.

##  Reference

This work is based on insights from the research paper included in the repo:  
**"Weather Forecasting using Machine Learning Techniques"** *(PDF attached)*

##  How to Run

```bash
# Install dependencies
pip install -r requirements.txt

# Run the model script
python forecast_model.py
```

##  License

This project is for educational and research purposes.