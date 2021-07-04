# Starbucks-Promotions-Capstone-Project
The capstone project to complete my Udacity Data Scientist nanodegree programme

## Libraries used
This project required use of the following libraries
* pandas - for data analysis, cleaning, transforming
* numpy - for working in arrays and mathematical functions
* json - for reading the json input files
* matplotlib - for data visualisations, mainly histograms to explore the distribution of data
* sklearn - scikit-learn being one of the primary libraries for machine learning models


## Motivation
This capstone project for my Udacity Data Scientist nanodegree programme gave me the opportunity to demonstrate my skills and experience with applying machine learning solutions to real business problems.  Selecting which promotions to send to certain customers is a very real problem faced by many businesses and Starbucks is an excellent case study for this - with data that can be used to measure the response in previous promotional periods.


## Files
* Starbucks_Capstone_notebook.ipynb - this is the main Jupyter notebook containing all the code and models as well as commentary and visualisations
* data/portfolio.json - the file with the details of each individual offer
* data/profile.json - the file with details of 17,000 members
* data/transcript.json - this is the main 'events' file with over 300,000 rows containing all the transactional data and the data about when an offer was received, viewed and completed


## Summary of results
The outcome of this analysis is a Random Forest Classifier model that predicts whether a customer is likely to respond to a particular offer with a 75% accuracy.  This would be of benefit to Starbucks as it would improve the relevance of offers that are sent.

## References
This project was helped enormously by the excellent resources provided in the Udacity Data Scientist nanodegree programme.  I also used many of the library documentation resources to assist with the coding (e.g. www.scikit-learn.org).  Wherever I used stackoverflow or similar community sites to solve problems I have provided a link in the Jupyter notebook.