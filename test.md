---
layout: page
title: Test
permalink: /projects/Test
---

### [Soothsay: NYC Real Estate Appreciation Value Forecaster](https://github.com/gfsoileau/soothsay)

Searching for a home or apartment in the NYC real estate market is cruel, daunting and pricey. Soothsay is an attempt to help narrow your search by finding neighborhoods with the best appreciation potential. It seeks to find neighborhoods on the cusp of gentrification, buy low / sell high. To find these neighborhoods, I used approximately 9 years of real estate data, Google search term volume and mentions in the NY Times Real Estate section, aggregated into monthly buckets.

I used vector autoregression (VAR) to model my three time series, median price, google trends, nytimes mentions. The results of the prediction were then used to color a D3 choropleth map of every neighborhood in New York City. Happy house hunting!

https://github.com/gfsoileau/soothsay

### [Movie Seasonality](https://github.com/gfsoileau/Seasonality)
OLS regression was used to predict changes in movie revenue when a specific genre of movie is released "out of season”. For example, calculate the total predicted domestic revenue of an action film, with a stated budget if it released in May, August and December. Hint: it will earn much more in May!

https://github.com/gfsoileau/Seasonality

### [Marketing](https://github.com/gfsoileau/Mcnulty)

With this project I predicted the outcome of a targeted marketing campaign using depositor demographics and macroeconomic factors provided by a bank. I compared several models including: SVG, Decision Tree, K-nearest Neighbors, GaussianNB, Random Forest and Logistic Regression. I built a function that tuned each model by trying several parameters and logging the results. 

https://github.com/gfsoileau/Mcnulty



