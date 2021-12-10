# ml_final_project

1. Data:
    1. country_vaccine_release_dates.csv: Gwenyth pulled this for knowing when vaccines came out. Use for informed imputation.
    2. covid-variants-area.csv - the raw variant data set
    3. df_averaged_by_month.csv - the rows of full.csv averaged and collapsed into single monthes
    4. df_most_recent_day - the rows of full.csv corresponding to the most recent observation for each country
    5. df_november_2021 - the rows of df_averaged_by_month.csv corresponding to november 2021
    6. df_usa_only - the rows of full.csv corresponding to only to iso_code USA
    7. full.csv - covid-variants.csv + owid-covid-date.csv + vaccinations.csv joined into a single dataset by date & iso_code
    8. full_biweekly.csv - Drew's dataframe of rows in full.csv with non-na variants data
    9. logan_biweekly.csv - Logan's dataframe of rows in full.csv with non-na variants data
    10. owid-covid-data.csv - the raw covid dataset
    11. vaccinations.csv - the raw vaccination dataset
    12. biweekly_imputed.csv - imputed data to be used in regressions
    13. biweekly_train_imputed.csv - imputed training data to be used in regressions
    14. biweekly_test_imputed.csv - imputed testing data to be used in regressions
2. DataCleaning_Exploration: explores missing data, organizes many csv files by area and time. Imputes data.
3. LinearRegressions: Performs Linear Regressions on deaths & cases for imputed data
4. histograms folder - contains jpg images of histograms for each of the predictors/response in the regression
5. GLMs: Notebook for generalized linear regressions. Current model is preliminary, will be updated

All data sets with names appended with "_new" are equivalent to the old data set but with data collected on 12/5/2021
