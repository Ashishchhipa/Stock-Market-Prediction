# Stock-Market-Prediction

* Your folder should contain multiple .csv files, each representing historical stock data for a different company.
* Each CSV file should have columns similar to:   Date | Open | High | Low | Volume | Close | Adj Close

* How It Works
* For each CSV file in the folder:
   * .Reads and cleans the file.
   * .Ensures required columns are present.
   * .Computes technical indicators.
   * .5-day Moving Average (ma5)
   * .10-day Moving Average (ma10)
   * .Predicts the next day's close price using the last row of data.
   * .Prints the prediction in a readable format.



*Found 50 CSV files in 'data/'

*[1/50] ✅ INFY: Predicted Next Day Close = ₹1423.67
*[2/50] ✅ TCS: Predicted Next Day Close = ₹3692.24
*[3/50] ❌ Skipping RELIANCE.csv - Missing required columns.
...
*✅ Done with all predictions.


*🐍 Requirements
*Python 3.7+
*pandas
*scikit-learn   


*from your_script import predict_next_day_close_from_folder
*predict_next_day_close_from_folder("path/to/your/csv/folder", max_files=10)


   
