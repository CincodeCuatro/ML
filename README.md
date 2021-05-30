# ML

We want to optimize the pastry inventory. Therefore we want to:
- know what amount of pastry is needed/consumed on a given day
- how what are possible outliers (and their possible explanations) (e.g., a lot of pastry consumption on casual Friday?)
- the provided data, as visible, is a time-series of one month (April 2019)

Dataset source: [Link](https://www.kaggle.com/ylchang/coffee-shop-sample-data-1113?select=pastry+inventory.csv)

# Implenetation
Python
## Libaries 
* pandas 
* numpy
* sklearn
* matplotlib
* seaborn

Use linear regression to predict the quantity_sold on a given day at a given location
ex:
#sales outlet 3, product id 72 (ginger scone), weekday = 0, Monday
math.ceil(model.predict([[3, 72, 0]]))
