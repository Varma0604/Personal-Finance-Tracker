# Personal Finance Tracker

## Description
A web-based personal finance management tool that helps users track their expenses, manage their budget, and visualize spending trends. The application allows users to input expenses, track total spending, and view remaining budget amounts. Additionally, users can see recent expenses and a graphical breakdown of expenses by category.

## Key Features
- **Expense Tracking**: Users can add expenses by category and amount through a simple form.
- **Budget Overview**: Displays total budget, total expenses, and the remaining balance dynamically.
- **Expense Breakdown (Pie Chart)**: A real-time pie chart visualizing expenses by category using Chart.js.
- **Recent Expenses List**: Shows the five most recent expenses with options to edit or delete.
- **Form Validation**: Ensures both category and amount fields are filled before adding an expense.
- **Dynamic Updates**: The budget, expenses list, and chart automatically update upon adding or removing expenses.

## Technologies Used
- **HTML5**: For structuring the content of the web application.
- **CSS3**: For styling, including layout, forms, and visual elements.
- **JavaScript**: For dynamic interaction, form handling, and updating the budget and expense details.
- **Chart.js**: For generating dynamic pie charts to visually represent expenses.
- **Font Awesome**: For icons used in the edit and delete buttons for expenses.

## Code Highlights
- **Dynamic Form Handling**: 
    - Tracks user inputs for category and amount.
    - Validates the form and prevents submission if fields are empty.
  
- **Real-time Budget Overview**:
    - Calculates and displays total expenses and remaining budget.
    - Updates automatically as users add or delete expenses.

- **Expense Breakdown Visualization**:
    - Uses Chart.js to display a pie chart of expenses categorized by user-defined categories.
    - Updates the pie chart dynamically with every expense addition or removal.

- **Recent Expenses List**:
    - Displays the five most recent expenses with options to edit or delete.
    - Editing an expense populates the form fields for easy updating.

## How to Use
1. Set your **category** and **expense amount** in the form.
2. Click **Add Expense** to update the total expenses and budget overview.
3. View the **Expense Breakdown** pie chart for a visual summary.
4. See the most recent expenses in the **Recent Expenses** list.
5. Use the **edit** or **delete** buttons to manage your expenses.

## Possible Enhancements
- Add authentication to track expenses for different users.
- Include an option to set a custom total budget.
- Implement a feature to track income and savings in addition to expenses.
- Provide expense filtering and categorization for detailed financial analysis.
