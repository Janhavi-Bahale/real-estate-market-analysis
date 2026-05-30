Real Estate Market Analysis

Overview
End-to-end data analysis project on real estate property sales data.
Performed data cleaning and exploration in Python, stored results in MySQL,
and visualized key trends using Power BI and Excel.

Tech Stack
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- MySQL + MySQL Workbench
- Power BI
- Excel
- Git & GitHub

Project Structure
real-estate-market-analysis/
├── real_estate_analysis.ipynb   # Main analysis notebook
├── queries.sql                  # MySQL queries used
├── price_by_city.png            # Output chart
└── README.md                    # Project documentation

Key Steps
1. Loaded and cleaned 10,000+ property records using Pandas
2. Handled null values, duplicates, and data type corrections
3. Stored cleaned data in MySQL and ran aggregation queries
4. Built Power BI dashboard with price trends and regional filters
5. Created Excel pivot table summary for stakeholder reporting

Key Findings
- Top 3 highest-priced cities identified from dataset
- Properties with 3–4 bedrooms showed highest market volume
- Average price varies by 40%+ across regions

How to Run
1. Clone the repo
2. Install dependencies: `pip install pandas numpy matplotlib seaborn`
3. Open `real_estate_analysis.ipynb` in Jupyter Notebook
4. Run MySQL queries in MySQL Workbench using `queries.sql`
