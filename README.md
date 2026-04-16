
#  Customer Shopping Behaviour Analytics

##  Overview

In this project, I analysed customer shopping behaviour using transactional data to generate practical business insights.

The project follows a full data analytics workflow, including data cleaning and exploratory analysis in Python, running SQL queries in PostgreSQL, and building a Power BI dashboard to present the results clearly.

## Dataset

Records: 3,900 transactions
* **Features:** 18 columns

### Data includes:

* Customer information (age, gender, location, subscription status)
* Purchase details (product, category, purchase amount, season)
* Shopping behaviour (discount usage, purchase frequency, review ratings, shipping type)

### Data preparation:

* Handled missing values in `review_rating`
* Standardised column names (snake_case)
* Removed redundant columns
* Created new features:

  * `age_group`
  * `purchase_frequency_days`
## 🛠️ Tools & Technologies

* Python (Pandas, NumPy, Jupyter Notebook)
* PostgreSQL
* Power BI
* Gamma (presentation slides)

## What I Did
### 1. Data Cleaning & EDA (Python)

* Explored the dataset using `.info()` and `.describe()`
* Identified and handled missing values
* Performed feature engineering to support analysis
* Prepared the dataset for database use
### 2. Database & SQL Analysis

* Connected Python to PostgreSQL and uploaded the cleaned data
* Wrote SQL queries to answer business-focused questions, such as:

  * Revenue by gender
  * Subscriber vs non-subscriber behaviour
  * Top-performing products
  * Impact of discounts on sales
  * Customer segmentation (New, Returning, Loyal)
  * Revenue by age group
##  Dashboard

I created an interactive **Power BI dashboard** to present key insights, including:

* Revenue trends
* Customer segments
* Product performance
* Discount usage
* Demographic patterns

The dashboard is designed to be simple and easy to understand for non-technical users

 ##  Key Insights

* Subscribers tend to spend more than non-subscribers
* Loyal customers contribute a large share of total revenue
* Discounts strongly influence purchasing behaviour
* Certain age groups generate higher revenue
* Customers using express shipping often spend more

##  How to Run

### 1. Python Notebook

```bash id="x4wx8x"
jupyter notebook Customer-Analytics-Dashboard.ipynb
```

### 2. PostgreSQL

* Create a database
* Run:

```sql id="gph5v5"
\i customer_analytics_sql_queries.sql
```

### 3. Power BI

* Open the `.pbix` file
* Refresh the data



##  Skills Demonstrated

* Data cleaning and preprocessing
* Exploratory data analysis
* SQL querying for business insights
* Data visualisation (Power BI)
* Communicating findings clearly

## Author
Whitney
