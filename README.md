# TwitterAPI & Video Intelligence API

EC601 project #1 API and Google Cloud Video Intelligence using

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Python Version: 3.6.5		
Packages needed: google.cloud // tweepy // ffmpeg		
Key needed: Twitter API key // google cloud video intelligence key

## Running the tests

Please change the '/keys.txt' with your Twitter API key file name in twitterAPI.py line 16		
Please change the '/googleKey.json' with your GCS video intelligence key file name in videoAnalysis.py line 8		

Change the twitter account and quantity of pictures in twitterAPI.py in line 115

### Break down into end to end tests

Run twitterAPI.py, this code will download pictures from a twitter account and covert all these pictures into a video in mp4 format. Then labels will be classified by video intelligence based on the video content.

## Authors

* **Frank Li** - *Initial work* - [PurpleBooth](https://github.com/FrankLiOnLine)

