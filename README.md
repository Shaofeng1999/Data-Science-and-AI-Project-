# Data Science & Artificial Intelligence Project- Exploratory Data Analysis on Movie Datasets


** Apologies that the front part of the ipynb file is mainly the extracted datasets. Please scroll further down to see the code. Running the file on Jupyter will give a clearer picture.  
## **Information**:  

1. Came out with our own questions:  
   a) Does release date affect revenue?  
   b) Does larger budget correlate to higher revenue?  
   c) Does movie runtime affect revenue?   

2. Extracted 2000 Movie Datasets from 2015-2019 using Postman from TMDB and clean the extracted data to suit the questions above
   
3. Use exploratory data analysis and statistical visualisation on revenue, runtime, profit and budget to gain relevant insights (Boxplots, Violin plots, Histogram, Pair Plots, Bar Charts)

4. Use Machine Learning techniques: Bayesian Linear Regression Model and Random Forest Classification tree  

## **Answering the 3 questions**:  


### 1. Release Date vs Revenue: 
#### a) Sort movies by month of release date using colour-indicated bar graph:  
     (i) Findings: More movies were released in the month of September   
     (ii) Reason: School Holiday Period, hence it is better for producers to release movies to earn more revenue as more people have free time to watch movies  
#### b) Sort revenues by month using colour-indicated bar graph:      
      (i) Findings: The highest revenue earned did not coincide with the most number of movies released for that month.    
      (ii) Reason: Although most movies were released in September, there were some very popular movies like "Avengers: Endgame" that was released in April and significantly pulled up the revenue for April.    


### 2. Budget vs Revenue:
#### Used machine learning technique: Bayesian Linear Regression Model 
    (i) Findings: R^2 = 0.533 on our test data. This was quite surprising as we thought that higher budget will give rise to higher revenue  
    (ii) Reason: Some film producers may spend a lot of money to hire high-profile actors but the movie plot may be dull, resulting in poor ticket sales and thus lower revenue  
    
### 3. Runtime vs Revenue:
#### a) Sort movies runtime into two categories type, runtime less than 100 mins and runtime more than 100 mins  
#### b) Built a single decision tree and used Random Forest Regression to generate 100 classification trees and obtained average result from the various trees.  
        (i) Findings: Classification Accuracy = 0.748. The movie runtime data were well-classified and correctly predicted the revenue  

     
     
     
     
