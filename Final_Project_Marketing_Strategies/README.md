# Final Project - Zlymo Online Cosmetics Store


```
Authors:
Harini Grandhi
Sumeet Gaglani
Nancy Jemimah Packiyanathan
```

<h2> Overview of our Store </h2>

Zlymo is an online cosmetic store striving to mark its presence in the field competing with major brands like Sephora, Ipsy etc. For this purpose they have decided to concentrate on promotions through multiple channels like email marketing, social media, referral etc.

<h2> Business Model </h2> 
  
To meet the requirements of Zlymo, we have decided to build two separate systems, one which is customer focused and the other for business partners.

    * Customer Centric System
    * Partner Centric System

<h2> Data Acquisition </h2>

To understand the performance of the company 

<b> Marketing funnel </b>   

     * View the product
     * Moving the product to the cart
     * Purchasing the product 
     
![Model](https://github.com/Harini-Grandhi/INFO7374DigitalMarketingAnalytics_team3/blob/master/Final_Project_Marketing_Strategies/MarketingFunnel.PNG)

<b> Information Collected from the customer </b>

Event_time - Time when event happened at (in UTC).

Event_type - Events can be:

view - a user viewed a product

cart - a user added a product to shopping cart

remove from cart - a user removed a product from shopping cart

purchase - a user purchased a product.

Product_id - ID of a product

Category_id - Product's category ID

Category_code - Product's category taxonomy (code name) if it was possible to make it. Usually present for meaningful categories and skipped for different kinds of accessories.

Brand - Downcase string of brand name. Can be missed.

Price- Float price of a product. Present.

User_id- Permanent user ID.

User_session - Temporary user's session ID. Same for each user's session. It changes every time a user comes back to an online store from a long pause.

<h4> Setting up the environment for this project </h4>

* Download or clone the repository
* Install all the requirements from requirements.txt
* Then inside the notebooks folder, there are implementation of various marketing algorithms.
* Run the code in your machine


<h2> Implementation Strategies </h2>

<h4> Synthetic Data Generation </h4>

<h4> Exploratory Data Analysis </h4>

<h4> Marketing Algorithms Implemented </h4>

<b> Pricing Strategies </b>

<b> Uplift modelling </b>

<b> Recommendation System with Ranking of the Product </b>

<b> Retention Rate and understanding existing & new customers </b> 

New Customer Ratio

First we should define what is a new customer. In our dataset, we can assume a new customer is whoever did his/her first purchase in the time window we defined. We will be using .min() function to find our first purchase date for each customer and define new customers based on that.

Retention rate should be monitored very closely because it indicates how sticky is your service and how well your product fits the market. For making Monthly Retention Rate visualized, we need to calculate how many customers retained from previous month.

```
Monthly Retention Rate = Retained Customers From Prev. Month/Active Customers Total
```

<b> Predicting Sales using LSTM </b>

Predicting sales is important to any organization. We can plan our demand and supply actions by looking at the forecasts. It helps to see where to invest more. Last but not least, it is an excellent guide for planning budgets and targets. In this project we used LSTM Model to predict our sales. Our sales was not a steady increase. We had a huge increase during the holiday season and then in the month of December & January there is fall in the sales.


<h2> Our Finding to improve the Zlymo </h2>

<h2> Brief View of our Key Metrics in our Dashboards </h2>

<h3> Report Link </h3> https://docs.google.com/document/d/1FYAanOyqtcnCXlRPF4uhrzVYM3MWCJvgVnAXFZgLk6o/edit#




