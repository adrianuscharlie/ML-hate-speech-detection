# Sentiment Analysis Using LSTM and Bidirectional LSTM on Selena Gomez

Create deep learning model for hate speech detection using LSTM and Bidirectional LSTM layer on Selena Gomez phenomenon.

## Features
- Dataset
- Preprocessing
- Modelling
- Evaluation 

## Dataset
Dataset that used is taken from scrapping from Twitter using python modul tweepy. Using tweepy and Twitter Developer Account to search tweets that contains "Selena Gomez" words in certain time. After that, save the scrapped data into excel file.
Here's some example of the dataset that taken from Twitter using tweepy module.
Here is the dataset link [Dataset Link](https://github.com/adrianuscharlie/ML-hate-speech-detection/blob/main/Selena%20Gomez/selenagomez.xlsx)
| created at | username | text |
| --- | --- | --- |
| Thu Mar 02 23:59:54 +0000 2023 | izzvhatirvh | RT @armylieber100: Aren't Selena Gomez fans tired yet? it's been almost a week like move on and leave Hailey alone|
|Thu Mar 02 23:59:44 +0000 2023 | Kenzie5Peterson | RT @juliannarvivas: Im a Selena Gomez &amp; you a Hailey Bieber.|
|Thu Mar 02 23:56:18 +0000 2023 | babyyyannieee | Justin Bieber &amp; Selena Gomez followed each other on Twitter 😭teenage me is crying 😭|

## Preprocessing
The preprocessing applied to the dataset is as follows:
--Filtering tweets that contains "RT" words
--Lowercase







