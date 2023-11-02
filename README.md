# interaction analysis
 Performing interaction analysis for covid-19 data in the year 2022 for Texas state
 ## Motivation
Age can be a significant predictor of health outcomes, and unemployment can have an impact on an individual's economic well-being. I wanted to determine if unemployment and old age have an impact on people's well-being by analysing the connection between age and unemployment with the deaths per counties due to covid in the year 2022.As a native of India, I witnessed how unemployment during the covid shutdown led to the deaths of many people, and how age also had a large role in the deaths of people in India.
 I wanted to investigate how unemployment and age affected people in the United States, particularly in Texas, which has the most counties and is the second most populous state in the country.
 As a result, my first project focuses on how age and unemployment effect death due to covid in 2022 for all 254 counties in Texas.


## Summmary
### Analysis 1
I began by assigning my measurements and factors from the data set that I obtained after cleaning and organizing my data from the raw data sets provided, and my first linear analysis for mean deaths and unemployment used my condition for unemployment to be greater than or equal to 3.8% as it is the average unemployment rate in the US, and we see that more than half of the counties in Texas have unemployment rates that are higher than the national average.After assigning and performing OLS regression, we notice that the P-value is 0.95, corresponding to a slope and 0 for intercept. As a result, we can conclude that unemployment has very little influence on deaths in counties.


<p align="center">
  <img src="https://github.com/shesitherreddy/interaction-analysis/blob/main/unemployment%20vs%20death%20-%20with%20reg.png" width="350"><br>
  <img src="https://github.com/shesitherreddy/interaction-analysis/blob/main/unemployment%20vs%20deaths%20summmary.jpeg" width="500">
</p>

### Analysis 2
Similarly I analysed my second factor age with mean deaths and i used my condition to be for age groups above 40 since most number of deaths till date due to covid is seen in people who are 40 plus in US.After assigning and performing OLS regression,we see that P-values for slope and and intercept to be zero. As a result, we can conclude that age has very highh influence on deaths in counties.


<p align="center">
  <img src="https://github.com/shesitherreddy/interaction-analysis/blob/main/age%20vs%20death%20-%20with%20reg.png" width="350"><br>
  <img src="https://github.com/shesitherreddy/interaction-analysis/blob/main/age%20vs%20deaths%20summary.jpeg" width="500">
</p>


### Interaction analysis
Finally I performed interaction analysis taking my two condiyions in to account we see that after assigning and performing OLS regression we see the P-values to be varying and in the model summary we get to know that P-values for the constant and x1 which is my age have shown to be a good fit for my data but for the unempolyment and interaction terms did not show us th industrial standard values in P. So finally we can conclude that my factors do not interact with each other.

<p align="center">
  <img src="https://github.com/shesitherreddy/interaction-analysis/blob/main/interaction%20summary.jpeg" width="500">
</p>



