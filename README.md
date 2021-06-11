# About The Project
The project is intended as a training exercise and is about explotation of an Airbnb dataset (specifically related to Sicily) to estimate cost 
distribution for a two weeks holyday trip 

## IMPORTANT - Please note
as Data files where to large to be uploaded on github, user will need to download the data at the following links

http://data.insideairbnb.com/italy/sicilia/sicily/2021-03-27/data/listings.csv.gz: To be extracted and stored as Data\listings_full.csv 

http://data.insideairbnb.com/italy/sicilia/sicily/2021-03-27/data/calendar.csv.gz: To be extracted and stored as Data\calendar.csv 

http://data.insideairbnb.com/italy/sicilia/sicily/2021-03-27/data/reviews.csv.gz: To be extracted and stored as Data\reviews_full.csv'

http://data.insideairbnb.com/italy/sicilia/sicily/2021-03-27/visualisations/listings.csv: To be extracted and stored as Data\listings_short.csv 

http://data.insideairbnb.com/italy/sicilia/sicily/2021-03-27/visualisations/reviews.csv: To be extracted and stored as Data\reviews_short.csv'

http://data.insideairbnb.com/italy/sicilia/sicily/2021-03-27/visualisations/neighbourhoods.csv: To be extracted and stored as Data\neighbourhoods.csv

The notebook presumes that all data, unzipped as csv files, are made availabble in a subdirectory named "Data"
Notebook 1

## Prerequisites

The software uses the following libraries: 
- numpy
- pandas
- matplotlib
- sklearn
- seaborn 
The software also assumes that the used airbnb dataset is stored in a subdirectory named "Data"

## Usage

The project consists of two python notebooks. The first one "Airbnb Sicily - Notebook 1 - Understanding data set" is intended to explore the
contesnts of the different files downloaded from Airbnb repository. The second "Airbnb Sicily - Notebook 2 - Questions and analysis" instead include the actual data analysis and the proposed outcomes.

## Roadmap

The project is an intial stage. Possible additiona step could include exploitation of files not used so far, specifically textual review and the info in the calendar file.

## License

Free to use

## Contact

roberto.paglino@gmail.com

## Project Link: 

https://github.com/rpaglin/UdacityNanodegreeAirbnb
