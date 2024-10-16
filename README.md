# Bitcoin Price Model (2013-2029)

## Project Overview
This project is a comprehensive exploration of Bitcoin price trends from 2013 to 2029. The model leverages historical data and various statistical techniques to forecast future Bitcoin prices. It aims to help analysts and investors understand long-term trends, make better investment decisions, and gain insights into Bitcoin's price volatility over time.

The model forecasts Bitcoin prices by analyzing historical price movements and fitting them to a trend that projects up to 2029. The project includes multiple steps, such as data cleaning, exploratory data analysis (EDA), model building, and visualization.

## Objectives
- **Data Exploration**: Understand historical price trends and major Bitcoin price events between 2013 and 2029.
- **Price Prediction**: Build models that predict Bitcoin prices up to 2029.
- **Visualization**: Create easy-to-understand graphs that show price predictions and their confidence intervals.
- **Trend Analysis**: Identify critical turning points and price trends over time.

## Data Source
The dataset used in this project is sourced from a trusted cryptocurrency API or dataset provider, tracking Bitcoin's price from 2013 to the present. (https://www.kaggle.com/datasets/mczielinski/bitcoin-historical-data) 

It includes:
- **Timestamp**: The date and time of each price record.
- **Close Price**: The closing price of Bitcoin for each day.
- **Other Features**: Additional data such as volume, market cap, and more (if applicable).

## Methodology
1. **Data Collection**: 
   - Bitcoin price data is collected from 2013 to the present. 
   - The data is preprocessed to ensure quality (handling missing values, outliers, etc.).
   
2. **Exploratory Data Analysis (EDA)**:
   - Visualize historical price trends, volatility, and price spikes.
   - Analyze year-over-year growth and periods of high volatility.

3. **Model Building**:
   - Several predictive models are explored:
     - **Linear Regression**: Used to estimate the overall trend.
     - **Logarithmic Transformations**: Applied to better understand exponential growth in prices.
     - **Power Law Trend**: A model similar to what is seen in Bitbo (or other cryptocurrency forecasting platforms) is used to fit Bitcoin's price trajectory.

4. **Evaluation**:
   - The models are evaluated using error metrics like Mean Absolute Percentage Error (MAPE) and Root Mean Squared Error (RMSE).
   - Results are compared to determine which model best captures the long-term trends in Bitcoin prices.

5. **Prediction & Visualization**:
   - Predict Bitcoin prices from 2024 to 2029.
   - Visualize the predicted prices along with confidence intervals to illustrate the potential range of price movements.

## Visualizations
The project includes several visual outputs:
- **Price Trend Graphs**: Shows historical and predicted prices from 2013 to 2029.
- **Confidence Intervals**: Visualize the uncertainty in predictions using confidence bands around the predicted trend line.
- **Volatility Analysis**: Visualize periods of high volatility and price drops/spikes.

## Results
The model provides price predictions for Bitcoin up to 2029 with a detailed trend analysis. The output includes visualizations of both historical and forecasted prices, alongside confidence intervals for uncertainty estimation. Analysts and investors can use these insights to understand future price movements and volatility patterns.

## Future Work
In future iterations of this project, the following enhancements and additions could be considered:

Incorporating Sentiment Analysis: Adding social media and news sentiment data to understand how public perception affects Bitcoin prices.
Feature Engineering: Introducing more advanced features such as macroeconomic indicators, global financial trends, and market sentiment indices.
Advanced Machine Learning Models: Applying more sophisticated machine learning techniques, such as Long Short-Term Memory (LSTM) networks or Reinforcement Learning, to further improve the accuracy of the predictions.
Real-time Forecasting: Incorporating real-time data streams to provide more up-to-date predictions that adjust based on the latest market information.

## Key packages include:
- **Python 3.x**
- **pandas**: For data manipulation.
- **numpy**: For numerical calculations.
- **matplotlib** & **seaborn**: For visualization.
- **scikit-learn**: For regression models.

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/bitcoin-price-model.git

## Requirements
To run this project, install the necessary dependencies by running:

```bash
pip install -r requirements.txt
