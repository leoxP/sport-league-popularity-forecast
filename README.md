# Sports Popularity Forecasting

This project applies a suite of time series forecasting models to historical data on sports popularity metrics, including viewership, attendance, or social media engagement. The models selected for analysis include:

- Support Vector Machines (SVM)
- Theta Method
- Seasonal Autoregressive Integrated Moving Average (SARIMA)
- Exponential Smoothing (SES)
- Replacement Method
- Outlier Detection and Correction
- Holt Linear
- Random Forest
- Simple Moving Average (SMA)
- Correlation Analysis
- Holt Winter’s Method
- Naive Method
- Simple Average

## Evaluation Metrics

We evaluate the performance of each model based on the following metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

Additionally, we visualize the forecasted values alongside the actual data using graphs and box plots to assess the models’ accuracy and reliability.

## Usage

To run this project, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies using the following command:
pip install -r requirements.txt
3. Run the main script `forecasting_models.py` to execute the time series forecasting models.
python forecasting_models.py

## File Descriptions

- `forecasting_models.py`: Contains the implementation of various time series forecasting models.
- `data.csv`: Sample historical data on sports popularity metrics.
- `README.md`: This file.

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- statsmodels
- seaborn
- matplotlib

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
