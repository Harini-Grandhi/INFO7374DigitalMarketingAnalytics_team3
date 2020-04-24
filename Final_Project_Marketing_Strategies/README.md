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
  - view - a user viewed a product
  - cart - a user added a product to shopping cart
  - remove from cart - a user removed a product from shopping cart
  - purchase - a user purchased a product.

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
 
As the data is limited to customer clicks, we have generated synthetic data which gives details of the capaigns and promotions.

  - Promotions: Promotions used to attract customer base to increase sales
      - Discount
      - Buy one Get one
      - Free Samples
      
  - Campaigns: The medium through which the promotions are marketed
      - Email
      - Socil Media
      - Reffral
      - Web Search
   
  - Channel: The device through which the promotion is accessed
      - Phone
      - Desktop
      
      
<h4> Marketing Algorithms Implemented </h4>

<b> Pricing Strategies </b>

<b> Uplift modelling </b>

<b> Recommendation System with Ranking of the Product </b>

<b> Retention Rate and understanding existing & new customers </b> 

<b> Predicting Sales using LSTM </b>

<h4> Implementation </h4>
  
The syntehetic data and the notebooks are uploaded in the cloud which will generate required data output. The data is stored in AWS Redshift, which is accessed by Spotfire.

![Model1](https://github.com/Harini-Grandhi/INFO7374DigitalMarketingAnalytics_team3/blob/master/Final_Project_Marketing_Strategies/project_mplimentation.PNG)
![Model3](https://github.com/Harini-Grandhi/INFO7374DigitalMarketingAnalytics_team3/blob/master/Final_Project_Marketing_Strategies/Cloud_implementation.jpg)


<h2> Zlymo Strategies End Product </h2>

We have created dashboards in spotfire, which give a brief overview of the data and can help brand to focus their promotions on targeted customer with recommended brands. We have also created dashboards which will give a brief on how the company performance is over the period and the performance profile of each customer.

A glimpse of the exploratory dashboard:

![Model2](https://github.com/Harini-Grandhi/INFO7374DigitalMarketingAnalytics_team3/blob/master/Final_Project_Marketing_Strategies/Dashboard1.jpeg)


<h3> Report Link </h3>
Detailed explanation of the algorithms and dashboards can be found here:
https://docs.google.com/document/d/1FYAanOyqtcnCXlRPF4uhrzVYM3MWCJvgVnAXFZgLk6o/edit#




