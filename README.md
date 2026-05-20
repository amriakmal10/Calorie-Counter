# Calorie Counter

A responsive and interactive web application that helps users calculate their daily caloric balance by tracking food intake (Breakfast, Lunch, Dinner, Snacks) and calories burned through Exercise. 

This project was built as part of the freeCodeCamp JavaScript Algorithms and Data Structures certification to master DOM manipulation, form handling, and string parsing.

##  Features

- **Dynamic Entry Management:** Add unlimited entry fields for different meal categories and exercise dynamically without reloading the page.
- **Calorie Balance Calculation:** Automatically calculates total consumed calories, total burned calories, and compares them against a daily budget goal.
- **Input Cleaning:** Uses Regular Expressions (Regex) to filter out invalid characters (like `+`, `-`, or spaces) from numeric inputs to prevent calculation bugs.
- **Surplus/Deficit Tracker:** Displays whether the user is in a caloric surplus or deficit with a clean, conditional UI update.
- **Clear Functionality:** Reset the entire form and all dynamic entries with a single click.

##  Tech Stack

- **HTML5:** Semantic structure for the form and entry containers.
- **CSS3:** Custom styling, including grid/flexbox layouts and conditional alerts.
- **JavaScript (ES6+):** Core logic focusing on:
  - Dynamic HTML generation using **Template Literals**.
  - Advanced DOM manipulation (`querySelector`, `insertAdjacentHTML`).
  - Input validation using **Regular Expressions (Regex)**.
  - Event listener management.

##  Key Concepts Learned

- **Template Literals & String Interpolation:** Dynamically generating HTML elements with precise, incremental `id` and `for` attributes (e.g., `` `Entry ${entryNumber} Name` ``).
- **The `insertAdjacentHTML` Method:** Efficiently appending raw HTML strings into the DOM without destroying existing event listeners.
- **Form Submission Handling:** Overriding default browser behaviors using `e.preventDefault()` to calculate values entirely on the client side.
- **NodeLists vs. Arrays:** Querying collections of inputs and converting or iterating through them to sum up totals.

1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR-USERNAME/calorie-counter.git](https://github.com/YOUR-USERNAME/calorie-counter.git)
