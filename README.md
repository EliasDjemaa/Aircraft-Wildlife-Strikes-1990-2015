# Aircraft-Wildlife-Strikes-1990-2015

## FAA Dataset
A dataset sourced from the U.S. Federal Aviation Administration (https://wildlife.faa.gov/). This dataset stores data on animal and aircraft collisions recorded from 1990-2015. The dataset includes information on specefic species of wildlife that have collided with an aircraf, as well as information on the aircraft involved in the collision (such as which part of the aircraft may have been damaged upon strike).

### Importing Data
To begin our path of exploring this dataset I began by importing the data within the external .CSV file into a dataframe named awsDF (Aircraft Wildlife Strikes DataFrame).

``` 
aws_ = pd.read_csv('database.csv', low_memory=False) 
awsDF = pd.DataFrame(aws_) 
```

### Previewing Data
In order to examine and understand the current status of the data which is being imported I breifly previewed the first and last four 'rows' of the data frame. This is so that any missing/unknown values can be handled prior to any attempt of manipulating the data.
```
awsDF.head()
```
