# Ecommerce-Pricing-Strategy
Presentation: https://drive.google.com/file/d/1bbA2KlbV_VPc1Q8LjqxehowkTgJateWq/view?usp=sharing

Company Background:
Consider a clothing store named "TrendElite" that specializes in a diverse range of apparel and accessories. TrendElite operates both physical stores and an online e-commerce platform. The company aims to enhance its revenue and market competitiveness by optimizing its pricing strategy.

Challenges Faced:
TrendElite encounters various challenges in effectively pricing its products:

1.	Competitive Landscape: The retail industry is fiercely competitive, with numerous rivals offering similar products. TrendElite seeks to differentiate itself by providing appealing prices while maintaining profitability.
2.	Inventory Management: Effective inventory management is crucial for TrendElite, requiring pricing strategies that balance supply and demand. Optimization based on inventory levels helps prevent overstocking or understocking of products.
3.	Seasonal and Trend Variations: Rapid changes in fashion trends and fluctuating demand throughout the year pose challenges for TrendElite. Adapting prices to reflect seasonal and trend variations is essential to capitalize on sales opportunities.

Solution: Price Optimization.

Dataset description: The data contains the demand and corresponding average unit price at a product - month_year level

Variable Description:
1.	product_id: A unique identifier for each product in the dataset.
2.	product_category_name: The name of the product category to which the product belongs.
3.	month_year: The month and year of the retail transaction or data recording.
4.	qty: The quantity of the product sold or purchased in a given transaction.
5.	total_price: The total price of the product, including any applicable taxes or discounts.Calculated using qty*unit_price
6.	freight_price: The average freight price associated with the product.
7.	unit_price: The average unit price of a single unit of the product.
8.	product_name_length: The length of the product name in terms of the number of characters.
9.	product_description_length: The length of the product description in terms of the number of characters.
10.	product_photos_qty: The number of photos available for the product in the dataset.
11.	product_weight_g: The weight of the product in grams.
12.	product_score: average product rating associated with the product’s quality, popularity, or other relevant factors.
13.	customers: The number of customers who purchased the product in a given category.
14.	weekday: Number of weekdays in that month.
15.	weekend: number of weekends in that month.
16.	holiday: Number of holidays in that month.
17.	month: The month in which the transaction occurred.
18.	year: The year in which the transaction occurred.
19.	s: the effect of seasonality
20.	Volume: Product Volume
21.	Comp_1: competitor1 price
22.	Ps1: competitor1 product rating
23.	Fp1: competitor1 freight price
24.	Comp_2: competitor2 price
25.	Ps2: competitor2 product rating
26.	Fp2: competitor2 freight price
27.	Comp_3: competitor3 price
28.	Ps3: competitor3 product rating
29.	Fp3: competitor3 freight price
30.	Lag_price : previous month price of the product
