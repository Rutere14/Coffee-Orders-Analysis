
# Coffee Orders Analysis


## About
In this project, I conducted a comprehensive analysis of coffee orders using Excel, focusing on four distinct coffee types: Arabica, Excelsa, Liberica, and Robusta. The dataset covers sales data across three different countries: the USA, UK, and Ireland. The goal of this analysis was to identify patterns and trends in coffee preferences across these regions, uncovering insights into which types of coffee are most popular in each country. The project involved data cleaning, visualization, and analysis to provide actionable insights that could inform marketing strategies and inventory management for coffee businesses operating in these markets.




## Objectives 

- **Identify Coffee Preferences by Country**: Analyze the dataset to determine the most popular coffee types (Arabica, Excelsa, Liberica, Robusta) in the three countries (USA, UK, Ireland).

- **Understand Regional Sales Trends**: Explore and compare coffee sales trends across the USA, UK, and Ireland to identify regional differences in consumer behavior.

- **Inform Marketing Strategies**: Use the insights gained from the analysis to recommend targeted marketing strategies based on the popularity of different coffee types in each country.

- **Optimize Inventory Management**: Provide data-driven recommendations for optimizing inventory management by aligning stock levels with the demand for specific coffee types in each region.

- **Enhance Business Decision-Making**: Equip stakeholders with actionable insights to drive business decisions related to product offerings, pricing, and market expansion.






## About the Data 
This dataset contains the following information:

### Orders Worksheet

| Column Name    | Description |
|----------------|-------------|
| `order_id`     | A unique identifier for each coffee order. |
| `order_date`   | The date when the order was placed. |
| `customer_id`  | An identifier linking the order to a specific customer. |
| `product_id`   | A unique identifier for each coffee product. |
| `quantity`     | The quantity of the coffee product ordered. |

### Customers Worksheet

| Column Name     | Description |
|-----------------|-------------|
| `customer_id`   | A unique identifier for each customer. |
| `customer_name` | The name of the customer. |
| `email_address` | Contact information for customers. |
| `phone_number`  | Another contact detail for customers. |
| `and_more`      | Explore various customer attributes for segmentation and analysis. |

### Products Worksheet

| Column Name      | Description |
|------------------|-------------|
| `product_id`     | A unique identifier for each coffee product. |
| `coffee_type`    | The type or blend of coffee, such as Arabica or Robusta. |
| `roast_type`     | The roast level, including light, medium, or dark roast. |
| `size`           | Information about the product size. |
| `unit_price`     | The price of a single unit of the coffee product. |
| `price_per_100g` | The price per 100 grams for detailed price comparisons. |
| `profit`         | Insights into the profitability of each coffee product. |



## Questions to Answer

1. Which coffee brand was the best seller overall?
2. Who are the top five customers?
3. Which year had the highest amount of revenue?
4. Which is the worst-performing coffee brand overall?
5. Which country is the highest consumer of coffee among the three?
6. What is the average order quantity for each coffee type?
7. How does the profitability of each coffee type compare?
8. Are there any seasonal trends in coffee sales across the years?







## Insights
1. Excelsa generated the highest revenue among all coffee types, totaling $12,306 over the four years.
2. Ireland had the lowest sales among the three countries, with total revenue amounting to $6,697 over the four years. This indicates potential opportunities for improvement, such as enhanced marketing strategies, to boost sales in this region.
3. Allis Wilmore was our top customer, contributing significantly to our overall sales.
4. Dark roast coffee was the least preferred in Ireland, with consumers showing a stronger preference for light and medium roasts.
5. The 2.5kg package was the most popular size across all regions.

## Tools Used
- Microsoft Excel
- **Formulas and Features Utilized:**
  - `XLOOKUP`
  - `IFS`
  - `INDEX MATCH`
  - `Pivot Tables`
  - `Visualization`
