# Pizza-Sales-Analysis
This is a sales analysis of Plato's Pizza restaurant transactional data, New Jersey.
# Brief Introduction
Plato's restaurant is into the sales of different pizza types and sizes. The restaurant have been collecting transactional data for a year now and haven't been able to put it to good use. So, recently, the Manager, Mario Maven hired me as a BI Consultant to help them analyze the data and put together a report to help find opportunities to drive more sales and work efficiently. 
## Brief Overview of the dataset
Data was provided by Maven Analytics Team and is a public dataset made available through Enrique Ruiz. The dataset is structured and contains 4 tables in CSV format - Orders, Order Details, Pizzas, and Pizza Types. Each table has at least 3 columns which consist of: Order Id, date, time, Order details id, pizza id, quantity, pizza type id, size, price, name, category, and ingredients. Also, the dataset contained data dictionary to help understand the data better. The data had about 49,000 rows.
## Problem Questions
* What days and times do we tend to be busiest?
* How many pizzas are we making during peak periods?
* What are our best and worst selling pizzas?
* What's our average order value?
* How well are we utilizing our seating capacity? (we have 15 tables and 60 seats)
## Tools used
* Excel
* Power Pivot
## Processes
* Conversion to Excel Table
* Check through for data cleaning
* Creation of DAX (Data Analysis Expression) measures
* Data modelling
![Screenshot (119)](https://github.com/SamadTechGuy/Pizza-Sales-Analysis-Report/assets/97789215/d4026580-f1f8-4717-a5c7-51c85eeb78a5)
* Data visualization - Dashboard
![Screenshot (116)](https://github.com/SamadTechGuy/Pizza-Sales-Analysis-Report/assets/97789215/a20596f7-eb80-41b0-b269-a2203290c5e5)
## Key Insights
* Here are some **key metrics** from the analysis. 
![Screenshot (128)](https://github.com/SamadTechGuy/Pizza-Sales-Analysis-Report/assets/97789215/d8d6690c-be22-4553-ad88-57493679276d)

* The **busiest days** were at the end of the week on **Thursdays** and **Fridays** with orders of **3,239** and **3,538** and **busiest hours** were during the **lunch - 12 to 1pm** with orders of **2,520** and **2,455** and **dinner time - 5 to 6pm** with orders of **2,336** and **2,399**.
![Screenshot (121)](https://github.com/SamadTechGuy/Pizza-Sales-Analysis-Report/assets/97789215/52aaae9c-35a5-4b80-b186-b9893254b75a)

* During the **peak periods - 12 to 1pm**, **6,776** and **6,413 pizzas**, and from **5 to 6pm**, **5,211** and **5,417 pizzas** were made.
![Screenshot (123)](https://github.com/SamadTechGuy/Pizza-Sales-Analysis-Report/assets/97789215/9769693c-15b1-4f61-87a6-08f505765c9a)
* **Thai Chicken Pizza** was the **Best Selling Pizza** by revenue - generated **$43,434.25**. The **Brie Carre Pizza** was the **Worst Selling Pizza** by revenue - generated **$11,588.50**.
![Screenshot (125)](https://github.com/SamadTechGuy/Pizza-Sales-Analysis-Report/assets/97789215/855faa46-37f3-4bfe-92b2-dca817fe438b)
* The **Average Order Value** was **$38.31**.
* We have **15 tables** and **60 seats**. So, let us assume there are **4 seats per table**. From the analysis the seating capacity were well utilized and even in some hours the seats were empty but during the peak periods, the seats and tables were not enough.
## Other Insights...
* The **Most Ordered Pizza** was **The Classic Deluxe Pizza** with **2,416 Orders** and the **Least Ordered Pizza** was **The Brie Carre Pizza** with **480 Orders**.
![Screenshot (130)](https://github.com/SamadTechGuy/Pizza-Sales-Analysis-Report/assets/97789215/f8749e89-f56b-4593-92c1-7c846049d530)
*  The **month of July** had the **highest sales** which accounted for **8.87%** of the **total sales**.
![Screenshot (132)](https://github.com/SamadTechGuy/Pizza-Sales-Analysis-Report/assets/97789215/c190234b-3324-47db-9cc3-18e1cdf8b12f)
* The **XXL Size Pizza** had the **least sales** with **$1,006.60** while the **L Size Pizza** had the **highest sales** with **$375,318.70** which accounted for **45.89%** of the **total sales**. **The Brie Carre Pizza** being the **Worst Selling Pizza** by revenue **ranked 2nd in revenue** for the **S Size Pizza**. Amongst the category, **Classic category** generated the highest revenue - **$220,053.10** which accounted for **26.91%** of the total sales compared to **Veggie category** that had the least revenue - **$193,690.45** which was **3.23%** less than the Classic.
![Screenshot (134)](https://github.com/SamadTechGuy/Pizza-Sales-Analysis-Report/assets/97789215/d39ce994-6813-4000-aec4-133706b10562)
## Recommendations
*  I would recommend that there should be **an increase in the number of employees** during the peak periods and days to improve customer satisfaction and sales.
*  Also, the **opening hours** should be reduced from **11am to 10pm** as it has been shown from the analysis that the **early hours - 9am to 10am and the last hour - 11pm generated the least orders, less 50 altogether** which was definitely affecting the operating costs. Furthermore, there should be **late night promotion** to encourage the customers to place more orders before 9pm so as to improve the sales.
*  In addition, I would recommend that a survey should be run for the **sizes of the Worst 5 Selling Pizzas** to identify the most preferred pizzas with the best ones selling for juicy discounts so as to improve sales. This is due to the fact that S size pizza was only sold for the **Least Selling Pizza - The Brie Carre Pizza** and it ranked 2nd in revenue.
*   Lastly, it is recommended to offer promotional sales on months where sales and revenues were really low to help improve monthly revenue.
 

















