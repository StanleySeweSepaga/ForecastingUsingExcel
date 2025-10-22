
# Plates & Cravings Food Demand Forecasting

<img width="275" height="183" alt="image" src="https://github.com/user-attachments/assets/b5a58dfb-75f7-4864-91c2-94f2610bbfe0" />


### Table of contents
- [Project Overview](#project-Overview)
- [Project Objective](#project-Objective)
- [Data Source](#Data-Source)
- [Key Insights](#Key-Insights)
- [Conclusion](#Conclusion)


## Project Overview
Plates & Cravings is a dynamic food brand offering a rich blend of authentic Nigerian and African dishes, complemented 
by a selection of international cuisine, desserts, and snacks. Founded with a passion for flavor, culture, and creativity, their goal is to serve meals that satisfy both everyday cravings and
special occasions.

As demand for diverse meals grows, Plates & Cravings faces the challenge of accurately predicting customer orders 
across its varied menu, which includes Nigerian/African dishes, international cuisine, and desserts. Fluctuating order
volumes, influenced by pricing, promotions, and seasonal trends, make it difficult to plan inventory, reduce food waste, 
and meet customer expectations consistently.

## Project Objective
- Provide a descriptive overview of the business’s current performance.
- Conduct Price Sensitivity Analysis to explore how demand changes with price, and time.
- Analyze trends and forecast orders for the four weeks (Month).

## Data Source
The data set used was provided by 10Alytics consulting services. It contains data on order dates, the meals available at Plates & Cravings, 
their respective base prices, and higlights on meals promoted through emails or homepage featuring.

## Key Insights
The use of pivot tables help get summary statistics such as the variance of population which helps track consistency of customers orders across the various centres
and meals.

Also, further analysis such as Pegging featuring meals on homepage against volume of orders helped uncover the fact (i.e using from Average values) that more orders come in when meals are featured on homepage. 
same for inference resulted when meals were promoted through emails.

Furthermore, a correlation matrix done on features: "number of orders" and "checkouts" help uncover if customers tend to abandon 
checkouts as their orders increase or decrease. 

Techniques like the **Naive appraoch, Exponential approach** and the **Moving average methods** were key techniques employed in perfoming the forecasting analysis. 
In evaluating how well these techniques work, metrics like the **Mean Absolute Error (MAE)**, **Mean Squared Error (MSE)**, **Mean Absolute Percentage Error (MAPE)** and **Accuracy******
were computed. 

Results from the best performing technique was relied on to guage orders for the next four weeks, hence guiding business decisions.

## Conclusion
With the use of data-driven forecasting solution, Plates and Cravings is able to optimize its operations and minimize losses, 
as it is able to anticipate demand patterns, assess the impact of promotional efforts, and strongly make strategic decisions 
in production and supply chain planning.
