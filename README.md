### Text Categories Classification through Supervised Learning

This repo documents the various approaches I used to conduct supervised learning of text categories. In particular, I was categorizing noise complaints received by an agency. The user was interested to group these complaints into categories so that follow-up actions based on the categories could be carried out like routing some complaints to another agency or forwarding the more serious ones to the police. As the number of complaints received every month was close to 10000, it was not feasible to manually intervene for each complaint.

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

Though the approach was targeted for classification of noise complaints, it is generic enough to be applied for other category classification needs.
