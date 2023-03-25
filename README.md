# TABLEAU-ME-EXAM

## 1 : - Explain in detail the area graphs and line graphs in tableau and how to create them with examples. (With the help of an example create one in tableau)

### Area Graphs in Tableau
Area graphs are used to display how a particular measure or variable changes over time, or across different categories. In an area graph, the area under the curve is filled with color, creating a visual representation of the data. Area graphs are often used to show trends in data, and can be useful when comparing the relative values of different categories.
To create an area graph in Tableau using the Sample Superstore dataset, follow these steps:
Open Tableau and connect to the Sample Superstore dataset.
Drag the "Order Date" field to the columns shelf, and drag the measure you want to graph (such as "Sales" or "Profit") to the rows shelf.
Click on the "Show Me" button in the top right corner of the screen, and select the "Area" graph type.
Tableau will automatically create an area graph showing the selected measure over time. You can further customize the graph by adding additional dimensions, colors, or labels.
Here's an example of what an area graph in Tableau might look like using the Sample Superstore dataset:
Tableau Area Graph Example
This graph shows the total sales over time, broken down by region. The area under each curve is filled with color, making it easy to see which regions have the highest sales over time.
Line Graphs in Tableau
Line graphs are similar to area graphs in that they are used to display how a measure or variable changes over time or across different categories. However, unlike area graphs, line graphs do not fill in the area under the curve with color. Instead, they use a single line to represent the data.
To create a line graph in Tableau using the Sample Superstore dataset, follow these steps:
Open Tableau and connect to the Sample Superstore dataset.
Drag the "Order Date" field to the columns shelf, and drag the measure you want to graph (such as "Sales" or "Profit") to the rows shelf.
Click on the "Show Me" button in the top right corner of the screen, and select the "Line" graph type.
Tableau will automatically create a line graph showing the selected measure over time. You can further customize the graph by adding additional dimensions, colors, or labels.
2 :-  What are the different steps in grouping fields and combining tables in tableau ? Explain with
examples. (With the help of an example create one in tableau)
Grouping Fields in Tableau
Grouping fields in Tableau involves combining multiple values into a single value based on some criteria. This can be useful when working with categorical data, such as product categories or customer segments. Grouping fields can help simplify a visualization by reducing the number of categories, or it can allow for more meaningful comparisons between categories.
To group fields in Tableau using the Sample Superstore dataset, follow these steps:
Open Tableau and connect to the Sample Superstore dataset.
Drag the dimension you want to group (such as "Category" or "Region") to the Rows or Columns shelf.
Select the individual values you want to group together by clicking and dragging them to the "Drag to Group" area at the bottom of the field list.
Once you have selected all the values you want to group together, right-click on one of the selected values and choose "Group" from the dropdown menu.
Enter a name for the new group, and click "OK". Tableau will automatically create a new field with the grouped values.
Here's an example of what grouping fields in Tableau might look like using the Sample Superstore dataset:
Tableau Grouping Fields Example
In this example, we've grouped the "Category" field into two groups: "Office Supplies" and "Everything Else". This makes it easier to compare the total sales and profit for each group, rather than looking at each individual category separately.
Combining Tables in Tableau
Combining tables in Tableau involves merging data from multiple tables into a single view. This can be useful when working with complex data models or when trying to combine data from different sources. There are several types of table joins in Tableau, including inner join, left join, right join, and full outer join.
To combine tables in Tableau using the Sample Superstore dataset, follow these steps:
Open Tableau and connect to the Sample Superstore dataset.
Click on the "New Data Source" button in the bottom left corner of the screen.
Select the second data source you want to combine, such as a CSV or Excel file.
Drag the common field between the two tables (such as "Order ID" or "Customer ID") from one table to the other to create a join.
Choose the type of join you want to use from the dropdown menu (inner join, left join, right join, or full outer join).
Once you have created the join, you can use the fields from both tables in your visualization


3 :- What is the use of color and size options in the marks cart of tableau ? (With the help of an
example create one in tableau) 
Color
Using color in Tableau can be a powerful way to highlight different categories or patterns in your data. By assigning different colors to different values in your data, you can create a more visually appealing and informative visualization. Color can also help to make your visualization more accessible for colorblind viewers.
In Tableau, you can assign color to your marks in several ways, including by dimension or measure. For example, you could use color to show the total sales for each region in a map or to highlight the product category for each data point in a scatterplot.
Here's an example of using color in Tableau using the Sample Superstore dataset:
Tableau Color Example
In this example, we've created a map that shows the total sales for each region in the Sample Superstore dataset. We've used color to highlight the highest and lowest sales regions, with darker shades of blue indicating higher sales and lighter shades indicating lower sales.
Size
Using size in Tableau can be another way to encode data in your visualization. By assigning different sizes to your marks based on a measure, you can highlight the importance or significance of different data points. For example, you could use size to show the total profit for each product in a scatterplot or to show the number of customers in each region in a bubble chart.
In Tableau, you can assign size to your marks by using a measure or by using the Size shelf. You can also adjust the size range and scale to make sure your visualization is clear and informative.
