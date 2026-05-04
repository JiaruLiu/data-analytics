# TEXT-MINING-ANALYSIS-PROJECT-FOR-AMAZON-REVIEWS

## 1 Data Description

*__Amazon Review Dataset__*  
We use the Kindle Store dataset which is a subset of the Amazon Review dataset. The Amazon Review dataset contains products and reviews information from 1996 to 2018. We also join ‘metadata’ to our dataset, which provides us detailed product information for analysis and verification.  

*__Kindle Store Data__*  
The kindle store dataset has more than 5 million reviews, and generally the review for books are longer and more informative, which to some extent helps us in LDA modeling. It contains 36 sub-categories. Among them, the reviews of “Travel” category are more informative and distribute well among each year and each reviewer. So we choose it for further analysis.  

*__Travel Category__*  
Reviews 1688 Reviewers 1322 Products 173

## 2 Project Objective

In this project, we would like to figure out the topic and sentiment embedded in travel category reviews and track yearly variation in both topics and emotions in order to make actionable recommendations for amazon and other related stakeholders.  

We first use entire dataset to find each customer’s favorite topic based on their review history. By doing so, Amazon could offer personalized book recommendations to each customer to boost sales and improve user experience. Then we separate the data by years to detect topic evolution trends so that publisher can invest more on books of trending topics in that year.  

With sentiment analysis, we could find what customers like about our service, what they dislike and the embedded emotions. So we do sentiment analysis on all the records to find which product is most or least likely to get positive reviews, and we use the topics in first part to track emotion change in each year. Therefore, we can take action to improve our services. For Amazon, if a particular category or topic keeps receiving reviews with negative emotion, the platform may need to consider a more careful selection of the book catalog.

## 3 Methodology

* Data Pre-processing  
* Topic Modeling
  * Latent Dirichlet Allocation
  * Model Evaluation
* Sentiment Analysis
  * Vader-Lexicon
  * Nation Research Council (NRC) Emotion Lexicon

## 4 Results and discussion

(1) Topic Definition

(2) Topic Evolution

(3) Sentiment Analysis in Rating and Review

(4) Sentiment Analysis in Reviews with 10 emotions

## 5 Recommendation based on insights

(1) Recommendation for Amazon

(2) Recommendation for travel book authors

(3) Recommendation for advertisers on Amazon

## 6 Possible shortcomings of your work and ways to overcome
(1) Precision/Accuracy  
For topic modeling, small number of observations limits the accuracy. To get more precise result we may use Spark to deal with the whole review dataset.  
For Vader lexicon, the method is inflexible in some level of extent. So the accuracy is not really true. If we want to more convincing results, we could use different kinds of model to train the dataset and use test model to acquire accuracy rate.


(2) Model limitation  
LDA may not be the best for short text topic modeling. PCA or bi-term topic model may works better for this data set.  
The definition of some words in the NRC emotion lexicon may be outdated. One possible option is to update how people are feeling about specific words.
