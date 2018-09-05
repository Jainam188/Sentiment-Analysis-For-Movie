# Sentiment-Analysis-For-Movie
This is the code for How_to_do_Sentiment_Analysis

##Overview

It uses TFLearn to train a Sentiment Analyzer on a set of IMDB Movie ratings. Once trained, given some input text, it will be able to classify it as either positive or negative. The neural network that is built for this is a recurrent network. It uses a technique called LSTM.

##Dependencies

tflearn

Use this guide to install TFLearn. Or just use the Amazon Web Services prebuilt AMI to run this in the cloud

##Usage

Run .py in terminal and it should start training

##Challenge

The challenge for this video is to train a model on this dataset of video game reviews from IGN.com. Then, given some new video game title it should be able to classify it. You can use pandas to parse this dataset. Right now each review has a label that's either Amazing, Great, Good, Mediocre, painful, or awful. These are the emotions. Using the existing labels is extra credit. The baseline is that you can just convert the labels so that there are only 2 emotions (positive or negative). Ideally you can use an RNN via TFLearn like the one in this example, but I'll accept other types of ML models as well.

You'll learn how to parse data, select appropriate features, and use a neural net on an IRL problem. Remember to ask each other questions for help in the Slack channel. Good luck!

##Credits

Credits for this code go to the author of TFLearn. I've merely created a wrapper to get people started.
