# Data-Mining-PVA

Customer Segmentation of PVA donors in such a way that it will be possible for them to better understand the behavior of their donors and to better identify the different segments of donors/potential donors within their database

# Introducing our Data

In order to intuitively fish out the potentially relevant attributes from our data with
number of attributes: 475, Number of examples/observations: 95412. We need to go through the data dictionary and understand the meaning of each and their relevance/contribution towards building our clusters. When we first scan through the dataset, we consider a number of variables to be potentially important variables. Below are some of the variables:

## CONTROLN:
  Control number tied to the donors (unique record identifier)
## INCOME: 
  Gives us an idea on how many people are earning and do they earn enough to be able to contribute as donation.
## AGE: 
  Younger or older people are more likely to donate. Age distribution is a must.
## MAJOR: 
  Shows us whether they have been major donors in the past.
## TIMELAG:
  Estimates the gap between two donations of a user. Helps us understand how often and after how long they can donate.
## HOMEOWNR:
  Do they own their own house or not? This shows us their assets to rely on. MDMAUD​: This will highlight a potential donor from the rest with the bits of    information that it provides.
## AVGGIFT:
  How much have they donated until now in the form of gifts. Historical information helps us predict the future amount too that they will likely donate

# Modelling

## Numeric Data

#### Density-based methods
#### Mean-Shift Clustering
#### Hierarchical methods
#### Partitioning methods (K-means)
#### Expectation-Maximization (EM) Clustering

## Categoric Data
#### K-Modes

## Combine Numeric and Categoric Data
#### K-Prototypes
