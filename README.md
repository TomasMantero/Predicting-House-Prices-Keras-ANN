# Predicting House Prices (Keras - Artificial Neural Network)

![Python](https://img.shields.io/badge/Python-3.7.6-blue) ![License](https://img.shields.io/badge/License-Apache%202.0-orange) ![Contributions](https://img.shields.io/badge/Contributions-Welcome-green)

In this notebook we analyze a dataset call [House Sales in King County, USA]( https://www.kaggle.com/harlfoxem/housesalesprediction), which you can find in Kaggle.

One of the objectives of this notebook is to show step-by-step how to analyze and visualize the dataset to predict future home prices. Moreover, we are going to explain most of the concepts used so that you understand why we are using them. In base of features like sqft_living, bathrooms, bedrooms, view, and others, we are going to build a deep learning model that can predict future price houses.
This dataset contains house sale prices for King County, which includes Seattle. It includes homes sold between May 2014 and May 2015.

To watch the Kernel directly from Kaggle click [here.]( https://www.kaggle.com/tomasmantero/predicting-house-prices-keras-ann)

***Feature Columns***

* **id:** Unique ID for each home sold
* **date:** Date of the home sale
* **price:** Price of each home sold
* **bedrooms:** Number of bedrooms
* **bathrooms:** Number of bathrooms, where .5 accounts for a room with a toilet but no shower
* **sqft_living:** Square footage of the apartments interior living space
* **sqft_lot:** Square footage of the land space
* **floors:** Number of floors
* **waterfront:** - A dummy variable for whether the apartment was overlooking the waterfront or not
* **view:** An index from 0 to 4 of how good the view of the property was
* **condition:** - An index from 1 to 5 on the condition of the apartment,
* **grade:** An index from 1 to 13, where 1-3 falls short of building construction and design, 7 has an average level of construction and design, and 11-13 have a high quality level of construction and design.
* **sqft_above:** The square footage of the interior housing space that is above ground level
* **sqft_basement:** The square footage of the interior housing space that is below ground level
* **yr_built:** The year the house was initially built
* **yr_renovated:** The year of the house’s last renovation
* **zipcode:** What zipcode area the house is in
* **lat:** Lattitude
* **long:** Longitude
* **sqft_living15:** The square footage of interior housing living space for the nearest 15 neighbors
* **sqft_lot15:** The square footage of the land lots of the nearest 15 neighbors

## License

This Notebook has been released under the Apache 2.0 open source license.
