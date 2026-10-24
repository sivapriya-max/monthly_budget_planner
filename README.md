# Monthly Budget Planner 

##  Project Overview

The **Monthly Budget Planner** is a Python-based desktop application developed using Tkinter. It helps users manage their monthly finances by recording income, adding expenses, calculating total expenditure, and displaying the remaining balance. The application also provides a category-wise expense summary, making it easier to understand spending patterns and manage money effectively.

##  Objectives

- Record and manage monthly income.
- Add expenses under different categories.
- Calculate total expenses automatically.
- Display the remaining balance after expenses.
- Generate a category-wise spending summary.
- Provide a simple and user-friendly graphical interface.

##  Technologies Used

- **Programming Language:** Python
- **GUI Framework:** Tkinter
- **Message Handling:** Tkinter Messagebox
- **Data Structures:** Lists and Dictionaries

##  Features

- **Income Management:** Enter and save monthly income.
- **Expense Tracking:** Record expenses with their respective categories.
- **Automatic Calculation:** Calculate total expenses and remaining balance.
- **Category-wise Summary:** View the total amount spent in each category.
- **Input Validation:** Display error messages for invalid amounts or missing categories.
- **Interactive GUI:** Simple desktop interface for easy financial tracking.

##  Working Principle

1. **Enter Income:** The user enters their monthly income and saves it.
2. **Add Expenses:** The user enters an expense amount and its category.
3. **Calculate Total:** The application automatically calculates the total of all recorded expenses.
4. **Update Balance:** The remaining balance is calculated by subtracting total expenses from income.
5. **Display Summary:** The interface displays the total expenditure, remaining balance, and category-wise spending details.

##  Getting Started

### Prerequisites

- Python 3.x
- Tkinter (usually included with standard Python installations)

### Installation and Execution

1. Clone the repository:

   ```bash
   git clone <your-repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd <project-folder>
   ```

3. Run the Python program:

   ```bash
   python budget_planner.py
   ```

4. Enter your income, add expenses, and view the updated financial summary.

##  Example

Suppose the user enters a monthly income of ₹20,000 and records the following expenses:

| Category | Amount |
|---|---:|
| Food | ₹2,000 |
| Transport | ₹1,000 |
| Education | ₹3,000 |
| **Total Expenses** | **₹6,000** |
| **Remaining Balance** | **₹14,000** |

##  Future Enhancements

- Save financial records to a file or database.
- Add expense editing and deletion options.
- Include monthly expense reports and graphical charts.
- Add budget limits and spending alerts.
- Provide date-wise transaction tracking.
- Support exporting financial reports to CSV or Excel.

## ⚠️ Limitations

The current application stores income and expenses in memory, so the records are lost when the application closes. It also uses integer values for financial amounts and does not maintain a permanent transaction history.

ython GUI project to demonstrate basic financial management, data handling, and desktop application development.

