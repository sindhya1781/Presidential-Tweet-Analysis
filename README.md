# Presidential-Tweet-Analysis using NLP
This repository consists of code written in R to analyze tweets by Donald Trump to understand the key words used by him over time alongside their impact on the number of retweets received on his Tweets. 

Source Data - 
https://www.thetrumparchive.com/

Libraries Used - 
- tidyverse
- tidytext
- tokenizers
- stringr
- glmnet

Models Used - 
Sparse Regression Model using glmnet package alongside Cross-Validation to select the sparsity parameter lambda

Min Lambda Noted - 218.8954

Results - 
1. #fnn has the highest positive coefficient noted that impacts retweets
2. Some other key terms noted here are photographs, quarantine, nuclear in the top 20 coefficients that positively impact retweets
