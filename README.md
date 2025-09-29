Superstore Interactive Dashboard

This project is an interactive dashboard built with Plotly Dash that visualizes sales and profit data from the Sample Superstore dataset. It includes key performance indicators (KPIs), filters, and dynamic charts to analyze sales trends, regional performance, and profitability across product categories.

🚀 Features

✅ KPIs at a glance

💰 Total Sales

📈 Total Profit

📊 Year-over-Year Growth (2019 → 2020)

✅ Interactive Filters

Region filter

Product Category filter

Custom Date Range filter

✅ Dynamic Visualizations

📉 Sales Trend Over Time (Line Chart)

🌍 Sales by Region (Bar Chart)

🏷 Profit by Category (Bar Chart)

🛠 Tech Stack

Python 3

Pandas (data manipulation)

Plotly Express (data visualization)

Dash (JupyterDash) (interactive web app framework)

ReportLab (for optional PDF report generation)

📂 Project Structure
├── Sample - Superstore.csv   # Dataset
├── dashboard.py              # Main dashboard script
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation

⚡ Installation & Setup

Clone the repo

git clone https://github.com/your-username/superstore-dashboard.git
cd superstore-dashboard


Install dependencies

pip install -r requirements.txt


Run the dashboard

python dashboard.py


Open your browser at http://127.0.0.1:8050/
 to view the app.

📊 Example Visualizations

Sales Over Time

Regional Sales Performance

Profit by Category

(📌 Add screenshots/gifs here of your dashboard when running.)

📑 Dataset

This project uses the Sample Superstore dataset, which contains sales transactions, profit, and product details across different regions and categories.

📌 Future Improvements

Export dashboard insights to PDF reports (ReportLab integration).

Add state-level analysis and sub-category drill-downs.

Deploy on Heroku/Render for online access.
