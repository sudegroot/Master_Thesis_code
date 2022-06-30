# Master_Thesis_code

This repository consists all the code used for the Master thesis 'Impact of crisis events on social media information virality
prediction'. The folder 'Scrape&Prepare data' consists of all the code used to scrape the data and make the appropriate train/test splits (the train and validation sets were combined for cross-validation). The folder 'Modeling&Figures' contains all code used for model training, model testing, and making figures for the thesis. 

The data used for this thesis can be found in the 'Data' folder. Due to Twitter regulations, the data only consists of the tweet ids of the tweets relating to the Russian invasion of Ukraine and COVID that are scraped for this study. Be aware that the number of tweet ids can differ from the number of tweets mentioned in the paper. This is because only tweets of which user features were available are used. The tweets and corresponding user features can be rehydrated using the Twitter API. However, it could be that some tweets or users might be deleted or put on private and are therefore no longer available. Moreover, user features might change over time. 
