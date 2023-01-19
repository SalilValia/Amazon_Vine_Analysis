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

The Total amount of Vine reviews that non-members didnt pay for was 15,663

