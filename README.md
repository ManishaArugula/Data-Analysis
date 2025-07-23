# Key Insights from Online Book Store Analysis

Dataset Source : https://www.kaggle.com/datasets/komal1111/online-bookstore-analysis<br>
Tableau Dashboars : https://public.tableau.com/app/profile/manisha.arugula/viz/Online_Bookstore_Analysis/Online_Bookstore_Analysis<br>
Description : This project presents a full-cycle analysis of an online bookstore using Python for data preparation, SQL for insight generation, and Tableau for interactive visualization. The goal was to extract actionable insights from customer, book, and order data to understand sales performance, customer behavior, and revenue trends. <br>
## Tools & Technologies <br>
1. Python (Pandas, NumPy, Matplotlib, Seaborn, pyodbc)<br>
2. Microsoft SQL Server (SSMS)<br>
3. Tableau (Public Dashboard)<br>
4. Git & GitHub for version control<br>


## I. Data Cleaning & Exploration in Python:
1.	Connect to SQL Server and loading CSV files into the server using Python
2.	Identify and handle missing values
3.	Detect and review outliers
4.  Perform initial exploratory data analysis by analyze distributions of numerical columns
5.	Clean and transform data as needed
6.	Export cleaned data back to SQL Server

## II. Business Insights via SQL Queries
1.	Total Revenue
Over the span of two years, the online bookstore generated a total revenue of $75,628.66.<br>
2.	Top and Bottom Performing Genres (by Revenue)<br>
o	 The Romance genre generated the highest revenue at $13,086.00.<br>
o	 The Fiction genre recorded the lowest revenue at $7,271.22.<br>
3.	Genres by Average Book Price<br>
o	Non-Fiction books had the highest average price per book at $28.77.<br>
o	Fantasy books had the lowest average price at $25.98.<br>
4.	Top Revenue-Contributing Countries<br>
The countries contributing the most to total revenue were:<br>
o	Cambodia – $1,398.90<br>
o	Heard and McDonald Islands – $1,341.22<br>
o	Macao – $1,264.00<br>
o	Saint Martin – $1,230.00<br>
5.	Revenue by Book Price Range<br>
Books priced between $35 and $49 generated the highest revenue, indicating stronger performance in the upper-mid price segment.<br>
6.	Sales by Price Range<br>
o	Books in the high-price range were the most sold<br>
o	Followed by the medium range, then the low-price range<br>
7.	Top Countries by Customer Count<br>
The highest number of customers came from:<br>
o	Cuba<br>
o	Micronesia<br>
o	Zimbabwe<br>
o	Heard and McDonald Islands<br>
o	Jersey<br>
8.	Top-Selling Authors<br>
o	Robert Garcia sold the most books with 19 copies sold<br>
o	Followed by David Miller with 17 copies sold<br>
9.	Top Spending Customers<br>
o	Kim Turner spent the highest amount at $1,398.00<br>
o	Followed by Jonathon Strickland with $1,080.00 in purchases<br>
10.	Monthly Revenue Trends<br>
o	The highest revenue was recorded in January, totaling $8,466.04<br>
o	Followed by May, with $8,288.07<br>

## III. Interactive Tableau Dashboard
1. KPI Summary on Revenue, Orders and Customers
2. Geographic Sales Map
3. Distribution of Number of Orders(Histogram)
4. Customer Segmentation Insights(Scatter Plot)
5. Distribution of Revenue by Genre
6. Revenue per Month
