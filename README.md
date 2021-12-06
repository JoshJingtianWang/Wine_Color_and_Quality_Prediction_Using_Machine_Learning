# Wine_Color_and_Quality_Prediction_Using_Machine_Learning
I set out to study whether several chemical characteristics such as acidity, sugar and pH can be used to predict the color (White/Red) and Quality (1-10[int]).
Decision Tree classification technique was found to reliably predict the Color dependent variable at 99% accuracy. It was found that ‘TotalSulfurDioxide’ and ‘Chlorides’ were the two most input variables that of this model.
Linear regression was used to predict the Quality dependent variable. After testing several input variables using the scatter plot, ‘FixedAcidity’, ‘VolatileAcidity’, ‘Alcohol’ were selected as the input variable for linear regression and R-squared value was 0.26.
In conclusion, chemical characteristics of wine can be used to reliably predict the color of the wine, but not the quality.

Wine drinking is becoming available to more and more people with diverse socio-economic backgrounds in recent years. Wine type (color: White/red) and quality determination is an important step in the wine industry, however, the assessment of those two properties usually requires human experts, which can be expensive. Here we are using machine learning models to predict the color and the quality of wines.
### Business Understanding
Using machine learning to determine the color and quality of wine could be a way to increase the production speed and reduce the cost for a wine company. 
### Data Understanding
Multiple chemical characteristics of wine has been collected, structured and deposited onto the UCI machine learning repository. The data used here is a 13-column dataset with 6496 entries.
### Data Preprocessing
The data has been cleaned and structured into .xlsx format prior to this analysis. The input variables are: 'FixedAcidity', 'VolatileAcidity', 'CitricAcid', 'ResidualSugar', 'Chlorides', 'FreeSulfurDioxide', 'TotalSulfurDioxide', 'Density', 'pH', 'Sulphates', 'Alcohol'. The dependent variables are 'Quality[DV]', 'Color[DV]'.
