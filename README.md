
# Data Science Portfolio By Jing Ming Li

Hi! My name is J.M Kevin Li, a impact-driven data scientist with previous experiences at Blackstone, Cboe Global Markets, Calamos Investments, and Dunkin'. Welcome to my portfolio. 

Below is a list of all my projects. Here is a copy of my [resume](https://github.com/klg125/portfolio/blob/master/notebooks/Kevin_Li_Resume_0920.pdf).

## Classification Problems 

### Amazon Reviews Classifications 

[Notebook](https://github.com/klg125/portfolio/blob/master/notebooks/AmazonReviews_Classification.ipynb)

Applied TF-IDF and sentiment analysis on 500K pre-processed retail reviews, built a late fusion algorithm on tuned SVM and Neural Network models to classify ‘positive’ and ‘negative’ reviews, achieving 0.91 F1-score on test set.

## Clustering + Dimensionality Reduction 

### Cereal Customer Segmentation 

The primary goal of this project is to analyze and cluster cereal products based on various nutritional factors. This involves examining different cereals' nutrient content to identify potential market segments, especially niche markets, and to understand manufacturers' strategies in positioning their products.

Principal Component Analysis (PCA) was used to reduce data dimensionality, resulting in two main components explaining most of the variation.
K-Means clustering helped segment the market into 9 distinct cereal types, identified as optimal using SSE, F, and Silhouette statistics.
Gaussian Mixture Models (GMM) were compared with K-Means for clustering, ultimately favoring the 9-cluster K-Means solution.
Logistic regression analyzed the relationship between cereal characteristics and their shelf placement, incorporating factors like "Healthy Nutrients" and "Unhealthy Nutrients".

[R Markdown](https://github.com/klg125/portfolio/blob/master/notebooks/Cereal%20Case.Rmd) 
[Notebook](https://github.com/klg125/portfolio/blob/master/notebooks/Cereal%20Clustering%20Case.pdf)

## Recommendation systems + NLP 

### Collaborative filtering, Latent semantic analysis

[Presentation](https://github.com/klg125/portfolio/blob/master/notebooks/IEMS308%20Recipe%20Project%20%E2%80%94%20Recommender%20Systems%20(1).pdf)
[Code](https://github.com/klg125/portfolio/blob/master/notebooks/ProjectLSA%20(1).R)

I leveraged LSA to create 7-dimensional user and recipe profile to recommend 10 new recipes for 3000 test users similar to previously downloaded recipes, achieving 32% precision@10 score.

## Regression Problems

### Opioid-Related Emergency Department Admissions Prediction through Internet Search Keywords
[Report](https://github.com/klg125/portfolio/blob/master/notebooks/Opioid_STEMFellowship.pdf)

Employed a polynomial regression model to examine whether keywords from Google Trends can predict opioid-related emergency department (ED) visits; accounted for 99% of variance in ED visits through best-fitting model.

### Constructing a Portfolio from Sentiments of Stock Ticker Symbols and Live News
[Report](https://github.com/klg125/portfolio/blob/master/notebooks/StockReturns.pdf)

Built sentiment-based portfolio by normalizing likability of ticker symbol and by regressing this portfolio on the Fama-French three-factor model; achieved 0.027% monthly outperformance compared to benchmark portfolio.

## Deep Learning

### Computer Vision: Golf Swing Outcome Prediction using Computer Vision

I extracted 90 frames from 590 three-second side-view golf swing video and conducted image dimension resizing using OpenCV. I leveraged Movenet Lightning to obtain position of 17 body parts for each frame; eliminated 93% of frames by building a frame selector algorithm that utilizes polar coordinates to identify 6 most important positions in the golf swing. Successfully predicted club face angle and club path of golf shot with elastic net regression that achieved MAE of 0.82 and 0.9, respectively. 

* Notebook not available due to privacy concerns 

## Micro Projects in R

### TelePrime Customer Churn Prediction 
Standardized 12 continuous features on credit score and customer demographics, creating 5 derived features on tenure length. Leveraged stepAIC to remove 6 features; applied logistic regression on finalized dataset; visualized accuracy, sensitivity, and specificity of model to locate 36.7% as the optimal probability cutoff to increase true positive rate.

[View Notebook](https://github.com/klg125/portfolio/blob/master/notebooks/TelePrime%20Churn.pdf)

### Biomedical Genome Regression 
Fitted regression tree to Trp63 genome dataset (3K rows and 230 features) to discover important transcription gene predictors. I applied pruning and bagging with best parameter from CV; found 3 influential genes through random forest and lasso regression. 

[View Notebook](https://github.com/klg125/portfolio/blob/master/notebooks/Regression%20in%20Biomedical%20Research_Github.pdf)



