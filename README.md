# Prospective_Restaurant_Evaluator
Dan Cersosimo | Data Scientist | Random Forest Regression

**Overview:**

For this project, I worked with a Yelp dataset for hundreds of thousands of businesses. Being an open-ended project, I explored this data to determine a viable task to provide an end product that would be functional for a specific sector of business. After pondering potential avenues, I focused on a specific component of the businesses, restaurants that are open and have over 100 reviews. This was done as restaurants were the most abundant business category and focusing on those of the stated criteria would increase the likelihood of successful restaurants being involved in training a model. The decision to focus on these would allow my results to be quite relevant in a specific realm of business, successful high-traffic restaurants. Following an intensive processing stage to ensure the data was suitable for modeling, I chose to utilize random forest regression due to the nature of the high dimensional data being of binary input features to predict a continuous target. Further explanations of the reasoning for this technique are discussed in the project itself and for the sake of the brevity of this overview, I will simply note this and leave the details to the file. Following the successful construction of the model, I visualized the importance of each feature and deployed the model to a user interactive tool that acquires user input for attribute features of a hypothetical restaurant and predicts the star rating. I also developed a geospatial visualization to portray the relevant restaurants alongside the prospective restaurants based on client specifications. The results of this project provide multiple products that can be useful for a prospective restaurant owner in evaluating how supplemental attributes could impact rating stars.

**Summary:**

• Processed a Yelp dataset to identify restaurants of specific criteria while conducting necessary feature engineering 

• Utilized Random Forest Regression to train a model of binary input features to predict a continuous target value, star rating

• Harnessed this model to construct a tool that predicts a star rating for a restaurant based on user-specified supplemental attributes

• Configured a geospatial visualization to portray the restaurants including the one designed by the client

**How to Run:**

In order to run, Jupyter Notebook must be installed alongside the necessary libraries as seen in the .ipynb file. The project is housed in the Jupyter Notebook in this repository.

***Thank you for viewing!***
