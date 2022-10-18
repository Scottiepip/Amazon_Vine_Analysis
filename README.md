# Amazon_Vine_Analysis

## Overview:
The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

 Our task is to use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Then we will use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. 
 
## Results:
![image](https://user-images.githubusercontent.com/108709071/196334228-0cff8c50-450a-4ffe-a8b2-017140b0bee9.png)
 
There are total 94 Vine reviews.

![image](https://user-images.githubusercontent.com/108709071/196334486-4954c9f9-48d4-4071-a6e5-f3c0e9549b60.png)
 
Among the 94 Vine reviews, 48 are 5-star reviews.

![image](https://user-images.githubusercontent.com/108709071/196334582-12f7a8bf-a890-408e-a72e-f245ceb60060.png)

51.06% of the Vine reviews are 5-star review.

![image](https://user-images.githubusercontent.com/108709071/196334678-52d06204-850d-4b01-8094-2ad56d7ab4c1.png)

There are total 40,471 non-Vine reviews.

![image](https://user-images.githubusercontent.com/108709071/196334747-3fd06885-7b01-47a5-b2c0-276872e34cde.png)

Among the 40,471 non-Vine reviews, 15,663 are 5-star reviews.

![image](https://user-images.githubusercontent.com/108709071/196334878-29ce9534-9c1f-4aeb-baf5-f6ead66872c1.png)

38.70% of the non-Vine reviews are 5-star review.

## Summary:
