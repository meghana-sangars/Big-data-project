# Big-data-project
This repository is maintained to document my big data analytics project.


The idea of the project is based on - C. Dabas, P. Kaur, N. Gulati and M. Tilak, "Analysis of Comments on Youtube Videos using Hadoop," 2019 Fifth International Conference on Image InformationProcessing (ICIIP), Shimla, India, 2019, pp. 353-358, doi:10.1109/ICIIP47207.2019.8985907.


The project consists of three tasks :
1. **Data visualization**
2. **Sentiment analysis with Naive Bayes classifier**
3. **Content based recommender system**

The data for task 2 and task 3 can be obtained as follows :
- For task 2, [Kaggle Trending YouTube Video Statistics and Comments dataset](https://www.kaggle.com/datasnaek/youtube) was used
- The steps followed for collecting data for recommeder system is explained in **data collection** under task 3

## Task 1 - Data visualization 
- Tableau has been used for viz and workbook is also provided
- [Link for published workbook](https://public.tableau.com/views/BDA_step1_step3_final/Sheet1?:language=en-GB&:display_count=y&:origin=viz_share_link)
- The data from 2 countries - US and GB only has been used
- Some interesting conclusions can be drawn from the plots which can be found under the file **viz**


## Task 2 - Sentiment analysis with Naive Bayes classifier 
- The sentiment analysis was performed on comments from "Education" category
- Polarity of the comment was found using textblob 
- The comments were categorized as either of the three - positive, neutral or negative
- A Naive bayes classifier was modelled on the categorized dataset
- The model achieved an accuracy of 89%(approximately)
- The notebook for combining the US and GB dataset and filtering "Education" comments can be found
- The notebook for classifier can also be found in the same folder
