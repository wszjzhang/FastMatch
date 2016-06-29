
0_data_scraping_from_LinkedIn.ipynb:
    This notebook is used for data scraping from LinkedIn profiles.

1_EDA_Concierge.ipynb:
    Data exploration.

2_Training_set_building.ipynb:
    Clean data and calculate meeting features for training and testing model. 

3_model_building.ipynb:
    !0-fold cross-validation for feature selection, model parameters optimization, model selection.
    Model evaluation on testing set.

4_match_meetings.ipynb:
    Calculate meeting features for available users and predict ratings for possible meetings.
    Give a list of all possible 5 star meetings.

5_LDA_comments.ipynb:
    Topic modeling on user feedback comments.

recommender_prototype:
    A prototype product of meeting recommender engine web-app.


Notes:
1,  The data set is still small. Simply increase the size of training dataset will improve the model's accuracy.
2,  The way of calculating the "match_score" can be improved by calculating the phrase similarity between title and looking_for. (try skip-thoughts)
3,  Please etrain the model for meeting recommender engine web-app before testing it.

