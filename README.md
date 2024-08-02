
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


## Visualizations

### 1. RFM Value Segment Distribution

<div align="center">
    <img width="697" alt="RFM Value Segment Distribution" src="https://github.com/user-attachments/assets/3b1abfd0-72c5-4ebf-8ca0-677a1c5dc9b0">
    <p><strong>Distribution of Customers Across RFM Value Segments</strong></p>
</div>

#### Description:
This bar chart illustrates the distribution of customers across different RFM value segments. The analysis reveals that:

- **Low-Value segment** has the highest number of customers
- **Mid-Value segment** follows closely behind
- **High-Value segment** has the least number of customers

This distribution provides insights into the overall value composition of the customer base.

### 2. RFM Customer Segments by Value

<div align="center">
    <img width="688" alt="RFM Customer Segments by Value" src="https://github.com/user-attachments/assets/e6a74fa9-3589-46ec-914d-e4f99ba63e4d">
    <p><strong>Treemap of RFM Customer Segments Across Value Categories</strong></p>
</div>

#### Description:
This treemap visualizes the distribution of RFM customer segments across different value categories. Key observations include:

- **Low-Value category** is dominated by "At Risk Customers" and "Can't Lose" segments
- **Mid-Value category** is primarily composed of "Potential Loyalists"
- **High-Value category** includes both "Potential Loyalists" and "Champions"

This visualization helps in understanding the composition of each value category and identifying target segments for marketing strategies.

### 3. Correlation Matrix of RFM Values within Champions Segment

<div align="center">
    <img width="713" alt="Correlation Matrix of RFM Values within Champions Segment" src="https://github.com/user-attachments/assets/446b6cf9-5de6-41ee-943a-1a58a269a3d2">
    <p><strong>Heatmap Showing Correlations Between RFM Metrics for Champions</strong></p>
</div>

#### Description:
This heatmap displays the correlation between Recency, Frequency, and Monetary scores within the Champions segment. Notable findings include:

- **Strong positive correlation** between Frequency and Monetary scores
- **Moderate negative correlation** between Recency and both Frequency and Monetary scores

These correlations provide insights into the behavior patterns of high-value customers.

### 4. Comparison of RFM Segments

<div align="center">
    <img width="650" alt="Comparison of RFM Segments" src="https://github.com/user-attachments/assets/afcd321e-5353-4bd8-8c8b-f4b07610e4b7">
    <p><strong>Bar Chart Comparing Customer Counts Across RFM Segments</strong></p>
</div>

#### Description:
This bar chart compares the number of customers in each RFM segment. Key insights include:

- **"Potential Loyalists"** form the largest segment
- **"At Risk Customers"** and **"Can't Lose"** segments have similar sizes
- **"Champions"** represent the smallest segment

This comparison helps in prioritizing marketing efforts and resource allocation across different customer segments.

### 5. Comparison of RFM Segments based on Recency, Frequency, and Monetary Scores

<div align="center">
    <img width="699" alt="Comparison of RFM Segments based on Recency, Frequency, and Monetary Scores" src="https://github.com/user-attachments/assets/83ef9126-c651-4a9b-b308-3f0585a0db46">
    <p><strong>Grouped Bar Chart Showing RFM Scores Across Customer Segments</strong></p>
</div>

#### Description:
This grouped bar chart compares the average Recency, Frequency, and Monetary scores across different RFM segments. Notable observations include:

- **"Champions"** have high scores across all three metrics
- **"Potential Loyalists"** show high Recency but lower Frequency and Monetary scores
- **"Lost"** customers have consistently low scores across all metrics


### 6. RFM Analysis Dashboard

<div align="center">
    <img width="710" alt="RFM Analysis Dashboard" src="https://github.com/user-attachments/assets/14ba1c14-3a70-43ec-9942-15d59d783fd0">
    <p><strong>Interactive RFM Analysis Dashboard</strong></p>
</div>

#### Description:
This image showcases the final interactive RFM Analysis Dashboard created using Dash. The dashboard provides a comprehensive view of customer segmentation based on RFM scores. Key features include:

- **Title and Description**: Clearly labeled "RFM Analysis Dashboard" with a brief explanation of its purpose.
- **Dropdown Menu**: Allows users to select different chart types to visualize various aspects of the RFM analysis.
- **Interactive Graph Area**: Displays the selected chart, enabling exploration of different visualizations of the RFM data.
- **Chart Options**: Includes various chart types such as:
  - RFM Value Segment Distribution
  - Distribution of RFM Values within Customer Segment
  - Correlation Matrix of RFM Values within Champions Segment
  - Comparison of RFM Segments
  - Comparison of RFM Segments based on Scores

This interactive dashboard enables users to **dynamically explore and analyze customer segments** based on their RFM scores, providing valuable insights for marketing strategies and customer relationship management.


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
   - Create and activate a virtual environment:
     ```bash
     python -m venv venv
     source venv/bin/activate  # On Windows use `venv\Scripts\activate`
     ```
   - Install required dependencies:
     ```bash
     pip install -r requirements.txt
     ```

3. **Run the Dashboard**:
   - Launch the dashboard using Dash:
     ```bash
     python app.py
     ```
   - Open a web browser and go to `http://127.0.0.1:8050/` to view the interactive dashboard.

4. **Explore the Dashboard**:
   - Use the interactive charts and visualizations to analyze customer segments and behavior based on RFM scores.

5. **Modify and Extend**:
   - Customize the dashboard, add new features, or apply the analysis to different datasets by editing `app.py` and other related files.
  
   
## Future Work

1. **Advanced Segmentation Techniques**:
   - Explore machine learning models for more sophisticated customer segmentation and prediction.

2. **Integration with Marketing Platforms**:
   - Develop integrations to apply insights directly to marketing platforms and campaigns.

3. **Enhanced Visualizations**:
   - Add more advanced visualizations and interactivity to improve user experience and insights.
