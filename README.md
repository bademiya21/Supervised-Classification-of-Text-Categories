### MSO Noise Complaints Classification Supervised Learning

This repo documents the various approaches I used to conduct supervised learning of noise complaints with categories provided by MSO. The data was labelled by me using Andrew's Text Annotator app. I labelled close to 10000 samples for 5 categories. Though I tried to get equal number of samples per category, the data was heavily biased towards certain categories as illustrated in the bar charts in the notebooks.

Some of the approaches:

    -   Feature Extraction
        1) Word Count Vectors
        2) TF-IDF Vectors
        These were used with Linear SVM classifers
        3) Mean Embedding Vectors
        4) TF-IDF Embedding Vectors
        These were used with Extra Tree Classifers
    
    -   Classifers
        1) Linear Support Vector Machines
        2) Extra Tree Classifiers
        
These approaches were heavily influenced by the works of Nadbor Drozd. His blog post on this can be viewed here - http://nadbordrozd.github.io/blog/2016/05/20/text-classification-with-word2vec/

Read the individual notebooks to understand what was done.