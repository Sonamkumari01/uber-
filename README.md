🛺 Uber Supply-Demand Gap – EDA Capstone Project
<!-- Replace with your own image URL -->

📊 Project Overview
This project analyzes Uber ride request data to identify key patterns and imbalances in supply and demand. Using Python and libraries like Pandas, Seaborn, and Matplotlib, we uncover the reasons behind unfulfilled requests and propose data-driven solutions to enhance Uber’s operational efficiency.

📁 Dataset
File: Uber Request Data.csv

Rows: 6,745

Columns: 6

Source: Provided for educational use (not publicly available)

🧰 Tools & Libraries Used
Python (Pandas, NumPy)

Data Visualization: Seaborn, Matplotlib

Data Cleaning: Pandas, datetime handling

Google Colab / Jupyter Notebook

🔍 Key Analyses Performed
Dataset structure and null value analysis

Demand patterns across different times of day

Supply shortfall and cancellations by location

Trip duration analysis

Status distribution heatmaps and bar charts

📈 Visualizations
Ride requests by hour

Trip status breakdown by pickup point

Cancellations vs. completed trips over time

Heatmaps and pair plots for numerical analysis

Violin plots for trip durations

<details> <summary>📷 Click to view sample visualizations</summary>
📌 Example 1: Ride Status by Hour

📌 Example 2: Pickup Point vs. Supply Gap

</details>
💡 Insights
Morning and evening peaks show the highest demand.

Airport rides are more likely to face supply issues.

“No Cars Available” is most frequent during rush hours.

Trip durations are typically between 15–45 minutes.

✅ Business Recommendations
Allocate more drivers to Airport during peak times.

Incentivize drivers to log in during high-demand hours.

Improve ETA predictions and customer communication.

📌 Folder Structure
bash
Copy
Edit
├── Uber_EDA_Project.ipynb     # Main analysis notebook
├── Uber Request Data.csv      # Dataset file
├── README.md                  # Project documentation
