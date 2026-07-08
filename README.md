# Expense-Tracker
A command-line app for logging your daily expenses and seeing where your money goes — totals overall, or broken down by category (Food, Rent, Fun, etc). Your data is saved to a local `expenses.json` file, so it's still there the next time you open the app.

## How to run
```bash
python expense_tracker.py
```
No extra libraries needed — just Python's built-in tools.

## What it does
- Add an expense (amount, category, optional note)
- View every expense you've logged
- See totals grouped by category
- See your grand total spent

## What this project demonstrates
- **File persistence** — expenses are saved to a JSON file so data survives between runs (a taste of how apps store data before you learn databases)
- **Classes** — an `ExpenseTracker` class keeps all the logic (loading, saving, adding, totaling) organized in one place instead of scattered loose functions
- **Error handling** — invalid number input (like typing "abc" for an amount) is caught and the user is asked again instead of the program crashing
- **Dictionaries** — used to group and total expenses by category

## Possible upgrades (good talking points in an interview)
- Add a monthly budget limit with a warning when you go over
- Export expenses to a CSV file
- Add a simple bar chart of spending by category using `matplotlib`
