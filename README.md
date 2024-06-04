#  Description of functions in run_analysis.R

The script contains 3 functions:
1. get_data():  This loads and combines the various data sources into a single data frame, keeping the necessary columns (see codebook.md)
2. get_summary(df):  This summarizes the data by activity and subject number
3. write_data_set( name='summary_data.csv' ):  This writes the file to a csv

# Instructions

1. Restart R (the script checks to see if the two dataframes 'clean_df' and 'summary_df' have been previously generated)
2. source(run_analysis.R)

If you wish to run the functions manually, then:
1. df <- get_data()
2. sum_df <- get_summary(df)
3. write_data_set( 'summary_data.csv' )
