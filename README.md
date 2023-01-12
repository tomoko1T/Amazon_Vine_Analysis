# Amazon_Vine_Analysis

## Overview of the analysis: 

The analysis was conducted to review Amazon reviews written by members of the paid Amazon Vine program.  The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products.  The requirement of Amazon Vine members is to write a reveiw, thus the purpose of this research is to determine if there is any bias of Vine Reviews.  The datasets of the Musical Instrument reviews were chosen for this analysis, and there are two parts as follows.   

Analysis 1: Perform ETL on Amazon Product Reviews
By using PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.

The analysis code is found [GitHub Pages](https://github.com/tomoko1T/Amazon_Vine_Analysis/blob/main/Amazon_Reviews_ETL.ipynb)

Analysis 2: Determine Bias of Vine Reviews
PySpark was used to determine if there is any bias reviews from Vine members

The analysis code is found [GitHub Pages](https://github.com/tomoko1T/Amazon_Vine_Analysis/blob/main/Vine_Review_Analysis.ipynb )

## Results: 

- How many Vine reviews and non-Vine reviews were there?

    Vine reviews: 59      Non-Vine reviews: 13,480

    ![This is an image](https://github.com/tomoko1T/Amazon_Vine_Analysis/blob/main/images/totalno_paid.png)
    
    Total number of vine reviews

    ![This is an image](https://github.com/tomoko1T/Amazon_Vine_Analysis/blob/main/images/totalno_unpaid.png) 
    
    Total number of non-vine reviews

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

    Vine reviews: 34      Non-Vine reviews: 7,678 
 
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

    Vine reviews: 58%     Non-Vine reviews: 60 %  

## Summary: 

According to the results, there is no positivety bias for review in the Vine program.  Although the number of reviews from Vine program is much lower than the one from the non-vine program, the percentage proves no bias on the reviews.  The percentage of reviews with 5 stars on both programs are almost equal, 58 % for Vine program customers and 60 % for non-Vine program customers.   

The additional analysis I would conduct is on the reviews with 1 star.  If there is bias on the vine program, the percentage of negative reviews might be low compared to the one from the non-vine program. 
 
