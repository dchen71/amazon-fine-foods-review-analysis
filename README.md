# amazon-fine-foods-review-analysis
Data Analysis of Amazon Fine Foods Review hosted on Kaggle

## Introduction

Given longitudinal data, one should be able to understand how things change over time. McAuley and Leskovec published a paper in 2013 detailing how they used Amazon's gourmet food section to build a recommendation classifier which builds upon the experience of a reviewer. Using this longitudinal dataset, there shoudl be many things that could be understood from looking into the data. For instnace, we could potentially see the trends of food over the years and maybe even capture the cupcake craze of 2011.  

The goals of this analysis is the following:  

* Understand the evolution of reviewers over time
* Understand the variation of helpfulness of reviews for products over time
* Visualize the changes in reviews over the 10 year period to understand what trends were important that year

## Results
Several results can be gathered through this notebook.  

* Review lengths over time become longer  
* Semantic prediction of summary and review text weakly but significantly correlated according to pearson correlation  
* The summary of the reviews also get slightly longer over time  
* The older a product is, the more variation for review scores   
* The helpfulness ratio generally increases overtime for a product  
* Scattertext plots showed the evolution of the Amazon platform and shows the transition from movies to foods. Earlier positive ratings stemmed from specific products but slowly shifted towards more sentiment based relationship.  

## Conclusion
This dataset for Fine Foods Reviews shows several trends. As writers become more experienced, the length of their reviews get longer. In addition, the summary of the reviews also seem to get longer. Additionally, older products have more variation in the review scores. Finally, using scattertext we can see some of the text features which are associated with higher or lower ratings for the product which eventually shifts to a more semnatic based relationship.

## References
[Amazon Fine Foods Review](https://www.kaggle.com/snap/amazon-fine-food-reviews)  
J. McAuley and J. Leskovec. [From amateurs to connoisseurs: modeling the evolution of user expertise through online reviews.](http://i.stanford.edu/~julian/pdfs/www13.pdf). WWW, 2013.
