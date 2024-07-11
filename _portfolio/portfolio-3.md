---
title: "Business Data Management"
excerpt: "Managing stockouts of raw materials in a healtcare manufacturing factory<br/><img src='/images/iitm.png'>"
collection: portfolio
---

## Overview
Inventory management is one of the most crucial aspects of any business model. It involves ordering, storing, using, and selling a company's inventory. The goal of inventory management is to have the right products in the right place at the right time. It deals with the optimization of inventory levels by providing high level of customer service without accumulating excess investment in inventory in order to maximize profits.

## Objectives

- Shortlist the most profitable products and use them for further analysis.

- Forecast the future demand for these products.

- Calculate the lead time, safety stock and reorder point for these products.

## Methodology

- 2.5 years of data (2021-2023) pertaining to raw materials received against purchase orders is collected.

- **ABC-VED analysis** is used to find the most profitable products based on the total issue amount. 6 products were shortlisted.

![abcved](/images/abcved.png)

<p align="center" style="font-size: smaller;"><i>Fig-1: Pareto chart for the RM data with total amount as value.</i></p>

- **Time series analysis** is carried out for the shortlisted products using 3 different models: LSTM, SARIMA, and facebook prophet. Predictions for future demand are made using the prophet model (least MAE).

![ts](/images/ts.png)

<p align="center" style="font-size: smaller;"><i>Fig-2: Time series model fit on training data for Telmisartan.</i></p>


- **Safety stock and reorder point** for the products are calculated and reported using the standard formulae. 


## Results and Findings 

- Demand for most products peaked during the months of September and October. This is likely due to the fact that the weather changes frequently during this time and hence more people fall sick.

- Overall trend in the demand for most products followed a downward curve. 

- The values of safety stock and reorder point for all products were calculated to mitigate any stockouts.

## Tech stack used
-Python
-MS Excel


For more details check - <a href = "https://github.com/utkarsh11252/BDM-Project">https://github.com/utkarsh11252/BDM-Project</a>