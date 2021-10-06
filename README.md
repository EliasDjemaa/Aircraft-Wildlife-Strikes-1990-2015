# Aircraft-Wildlife-Strikes-1990-2015

## FAA Dataset
A dataset sourced from the U.S. Federal Aviation Administration (https://wildlife.faa.gov/). This dataset stores data on animal and aircraft collisions recorded from 1990-2015. The dataset includes information on specefic species of wildlife that have collided with an aircraf, as well as information on the aircraft involved in the collision (such as which part of the aircraft may have been damaged upon strike).

### Importing Data
To begin our path of exploring this dataset I began by importing the data contained within the external .CSV file within a dataframe named awsDF (Aircraft Wildlife Strikes DataFrame).

``` 
aws_ = pd.read_csv('database.csv', low_memory=False) 
awsDF = pd.DataFrame(aws_) 
```

