# DisasterRecoverTweets

For this challenge, we are going to use tweets from X (formerly Twitter) to identify certain tweets that indicate that there is a disaster or emergency. This provides an opportunity to create early detection systems on public information that will help first responders to prepare for large relief efforts.

The dataset that we are going to be using is a dataset of tweets (10.7K) that have been labeled with Emergency / No Emergency. We are going to be using around 7K of these tweets to help train our neural network. We are given a category, a location from where the tweet originated, a class, and the text that highlights the text.

Our objective is to build a binary classifier using the text running it through a LSTM model, and then take the text and predict if it is an emergency tweet or not.
