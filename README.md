# COVID-19 hackathon

For an entry to the AWS Marketplace Devpost competition, not finished. Takes data from https://github.com/nytimes/covid-19-data/blob/master/us-counties.csv, formats into pandas dataframe, imports and cross-references data from USDA by US county to associate the number of recorded cases and deaths for each US county on certain dates with socioeconomic data from that county. Trains regression models on AWS Sagemaker using S3 and configured endpoints. Originally developed on Sagemaker Studio.


