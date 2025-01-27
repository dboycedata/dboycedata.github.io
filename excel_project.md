# From Data to Decisions: Analyzing DoorDash Marketing Strategies in Excel  
**Created By:** Dunkan Boyce  

DoorDash is a top food delivery option in the United States. The company wants to increase the effectiveness of its marketing. Therefore, DoorDash has been conducting marketing campaigns and wants its data analytics team to provide information and recommendations on the best campaign and future direction of its marketing. The data provided was exclusively analyzed in Excel.  

---

## Business Questions:  
- What is the total amount spent by customers?  
- Which campaign had the most success?  
- What was the overall effectiveness of Campaign 6 for DoorDash?  
- Does the age of a customer affect the amount of money they spend?  
- What is the average amount of money spent by each customer?  
- What is the age range of the customers that are participating in DoorDash campaigns?  

---

## My Analysis:  
- **Data Preparation:**  
  Using Excel, I added a new column named "Customer ID" and sorted and filtered the data.  

- **Data Aggregation:**  
  Keeping the business questions in mind, I used Excel functions like `AVERAGE`, `SUM`, `MAX`, and `MIN` to extract relevant information.  

- **Age Correlation Analysis:**  
  To analyze if a customer's age correlated with their spending, I created a new column, “Age Group,” categorizing customers into four age groups: 24–35, 36–50, 51–65, and 66+.  

---

## Graphs/Charts:  
- **Scatter Plot:**  
  A scatter plot was created to visualize "income" versus "total spent," including the R-squared value to represent the percentage of variance. This helped analyze the relationship between income and spending.

  <img src="/images/excel_project_pics/scatter_plot.png?raw=true"/>  

- **Campaign Success:**  
  To identify the most successful campaign, I calculated the total participants for each campaign and created a bar chart. Campaign 6 had an overwhelmingly high number of participants. A deeper analysis of the factors contributing to this success is recommended.

  <img src="/images/excel_project_pics/campaign1_6.png?raw=true"/>  

- **Campaign 6 Participants by Age Group:**  
  I created a pivot table with the "Age Group" column and participant data, followed by a pie chart visualizing the distribution of Campaign 6 participants by age group.

  <img src="/images/excel_project_pics/campaign6agerange.png?raw=true"/>  

- **Spending by Age Range:**  
  I analyzed spending for each age group and found that the 36–50 age group spent the most during Campaign 6. A chart was created to examine this trend further.

  <img src="/images/excel_project_pics/totalmoney.png?raw=true"/>  

- **New Customers by Month:**  
  I plotted a line graph showing the total number of new customers acquired each month to identify patterns and trends.

  <img src="/images/excel_project_pics/#ofnewcustomers.png?raw=true"/>  

- **Customer Spending Tool:**  
  Using `VLOOKUP`, I built a multi-tab tool in Excel. This allows users to enter a customer ID and see the exact amount spent by that customer.

  <img src="/images/excel_project_pics/vlookup.png?raw=true"/> 

---

## Insights:  
- The average amount spent by customers during Campaign 6 was **$924.40**.  
- The total amount spent during Campaign 6 was **$307,828**.  
- The **36–50 age group** spent the most during Campaign 6, indicating they are more financially stable and willing to spend.  
- The oldest participant in Campaign 6 was **77 years old**. A notable number of participants were in the **66+ age group**, though they did not spend the most.  
- There is **no direct correlation** between a customer’s income and their spending on DoorDash.  

---

## Recommendations:  
Campaign 6 was significantly more successful than previous iterations.  

One key observation was the surge in new users between **January and March**. Conducting a deeper analysis to uncover the factors behind this surge would be beneficial for future campaigns. By aligning promotional efforts with these periods of high engagement, DoorDash could attract and retain more customers, driving higher revenue growth.  

---

If you enjoyed this article or have feedback, feel free to connect with me!  
**Thank you for reading!**  

**Dunkan Boyce** | [LinkedIn](#)  

