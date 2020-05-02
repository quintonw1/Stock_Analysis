# Stock_Analysis

#Challenge 2: Refractoring Code 

The existing code to prepare and analyze various stock data took quite some time to complete. The following improvements were made which significantly decreased the time to execute: 

1. Using arrays to store data instead of re-initializing variables within a loop allows you to reduce the number of total steps within your code. 
2. Since the data was sorted in an alphabetical manner, a statement can be implemented which increases the ticker index once the data for the current ticker was completed. This would completely remove the need for running the outer loop and as a result would allow the entire analysis to be performed within one execution of the inner loop.

