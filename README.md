
# Customer Segmentation RFM Dashboard: Visualizing Customer Insights

## Project Overview

This project features an interactive RFM (Recency, Frequency, Monetary) Analytics Dashboard designed to help businesses visualize and analyze customer segments. The dashboard is built using Python and Dash, and it provides valuable insights into customer behavior through engaging and interactive visualizations.

### What Was Done

- **Data Preparation**: Cleaned and preprocessed customer transaction data for effective RFM analysis.
- **RFM Analysis**: Implemented Recency, Frequency, and Monetary metrics to categorize customers into meaningful segments.
- **Interactive Visualization**: Created dynamic charts and dashboards using Dash to explore customer segments and trends.
- **Insights Extraction**: Developed tools to extract actionable insights from the RFM analysis to guide marketing strategies.

### Key Findings

- **Customer Segmentation**: Identified distinct customer segments based on their purchasing behavior.
- **Behavioral Patterns**: Unveiled trends in customer recency, frequency, and monetary metrics.
- **Actionable Insights**: Provided recommendations for targeted marketing strategies based on customer segments.

## Skills Demonstrated

- Data Cleaning and Preprocessing
- RFM Analysis and Customer Segmentation
- Interactive Data Visualization (Dash, Plotly)
- Insights Extraction and Interpretation

## Dataset

### Description

The analysis is based on a synthetic customer transaction dataset used to perform RFM analysis. This dataset includes customer transaction history necessary for calculating Recency, Frequency, and Monetary values.

### Dataset Linkage Diagram

*Replace this placeholder with a relevant image link once available.*

![Dataset Linkage Diagram](https://github.com/crishN144/Customer-Segmentation-RFM-Dashboard/assets/your-dataset-linkage-diagram)

### Main Tables

1. **Customer Transactions**: Contains transaction details including transaction date, amount, and customer ID.
2. **Customer Information**: Includes demographic information such as customer ID, age, and location.

### Key Attributes

| Attribute Name     | Description                     | Data Type | Example Value |
|--------------------|---------------------------------|-----------|---------------|
| `Customer_ID`      | Unique identifier for customers | String    | C12345        |
| `Transaction_Date` | Date of the transaction         | Date      | 2024-05-01    |
| `Amount`           | Transaction amount              | Float     | 250.00        |
| `Recency`          | Days since last purchase        | Integer   | 30            |
| `Frequency`        | Total number of purchases       | Integer   | 15            |
| `Monetary`         | Total spent by the customer     | Float     | 3750.00       |

## Visualization

### 1. Customer Segmentation Overview

<div align="center">
    <img width="600" alt="Customer Segmentation Overview" src="https://github.com/crishN144/Customer-Segmentation-RFM-Dashboard/assets/customer-segmentation-overview.png">
    <p><strong>Customer Segmentation Overview</strong></p>
</div>

- **Purpose**: Visualizes overall distribution of customer segments based on RFM metrics.

### 2. Recency Distribution

<div align="center">
    <img width="600" alt="Recency Distribution" src="https://github.com/crishN144/Customer-Segmentation-RFM-Dashboard/assets/recency-distribution.png">
    <p><strong>Recency Distribution</strong></p>
</div>

- **Purpose**: Shows how recent customer interactions are distributed across different segments.

### 3. Frequency Distribution

<div align="center">
    <img width="600" alt="Frequency Distribution" src="https://github.com/crishN144/Customer-Segmentation-RFM-Dashboard/assets/frequency-distribution.png">
    <p><strong>Frequency Distribution</strong></p>
</div>

- **Purpose**: Illustrates the frequency of customer transactions across various segments.

### 4. Monetary Value Distribution

<div align="center">
    <img width="600" alt="Monetary Value Distribution" src="https://github.com/crishN144/Customer-Segmentation-RFM-Dashboard/assets/monetary-value-distribution.png">
    <p><strong>Monetary Value Distribution</strong></p>
</div>

- **Purpose**: Displays the distribution of total spending across customer segments.

## Conclusion

The RFM Analytics Dashboard provides a powerful tool for businesses to segment their customers and gain insights into their purchasing behavior. By utilizing RFM metrics, businesses can better understand customer value and tailor their marketing strategies accordingly.

## How to Use

To explore and utilize this project:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/crishN144/Customer-Segmentation-RFM-Dashboard.git
   cd Customer-Segmentation-RFM-Dashboard
   ```

2. **Set Up the Environment**:
   - Create a virtual environment:
     ```bash
     python -m venv venv
     source venv/bin/activate  # On Windows use `venv\Scripts\activate`
     ```
   - Install required dependencies:
     ```bash
     pip install -r requirements.txt
     ```

3. **Run the Dashboard**:
   - Open Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   - Navigate to and open the notebook:
     - `RFM_Analysis_Dashboard.ipynb`
   - Run the cells sequentially to see the interactive dashboard.

4. **Explore the Results**:
   - Use the interactive charts and visualizations to analyze customer segments and behavior.

5. **Modify and Extend**:
   - Feel free to customize the dashboard, add new features, or apply the analysis to different datasets.

## Future Work

1. **Advanced Segmentation Techniques**:
   - Explore machine learning models for more sophisticated customer segmentation and prediction.

2. **Integration with Marketing Platforms**:
   - Develop integrations to apply insights directly to marketing platforms and campaigns.

3. **Enhanced Visualizations**:
   - Add more advanced visualizations and interactivity to improve user experience and insights.
