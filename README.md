# ETL-challenge
This ETL Project consists of two data sets, one from https://catalog.data.gov/dataset/nypd-complaint-data-current-year-to-date, which entails NYPD-complaint-data and the other from https://public.opendatasoft.com/explore/dataset/us-zip-code-latitude-and-longitude/table/ which entails US zipcode latitude and longitude. We decided to use two months(July and December) and two years(2019, 2020). We choose July and December as our months because we wanted to use a summer month and a winter month. Since the NYPD-complaint-data doesn't provide the zip code in its data set, we choose to inner join the US zipcode latitude and longitude to map the zipcodes to the NYPD complaints. By rounding the latitude and longitude numbers by two on the NYPD complaint data, it gave it more significant results when joining the US zipcode latitude and longitude data.