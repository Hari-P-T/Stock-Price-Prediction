# Stock-Price-Prediction

This C++ program reads data from a CSV file, calculates the average of the last 3 and 21 days' closing prices, and predicts whether the price is expected to go UP or DOWN. The prediction is made based on the comparison of the averages.

## Requirements

- C++ compiler (GCC recommended)

## Usage

1. Make sure you have a valid CSV file named `data.csv` in the same directory as the executable or provide the correct path to the CSV file when running the program. The CSV file should contain numerical values representing the stock data, with each row having one data point (e.g., date, open, high, low, close, volume, etc.) .

2. Compile the C++ program using your preferred C++ compiler:

```bash
g++ stock_prediction.cpp -o stock_prediction
```

3. Run the compiled executable:
   ```bash
./stock_prediction
```

## Important Note
The program assumes that the CSV file is in a specific format and contains the necessary stock data in the correct columns. Make sure the CSV file is structured accordingly to avoid any issues.

