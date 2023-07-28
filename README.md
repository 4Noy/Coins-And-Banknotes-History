
# Expense Tracker Web App

The Expense Tracker Web App is a Flask-based web application that allows users to track their daily expenses by entering the amount spent on various denominations of coins and banknotes. The entered data is stored in an Excel file (`data.xlsx`) for record-keeping and easy access to past entries.

## Requirements

- Python 3.X - To install Python 3, please visit the official website: [https://www.python.org/](https://www.python.org/)
- openpyxl - To install the required library, use the following command:
  ```bash
  pip install openpyxl
  ```

## Usage

1. Run the app using Python:
   ```bash
   python expense_tracker.py
   ```

2. Access the web application by visiting `http://localhost:5002` in your web browser.

3. Enter the date and the number of each denomination of coins and banknotes spent on that day.

4. Click the "Add Entry" button to record the expenses.

5. To view the summary of all recorded expenses, click the "Summary" link on the top navigation bar.

6. To view the expenses for a specific date, enter the date in the "Precise Date" section and click the "View" button.

7. To download the Excel file containing all recorded expenses, click the "Download Excel File" button.

## Data Storage

The app uses an Excel file named `data.xlsx` to store all the recorded expenses. If the file does not exist when you run the app for the first time, it will be created automatically with appropriate column headers.

## Note

- The app allows you to track the number of coins and banknotes spent in different denominations, ranging from 1 centime to 200 euros.
- If you wish to remove any amount from your expenses, you can enter the number of banknotes to be removed in the respective "Enlevé" section.

## Author

- [Noy](https://github.com/4Noy)

## Version

- 0.1
