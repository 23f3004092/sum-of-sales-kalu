# Sales Summary Application

This is a simple single-page web application that displays product sales data and calculates the total sales.

## Features

- Fetches sales data from an embedded CSV string.
- Calculates the sum of the 'sales' column.
- Displays the total sales on the page.
- Renders a Bootstrap table (#product-sales) listing each product with its total sales.
- Ensures #total-sales is accurate after render.
- Uses Bootstrap 5 for styling.

## How it works

The `index.html` file contains an embedded CSV string representing the sales data. Upon page load, the JavaScript code parses this CSV, sums the sales figures, and updates the `#total-sales` element with the calculated total. It also populates a table with individual product sales.
