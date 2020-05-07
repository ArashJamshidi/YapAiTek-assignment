# YapAiTek-assignment
This analysis consists of two major parts: </br>
1- In this part i did data cleaning and some basic statistics analysis. For example how many times each share name got mentioned? which of shares names got mentioned in the same posts (maybe they are related?), what Industries (and their related shares) get mention more often? & etc. </br>
2- In this part i continued my data cleaning (removing digits and removing stop words). I could've used other data cleaning methods (like Lemmatizer or Stemmer) too but as i didn't know which Persian NLP library is reliable enough i didn't move forward with it. After that i modeled our documents using LDA (latent dirichlet allocation) algorithm to understand our text better. Also there are two pyLDAvis plots (based on my LDA model) which you can see their html file in LDA plot folder. </br>
For more information and to see the code, plots and read markdowns visit the notebook.

P.S: For some part of the code, i could've write cleaner code (for example concatenate different parts into one function) but i didn't; to show exactly how  my iterative thought process was. </br>
P.S II : Other works that we can do on these texts: 1- word2vec (altough i think we need a bigger corpus for a good representation) 2- trying to understand different numbers in text (prices for example) 3- Sentiment Analysis (needs labeling)
