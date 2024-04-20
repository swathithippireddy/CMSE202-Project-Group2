# CMSE202-Project-Group2

## Project group name:
    - Finacial 2 Team C: Predict house prices based on a set of features.
    
## Project members:
    - Swathi Thippireddy
    - Anuj Jadhav
    - Lalitha Hasa Perakam
    - Sharif Safwan Hossain
    
## Abstract:

This housing data analysis project delves into exploring and predicting house prices using various machine learning techniques. The dataset used contains information on different aspects of residential properties, such as the number of bedrooms, living area size, year built, and sale prices. The project aims to build predictive models to estimate house prices based on these features.

The analysis begins with an overview of the dataset, which includes a look at the distribution of house prices. The distribution plot reveals that house prices are right-skewed, indicating that most houses are priced below the mean. Following this, the numerical features of the dataset are examined to understand their distributions. Histograms are used to visualize the spread of features like living area, number of bedrooms, and other relevant numerical attributes.

Next, correlation analysis is performed to understand the relationships between numerical features and the target variable (sale price). A correlation heatmap is generated, highlighting which features have the strongest correlations with house prices. This analysis helps in feature selection for the predictive models.

The project then moves on to building and evaluating three types of predictive models: Linear Regression, Multiple Regression, and Random Forest Regressor. In Linear Regression, the model is trained on the numerical features to predict house prices. The Mean Squared Error (MSE) and R-squared values are calculated to evaluate the model's performance. Additionally, a scatter plot of actual versus predicted prices is plotted, showing how well the model's predictions align with the actual prices.

In Multiple Regression, the focus shifts to selecting the top three features with the highest correlation with sale prices. The model is trained on these features, and its performance is evaluated similarly to Linear Regression. The scatter plot and MSE provide insights into the model's accuracy.

Lastly, a Random Forest Regressor model is employed, utilizing features like Overall Quality, Living Area, Total Basement Area, Year Built, Full Bathrooms, and Bedrooms above Grade. This model aims to capture non-linear relationships and interactions between features to predict house prices. The evaluation metrics, MSE and R-squared, are computed, and a scatter plot of actual versus predicted prices is created. The model's prediction errors are also visualized in a histogram.

Overall, the project demonstrates the process of analyzing housing data, selecting relevant features, building predictive models, and evaluating their performance. The findings suggest that the Random Forest Regressor performs slightly better than Linear and Multiple Regression models in predicting house prices. However, all models show potential for further improvement with additional feature engineering and tuning. The project provides valuable insights for stakeholders in the real estate industry, offering tools to estimate house prices more accurately based on key property attributes.

## Project members contributions.:
    - Swathi
        - Setup the Github repository and included all intial files. 
        - Worked on finding most accurate models to predict housing prices, including SVMs and Random Forest Regrssion models. 
        - In charge of setting up meeting dates and times amongst the project members to ensure that the project would be delivered in time and that the presentation was well prepared for. 
        - Worked on the powerpoint slides for the final presenation. 
    - Anuj Jadhav
        - Worked on the Multiple regression model for house price prediction
        - Kept a track of files and branches on the Proeject Repositiory
        - Worked on the powerpoint slides for the final presenation. 
    - Lalitha Hasa Perakam
        - Kept a record of all the updated files and made sure everything runs smoothly.
        - Worked on finding a relevant dataset for the project.
        - Made the relevant visualizations and cleaned up the dataset to fit the project's needs.
        - Worked on the powerpoint slides for the final presentation.
    - Sharif Safwan Hossain
