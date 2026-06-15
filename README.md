# personalfinanceadvisor

A Flask web app for personal finance management — covering budgeting, debt tracking, savings goals, investment planning, and daily financial literacy tips.

## What it does

- Multi-page web app with dedicated sections for each finance area
- Budget tracker — log income and expenses, see where money is going
- Debt manager — track outstanding debts and payoff progress
- Savings planner — set and monitor savings goals
- Investment overview — track investment allocations
- Daily tip — surfaces a rotating financial literacy tip on the home page
- User management — add and switch between user profiles

## Project structure

```
app.py              # Flask application and route definitions
static/
  style.css         # Stylesheet
templates/
  index.html        # Home / daily tip
  budget.html       # Budget tracker
  debt.html         # Debt manager
  savings.html      # Savings goals
  investment.html   # Investment overview
  literacy.html     # Financial literacy content
  add_tip.html      # Add a new daily tip
  add_user.html     # Add a user profile
  today_tip.html    # Today's tip view
```

## Setup

```bash
pip install flask
python app.py
```

Then open `http://localhost:5000` in your browser.
