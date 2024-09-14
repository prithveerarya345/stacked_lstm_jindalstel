# stacked_lstm_jindalstel
This project implements a Stacked Long Short-Term Memory (LSTM) neural network to predict stock prices. The model is trained and tested on historical stock data for Jindal Steel obtained from Yahoo Finance.

## Project Overview

The notebook `stacked_lstm_jindalstel.ipynb` contains the following key components:

1. Data collection using yfinance
2. Data preprocessing and scaling
3. Creation of a Stacked LSTM model
4. Model training with early stopping
5. Performance evaluation using MAPE, RMSE, and R2 Score
6. Visualization of results
7. Future price prediction for the next 30 days

## Model Architecture

The Stacked LSTM model consists of:
- 3 LSTM layers with 50 units each
- 1 Dense output layer

The model is trained using the Adam optimizer and Mean Squared Error loss function.

## Results

Train MAPE: 0.0233
Test MAPE:0.0197

Train RMSE: 17.3739
Test RMSE: 18.0160

Train R2 Score: 0.9912443199720601
Test R2 Score: 0.9891419464940624

## Future Improvements

Potential areas for improvement include:
- Experimenting with different model architectures
- Including additional features (e.g., trading volume, technical indicators)
- Implementing a rolling window approach for continuous prediction

## Disclaimer

This model architecture was inspired from this youtube video: https://youtu.be/H6du_pfuznE?si=uOUbPPqaowR0GkmC 

This project was to only familiarise myself with certain technologies. Not financial advise.

## License

This project is open-source and available under the MIT License.
