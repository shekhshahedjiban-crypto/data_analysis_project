Markdown
#  Classic Models E-Commerce EDA & Sales Analysis

An end to end Exploratory Data Analysis (EDA) project using SQL and Python to analyze customer behavior, sales trends, order fulfillment, and product line performance on the **MySQL Classic Models** e-commerce dataset.

---

##  Project Overview

The objective of this project is to perform a comprehensive data analysis of an e-commerce business specializing in classic scale model vehicles. By querying the relational database and analyzing sales trends, this project aims to unlock key business insights regarding overall revenue, top performing product categories, customer segmentation, and order status metrics.

---

##  Dataset Architecture

The project utilizes the standard **Classic Models** sample database, which models a scale model car distributor's operations across 8 interconnected tables:

* **`Customers`**: Demographic and account details (credit limits, country, sales rep).
* **`Orders` & `OrderDetails`**: Transaction history, line items, quantities, and pricing.
* **`Products` & `ProductLines`**: Catalog details, stock levels, buy price, and MSRP.
* **`Payments`**: Customer payment records and transaction dates.
* **`Employees` & `Offices`**: Sales representative assignments and office locations.

---

##  Tech Stack & Tools

* **Database Engine**: MySQL 8.0
* **Analysis & Environment**: Python 3.x, Jupyter Notebook (`.ipynb`)
* **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `SQLAlchemy` / `mysql-connector-python`
* **Version Control**: Git & GitHub

---

##  Key Business Questions & Analysis Focus

1. **Sales & Revenue Performance**: 
   * What is the total revenue generated over time?
   * Which months and years exhibit peak purchasing behavior?
2. **Product Line Breakdown**:
   * Which product categories (e.g., Classic Cars, Vintage Cars, Motorcycles) drive the most revenue vs. volume?
   * What are the top-selling products by profit margin?
3. **Customer Segmentation & Lifetime Value**:
   * Who are the top high-value customers by total spend?
   * How are sales distributed across different geographical regions?
4. **Operations & Fulfillment**:
   * What percentage of orders are shipped, in process, or cancelled?
   * What is the average order turnaround/fulfillment time?

---

##  Getting Started

### Prerequisites

Ensure you have the following installed on your local machine:
* [MySQL Server](https://dev.mysql.com/downloads/mysql/) & MySQL Workbench
* Python 3.8+
* Jupyter Notebook or VS Code

### Installation & Setup

1. **Clone the Repository**:
   ```bash
   git clone [https://github.com/shekhshahedjiban-crypto/data_analysis_project.git](https://github.com/shekhshahedjiban-crypto/data_analysis_project.git)
   cd data_analysis_project/"E-commerce sales"
Database Setup:

Import the mysql-classicmodesl.sql file into your MySQL instance:

Bash
mysql -u root -p < mysql-classicmodesl.sql
Run the Notebook:

Open E-commerce.ipynb in Jupyter Notebook or VS Code.

Update the database connection credentials in the notebook (host, user, password).

Execute the cells to view data extraction, visualization, and analytical insights.

 Project Directory Structure
Plaintext
E-commerce sales/
│
├── mysql-classicmodesl.sql   # MySQL database schema and data creation script
├── E-commerce.ipynb          # Jupyter Notebook containing SQL queries & EDA visualizations
└── README.md                 # Project documentation
