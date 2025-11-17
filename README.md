# Sales Summary Dashboard

This is a simple, single-page web application designed to fetch sales data from a `data.csv` file, calculate the total sales, and display it in a clean, responsive interface using Tailwind CSS.

## Features

*   **Data Fetching:** Automatically loads sales data from `data.csv`.
*   **Sales Aggregation:** Calculates the sum of the 'sales' column.
*   **Dynamic Title:** Updates the page title with a sales summary and current date.
*   **Responsive Design:** Utilizes Tailwind CSS for a modern and mobile-friendly layout.
*   **Error Handling:** Provides user feedback if data cannot be loaded or processed.

## Setup and Usage

1.  **Place `index.html` and `data.csv`:** Ensure both `index.html` and `data.csv` are in the same directory.
2.  **`data.csv` Format:** The `data.csv` file must contain a header row, and one of the headers must be exactly `sales` (case-sensitive) for the application to function correctly. The values in the `sales` column should be numerical.

    Example `data.csv`:
    ```csv
    id,product,sales
    1,Laptop,1200
    2,Mouse,25
    3,Keyboard,75
    4,Monitor,300
    ```

3.  **Open `index.html`:** Simply open the `index.html` file in your web browser. The script will automatically fetch, process, and display the total sales.

## Technologies Used

*   **HTML5:** Structure of the web page.
*   **JavaScript (ES6+):** For data fetching, parsing, and dynamic content updates.
*   **Tailwind CSS:** For styling and responsive design.

## Development

No build steps are required for this application as it uses CDN for Tailwind CSS and pure JavaScript for logic.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.