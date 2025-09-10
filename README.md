# Analyzing Dashboard

## Description

This is an interactive **Power BI** dashboard designed to provide insights into customer and product data. The dashboard includes various metrics and charts, such as:

- Total amount by product category
- Price per unit by product category
- Predicted total vs actual total by product category
- Total amount by gender, month, and product category

The predictions are generated using **Python** for predictive analytics, which helps in comparing predicted sales against actual sales data.

## Features

- **Interactive Visualizations**: Display data through pie charts, bar charts, and line graphs.
- **Predicted vs Actual Sales**: Compare predicted sales with actual sales to evaluate the model's performance.
- **Data Breakdown**: View data based on different categories such as product category, month, and gender.
- **Prediction Modeling**: Use Python for sales prediction to improve business forecasting.

## Technologies Used

- **Power BI**: For creating interactive visualizations and dashboards.
- **Python**: For implementing predictive modeling and generating sales forecasts.
- **Dataset**: Customer and product sales data (https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset?resource=download).

## Installation

### Prerequisites

Make sure you have the following installed:

- **Power BI Desktop**: [Download Power BI Desktop](https://powerbi.microsoft.com/downloads/)
- **Python**: Ensure that Python is installed for running the prediction model (if used outside Power BI).

### Steps to Run

1. Clone this repository:
2.   ```bash
   git clone https://github.com/your-username/Analyzing-Dashboard.git
Navigate to the project directory:

cd Analyzing-Dashboard


Open the Power BI file (Dashboard.pbix) to view the interactive dashboard.

If you want to run the Python model independently, execute the prediction model (Python code) for generating predicted sales data. You can use the following:

python predict_sales.py


Note: If the Python script isn't available, the prediction model will be integrated into Power BI via Python visual or custom queries.

Refresh the dataset in Power BI to load the processed data and interact with the visualizations.

Screenshots
Dashboard Preview

<img width="593" height="327" alt="image" src="https://github.com/user-attachments/assets/b7e23bc4-4c5e-48a0-b183-08b749efa10d" />



Contributing

Feel free to fork this project and contribute by creating pull requests. Please make sure your changes pass tests and follow the project's style guide.

License

This project is licensed under the MIT License - see the LICENSE
 file for details.

Contact

For any questions or feedback, feel free to open an issue on GitHub or reach out to me via email.

Happy analyzing! 🚀
