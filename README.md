# Project: WeRateDogs Data wrangling, analyzing and visualizing

## 1. Introduction

**WeRateDogs** is a Twitter account that rates people's dogs with a humorous comment about the dog. The account was started in 2015 by college student Matt Nelson, and has received international media attention both for its popularity. The dataset that we shall be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

Below are are some definition of some characteristics of dog:

<image src = dogtionary-combined.png>

## 2. Getting Started
To get a local copy up and running follow these simple example steps.

Prerequisites
The prerequisites needed to successfully run this project are:

    * Twitter API and Elevated Access.
        Twitter API and having an Elevated Developer Account helps scrape data from twitter. 
        
    * The requirements and dependancies can found in the requirement.txt file    

## 3. Project Context

To wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations.

## 4. Project Steps Overview
Our tasks in this project are as follows:

        Step 1: Gathering data

        Step 2: Assessing data

        Step 3: Cleaning data

        Step 4: Storing data

        Step 5: Analyzing, and visualizing data

        Step 6: Reporting

            * the data wrangling efforts
            * the data analyses and visualizations
            
 ## 5. Data relevance

In this project, we shall work on the following three datasets.

**i). Enhanced Twitter Archive**

The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets, but not everything. One column the archive does contain though: each tweet's text, which I used to extract rating, dog name, and dog "stage" (i.e. doggo, floofer, pupper, and puppo) to make this Twitter archive "enhanced." Of the 5000+ tweets, I have filtered for tweets with ratings only (there are 2356).

**ii). Image predictions File**

This file (image_predictions.tsv) is present in each tweet according to a neural network. It is hosted on Udacity's servers and will be downloaded programmatically using the Requests library and the following URL: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv

**iii). Twitter API**

We shall also use Twitter API to get additional data for the Project

## 6. License

Distributed under the MIT License. See license.txt for more information.
