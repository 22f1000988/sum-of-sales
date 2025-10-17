# Sales Summary DashboardThis project provides a simple, single-page web application to display a summary of sales data. It fetches sales figures from a `data.csv` file, calculates the total sales, and presents the sum on a responsive dashboard using Tailwind CSS.
## Features
- **Data Fetching**: Automatically loads `data.csv` from the same directory.
- **Sales Calculation**: Parses the CSV to identify and sum values in the 'sales' column.
- **Dynamic Display**: Shows the calculated total sales on the page.
- **Responsive Design**: Utilizes Tailwind CSS for a clean, mobile-friendly layout.
- **Single-File Application**: All functionality is contained within `index.html` for easy deployment.
## Setup
To run this application, simply place the `index.html` and `data.csv` files in the same directory and open `index.html` in your web browser. Ensure that `data.csv` contains a column header named 'sales' with numerical values.
## File Structure
```
.
├── index.html
└── data.csv
```
## Usage
1. Ensure `data.csv` is present in the same folder as `index.html`.
2. The `data.csv` file must have a column with the header `sales`.
3. Open `index.html` in any modern web browser.
4. The page will automatically fetch `data.csv`, calculate the total sales, and display it.
## Example `data.csv` format
```csv
product,sales,region
Laptop,1200.50,East
Keyboard,75.25,West
Monitor,300.00,North
Mouse,25.75,South
```