# Comprehensive Sales Analysis Dashboard

This project is a comprehensive sales analysis dashboard built using Streamlit. The dashboard allows users to filter sales data based on various dimensions such as customer segments, product categories, states, and date ranges. It provides insightful visualizations like sales trends, profit analysis, and order priority analysis.

## Technologies Used

- **Python**: The core programming language used for data manipulation and analysis.
- **Streamlit**: Used to build the interactive web-based dashboard.
- **Pandas**: Used for data manipulation and analysis.
- **Plotly**: Used for creating interactive visualizations.

## Features

- **Filter Data**: Users can filter data by Customer Segment, Product Category, and State.
- **Date Range Filter**: Allows users to select a specific date range for analysis.
- **Sales Trend**: Visualizes monthly sales trends.
- **Profit Analysis**: Provides profit analysis by product category.
- **Order Priority Analysis**: Displays sales and profit by order priority.

## Installation and Setup

### Prerequisites

Before running the application, ensure you have the following installed:

- Python 3.7 or higher
- Streamlit
- Pandas
- Plotly

### Installation

1. **Clone the repository**:

   ```bash
   git clone 
   cd 
   ```

2. **Create a virtual environment** (optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required packages**:

   ```bash
   pip install streamlit pandas plotly
   ```

### Running the App

1. **Download the Dataset**:

   The dataset can be downloaded from the following link: [Walmart Sales Data](https://www.kaggle.com/datasets/saadabdurrazzaq/walmart-retail-data).

2. **Place the dataset in the project directory**:

   Ensure the dataset is named `WALMARTT.csv` and is placed in the root of the project directory.

3. **Run the Streamlit app**:

   ```bash
   streamlit run app.py
   ```

4. **Access the dashboard**:

   Once the app is running, it will open in your default web browser. If not, you can manually visit `http://localhost:8501` to access the dashboard.

## Usage

- Use the sidebar to filter data by Customer Segment, Product Category, and State.
- Adjust the date range to focus on a specific period.
- Explore the visualizations provided in the main section of the dashboard.

## Additional Information

- **Customization**: Feel free to modify the code to add more features or visualizations based on your analysis needs.
- **Issues and Contributions**: If you encounter any issues or have suggestions for improvement, feel free to open an issue or contribute to the repository.
