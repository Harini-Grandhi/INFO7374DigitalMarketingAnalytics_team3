# Final Project - Zlymo Online Cosmetics Store

<h2> Overview of our Store </h2>

Zlymo is an online cosmetic store striving to mark its presence in the field competing with major brands like Sephora, Ipsy etc. For this purpose they have decided to concentrate on promotions through multiple channels like email marketing, social media, referral etc.

<h2> Business Model <h2> 
  
To meet the requirements of Zlymo, we have decided to build two separate systems, one which is customer focused and the other for business partners.
    * Customer Centric System
    * Partner Centric System

<h2> Data Acquisition </h2>

To understand the performance of the company 

<b> Marketing funnel </b>   
     * View the product
     * Moving the product to the cart
     * Purchasing the product 

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






