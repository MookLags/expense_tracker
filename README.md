# 💸 Expense Tracker CLI

A simple and straightforward command-line Expense Tracker built with Python. Perfect for keeping tabs on your daily expenses — one line item at a time!

---

## 🚀 Features

- ✅ Add new expenses by amount and category  
- 📋 View all recorded expenses  
- 📊 Calculate the total amount spent  
- 🔍 Filter expenses by category  
- ❌ Exit gracefully when you're done budgeting

---

## 🧠 How It Works

This script runs a looped CLI where users can interactively:

1. Add expenses
2. View all past entries
3. Get a sum of total spending
4. Filter spending by a specific category
5. Exit the program

Under the hood, expenses are stored as a list of dictionaries, and Python’s functional programming tools help keep things clean and readable.

---

## 🛠️ Functions Breakdown

```python
def add_expense(expenses, amount, category):
    # Adds a new expense dictionary to the expenses list
```
```python
def print_expenses(expenses):
    # Prints each expense in a readable format
```
```python
def total_expenses(expenses):
    # Returns the sum of all expense amounts
```
```python
def filter_expenses_by_category(expenses, category):
    # Returns a filtered list of expenses matching a category
```
🧪 Example Usage
```
$ python expense_tracker.py

Expense Tracker
1. Add an expense
2. List all expenses
3. Show total expenses
4. Filter expenses by category
5. Exit

Add an expense:

Enter amount: 50.00
Enter category: Groceries

Filter by category:

Enter category to filter: Groceries
Expenses for Groceries:
Amount: 50.0, Category: Groceries
```

📦 Requirements

No external dependencies — just Python 3.x!
📁 File Structure

expense_tracker.py   # Main CLI script with all functionality

🚀 Getting Started

Make sure you have Python 3 installed.

Save the script to a file, e.g., expense_tracker.py

Run it from the terminal:

💡 Future Improvements

    Save/load expenses to/from database (SQLite or maybe Postgres)

    Add date field for each expense

    Include basic analytics or visualization

    GUI version

    Monthly Review of expenses
