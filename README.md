**SQL Layoffs Data Analysis**

SQL project for data cleaning and exploratory data analysis (EDA) of a global layoffs dataset.

This project demonstrates skills in:
* Handling duplicates, null values, and inconsistent formatting
* Exploratory Data Analysis (EDA) using SQL
* Time-series analysis with rolling totals
* Advanced queries with window functions

---

**📂 Project Structure**
* layoffs_cleaning.sql → Script for cleaning raw layoffs dataset
* eda_layoffs.sql → Exploratory Data Analysis queries
* screenshots/ → Folder containing charts and query outputs
* README.md → Project documentation

---

**🛠️ Data Cleaning Steps**
* Remove duplicates
* Handle NULL and blank values
* Standardize formats (company, industry, country)
* Convert date column into proper format

---

**📊 Exploratory Data Analysis (EDA)**

**1. Layoffs Over Time**

Total layoffs aggregated per year and per month.

<img src="screenshots/Total%20Layoffs.png" alt="Total Layoffs" width="500"/>


**2. Layoffs by Industry**

Identifying which industries were most impacted.

<img src="screenshots/Layoffs%20by%20Industry.png" alt="Layoffs by Industry" width="500"/>

**3. Layoffs by Country**

Distribution of layoffs across countries.

<img src="screenshots/Layoffs%20by%20Country.png" alt="Layoffs by Country" width="500"/>

**4. Top 5 Companies per Year**

Using DENSE_RANK() to identify companies with the highest layoffs each year.

<img src="screenshots/Top%205%20Companies.png" alt="Top 5 Companies" width="500"/>

---

**📈 Key Insights**
* The peak of layoffs occurred in **January 2023**, with a total off **84.714**.
* **Consumer** was the most affected, followed by **Retail**.
* **United States** accounted for the highest layoffs globally.
* Top 5 Companies with Most Layoffs per Year

  **2020: Uber, Booking.com, Airbnb, Groupon, Swiggy**

  **2021: Bytedance, Katerra, Zillow, Instacart, WhiteHat Jr**
  
  **2022: Meta, Amazon, Cisco, Peloton, Carvana and Philips**

  **2023: Google, Microsoft, Ericsson, Amazon and Salesforce, Dell**

---

**🚀 Tech Stack**
* **SQL** (MySQL) for data cleaning and EDA
* **GitHub** for version control and portfolio presentation

---

**▶️ Usage**
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/username/layoffs-sql-analysis.git
   
   cd layoffs-sql-analysis

2. Import the **layoffs dataset** (layoffs.csv) into MySQL.

3. Run the **data cleaning script**:
   ```sql
   SOURCE layoffs_cleaning.sql;

4. Run the **exploratory data analysis (EDA) script**:
   ```sql
   SOURCE eda_layoffs.sql;

5. Explore the query outputs in **MySQL Workbench** or the **command-line client**.

