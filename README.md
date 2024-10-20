# Financial and Election Analysis Project

This project contains two Python scripts: one to analyze financial data and another to analyze election data. Below is a brief description of each and how to run them.

## Included Scripts

1. **PyBank**: Analyzes financial data from a CSV file.
2. **PyPoll**: Analyzes election data from a CSV file.

## Requirements

- Python 3.10
- `csv` module (included with Python)
- `os` module (included with Python)

## Instructions

### PyBank

1. Ensure the `budget_data.csv` file is in the `Resources` folder.
2. Run the `PyBank` script with the following command:
    ```sh
    python pybank.py
    ```
3. The data analysis will be saved in `analysis/budget_analysis.txt`.

### PyPoll

1. Ensure the `election_data.csv` file is in the `Resources` folder.
2. Run the `PyPoll` script with the following command:
    ```sh
    python pypoll.py
    ```
3. The data analysis will be saved in `analysis/election_analysis.txt`.

## Results

### PyBank

The `PyBank` script performs the following analysis on the financial data:
- Total months analyzed.
- Net total of profits/losses.
- Monthly average change.
- Greatest increase in profits (date and amount).
- Greatest decrease in profits (date and amount).

### PyPoll

The `PyPoll` script performs the following analysis on the election data:
- Total votes cast.
- Percentage of votes for each candidate.
- Total number of votes for each candidate.
- Winning candidate based on the number of votes.

## Contributions

Contributions are welcome. If you have suggestions or improvements, please open an issue or submit a pull request.

