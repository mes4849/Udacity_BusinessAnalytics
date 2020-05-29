# Predicting Diamond Prices
Purpose of project:
1. Introduce course content and purpose
2. Introduce to course submisison interface
3. Ensure comfort with course content


## Overview:
A jewelry company wants to put in a bid to purchase a large set of diamonds, but is unsure how much it should bid. This project will use the results from a predictive model to make recommendations on how much the jewelry company should bid for the diamonds.

Problem Statement: Business is unfamiliar on how to price a diamond purchase  
Solution: Use predictive analytics to price dimaond purchase



## US Number System:
This project will be using the US number system - where a decimal "." represents a fraction of a whole number.  
Ex - `$1.25` is `1 and a 1/4 dollars`, or `1 dollar and 25 cents`.



## Project Details:
Provided with linear regression model built from large database of diamonds, their price, and attributes  
Tasked with applying the linear regression model to make a reccomendation for a bid on a 3,000 diamon piece set.  
Linear regression model provides the following equation:  
  `Price = -5269 + 8413*Carat + 158.1*Cut + 454*Clarity`  


#### Data
There are two data sets:
1. "diamonds.csv" - contains the data used to build the model  
2. 'new_diamonds.csv' - contains the data for the diamonds the company would like to purchase  
Properties:
- Carat: Weight, numerical variable
- Cut: Quality, based on 5 value enum `fair, good, very good, ideal, premium`  
  Represented by numerical category `1-5`
- Clarity: Purity of the diamon, based on 8 value enum `l1, sl1, vs1, vs2, vvs2, vvs1, IF`  
  Represented by numerical categories `1-8`

#### Calculating Diamon Price
- We will use the provided formula and evaluate over the set of proposed bid diamonds

#### Recommendation
- Calculate price for the whole diamond set and make a reccomendation
- **Note** that the **Calculated price** is retail price; jewelry client only pays around 70% when purchasing from a distrbituer


## Project Submission
#### Understanding The Model
1. If a diamond differs from another by just +1 carat, how much more will it's retail price be? Why?
2. What is the retail price for a 1.5 carat diamond, with 3 cut, and 5 clarity?

#### Visualizing the Data
1. Plot 1 - plot the data for diamonds in the database (with price), with carat on the x-axis and price on the y-axis
2. Plot 2 - Plot the data for diamonds we are predicting prices for, with carat on x-axis and price on the y-axis
3. Give insightts on the plots.

#### Recommendation
What would we recommend as a bid for the 3,000 diamonds for sale?
