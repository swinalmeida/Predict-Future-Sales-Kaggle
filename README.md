# Predict Future Sales Kaggle

In this repository, I work with data from a Kaggle Competition. In this competition I am working with time-series dataset consisting of daily sales data, trying to predict total sales for every product and store in the next month. I used two different regression models; Random Forest Regression and XGBoost.

### Data Description:
<br/>https://www.kaggle.com/c/competitive-data-science-predict-future-sales/data
<br/>
You are provided with daily historical sales data. The task is to forecast the total amount of products sold in every shop for the test set. Note that the list of shops and products slightly changes every month. Creating a robust model that can handle such situations is part of the challenge.

<br/>File descriptions:
<br/>sales_train.csv - the training set. Daily historical data from January 2013 to October 2015.
<br/>test.csv - the test set. You need to forecast the sales for these shops and products for November 2015.
<br/>sample_submission.csv - a sample submission file in the correct format.
<br/>items.csv - supplemental information about the items/products.
<br/>item_categories.csv  - supplemental information about the items categories.
<br/>shops.csv- supplemental information about the shops.
<br/>
<br/>Data fields
<br/>ID - an Id that represents a (Shop, Item) tuple within the test set
<br/>shop_id - unique identifier of a shop
<br/>item_id - unique identifier of a product
<br/>item_category_id - unique identifier of item category
<br/>item_cnt_day - number of products sold. You are predicting a monthly amount of this measure
<br/>item_price - current price of an item
<br/>date - date in format dd/mm/yyyy
<br/>date_block_num - a consecutive month number, used for convenience. January 2013 is 0, February 2013 is 1,..., October 2015 is 33
<br/>item_name - name of item
<br/>shop_name - name of shop
<br/>item_category_name - name of item category
