# Vancouver-House-Market-Prediction-
### Project Overview:

In this project, a **multiple linear regression model** was developed to predict the sale price of houses in Vancouver.

### Methods:

- The project commenced by dividing the dataset into two distinct sets: a training set and a validation set. The training set was utilized to develop the predictive model.
- **Exploratory data analysis** was conducted, including visualizations that highlighted the relationships between the variables.
- The main part of the project presented the results of the **best model**, referred to as the final model.
- The final model was selected based on several considerations, such as ensuring that assumptions were met, assessing goodness of fit to the training set, evaluating the model's complexity and variable selection, and examining its performance in predicting new data.
- Prior to determining the final model, alternative **candidate models** were also considered.

### Final Remarks:

- The project concluded with a discussion of the strengths and limitations of the final model. Recommendations were provided to address any identified limitations.
- The predictive model aimed to provide valuable insights for real estate professionals in Vancouver, enabling them to make informed decisions while representing both sellers and buyers of houses.

### Discussions:

The **predicted housing prices** provided by the model can assist both buyers and sellers in making optimal decisions when trading house properties in Vancouver. From the seller's perspective, variables such as Total Floor Area, Lot Size, and Age can be easily calculated to set competitive prices using statistical methods. On the buyer's side, this model serves as a valuable tool for negotiating with property agents and making informed purchasing decisions, offering benefits to both parties.

The model's **strengths** lie in its interpretability and practicality. Coefficients within the model provide straightforward interpretations of how each explanatory variable influences the response variable. For instance, a coefficient of 32,086 for Total Floor Area implies that a one-unit increase in the square root of Total Floor Area results in a price increase of $32,086. The absolute values of these coefficients can be employed to compare the relative impact of different variables. In terms of practicality, users can conveniently gather explanatory data by conducting calculations or utilizing readily available online resources, **significantly saving time and resources** typically expended on data collection. Furthermore, the objectivity of the collected data ensures consistency in calculations without concerns about scale variations.

Nonetheless, there are limitations associated with the prediction model. The model cannot entirely fulfill the assumption of independence concerning time and space. For instance, it may not be suitable for predicting housing prices post-pandemic due to the data's collection before COVID-19. Additionally, the model lacks the ability to differentiate between Vancouver neighborhoods. Similar properties in terms of age, lot size, and total floor area may have significantly varying prices between areas like Dunbar and east Vancouver. Users should remain cautious about the model's time and space constraints to avoid making incorrect decisions.

A **recommendation** to address these limitations involves enhancing data collection and processing. It is suggested to include more location data, particularly neighborhood information, during data collection to improve prediction accuracy. Furthermore, data processing can be enhanced by converting the address variable into quantitative data such as longitude and latitude, thereby resolving location-related challenges.
