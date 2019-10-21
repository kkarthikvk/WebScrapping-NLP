# WebScrapping-NLP
Webscraped flipkart realme 5 pro reviews using beautifulsoup package and did NLP  to predict Ratings
Find the Co-Relation between Ratings and Reviews 
BRIEFLY:
         1.From flipkart page i have taken the reviews of realme 5 pro phone . 
         2.In which each review is in one page so we have to take the url separately for each page and parser each page .
         3.After parsing into the page . Collect all the information in one variable and access the information by finding the root 
           class.
         4.After finding the root class . Using loop statement try to find the information hidden inside the class by giving index value
           to the stored variable. 
         5.Then collect all the data that are all necessary i have scraped reviews and rating to find the co-relation between them . 
         6. We do all preprocessing steps to convert sentence into numeric , So that our model could perform.
         7.NLTK preprocessing steps:-
                     (i). Tokenization using re
                    (ii).Converting into lowercase
                   (iii).Removing numbers and Punctuations using string
                    (iv).Stemming using PorterStemmer
                     (v). Vectorization using sklearn.TfIdfvectorization
         8.Used GradientBoostingClassifier to predict the Ratings


NOTE:-
          only scraped 3 pages and trained the model with less number of data . So , got accuracy of 99% for training and 67% for testing           set . If we have more data we could get more accuracy. 
        
