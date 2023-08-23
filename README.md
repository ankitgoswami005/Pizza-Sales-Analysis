Hello viewer! This is related to something that most youngsters enjoy as a junk food. So this time I have decided to display an analysis which is regarding Pizza sales business.

Though I have created a filter of Pizza Category to create visuals interaction and also I have used some basic Power BI visuals to complete this dashboard, and I would like to explain all of them one by one:

i. KPI Cards: 
1. Total Orders - I have calculated this measure with the help of counting Order IDs.
2. Total Revenue - I have calculated this measure by multiplying quantity sold with price per unit.
3. Average Order Value - I have calculated this measure by dividing total revenue by total orders.
4. Total Sales - I have calculated this measure by using function SUMX(Sales, Sales[UnitPrice] * Sales[QuantitySold])

ii. Total Revenue by Pizza Category: In this visual, I have used a Donut chart to get the required visual by adding Total Revenue in Values field and Pizza Category in the Legend field.

iii. Total Orders by Day of the Week: In this visual, I have used a Stacked bar chart to get the required visual by adding Total No. of Orders measure in X-axis and Day of the Week measure in Y-axis.

iv. Top 5 Best-Selling Pizzas: In this visual, I have used a Multi-row card required visual by adding pizza names to the fields and the Top N filter to get Top 5 best-selling pizzas.

v. Bottom 5 Worst-Selling Pizzas: In this visual, I have used a Multi-row card required visual by adding pizza names to the fields and the Top N filter to get Bottom 5 worst-selling pizzas.

vi. Top 5 Orders by Pizza Size: In this visual, I have used a Pie chart to get the required visual by adding Total No. of Orders measure in Values field and Pizza Size in the Legend field and Top N filter to get Top 5 Orders by Pizza Size.
