

# 🏏 IPL Data Analysis using PySpark on Databricks

This project showcases an end-to-end data analysis pipeline built on **PySpark** and **Databricks**, focused on IPL (Indian Premier League) datasets.

---

## 📌 Project Workflow

1. **Created a Public S3 Bucket**  
   - Uploaded raw IPL datasets (`Ball_By_Ball.csv`, `Match.csv`, `Player.csv`, `Player_Match.csv`) to AWS S3  
   - Made the bucket publicly accessible for Spark ingestion

2. **Set Up Databricks (Serverless Community Edition)**  
   - Created a free Databricks account  
   - Used Databricks Notebooks for data engineering and analysis

3. **Data Ingestion**  
   - Loaded CSV files directly from S3 using PySpark  
   - Defined custom schemas and registered DataFrames as temporary SQL views

4. **Data Processing & Filtering with Spark SQL**  
   - Joined multiple datasets using SQL  
   - Performed aggregations like total runs, dismissals, strike rate  
   - Extracted top performers by season using window functions

5. **Data Visualization**  
   - Visualized results using Databricks' `display()` function  
   - Created summary tables and charts directly in notebooks

---

## ✅ Tools & Technologies

- **Apache Spark (PySpark)**
- **AWS S3 (Public Bucket)**
- **Databricks (Free Serverless)**
- **Spark SQL**
- **Python & Pandas (for quick previews)**

---

## ✍️ Author

**Mandeep Singh**  
📫 [GitHub](https://github.com/mandeeps1nghh) | [LinkedIn](https://linkedin.com/in/mandeepsingh0106)



