# Amazon_Vine_Analysis
 module 17

## Overview
The purpose of this module was to analyze the Amazon Vine program and to see if there was any bias in reviews made by the Vine members. In this analysis we used PySpark to perform the ETL process and to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics. I decide to focus on the U.S reviews for video games since I enjoy and play a lot of video games growing up and still on my free time.

## Results
Total number of Vine reviews that was paid we had is 94

![image](https://user-images.githubusercontent.com/111409181/213398281-64d7694e-0c9b-40f5-a095-76fc33c083ec.png)

Then the Total number of Non-Vine reviews that went unpaid was 40,471

![image](https://user-images.githubusercontent.com/111409181/213399009-893bae68-c93c-41ca-b7b8-897ec0539740.png)

Now we will take a look at the 5-star reviews.

Total amount of Vine reviews that were 5-stars is 48

![image](https://user-images.githubusercontent.com/111409181/213400027-11b74723-1b96-4ffc-84ef-ce7a4e788805.png)

The Total amount of Vine reviews that are non-members didnt pay for what was 15,663

![image](https://user-images.githubusercontent.com/111409181/213401065-cb7a56ee-a047-4833-bfb5-1ba5329427f4.png)

Finally we have the percentages of the 5-star reviews for Vine members and non-members. 

![image](https://user-images.githubusercontent.com/111409181/213401782-e0b9e943-022e-439a-aa7d-da7552b0a338.png)

The first pic was the Vine reviews percentage of 51.06

![image](https://user-images.githubusercontent.com/111409181/213402592-e5461dcf-c0ab-4854-9589-e9894718de18.png)

This second pic shows the percentage of non-Vine members having 5-start reviews. The percentage was at 38.7

## Summary 
This results show that 51.6 percent of the Vine program had 5-star reviews while for the non-Vine reviews still had about 38.7 percent.
This clearly shows the Vine members tend to give out 5-star reviews and be more bias in a more positive way. One additional analysis we can do is to get the statistics of the data set by getting the mean, median, and mode of each star rating. 




