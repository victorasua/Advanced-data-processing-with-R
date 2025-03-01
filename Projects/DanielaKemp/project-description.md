## Looking at Food Facts
Data Source: [OpenFoodFacts](https://app.gigasheet.com/spreadsheet/OpenFoodFacts-org-Products-Database/9a056567_9b41_4dda_a673_37fe1d3526b5)

The given data is a subset of the data containing 25 000 rows.

The data table is pretty sparse, in a lot of rows column data is missing. For any analysis you'd have to explain which subset of the data you used, and how you got this subset. Using a subset of the table with only the relevant rows is advised.

# Preprocessing:

1. Define a subset of the table without any Nestle products or products using palm oil.

2.   Delete all rows where the sum of all sugars is greater than the amount of carbohydrates

3.   Use kj/100g to fill out the blanks in kcal/100g and vice versa.

# Tasks  
 -  Group foods depending on type (pnns_groups_1), and find the average nutriscore for each group. Visualize this in a suitable plot, using the nutri-score colors if applicable.

 -  The nutri-score was established in 2016 in France. Using different indicators (like kj/100g, portion size, additives), can you see a difference in the 'healthyness" difference in food quality between 2016 and 2021(Germany voluntarily adopts the nutri-score) in France and Germany?

  - Look at additives in the food and try to find correlations between foodgroups and additives.

  - Try to find a method to classify (define classes yourself) the foods for CO2-usage (carbon foodprint 100g), and use this method to classify the food items from each unique countrie with the highest/lowest/median energy-kcal_100g

 - Visualize the exports of every country with a sufficiently large number of different exports by food type

 - Visualize whatever you find most interesting here

