# Topic-Modelling-on-News-Articles

![image](https://user-images.githubusercontent.com/102039796/216698497-9156f7a9-b421-446e-a07a-8a689e11275b.png)

## Summary![rainbow](https://user-images.githubusercontent.com/102039796/216665284-9f6c1442-64b3-467c-b1d7-500a5e47da06.png)

The datset contained over 2225 documents, with different topics hidden inside them. The goal of topic modelling was to perform textual pre-processing and implemnt ML algorithms to correctly identify topics given in the documents. After reading all the lines and appending the text & topics in respective list, data was cleaned and visualized wrt length of document and word_count present in the documents.Further test pre-processing was done where-in all the irrelevant string data [ punctuations , non-words, stopwords, nuumbers etc] were removed and after performing vectorization using TF-IDF final clean news was obtained which was used for model implementation. First, LDA was implemnted with considerable results , LSA gave not so satisfactory resluts using CountVectorization & also using TF-IDF . The best topic predictions was done by LDA using gensim library algorithm which correctly classified topics based on the importance of words for each document
