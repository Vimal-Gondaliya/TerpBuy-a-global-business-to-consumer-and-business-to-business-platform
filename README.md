# TerpBuy Data Analysis Project

## Introduction

During this course, two powerful tools—**Python** and **SQL**—were added to your data science toolkit. In this project, you will apply what you've learned to derive insights from the TerpBuy database and present key findings to the management team.

---

## Scenario

TerpBuy is a global **business-to-consumer** and **business-to-business** platform headquartered in College Park, Maryland, USA, with a distribution center in Mumbai, India. The company seeks insights into its customer base, product offerings, departments, and orders. Your task is to analyze this data and generate actionable insights for the company’s decision-making process.

---

## Data Set

You will be using the **TerpBuy** dataset, available as an SQL script, which needs to be imported into a database for querying. This dataset includes information about:
- Customers
- Products
- Orders
- Departments

A data dictionary is also provided to assist you in understanding the attributes of each table.

---

## Project Tasks

### **Part I: SQL Queries**

You will write SQL queries to address the following business questions:

1. **Row Count for Each Table**  
   Find the number of rows stored in each table.

2. **High-Priced Products**  
   List all products with prices exceeding $100.

3. **Florida Customer Orders**  
   List all orders placed by customers from Florida, along with customer details (first name, last name, city, segment), and order information.

4. **Category-Based Product Search**  
   Find products in categories such as 'Computers', 'Toys', 'Tennis & Racquet', and include details like name, category, department, and price.

5. **Unsold Products**  
   Identify products that have not been sold yet, including their name, category, and department.

6. **Delayed Shipments**  
   List cities where orders were shipped with delays and show the number of delayed orders, sorted from highest to lowest.

7. **Customer Segments**  
   Find the number of customers in each segment, with the most popular segment at the top of the results.

8. **Orders from Q1 2021**  
   Find how many orders were placed in the first quarter of 2021.

9. **States with Multiple Segments**  
   List states that support more than one customer segment, sorted alphabetically.

10. **Inactive Corporate Customers**  
    Identify corporate segment customers who have not placed any orders and include their personal details.

11. **Recall on Nike Shoes**  
    List all customers who purchased the "Nike Mens Free 5.0+ Running Shoe" and offer them a discount coupon.

12. **Premium Customers**  
    Find premium customers with order amounts greater than the average order amount.

### **Part II: Connecting Python to SQL**

#### 1. **Department Sales Query**
Write a query to show the quantity of items sold by each department, and visualize the results using a bar chart.

#### 2. **Orders by Year**
Write a query to show the number of orders placed each year, and visualize the trend using a line graph.

#### 3. **Observations**
For both visualizations, explain the trends and key insights observed from the data.

---

## **Part III: Executive Summary**

Based on your data analysis, provide an executive summary (200–300 words) highlighting the most important insights. Focus on actionable recommendations for:
- Product offerings
- Customer engagement
- Department performance
- Overall business strategy

---

## **How to Run the Project**

1. **Prerequisites**  
   - Python 3.x  
   - MySQL (or any other compatible SQL database)
   - Jupyter Notebook  
   - Libraries: `pandas`, `matplotlib`, `sqlalchemy`

2. **Steps**  
   - Load the TerpBuy data into the SQL database.
   - Use Jupyter Notebook for connecting Python to SQL.
   - Run the queries and generate visualizations as per the tasks outlined.

---

## **License**

This project is licensed under the BSD 3-Clause "New" or "Revised" License.
