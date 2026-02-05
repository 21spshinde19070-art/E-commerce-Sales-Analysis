

#  E-Commerce Sales Analysis

## Project Overview

This project performs a **complete data analysis pipeline** on e-commerce sales data. The goal is to analyze sales trends, product performance, and regional performance using Python, and generate professional visualizations to support business insights.

**Key Objectives:**

* Identify monthly sales trends
* Find top-selling products
* Analyze regional sales distribution
* Generate actionable insights for business strategy

---

## Dataset

The dataset used is `sales_data.csv` with **100 rows** and the following columns:

| Column      | Description                         |
| ----------- | ----------------------------------- |
| Date        | Date of the sale                    |
| Product     | Name of the product sold            |
| Quantity    | Number of units sold                |
| Price       | Price per unit                      |
| Customer_ID | Unique identifier for each customer |
| Region      | Region of the customer              |
| Total_Sales | Total revenue for the sale          |

> Data is cleaned and formatted for analysis.

---

## Project Structure

```
ecommerce-sales-analysis/
│
├── data/
│   └── sales_data.csv              # Original dataset
├── visualizations/                 # Generated charts
│   ├── monthly_sales.png
│   ├── Out-Put_SS.png
│   ├── Total_sales_by_product.png
│   ├── Total_sales_by_region.png
│   
├── report/
│   └── report.txt                    # Full analysis report 
├── E-commerce Sales Analysi.py       # Python script for full analysis
├── README.md                         # Project overview and instructions
└── requirements.txt                  # Python dependencies
```

---

## Installation & Setup

1. Clone the repository:

```bash
git clone <your-repo-url>
cd ecommerce-sales-analysis
```

2. (Optional) Create a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Ensure the dataset `sales_data.csv` is in the `data/` folder.

---

## Usage

Run the analysis script:

```bash
python main.py
```

The script will:

* Load and clean the data
* Validate required columns
* Perform analysis: monthly, product, and regional sales
* Generate **visualizations** in the `visualizations/` folder
* Print key metrics:

  * Total revenue
  * Total units sold
  * Unique customers

> Charts will be saved automatically and can also be displayed on screen.

---

## Visualizations

1. **Monthly Sales Trend (Line Chart)** – Shows trends over time
2. **Total Sales by Product (Bar Chart)** – Highlights top-selling products
3. **Total Sales by Region (Bar Chart)** – Compares revenue across regions


---

## Insights

* Sales show **seasonal trends** with peaks in certain months
* A few products generate the **majority of revenue**
* Some regions outperform others, suggesting **marketing priorities**
* Average sales per order indicate **high-value customer segments**
* Regional distribution highlights **market dominance**

---

## Technical Details

* **Language:** Python 3.x

* **Libraries:** Pandas, Matplotlib, OS

* **Pipeline Steps:**

  1. Load and validate dataset
  2. Clean data and handle missing values
  3. Aggregate sales by month, product, and region
  4. Generate visualizations (line, bar, pie charts)
  5. Save charts to `visualizations/` folder

* Code is modular with separate functions for loading, cleaning, analyzing, and visualizing data.

---

## Requirements

Contents of `requirements.txt`:

```
pandas>=1.5
matplotlib>=3.7
```

Install with:

```bash
pip install -r requirements.txt
```

---

## Author

Siddesh Shinde
Email: siddeshshinde020@gmail.com

---

## License

This project is for **educational purposes**.

---





