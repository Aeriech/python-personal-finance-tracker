### Project Overview - PyNance Tracker
This project is a CLI-based finance tracker built with Python. It enables users to record financial transactions, categorize income and expenses, and generate insightful summaries. The application stores data in a CSV file, allowing users to retrieve transactions within a specified date range and visualize financial trends using Matplotlib.

Key Features:
   - CSV-Based Storage – Stores transaction data in a structured CSV format.
   - Transaction Logging – Allows users to enter date, amount, category (Income/Expense), and description.
   - Date-Based Filtering – Retrieves transactions within a user-specified date range.
   - Financial Summary Reports – Calculates total income, expenses, and net savings.
   - Data Visualization – Generates line graphs of income and expenses over time.
   - User-Friendly CLI Interface – Provides an interactive menu for adding and viewing transactions.

Tech Stack:
   - Python (Primary Language)
   - Pandas (Data manipulation)
   - CSV Module (Data storage)
   - Datetime (Date formatting and handling)
   - Matplotlib (Data visualization)
   
## **Getting Started**

### Prerequisites

Ensure you have the following installed:

- [Python](https://www.python.org/downloads/) (version 3.13.2 or higher)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Aeriech/python-personal-finance-tracker.git
   ```

2. Install dependencies:
   ```bash
   cd python-personal-finance-tracker
   pip install matplotlib
   pip install pandas
   ```

3. Run development:
   ```bash
   python main.py 
   ```