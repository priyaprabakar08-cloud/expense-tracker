# Expense Tracker

A web app to record daily expenses, set monthly budgets for each category, and get a warning before you overspend. Built as a team project (team of 2).

## Features

- **Dashboard** with a progress bar for each category's monthly budget and a spending-by-category pie chart
- **Budget alerts:** a category is flagged as "Nearing limit" at 80% of its monthly budget and "Over limit" at 100%
- **Add and delete expenses** with validation for amount, category and date
- **Filter expenses** by category and date range
- **Recurring expenses:** mark an expense (such as rent or a subscription) as recurring, and the app adds it automatically each month if it is not already logged
- **Set budgets** per category: Food, Travel, Bills, Shopping and Other

## Tech Stack

- Python
- Flask
- Flask-SQLAlchemy
- SQLite
- HTML

## How to Run

1. Clone the project:
```
   git clone https://github.com/priyaprabakar08-cloud/expense-tracker.git
   cd expense-tracker
```
2. Install the requirements:
```
   pip install -r requirements.txt
```
3. Start the app:
```
   python app.py
```
4. Open http://localhost:5000 in your browser. The database is created automatically the first time you run the app.

## Project Structure

- `app.py` : routes and app logic (budget checks, recurring expenses, filters)
- `models.py` : database models for expenses and budgets
- `templates/` : HTML pages
- `static/` : static files

## Screenshots

(Add your screenshots here)

## Future Improvements

- Edit existing expenses
- More recurring options: daily, weekly and yearly
- Deploy the app online

## Team

Built by a team of 2 as a college project.
