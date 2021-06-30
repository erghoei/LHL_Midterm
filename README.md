# LHL_Midterm
Midterm NYC neighborhood clustering with Meghan Pick

### Data Preparation
In the Data_Preparation folder contains all of the raw data as well as several checkpoints made as csv files.
Notebooks are titled as "data conversion.ipynb" with their respective data in file names to represent which data files were converted for use.
These notebooks contains the methods used to convert and clean the data.

The final data is the "nyc_data.csv" file which contains:\
    -name (of NYC neighborhood)\
    -longitude\
    -latitude\
    -uber_count (how many times an uber service was called for in the neighborhood)\
    -avg_price (of restaurants in the neighborhood)\
    -adj_pop (population of neighborhood, adjusted from original data for compatibility to our data)\
    -median_daily_test_rate (of covid testing rate in neighborhood per 100000 people)\
    -avg_test_score (the average test score of elementary schools within the neighborhood)

### Model Set Up
The model_set_up folder contains the final data for use (nyc_data.csv) as well as notebooks used to attempt to model our algorithm.
For modeling, K-means clustering, hierarchical agglomerative clustering, and DBScan were all tried and tested to make a model.

The results of our testing in fitting a model proved that K-means clustering provides the best separation in creating clusters.

