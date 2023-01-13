# Module_17_Challenge

## Overview of the analysis: Explain the purpose of this analysis.


In this challenge I used Pyspark to complete the ETL process. We used pyspark to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and connect to the database that was generated through AWS. 


## Results: 

Using bulleted lists and images of DataFrames as support, address the following questions:

### How many Vine reviews and non-Vine reviews were there?

In total we had 4,291 vine reviews in the dataset, and 40,471 non-vine reviews 


### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

 In this dataset there were 15,711 5-star reviews total, 15,663 of which are non-vine reviews. 


### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

38.2% of the five star reviews were vine
38.9% of the five star reviews were non-vine

![proj1](https://user-images.githubusercontent.com/69175360/212231003-2b9ac3d2-dcd5-4c5e-a3c0-3fe20c80d3f3.JPG)


![proj2](https://user-images.githubusercontent.com/69175360/212231014-824bf426-21aa-4bec-96a4-57e11d4c1f98.JPG)


![proj3](https://user-images.githubusercontent.com/69175360/212231020-3f54c067-30aa-4c01-b692-f7e9cadeb5e7.JPG)



### Summary:

After our analysis was complete we can determine that there does not appear to be any sort of positivity bias because the percentages of the reviews above are both hovering around 38%. 
