# Instacart Market Basket Analysis

### Business Scenario

- The dataset is obtained from Instacart, an electronic commerce grocery ordering and delivery organization. The dataset contains a sample of over 3 million grocery orders from more than 200,000 Instacart users. The dataset contains details about the orders placed by various users, the sequence of products purchased in each order, the week and hour of day the order was placed, and a relative measure of time between orders. It also has information about the aisle and department for the sold products.

In this scenario, our stakeholder is keen to understand customer behavior regarding grocery purchases through their app. They have several specific questions they'd like to explore, such as:

### Questions
<ul>
  <li>What are the busiest of times of the week?</li>
  <li>What days tend to be the busiest throughout the week?</li>
  <li>How long after their previous order, do customers order again? And when are customers most likely to order again?</li>
  <li>What are the Top 3 best selling products?</li>
  <li>How many items do customers most often order?</li>
  <li>What are the top 3 aisles that customers mostly order from?</li>
  <li>What are the top products from each time of day customer groups? (Early Birds, Late Night Hours, Weekend Busiest Hours, etc.)</li>
</ul>

# Visualization
<img src = "Instacart Dashboard.png"></img>

### Dashboard Components

#### Busiest Hours:
- A distribution of Instacart users utilizing the app to make grocery orders at certains time of the day throughout the week

#### Busiest Days of the Week:
- A bar chart of Instacart users utilizing the app to make grocery orders for each day

#### Days Since Prior Order:
- Displays a histogram chart of how long after a customer's previous order until they order again

#### Best Selling Products:
- A bar chart displaying the best selling products in the app

#### Number of Items Purchased per Order:
- A distribution on the number of items a customer tends to buy per order

#### Treemap of Aisles and Products:
- A treemap visualizing customer product purchases within a designated store aisle

#### Top Products per Group:
- A bar chart showcasing the top products purchased by different customer segments, including Early Birds, Evening Shoppers, and more


These visualizations are created in Tableau and can be found here: <a href = "https://public.tableau.com/app/profile/alejandro.de.la.cruz5286/viz/InstacartMarketBasketAnalysis_17122561477850/InstacartMarketBasketAnalysis" rel="unfollow">Instacart Market Basket Analysis</a>

# Analysis

Now, we will dive into the analysis to provide insights into the specific questions our stakeholder is eager to understand.

<ol>
  <li>The busiest hours are typically from 8:00 AM to 6:00 PM</li>
  <li>The busiest days throughout the week tend to be Saturday and Sunday where users use the app to purchase their groceries</li>
  <li>Based from the <b>Days Since Prior Order</b>, we can likely say that it would take the customer/user about a week (7 days) or up to a month (30 days) before the customer makes their next purchase on the app</li>
  <li>The best selling products on the app that customers would typically buy would be bananas, organic bananas, and organic strawberries</li>
  <li>Based from the <b>Number of Items Purchased per Order</b> most of the customer would typically buy 3-8 items for each order the customer makes</li>
  <li>In the treemap, we could see that the customers would tend to order from fresh fruits, fresh vegetables, and packaged veggies and fruits aisles</li>
  <li><b>Refer to visualization</b>, but in the <b>Top Products per Group</b> chart, we can see that these groups of people tend to buy those certain products at certain times of the day of the week</li>
</ol>
