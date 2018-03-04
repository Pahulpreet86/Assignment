# Assignment
# 1) Stock Prediction Using Regression Model
1) Stock Prediction (Dataset Creation).ipynb                                                                               
  Samsung last 5 year data (from 2013 ) google finance (attributes:Date,Open,High,Low,Close,Volume)               

    additional attributes created:                                                          
     i. Avg _price of day= (low price + high price)/2                                  (independent)                 
     ii. High_change =high price of today - the high price of the previous day       (independent)                       
     iii. Low_change =Low price of today - Low price of the previous day (independent)                                 
     iv. Volume_change = Volume today - Volume previous day                 (independent)                
     v. Open_change = open price of today - the Open price of the previous day (independent)             
     vi. Close_change = close price of today - the Close price of the previous day  (independent)                  
     vii. Tomorrow_Change=open price of next day - close price of today    (target variable/ dependent variable)             

2) Stock Prediction ( Data Processing) .ipynb                                               
  normalize data                                                                           
  find and visualize the correlation                                                         
  Modeling – using backward elimination (remove volume and volume change on the basis of p-value )                  

3) Regression Model and Visualisation of Result.ipynb                                           
  analyze the final dataset (removed volume and volume changed)                                                    
  4 Regression Model analyzed – Multiple Linear Regression, Decision Tree, Random forest, Support Vector Regression       
  Best Regression Model-  Multiple Linear Regression             
  Visualize Result for Multiple Linear Regression                   


# 2) Sentiment Analysis of a Company                                         
    1) Use BeautifulSoup to scrap news of Samsung Electronics Co., Ltd. (005930.KS) from yahoo finance site            
    2) process the tags in the headline to find news specific to Samsung (only)                 
    3) Use TextBlob to analyse and find overall sentiment                                

