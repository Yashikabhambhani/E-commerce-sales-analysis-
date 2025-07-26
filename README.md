🛒 E-commerce Sales Analysis
📊 Project Overview
This project performs a comprehensive analysis of e-commerce transactional data to uncover insights about customer behavior, order trends, product sales, and payment performance. It uses Python, SQL, and Jupyter Notebook for data preprocessing, visualization, and querying.

📁 Project Structure
bash
Copy
Edit
E-commerce-Sales-Analysis-main/
├── merge_n_clean_data.ipynb       # Python notebook to merge and clean datasets
├── e-commerce-analysis.sql        # SQL queries for analysis
├── e-commerce-analysis.pdf        # Report or presentation of insights
├── er-diagram.png                 # Entity-relationship diagram
├── data/
│   ├── *.csv                      # Original dataset files
│   ├── train/                     # Training data (CSV format)
│   └── test/                      # Testing data (CSV format)
📚 Datasets
Customers.csv: Customer IDs and location

Orders.csv: Order status, timestamps, and customer info

OrderItems.csv: Product quantity and pricing per order

Products.csv: Product category and name

Payments.csv: Payment method and transaction value

⚙️ How to Run
Set up your environment
Recommended: Python 3.8+ with Jupyter Notebook

Install dependencies

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn
Run the notebook
Open merge_n_clean_data.ipynb to view the data preprocessing steps.

Run SQL Analysis
Use a SQL-compatible tool (e.g., MySQL, SQLite) to execute queries in e-commerce-analysis.sql.

📈 Key Analyses
Total orders and monthly trends

Top performing product categories

Payment method statistics

Customer purchasing behavior

Average revenue per order

📌 ER Diagram
The included ER diagram (er-diagram.png) outlines relationships between key entities like Customers, Orders, Products, and Payments.

📄 Report
Refer to e-commerce-analysis.pdf for summary insights and visualizations.

