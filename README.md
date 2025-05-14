# Google Playstore App Review Analysis

![image alt](https://www.google.com/imgres?q=playstore%20analysis&imgurl=https%3A%2F%2Fmiro.medium.com%2Fv2%2Fresize%3Afit%3A1400%2F1*75SwvWQrspM0aKlN02uWTQ.jpeg&imgrefurl=https%3A%2F%2Fmedium.com%2F%40ritz1602.rs%2Fgoogle-play-store-analysis-eda-4321dc6d36df&docid=S_02X_Et1pFbHM&tbnid=cBqcGHZ3IhW5YM&vet=12ahUKEwjwhd2Vm6ONAxV56jgGHb4WOhQQM3oECFsQAA..i&w=1400&h=379&hcb=2&ved=2ahUKEwjwhd2Vm6ONAxV56jgGHb4WOhQQM3oECFsQAA)

# Project Summary

This exploratory data analysis (EDA) project focuses on analyzing the Google Play Store apps data and customer reviews dataset. The goal is to derive actionable insights that can help app-making businesses succeed in the Android market.

The **Google Play Store** data includes information about various apps such as their names, categories, average user ratings, number of reviews, size, number of installs, pricing, content rating, genres and more. This dataset provides a comprehensive overview of the apps available on the Play Store.
The **user reviews** dataset contains customer reviews for different apps. It includes the app name, sentiment of the review (positive, neutral, or negative), sentiment polarity (numerical score indicating the review's positivity or negativity) and sentiment subjectivity (score indicating the extent to which a piece of text expresses personal opinions, emotions, evaluations, or beliefs, rather than objective factual information).

# Problem Statement
The Play Store apps data has enormous potential to drive app-making businesses to success. Here we need to draw actionable insights for developers to work on and capture the Android market.Each app (row) has values for category, rating, size, and more. Another dataset contains customer reviews of the android apps.

# Business Objective:
Discovering key factors responsible for app engagement and success.

# Dataset Description:

## Google Play Store Data
* App - Name of the app
* Category - Category of the app
* Rating - The average user rating of the app, ranging from 1 to 5
* Reviews - Number of user reviews for the app
* Size - Size of the app in MB
* Installs - Number of installs for the app
* Type - Whether the app is free or paid
* Price - Price of the app (o if the app is free)
* Content Rating - Age group for which the app is suitable
* Genres - The category of the app according to the Play Store's classification system
* Last Updated - The date when the app was last updated on the Plav Store
* Current Ver - Current version of the app
* Android Ver - Minimum Android version reguired to run the app

## User Reviews Data
* App - The name of the app for which the review was submitted
* Translated_Review - The review text submitted by the user, translated to English if necessary.
* Sentiment - The sentiment of the customer review, which can be "Positive", "Natural", or "Negative".
* Sentiment_Polarity - The numerical polarity score of the review, rangig from -1(most negative) to 1(most positive)
* Sentiment_Subjectivity - The subjectivity score of the review, ranging form 0(objective) to 1 (subjevtive)
