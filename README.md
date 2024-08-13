# Sales Report Dashboard

Welcome to the Sales Report Dashboard repository. This repository contains the data files and Power BI dashboard used for analyzing sales performance and generating comprehensive reports.
![image](https://github.com/user-attachments/assets/6dc68b47-1cf3-4cfa-a942-d961a137ae43)

## Contents

- `Details.csv`: Contains detailed information about sales transactions.
- `Orders.csv`: Contains information about orders and customer details.
- `SalesReport.pbix`: The Power BI dashboard file that visualizes and analyzes the sales data.

## Files

### `Details.csv`

- **Description**: This file includes detailed records of sales transactions, including financial metrics and product details.
- **Format**: CSV (Comma-Separated Values)
- **Columns**:
  - `Order ID`: Unique identifier for each order.
  - `Amount`: Total amount of the sale.
  - `Profit`: Profit made from the sale.
  - `Quantity`: Number of units sold.
  - `Category`: Product category.
  - `Sub-Category`: Specific sub-category of the product.
  - `PaymentMode`: Mode of payment (e.g., Credit Card, PayPal).

### `Orders.csv`

- **Description**: Contains order-specific information including customer and location details.
- **Format**: CSV (Comma-Separated Values)
- **Columns**:
  - `Order ID`: Unique identifier for each order (corresponds to `Order ID` in `Details.csv`).
  - `Order Date`: Date when the order was placed.
  - `CustomerName`: Name of the customer who placed the order.
  - `State`: State where the customer is located.
  - `City`: City where the customer is located.

### `SalesReport.pbix`

- **Description**: Power BI report file that integrates `Details.csv` and `Orders.csv` to provide interactive sales visualizations and insights.
- **Format**: Power BI Desktop file
- **Features**:
  - Interactive dashboards with visualizations of sales performance.
  - Filters and slicers for analyzing sales data by various dimensions (e.g., date, product category, payment mode).
  - Key metrics such as total sales amount, total profit, and sales trends by region and customer.

## How to Use

1. **Download** the CSV files and the Power BI file from this repository.
2. **Open** Power BI Desktop.
3. **Import** the CSV files into Power BI:
   - Go to `Home` > `Get Data` > `Text/CSV`.
   - Select and load `Details.csv` and `Orders.csv`.
4. **Open** the `SalesReport.pbix` file in Power BI Desktop to view the dashboard.
5. **Interact** with the dashboard to explore sales data and generate insights.
6. **Publish** the dashboard to Power BI Service if you wish to share it with others.
