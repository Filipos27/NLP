# NLP
In this repository we will put nlp projects

### Diferences between TfidfVecorizer and CountVectorizer
TfidfVectorizer and CountVectorizer both are methods for converting text data into vectors as model can process only numerical data.

In CountVectorizer we only count the number of times a word appears in the document which results in biasing in favour of most frequent words. this ends up in ignoring rare words which could have helped is in processing our data more efficiently.To overcome this , we use TfidfVectorizer .
In TfidfVectorizer we consider overall document weightage of a word. It helps us in dealing with most frequent words. Using it we can penalize them. TfidfVectorizer weights the word counts by a measure of how often they appear in the documents.


## Results

|   Model             | Imbalanced (score)  | Balanced  (score)  |    
|----------------------|---------------------|--------------------|
|SVM                   |     83.8 %          |      86.5 %        |                   
|DecisionTree          |     79.9%           |      75.76 %       |               
|Naive Bayes           |     64.53%          |      72.03 %       |  
|LogisticRegression    |     87.03%          |      86.03 %       |  

In inbalanced dataset we used CountVectorizer and in balanced dataset we used TfidfVectorizer.
