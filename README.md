# Sales Summary 419

## Summary
Sales Summary 419 is a simple single-page web application designed to read sales data from a CSV file and compute the total sales for specified categories. Using the Fetch API, the application loads `sales.csv`, sums the sales from categories where the category number is less than or equal to 29, and displays the result rounded to two decimal places in the designated HTML element.

## Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/sales-summary-419.git
   cd sales-summary-419
   ```

2. **Add the sales.csv file**
   Ensure the `sales.csv` file is placed in the project directory.

3. **Open the index.html file**
   Use your preferred web browser to open `index.html`. The application will automatically fetch data from the CSV and display the total sales.

4. **Run a local server (optional)**
   If you wish to run a local development server, you can use the following command if you have Python installed:
   ```bash
   python -m http.server
   ```
   Navigate to `http://localhost:8000` in your web browser.

## License
MIT License