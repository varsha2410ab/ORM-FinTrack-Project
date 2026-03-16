# FinTrack Pro – CLI Finance Manager

FinTrack Pro is a Python-based Command Line Interface (CLI) application to help users manage their personal finances efficiently. It allows you to track expenses, categorize spending, manage subscriptions, and monitor monthly budgets.

The app uses **SQLite** as the database and **SQLAlchemy ORM** for database interaction. Data is stored locally, so your expenses and categories persist between runs.

## Features
- Add, update, and delete expenses
- Categorize expenses into different categories
- Search expenses by specific date
- Generate category-wise expense reports
- Set monthly budgets
- Receive budget alerts when spending exceeds limits
- Track subscriptions with their next due date

## Tech Stack
- Python 3
- SQLite (database)
- SQLAlchemy ORM
- Command Line Interface (CLI)

## How to Run
1. Clone the repository or download the project.
2. Open Command Prompt / PowerShell in the project folder.
3. Install SQLAlchemy if not already installed:

```bash
pip install sqlalchemy
