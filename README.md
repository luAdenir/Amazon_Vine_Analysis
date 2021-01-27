# Amazon_Vine_Analysis

ETL, SQL, PySpark, Google Colaboratory

## Overview

Perform ETL process and analysis to determine if there are any biases toward favorable reviews from Vine members in Amazon "Home Entertainment" review dataset.

## Results

<img width="670" alt="Screen Shot 2021-01-26 at 9 57 59 PM" src="https://user-images.githubusercontent.com/71112826/105950836-ebbbb000-6023-11eb-992b-01b058244b90.png">

* 261 number of paid reviews.

* 24040 were unpaid reviews or not a part of the vine program.

<img width="669" alt="Screen Shot 2021-01-26 at 10 10 58 PM" src="https://user-images.githubusercontent.com/71112826/105950847-efe7cd80-6023-11eb-9352-41c0cae0b20b.png">

* 11,005 or 45% were five star reviews. 

* 46%  of Vine reviews were 5 stars.

* 45% of unpaid reviews were 5 stars. 

## Summary

Amazon Home Improvement reviews dataset was used for this analysis. Reviews that are at least 20+ votes and at least 50% of helpful votes were filtered. Out of these votes 24040 were unpaid and 10,818 were 5 stars. 261 reviews were part of the vine program. 24040 unpaid vs 261 paid, I think it is safe to conclude that there is a very low possibility of biases in this review dataset. To explore and do analysis on the rest of the "star ratings" might be very helpful for a better interpretation and more accurate conclusion.

<img width="778" alt="Screen Shot 2021-01-26 at 11 23 44 PM" src="https://user-images.githubusercontent.com/71112826/105957147-a9976c00-602d-11eb-9ad3-2b0c44ea5124.png">
