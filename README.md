# Global-Superstore
## This project provides information on the sales analysis of a multi-national firm with products sold across different parts of the world. The project was analyzed and visualized with Power BI after an effective data cleaning process was done in Excel.

##  Data Cleaning

The dataset used for this analysis was obtained from [Kaggle](https://www.kaggle.com/datasets/laibaanwer/superstore-sales-dataset). The data was downloaded as a CSV file and loaded into Microsoft Excel. Then, some data cleaning processes such as removing duplicates, removing blank rows, removing unwanted columns, etc. were also done.

## Creating Primary Keys and Pivot Tables

After data cleaning was done, the dataset was then converted into a table and pivot tables were created for Customers, Products, Location, and Orders; from the Main Sales Table. Primary Keys were also created for the Location and Customers tables which were used to detect relationships with the Main Sales Table when loaded into Power BI.

## Importing to Power BI

After the tables were created, the resulting worksheet was saved and loaded into Power BI for more analysis and visualization. In Power BI, new measures for Total Sales, Total Profit, and Profit Margin were created. Visualizations were also done using cards, donut chart, row charts, line chart, and slicers to present major findings from the dataset.

## Remarks

Some insights I was able to generate from this analysis are outlined below:

- **Sales & Profit Trend:** There was a steady growth in sales and profit from 2011 to 2014. However, Q1 had the lowest numbers in sales and profits across all the years. February was also the month with lowest sales YoY.
- **Customer with the highest number of sales:** "Tom Ashbrok" was the customer who generated the highest sales for the firm. Most of his sales were gotten in 2014 where he purchased products worth over $23,000.
- **Low performing countries based on profit:** Over 10 countries incurred loss for the firm, with Turkey, Nigeria, Netherlands, Honduras, and Pakistan appearing in the bottom 5, incurring a loss of over $150,000 for the firm.
- **Best Performing Country:** The United States is the best performing country for the firm, generating over $300,000 in profits.
- **Top Product Categories:** The Technology category is the top performing category generating the highest number in sales and profits for the firm. Under this category, "Phones", "Copiers", and "Machines" are the top 3 sub-categories.

![](https://github.com/Ernestug/Global-Superstore/blob/main/Global%20Superstore%20Dashboard.jpg)

