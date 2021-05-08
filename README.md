# Correlation between COVID-19 and mobility.

## What
Assessment of the correlation between intercity human mobility (flow) and COVID-19 cases in Brazil.

## Why
To try to understand factors that impacts on the spreading of the virus or increase/decrease in the number of cases.
## How
Comparing both variables with the help of vizualizations (scatter plots) and statistical tools. 

The assessment was made with 2 different approaches:

*  Considering total Covid-19 cases.
*  Considering Covid-19 cases per 100,000 inhabitants.

in each of these aproaches, it was used 3 different geographical scales:

* Municipal scale, where each instance is a city and considers all cities of Brazil.
* State scale, where each instance is a state and considers all states of Brazil.
* Municipal scale, where each instance is a city and considers the cities of each state of Brazil.

## Results

* When using the first approach (i.e considering total cases for COVID-19), there was a high positive correlation between mobility and COVID-19 cases for all scales.
* When using the second approach (i.e considering the cases per 100,000 inhabitants), there was little or no correlation between mobility and COVID-19 cases for all scales.

But since in both approaches we are using COVID-19 data, why are the results so different? Since approach one shows a high correlation between both variables, can we say that a high intermunicipal flow causes COVID-19 cases to rise? The answer is NO. At least with this data.

This is due to a very known principle in statistics that states that "correlation does not imply causation". When 2 variables X and Y are correlated with each other, there are 4 possible reasons:

* X causes Y.
* Y causes X.
* Neither of them cause each other.
* Another variable C causes both X and Y.

In our case, what happens is the latter. That means that another variable causes both total COVID-19 cases and people's flow to rise, and that variable is the POPULATION. That is why when using approach 2 there was no correlation, because when using the cases per 100k inhabitants we remove the influence of the population.
