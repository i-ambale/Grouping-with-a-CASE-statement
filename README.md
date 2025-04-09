# 📊 Grouping with a CASE Statement
© ExploreAI Academy

This notebook demonstrates how to categorize and group data using SQL's `CASE` statement in combination with aggregate functions. It is designed for learners aiming to improve their SQL querying skills using practical, real-world datasets.
---
## 🚧 Important Notice
⚠️*This notebook will not run on Google Colab because Colab cannot connect to a local database.
Please ensure that the notebook is running on the same local machine where both MySQL Workbench and the `united_nations` database are installed.*
---
## 🎯 Learning Objectives
By the end of this notebook, you should be able to:

- ✅ Use `CASE` statements to categorise data based on specific conditions.

- ✅ Combine `CASE` statements with aggregate functions (`MIN`, `MAX`, `AVG`, etc.) for summarised insights.

- ✅ Apply `GROUP BY` with `CASE` to group data meaningfully.
---

## 🗄️ Dataset Description
**We’ll be working with the `Access_to_Basic_Services` table from a MySQL database named `united_nations`.
This table includes country-level indicators on access to managed drinking water services.**
---

## 🛠️ Setup and Requirements
To run this notebook:

- Make sure MySQL Server and MySQL Workbench are installed and running.

- Ensure the united_nations database is already created and contains the Access_to_Basic_Services table.

- Required Python libraries:

  - `sqlalchemy`
  
  - `pymysql`
  
  - `jupyter` (if running in a notebook)

You can install the required libraries using pip:
```
pip install sqlalchemy pymysql
```
---
## 📡 Database Connection
The notebook uses the following connection string format to connect to the local MySQL server:
```
mysql+pymysql://<username>:<password>@localhost:3306/united_nations
```
Replace `<username>` and `<password>` with your actual MySQL credentials.
---
## Happy querying! 🧠💻
ExploreAI Academy – Learn by doing.

Adopted by Ibrahim Ambale




