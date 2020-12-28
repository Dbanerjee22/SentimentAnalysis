# SentimentAnalysisREADME
This neural network will take a incident of amazon employees memory of what makes them happy and categorized them into 7 segments.
"affection": 0, "exercise" : 1, "bonding" : 2,"leisure" : 3,"achievement" : 4,"enjoy_the_moment" : 5,"nature" : 6
Steps to perform this task:
1.	we convert the category from alphabet to number.
2.	First, we need to clean the data because weather the alphabets are in Upper Case or lower won’t help us in prediction. Similar for punctuation and special character.
3.	We need to find all the unique words in the text and tokenized it.
4.	Make all the sentence length same by making all the sentence length of the highest sentence by padding the data.
5.	I used F1 score to find accuracy because the count of different category is significantly different so by using F1 score as measure we will get better idea of the accuracy.
6.	I used a LSTM model because LSTM networks are well-suited to classifying, processing and making predictions based on time series data.
7.	Then we convert the output in given category.  

