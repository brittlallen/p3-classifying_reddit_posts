Problem Statement
----
Develop a NLP model to accurately and efficiently predict whether posts came from [r/menstruation](https://www.reddit.com/r/menstruation) or [r/BabyBumps](https://www.reddit.com/r/BabyBumps).


## Executive Summary
We cleaned and analyzed 2 features (post text and post title) which we engineered by way of Count Vectorizing. We removed English stop words, stripped ASCII accents for both features.  This resulted in a 393 features which we fed into 2 variations of Logistic Regression, Decision Tree, Random Forest and Multinomial NB models each.

Our best model was a Multinomial NB which achieved an accuracy score of 92.4% on training data and 92.2% on unseen data. This means our model is slightly and probably inconsequentially overfit.

#### Recommendations

* Go with Multinomial Naive Bayes Model #2
 * Version 2 handled bias/variance the best

* Spend more time with current features
 * e.g. Engineer a character or word length feature

* Explore new features
 * Upvotes
 * Post comments

   
#### Our presentation can be found [here.](https://docs.google.com/presentation/d/1S3R8KSKmX8M_uOtiXYiAQbVpRUHqMC8QfxfBW7Zx18k/edit?usp=sharing)