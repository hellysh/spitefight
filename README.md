# spitefight
Deep Learning Final Project

## Readings:

#### [Predicting Factuality of Reporting and Bias of News Media Sources](https://arxiv.org/pdf/1810.01765.pdf)
* Predicts the factual-ity of reporting and bias of news media.
* Creates a new dataset of news mediasources, which has annotations for both factual-ity and bias.
* Provides an overview of related work (Must read for possible feature ideas!).
* Uses features such as Structure, Sentiment, Engagement, Topic, Complexity, Bias and Morality.
* Uses the sources' articles, Wikipedia, Twitter to extract information.
* Textual features extracted from the ARTICLES yielded the best performance on factuality...the WIKIPEDIA features are less useful for factuality and perform reasonably well for bias...the TWITTER features perform moderately for factuality and poorly for bias.

#### [Automated Fact Checking:Task formulations, methods and future directions](https://www.aclweb.org/anthology/C18-1283.pdf) 
This paper provides many interesting ideas for feature selection and differentiating between claims. For e.g., should numerical claims and position statements be treated differently?

#### [Liar Liar Pants on Fire](https://arxiv.org/pdf/1705.00648.pdf)
* Makes a dataset via sourcing 12,836 labelled statements from Politifact.
* Talks about related studies and datasets (Should read).
* Asks the following research questions: 
  - Based on surface-level linguistic realizations only,  how  well  can  machine  learning  algorithms classify a short statement into a fine-grained category of fakeness?
  - Can we design a deep neural network architecture to integrate speaker related meta-data with text to enhance the performance of fakenews detection?
* Has dis-heartening results with existing models. 

#### [Where is your Evidence: Improving Fact-checking by Justification Modeling](https://www.aclweb.org/anthology/W18-5513.pdf)
This paper builds upon the models in above, and achieves better accuracies.

#### [Using Machine Learning To Move Fact Checking From Articles To Claims](https://www.forbes.com/sites/kalevleetaru/2019/06/25/using-machine-learning-to-move-fact-checking-from-articles-to-claims/#ccdec1b48869) 
This article talks about ideas very similar to ours. It is essentially an ideological parallel.

#### [Classifying facts and opinions in Twitter messages: a deep learning-based approach](https://www.tandfonline.com/doi/full/10.1080/2573234X.2018.1506687)
The title says it all. 


## Data Collection:

### Features

## Model:
