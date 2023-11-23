---
title: Crypto-prediction
summary: Cryptocurrencies price prediction.
tags:
  - Python
date: "2022-06-22T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: 

image:
  caption: Photo by CNBC
  focal_point: Smart
  
  
links:
  - icon: github
    icon_pack: fab
    name: View code
    url: https://github.com/BOUGHANMIChaima/Crypto-prediction
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''  
  
---

This is an artificial intelligence challenge I took part in on Kaggle . Using repisotory https://github.com/manthanthakker/BitcoinPrediction for inspiration, it presents implementations of machine learning algorithms (Random Forest, regression, etc.) and recurrent neural networks/long-term memory networks for BitCoin prediction. Furthermore, in our case, we have identified that BitCoin is the most important currency, as most other digital currencies will closely follow its trends. So having an accurate BitCoin prediction model should be an essential part of the project.

After importing the data obtained from Kaggle from our database, which contains historical information on several cryptocurrencies such as Bitcoin and Ethereum, I moved on to the data preparation and cleaning stage.

The next step is to deal with the missing values, rather in the difference in timestamp intervals. I started by extracting each cryptocurrency with its corresponding timestamps, visualizing them to better detect the differences and then imputing each missing value by the average of the value before and the value after.
