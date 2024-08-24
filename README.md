# TradingBot

This repository contains the code for a Trading Bot that uses machine learning models and various APIs to analyze market data and execute trades automatically. The bot is designed to work with multiple trading platforms and supports a range of trading strategies.

## Repository Contents

- **tradingbot.py**: The main script that runs the trading bot. It handles data fetching, model prediction, and trade execution.
- **finbert_utils.py**: Utility functions to process financial data and integrate with FinBERT, a financial sentiment analysis tool.
- **requirements.txt**: Lists all the Python dependencies required to run the bot.

## Features

- **Automated Trading**: Execute trades based on real-time data and predefined strategies.
- **Market Data Analysis**: Uses multiple data sources and APIs for comprehensive market analysis.
- **Machine Learning Integration**: Utilizes LSTM models for predicting stock prices.
- **Sentiment Analysis**: Integrates FinBERT for analyzing market sentiment from financial news.

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/kabirkohli123/Trading-Bot.git
   ```

2. Navigate to the repository directory:

   ```bash
   cd Trading-Bot
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Configure the Bot**: Edit the configuration in `tradingbot.py` to set your API keys, trading parameters, and strategy preferences.
   
2. **Run the Bot**: Execute the following command to start the bot:

   ```bash
   python tradingbot.py
   ```

3. **Monitor Performance**: The bot logs all trading activities and provides real-time feedback on its performance.

## Requirements

The project requires Python 3.x. All additional Python dependencies are listed in the `requirements.txt` file.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact

For any questions or feedback, please contact Kabir Kohli(mailto: kabirkohliyuvi@gmail.com).

