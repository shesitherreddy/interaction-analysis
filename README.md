# Interaction analysis project 1
 Performing interaction analysis for covid-19 data in the year 2022 for Texas state
 ## Motivation
Age can be a strong predictor of health outcomes, and unemployment can have an impact on a person's financial well-being. I wanted to see if unemployment and old age have an affect on people's well-being by analyzing the relationship between age and unemployment and the number of deaths from covid in each county in 2022.As a native of India, I watched how unemployment during the COVID-19 shutdown resulted in the deaths of many people, and how age played a significant role in the deaths of people in India.
 I wanted to look into how unemployment and age affected people in the United States, particularly in Texas, which has the most counties and is the second most populous state in the nation.
 As a result, my first project focuses on how age and unemployment effect death due to covid in 2022 for all 254 counties in Texas.


## Summmary
### Analysis 1
I started by assigning my measurements and factors from the data set that I obtained after cleaning and organizing my data from the raw data sets provided, and my first linear analysis for mean deaths and unemployment used my condition for unemployment to be greater than or equal to 3.8%, which is the average unemployment rate in the US, and we see that more than half of the counties in Texas have unemployment rates higher than the national average.After assigning and running the OLS regression, we see that the P-value is 0.95, which corresponds to a slope and 0 for an intercept. As a result, we can conclude that unemployment has negligible influence on county-level deaths.


<p align="center">
  <img src="https://github.com/shesitherreddy/interaction-analysis/blob/main/unemployment%20vs%20death%20-%20with%20reg.png" width="350"><br>
  <img src="https://github.com/shesitherreddy/interaction-analysis/blob/main/unemployment%20vs%20deaths%20summmary.jpeg" width="500">
</p>

### Analysis 2
Similarly, I analyzed my second component age with mean deaths, and I set my condition to be for age groups over 40 because the majority of deaths caused by covid in the United States have occurred in adults over the age of 40.After assigning and doing OLS regression, we find that the P-values for slope and intercept are zero. As a result, we can conclude that age has a significant impact on fatalities in counties.


<p align="center">
  <img src="https://github.com/shesitherreddy/interaction-analysis/blob/main/age%20vs%20death%20-%20with%20reg.png" width="350"><br>
  <img src="https://github.com/shesitherreddy/interaction-analysis/blob/main/age%20vs%20deaths%20summary.jpeg" width="500">
</p>


### Interaction analysis
Lastly, I conducted interaction analysis. Taking my two conditions into account, we can see that after assigning and performing OLS regression, the P-values vary, and in the model summary, we can see that the P-values for the constant and x1, which is my age, are a good fit for my data, but the unemployment and interaction terms do not show us the industrial standard values in P. So, eventually, we can say that my factors do not interact with one another.

<p align="center">
  <img src="https://github.com/shesitherreddy/interaction-analysis/blob/main/interaction%20summary.jpeg" width="500">
</p>



