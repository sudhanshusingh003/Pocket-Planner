# Pocket-Planner
This code represents a simple personal finance management web application called "Pocket Planner". The app allows users to set a budget, track expenses, and manage their finances through a clean, user-friendly interface. Here is a breakdown of the key components and functionality:

# HTML Structure:
Head Section:

Links to external stylesheets (Font Awesome, custom stylesheets, and GSAP).
Sets meta tags for character encoding and viewport settings.
References a JavaScript file (app.js).
Body Section:

Navigation Bar: Displays the app's title.
Header: Contains the dashboard title, greeting message, and reset button.
Main Dashboard:
Budget Section: Displays total balance and a form to add a budget.
Expense Section: Contains cards for current amount and expense, a list of expenses, and a form to add expenses.
Footer: Includes copyright information and social media links.
#CSS Styles:
Global Styles:

Defines colors, fonts, and utility classes.
Sets default styles for body, html, and common elements.
Responsive Design:

Media queries adjust styles for screens smaller than 980px, 780px, and 650px, ensuring the app is mobile-friendly.
JavaScript Functionality:
GSAP Animations:

Adds animations to various elements on the page for a smoother user experience.
Budget Management:

Listens for a click event on the "Add Budget" button, validates the input, and updates the budget display.
Adds a new budget item and updates the current balance.
Expense Management:

Defines a function (createExpenseList) to create and display expense items in the expense list.
Allows for deleting and editing expense items, with updates to the balance and expense totals.
Listens for a click event on the "Add Expense" button, validates the input, and adds a new expense item to the list and the budget calculations.
Class Definition:

Defines a List_data class to structure expense items as objects, making it easier to manage them in an array.
Summary:
The "Pocket Planner" app provides a straightforward way to manage personal finances. Users can set a budget, add and track expenses, and see their current financial status at a glance. The use of modern web technologies like GSAP for animations, and a clean, responsive design ensures a pleasant user experience. If you need further assistance or more features added, feel free to ask!
