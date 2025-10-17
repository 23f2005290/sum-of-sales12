# Sales Summary Dashboard

This project provides a simple, single-page web application to display a summary of sales data fetched from a local `data.csv` file.

## Features

-   **Data Fetching**: Automatically loads `data.csv` from the same directory.
-   **Sales Calculation**: Parses the CSV to sum the values in the 'sales' column.
-   **Dynamic Display**: Updates the page title and a dedicated div with the calculated total sales.
-   **Responsive Design**: Utilizes Tailwind CSS for a clean and responsive user interface.
-   **Error Handling**: Provides informative messages if the CSV file is not found, malformed, or missing the 'sales' column.

## File Structure

```
. பணியா
├── index.html
└── data.csv
```

## How to Use

1.  **Save Files**: Ensure `index.html` and `data.csv` are in the same directory.
2.  **Open in Browser**: Simply open the `index.html` file in your web browser.
3.  **View Summary**: The application will automatically fetch `data.csv`, calculate the total sales, and display it on the page.

### `data.csv` Format

The `data.csv` file is expected to have a header row, and one of the columns must be named `sales`. Example:

```csv
product,sales,region
Laptop,1200,North
Mouse,25,South
Keyboard,75,East
Monitor,300,West
```

## Technologies Used

-   **HTML5**: Structure of the web page.
-   **JavaScript**: For fetching, parsing, and displaying data.
-   **Tailwind CSS**: For styling and responsive design.