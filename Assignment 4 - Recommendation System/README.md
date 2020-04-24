# SNACKBOX RECOMMENDATION SYSTEM - PROTOTYPE


# Introduction to Recommender System

In this modern world we are overloaded with data and this data provides us the useful information. But it's not possible for the user to extract the information which interest them from these data. In order to help the user to find out information about the product , recommedation systems where developed.

Recommeder system creates a similarity between the user and items and exploits the similarity between user/item to make recommendations.

What recommeder system can solve ?

* It can help the user to find the right product.
* It can increase the user engagement. For example, there's 40% more click on the google news due to recommendation.
* It helps the item providers to deliver the items to the right user.In Amazon , 35 % products get sold due to recommendation.
* It helps to make the contents more personalized.In Netflix most of the rented movies are from recommendations.

<h3> Setting up this environment to run the python notebooks </h3>

To setup on your local machine:
  1. Install Anaconda with Python >= 3.6. Miniconda is a quick way to get started.
  2. Clone the repository
  3. Setup and Install necessary python package. Download xlearn to run our Factorization Machine & Field Aware Factorization Machine algorithm
  
<h3> Stages of building the recommendation System </h3>
  1. Data Preparation - data split/transform
  2. Model Building 
  3. Evaluation Metrics to evaluate the model
  4. Deploy it in production
  
In this repository, we have covered stages till evaluation 

**Stage 0** - <a href = "https://github.com/NancyJemimah/INFO7374_AlgorithmicDigitalMarketingTeam3/tree/master/Assignment%204%20-%20Recommendation%20System/notebooks/00_quick_start"> Quick Start </a> --> which gives the basic approach of how the content based recommendation is built

**Stage 1** - <a href = "https://github.com/NancyJemimah/INFO7374_AlgorithmicDigitalMarketingTeam3/tree/master/Assignment%204%20-%20Recommendation%20System/notebooks/01_prepare_data"> Prepare the data </a> --> for most of the content based system, we are recommending to use chronological datas plit, in the notebook, there are other splitting techniques discussed too.

**Stage 2** - <a href = "https://github.com/NancyJemimah/INFO7374_AlgorithmicDigitalMarketingTeam3/tree/master/Assignment%204%20-%20Recommendation%20System/notebooks/02_model"> Model - FM/FFM </a> --> Our models are implemented using xlearn 

**Stage 3** - <a href = "https://github.com/NancyJemimah/INFO7374_AlgorithmicDigitalMarketingTeam3/tree/master/Assignment%204%20-%20Recommendation%20System/notebooks/03_evaluate"> Evaluation Metrics </a> --> Notebooks discuss about various metrics used to evaluate the recommendation system 

# Factorization Machine & Field Aware Factorization Machine 

![Model](https://github.com/NancyJemimah/INFO7374_AlgorithmicDigitalMarketingTeam3/blob/master/Assignment%204%20-%20Recommendation%20System/images/FFM.png)



**Report Link** - ![Snack Recommender - Prototype]( https://docs.google.com/document/d/1GVfmgDzT2O5c9bq6bB7PteKUJnCxw4R6JSxcEMjNBrk/edit#)


# Citations: 

Modified and Recreated the code from this repository → <a href = "https://github.com/microsoft/recommenders"> Microsoft - Best Recommendation System Practices </a>
