
# Predicted Car Price Analysis

## How to check the analysis?

To check the analysis done in Microsoft Power BI, please download Microsoft Power BI, if not already. Then, open the .pbix file.

## Key Findings and Conclusions

* The Power BI Dashboards contain a summary of various Machine Learning models trained on datasets of two car models: Fiesta and Focus
*  The results are visualized with various plots to help us interpret how each machine learning model performed
*  The dataset had features like price, engineSize, tax, mileage, MPG, and fuelType.  The price is taken as our dependent variable whereas, engineSize, tax, mileage, MPG are considered independent variables
*  For an overall model performance comparison, we use a clustered bar chart to visualize the difference between the train and test set error among all the models
*  From the analysis, it can be seen that for Fiesta, Random Forest gives us the most reliable predictions. In comparison, it’s not the same for Focus where ANN is most reliable when compared to the other three ML methods.
*  We also learned how different features like year, mileage, tax, MPG, fuelType play a role in the valuation of used car prices. Analysis shows that for Fiesta, it’s year and mileage that impact the used car price whereas, for Focus, it’s year and engineSize.
*  This is probably because the Focus model, having a larger dimension, requires larger engineSizes and therefore engineSize has a higher impact on its price. While Fiesta, being smaller in size compared to Focus, emphasizes more on the mileage and efficiency. 
*  For both Fiesta and Focus, ANN has the least difference. Even though the error is higher compared to other models when considering the test and train errors individually, if we consider both errors together then ANN seems to be the most reliable model
*  Random Forest provides feature importance analysis. This can be different from the correlation plot as the latter is a statistical estimation. Random Forest relied on ‘year’ alot to predict price. In case of Focus, after ‘year’ it relied on engineSize and, for Fiesta it relied on mileage. The tax seems to have the weakest significance. 
