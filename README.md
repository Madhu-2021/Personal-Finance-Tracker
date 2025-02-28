# Finance Tracker

## Overview
This is a simple finance tracking application that allows users to record and analyze their financial transactions. The application stores transaction data in a CSV file and provides a summary of income and expenses within a specified date range. It also offers a visualization of income and expense trends over time.

## Features
- Add new transactions with details such as date, amount, category, and description.
- View all transactions within a specified date range.
- Display a summary of total income, total expenses, and net savings.
- Generate a graphical representation of income and expenses over time.

## Requirements
Ensure you have the following dependencies installed before running the script:
- Python 3.x
- pandas
- matplotlib

You can install the required dependencies using the following command:
```bash
pip install pandas matplotlib
```

## Usage

### Running the Program
To run the program, execute the following command:
```bash
python finance_tracker.py
```

### Menu Options
1. **Add a new transaction**
   - You will be prompted to enter the transaction date, amount, category (Income/Expense), and description.
2. **View transactions and summary within a date range**
   - Enter the start and end date to filter transactions.
   - The script will display a summary including total income, total expenses, and net savings.
   - Optionally, you can generate a graphical plot of income and expenses over time.
3. **Exit**
   - Closes the program.

### Data Storage
All transactions are stored in a CSV file named `finance_data.csv` with the following columns:
- `date` (dd-mm-yyyy format)
- `amount`
- `category` (Income or Expense)
- `description`

## Functions
- `CSV.initialize_csv()`: Initializes the CSV file if it does not exist.
- `CSV.add_entry(date, amount, category, description)`: Adds a new transaction to the CSV file.
- `CSV.get_transactions(start_date, end_date)`: Retrieves transactions within a specified date range and displays a summary.
- `plot_transactions(df)`: Generates a graph of income and expenses over time.
- `main()`: Handles user interaction and menu selection.

## License
This project is open-source and free to use.

## Author
Developed by Madhumitha M ☺️

