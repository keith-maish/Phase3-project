# Phase 3 project
### Author: Keith Maina

## Overview
In this project we are going to be creating a machine learning model that determines whether a user of the SyriaTelcom service churns out of the service or not.

# Business Understanding
### <u>Stakeholder</u>
This project is for the SyriaTel telecom business.
### <u>Business Problem</u>
Clilents who stop using a service are not good for any business, because that leads to losses. We need to find out the clients that are likely to churn prior to when they do actually churn, so that we could target client retention efforts toward them.

## Data
This project uses data from SyriaTelcom which contains information on the kinds of subscriptions they have, their phone numbers, the state they're in along with whether past users have churned or not.

## Methods
The data provided had no null values, so no cleaning was necessary.<br>
The data was split into training and testing subsets.
All categorical columns were one hot encoded and so was the state column.<br>
The data was also normalized for KNN- models.

## Results
I was able to produce a deployable model after 8 iterations and I chose it for having  both the highest f1_scores and the most area under the curve out of all the models generated.