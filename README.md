# -Disneyland-theme-Parks-Data-Analysis
## Business Problem

The main aim of Walt Disney is to predict if theme parks should implant better facilities/ services or not, to maintain or hike customer retention for increased business profits. They are more focused to address customers concerns and interests to manage the Walt Disney theme park better and provide the best services to the customers. Thus, we have summarise sentiments using customer review and to club similar emotions under topics to interpret the outcomes adequately.

## DataSet
The dataset used in this project consists of approximately 42,000 reviews, posted by visitors to a popular
travel review platform (TripAdvisor). 
The data include the following information:

- **Review_ID**        :   Unique Id 
- **Rating**            :   Ranging from 1 (unsatisfied) to 5 (satisfied)
- **Year_Month**        :   When the reviewer visited the theme park.
- **Reviewer_Location**  :   Country of origin of visitor.
- **Review_Text**        :   Comments made by visitor.
- **Branch**            :   Location of Disneyland Park.


## Approach

I have implanted various approaches to understand the visitor's sentiments. Firstly, the data is explored using data visualisation techniques. All the identified missing values were removed for better visualisation. Customer ratings and most frequent visitors are examined using bar charts to find more insights on the visitors. Then, sentiment analysis is performed on the data to understand more about the visitor's sentiments. We have summarised the emotions as positive, negative and neutral. Aspect based sentiment analysis is performed to know the quality of services and facilities provided at Disneyland theme parks at various location. Topic modelling has been presented to understand more about the visitor's concerns and interest in specific sectors of the theme park at multiple locations.

I have used below techniques:

- **Data Visualization Analysis**: Using Pandas, matplotlib and seaborn Libraries

- **Sentiment Analysis**: 
1. *Machine learning-based model*: Using Bag of Words and Naive Bayes classifier
2. *Lexicon-based model*: SentimentIntensityAnalyzer package is used 

- **Topic Modelling** : Is done using LatentDirichletallocation (LDA) approach and Gensim package 








## References
- Medium. 2020. Plotting With Pandas — Dates And Bar Plots. [online] Available at: https://codeburst.io/plotting-with-pandas-dates-and-bar-plots-227f25351274 [Accessed 9 August 2020].
- (Tutorial) Text ANALYTICS for Beginners using NLTK. (2020). Retrieved 10 August 2020, from https://www.datacamp.com/community/tutorials/text-analytics-beginners-nltk
- 2020.[online] Available at: https://www.researchgate.net/publication/221614404_Evaluating_topic_models_for_information_retrieval [Accessed 10 August 2020].
- R.Smith, M. a. (2005). An alternative viewpoint of the similarities and differences of SVD and FT deconvolution algorithms used for quantitative MR perfusion studies. Science digest journals and book.
- Resnik, J. B.-G. (n.d.). Holistic Sentiment Analysis Across Languages: Multilingual Supervised Latent Dirichlet Allocation.
