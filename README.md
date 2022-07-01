# WeRateDogs-Twitter

This project was carried out as the second project in the ALX/Udacity data analysis nanodegree program.
It is the analysis of the tweet archive of the WeRateDogs (@dog_rates) acount. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage. 
This project required data to be gathered using three different approaches and from three different sources. First dataset was downloaded manually and read into Jupyter notebook usind pandas read_csv. The second was downloaded programmatically from a url and the thrird dataset was obtained from the twitter API using Tweepy. 
The three datasets were assessed and cleaned individually before there were merged into a master dataset. This is to ensure data integrity.
Insights and visualizations were generated from the cleaned dataset.
Other requirements were to identify at least 8 data quality and 2 tidiness issues

Providing more context, below are the meanings of some columns that might not be so clear.
p1 is the algorithm's #1 prediction for the image in the tweet → golden retriever
p1_conf is how confident the algorithm is in its #1 prediction → 95%
p1_dog is whether or not the #1 prediction is a breed of dog → TRUE
p2 is the algorithm's second most likely prediction → Labrador retriever
p2_conf is how confident the algorithm is in its #2 prediction → 1%
p2_dog is whether or not the #2 prediction is a breed of dog → TRUE
p3 is the algorithm's third prediction
etc.
