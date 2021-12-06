# ml_final_project

ML_Final_Project_Logan - the notebook Logan has done all data cleaning, exploration in

histograms folder - contains jpg images of histograms for each of the predictors/response in the regression

covid-variants-area.csv - the raw variant data set

owid-covid-date.csv - the rae covid dataset

vaccinations.csv - the raw vaccination dataset

full.csv - covid-variants.csv + owid-covid-date.csv + vaccinations.csv joined into a single dataset by date & iso_code

df_averaged_by_month.csv - the rows of full.csv averaged and collapsed into single monthes

df_most_recent_day - the rows of full.csv corresponding to the most recent observation for each country

df_november_2021 - the rows of df_averaged_by_month.csv corresponding to november 2021

df_usa_only - the rows of full.csv corresponding to only to iso_code USA

full_biweekly.csv - Drew's dataframe of rows in full.csv with non-na variants data

logan_biweekly.csv - Logan's dataframe of rows in full.csv with non-na variants data

Data_Cleaning&Exploration&LinearRegression.ipynb - Builds on Data_Cleaning&Exploration.ipynb to adjust the imputation (fixes an error) and add linear regression code for new cases and new deaths

All data sets with names appended with "_new" are equivalent to the old data set but with data collected on 12/5/2021