# 💰 Expense Tracker

A simple command-line **Expense Tracker** built using Python and SQLite. This project allows users to manage their budgets, record daily expenses, and monitor their remaining balance through an interactive menu-driven interface.

## 🚀 Features

- **Add Budget:** Set and store your budget in the database.
- **Add Expenses:** Record expenses under different categories.
- **Categorized Expenses:** Organize spending into Food, Grocery, and Miscellaneous.
- **Total Expenses:** View expenses grouped by category and calculate total spending.
- **Total Budget:** Calculate the total amount of budget added.
- **Remaining Budget:** Automatically calculate the remaining balance.
- **Data Persistence:** Store budget and expense records using SQLite.

## 🛠️ Technologies Used

- **Python 3** – Core programming language.
- **SQLite3** – Database management.
- **SQL** – Database queries and operations.

## 📂 Project Structure

```text
Expense-Tracker/
│
├── expense_tracker.py
├── expense_tracker.db
└── README.md
```

*Note: The SQLite database file is automatically created when the program runs if it does not already exist.*

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone YOUR_REPOSITORY_URL
```

### 2. Navigate to the project directory

```bash
cd Expense-Tracker
```

### 3. Run the Python program

```bash
python3 expense_tracker.py
```

**No external libraries are required.** SQLite3 comes included with standard Python installations.

## 📸 How It Works

The program provides an interactive menu:

```text
===== EXPENSE TRACKER =====

1) Add budget
2) Add expenses
3) Total expenses
4) Total budget
5) Remaining budget
6) Exit

Enter operation number:
```

Choose an operation by entering its corresponding number.

## 🗄️ Database Structure

The project uses SQLite with two tables:

### Budget Table

| Column | Data Type | Description |
|---|---|---|
| id | INTEGER | Primary key |
| amount | REAL | Budget amount |

### Expenses Table

| Column | Data Type | Description |
|---|---|---|
| id | INTEGER | Primary key |
| category | TEXT | Expense category |
| amount | REAL | Expense amount |

## 📚 Concepts Learned

Through this project, I practised:

- Python functions
- Conditional statements
- Loops and exception handling
- Dictionaries
- User input and validation
- SQLite database connectivity
- SQL INSERT and SELECT queries
- Aggregate functions such as SUM()
- GROUP BY operations
- Database CRUD fundamentals

## 👨‍💻 Author

**Ayush Jha**

B.Tech CSE (AI & ML) Student

---

⭐ If you find this project useful, consider giving the repository a star!

