Included files


final_dataset.csv: dataset called upon by my models.


final_model.Rmd: 
Main model using MCMC and simple linear regression.


Second model I compared to my first. It uses lasso-regression and includes interaction
terms.
final_model.nb.html


Original Dataset folder
        Cleanup.Rmd: all of the code used to compile the different sources into one dataset
                Cleanup.nb.html
        All original dataset files





________________


The data comes from several different sources and was compiled together by me. 


Demographic data 
U.S. Census Bureau. "ACS Demographic and Housing Estimates." American Community Survey, ACS 1-Year Estimates Data Profiles, Table DP05, 2022, https://data.census.gov/table/ACSDP1Y2022.DP05?t=Age and Sex&g=010XX00US$5000000. Accessed on December 16, 2023.


This dataset show demographic profiles by congressional district, with estimates and projections, based on survey results. I took only the sex and age data from this. 


Margins 
https://ballotpedia.org/United_States_House_of_Representatives_elections,_2022#Margin_of_victory


This shows margin of victory of each race in 2022. 


Partisan voting index and status
https://en.wikipedia.org/wiki/2022_United_States_House_of_Representatives_elections#Arizona


The partisan voting index (PVI) is made by Cook Political Report, but I found it in table format on wikipedia. Here is how Cook describes it on there website (https://www.cookpolitical.com/cook-pvi): 


“The Cook PVI measures how partisan a district or a state is compared to the nation as a whole. 


A Cook PVI score of D+2, for example, means that in the 2016 and 2020 presidential elections, that district performed an average of two points more Democratic than the nation did as a whole, while an R+4 means the district performed four points more Republican. 


Whereas race ratings reflect our outlook for which party will win the next election in each state and district, PVI values take a longer view and seek to measure the underlying partisanship of each district relative to the nation as a whole.“