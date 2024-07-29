# Stock Prediction Project

This project involves predicting stock prices using historical timeseries data. The data was preprocessed and fed into a neural network model, achieving high accuracy.

## Features
- Scraped timeseries data using `yfinance`.
- Preprocessed data using `MinMaxScaler` to normalize features, improving model performance and stability.
- Utilized `Matplotlib` for effective data visualization.
- Developed a neural network with LSTM, Dropout, and Dense layers.
- Achieved an R2 Score of `0.964`.

## Data Preprocessing
The timeseries data was scraped using the `yfinance` library. The data was then normalized using `MinMaxScaler` to ensure all features were on a similar scale, which helps in improving the model's performance and stability.

## Visualization
Data visualization was done using `Matplotlib`. This helped in understanding the trends and patterns in the data, which is crucial for effective model building.

## Model Development
The neural network model was developed using the following architecture:
- `LSTM` layers: To capture the temporal dependencies in the data.
- `Dropout` layers: To prevent overfitting.
- `Dense` layers: For output prediction.

## Performance
The model achieved an R2 Score of `0.964`, indicating a high level of accuracy in predicting stock prices.

## Usage
To use this project, follow these steps:
1. Clone the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the data preprocessing script to scrape and prepare the data.
4. Train the model using the training script.
5. Use the trained model to make predictions on new data.

## Conclusion
This project demonstrates the application of neural networks, specifically LSTM, in predicting stock prices. The preprocessing steps and model architecture played a crucial role in achieving high accuracy.
