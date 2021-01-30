# vacant-land-pricing-model
<BR>
ABOUT THIS PROJECT<BR>
This project is being prepared as part of my Dartmouth Professional Certificate in Applied Data Science program for the 2020-2021 session. I've made this project open to the public on Github because I want to eventually share the results and methods performed with the open source Python / Data Science community. The aim of this project is to analyze a Redfin dataset (.csv) of all the land-only (vacant, non use-specific) real estate transactions in Garland County, AR in the five year period ending in December 2020 to ultimately find an alternative method for creating a pricing model in the absence of typical metrics. <BR>

Unlike a typical linear regression analysis of real estate using housing features such as number of bedrooms, bathroom, off-street parking ...etc. In Phase 1 of this project, I seek to perform a K-Means cluster analysis of transaction prices (in price per acre) by geodetic coordinates only. The hypothesis is that for vacant land, other features such as those for typical residential regression models are not applicable, and clustering by geographic coordinates removes arbitrary town/city boundaries and has the (potential) capability to identify particular subdivisions that are worth more or less than nearby similar properties. <BR>

Next, in Phase 2, this project will seek to impute other variables into the dataset from non-Redfin sources that are hypothesized to contribute to the variance in the target value (price per acre). It is yet TBD which variables will be imputed as some of this may be determined by the availability of open-source and free API's to be integrated into this project; however, I am initially considering the imputation of proximities to nearby landmarks (distance to nearest elementary school, middle/junior high school, high school, gas station, mall, interstate exit, hospital etc.) as well as grouping by the present municipal zoning of each observation (grouped into one of three best fitting descriptions: residential, industrial, commercial retail). Finally, demographic data (if readily available) from the U.S. Census Bureau American Community Survey or other potential data sources may be added to provide a diversified range of variables of which to perform regression analyses. In Phase 2, a regression model will be prepared relating the target (y) data to the multiple variables identified in this paragraph. <BR>

In Phase 3, I will seek to combine results from the two different models uniquely prepared in Phase 1 and Phase 2 and attempt to make one model that maximizes the accuracy of the predicted values using a weighted index (much like a linear regression on each respective model's output) vs. a cross-validated test set.

I welcome any suggestions on ways to perform the above tasks. However, I must also be up front in that I am performing this project for academic credit, and I will need the work to be my own at least until I have completed the Dartmouth program, which will be around the end of April 2021.

<BR>
DATA<BR>

<BR>
PYTHON JUPYTER NOTEBOOKS<BR>


<BR>
