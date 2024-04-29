# Binance-Live-Aggregation-Liquidation-WebSocket

## WebSocket Bots for Real-Time Data Processing

## Description
This repository contains Python scripts for creating WebSocket bots that stream real-time data from the Binance API and process it for various purposes. Each bot is designed to connect to specific WebSocket streams, receive incoming messages, and perform designated tasks based on the data received.

## Bots

### Aggregated Trade Data Bot
- **Purpose**: Streams aggregated trade data for the BTC/USDT trading pair and saves it to a CSV file at regular intervals.
- **Features**:
  - Establishes a WebSocket connection with the Binance API to stream aggregated trade data.
  - Parses incoming messages, extracts relevant trade information, and stores it in a pandas DataFrame.
  - Saves the aggregated trade data to a CSV file every hour.
- **Dependencies**:
  - Python 3.x
  - pandas
  - websocket-client
  
### Liquidation Order Bot
- **Purpose**: Streams liquidation order data from the Binance API and saves it to a CSV file for analysis.
- **Features**:
  - Connects to the WebSocket stream for liquidation orders on Binance.
  - Processes incoming messages to extract liquidation order details such as symbol, order type, price, quantity, etc.
  - Stores the liquidation order data in a pandas DataFrame and saves it to a CSV file.
- **Dependencies**:
  - Python 3.x
  - pandas
  - websocket-client

## Usage
1. Clone or download the repository to your local machine.
2. Install the required dependencies listed for each bot.
3. Run each Python script in a Python environment.
4. The bots will establish WebSocket connections and start streaming real-time data.
5. The data will be processed and saved according to the specified functionality of each bot.

## Note
- Ensure you have an active internet connection to establish WebSocket connections with the Binance API.
- These bots are for educational purposes and demonstrate WebSocket data streaming and processing techniques.


## Contact
For any inquiries or support, please contact arman13m99@gmail.com
