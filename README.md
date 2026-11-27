
# SpendWise - Interactive Budget Tracker

## Project Description

SpendWise is a personal budget tracking application that helps users manage their money, record expenses, monitor spending, and calculate their remaining balance.

The application allows users to add and delete expenses while automatically updating their financial dashboard.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- GitHub

## Improvements Made This Week

- Added interactive expense management.
- Added automatic budget calculations.
- Added expense categories.
- Added the ability to add and delete expenses.
- Added real-time dashboard updates.
- Added budget warning messages.

## JavaScript Concepts Implemented

### 1. Conditional Statements

The application uses if, else if, and else statements to check the remaining balance.

It displays different messages depending on whether the user is within budget, has used the entire budget, or has exceeded the budget.

### 2. Arrays

An array called expenses stores multiple expense records.

Each record contains:
- Expense name
- Expense amount
- Expense category

### 3. Loops

The for loop calculates total expenses by processing all records in the expenses array.

The forEach loop displays each expense in the dashboard.

### 4. DOM Manipulation

JavaScript uses document.getElementById() to access HTML elements.

The textContent property updates the budget, total expenses, balance, and feedback messages.

The createElement() method creates expense rows dynamically.

### 5. Event Handling

The application uses addEventListener() to respond to user actions.

- The submit event adds new expenses.
- The click event handles deleting expenses.
- preventDefault() prevents the form from reloading the page.

### 6. Budget Calculations

The application calculates the remaining balance using:

Remaining Balance = Total Budget - Total Expenses

The dashboard updates automatically whenever an expense is added or deleted.

## Challenges Encountered

- Connecting JavaScript to HTML correctly.
- Managing multiple expense records using arrays.
- Updating dashboard information dynamically.
- Handling form submissions without reloading the page.

## How Challenges Were Resolved

I used DOM manipulation, event listeners, arrays, loops, and reusable functions to organize the application and make it interactive.

## How to Use SpendWise

1. Open the SpendWise website.
2. Enter an expense name.
3. Enter the expense amount.
4. Select an expense category.
5. Click Add Expense.
6. View the updated expenses and remaining balance.
7. Click Delete to remove an expense.

## GitHub Repository

Repository Name: SpendWise

Repository URL: ADD YOUR GITHUB LINK HERE

## Author

SpendWise Project - 2026
