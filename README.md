# Home-Price-Forecasting
The purpose of this project is to build the best model which predicts the future sales of Real Estate Market in California State by using the historical home sales Zillow data and the other dependent variable Fed interest rate data which contributes to sales. 

This enables the customers to invest on the properties where they can get the best ROI. It also helps the Real estate investment firms to invest on the expansion of residential homes based on ROI. The project uses time series to develop the models and fit the models using test data and identify the best model for future use. We used SARIMA (Seasonal Autoregressive integrated moving average) without dependent variables, SARIMA with dependent variables and FB Prophet with and without additional variables, LSTM (Long Short-term Memory) and calculated the RMSE of all the 5 


# Interpreting the Results:
• Based on 3 years return on investment and 5 years return on investment, the 5 zip codes stand out to be the best area to invest in. 94124, 94121, 94122, 94110, 94134 are good places to invest, but there could be some risk if we look at the lower side of ROI. However, the average ROI for 3 years is between 35 to 39%, similarly 5 years average return on investment is between 59 to 65% in these zip codes.
• Zip code 94124 risk of decreasing in price both 3 year and 5 years also they have high chance of getting profit to compare others too. This location is close to the coast and close to many public parks. So, this place is the best place to invest. The value of properties also depends on other factors such as development, facilities around the neighborhood and transportation.
• 94124: SFO County (3Yr ROI: -6% to 85%; 5Yr ROI: -31 to 161%)
• 94121: SFO County (3Yr ROI: 4% to 70%; 5Yr ROI: -1% to 127%)
• 94122: SFO County (3Yr ROI: 5% to 67%; 5Yr ROI: -4% to 127%)
• 94110: SFO County (3Yr ROI: 0% to 71%; 5Yr ROI: -13% to 134%)
• 94134: SFO County (3Yr ROI: 0% to 69%; 5Yr ROI: -13 to 133%)

# Next Steps:
Next steps are to remove outliers and evaluate SARIMA without any additional variables to observe if there will be any improvement. Next is instead of Dept and Markdown 3 as additional variables try different combinations and compare MSE and find the lowest MSE combination.
 
 • Consider using more additional variables, for example school district, public safety, size of the house, number of rooms.
• Get the latest data and compare our forecast with real time data from 2019 to 2021.
• Deploying a predictive model as an API
• Django and flask are two popular ways to deploy predictive models as a web service
• Calling predictive models using a URL from any front end like Tableau, Java or Angular JS
