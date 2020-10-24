# Project1DS6306
This repository contains all required project files as specified by class documents

Included in this repository are the following: Codebook, both .csv files, and my knitted HTML file of the project (as well as the original .rmd file), this document you are currently reading also contains the project summmary below.

Project Summary

We were contacted by Budwiesier to take a look at a dataset they have obtained and to turn the data into information. Essentially the data contained over 2400 individual beers and over 500 breweries, nonetheless, lots of data to analyze.

Budwiesier asked the following questions of us:
1) How many breweries are in each state?
2) To merge the beer dataset and the brewery dataset
3) To address the missing values in each column
4) Compute the median alcohol content and international bitterness unit count in each state
5) Determine which state has the single highest ABV beer, and which state has the highest IBU beer.
6) Discuss the summary statistics and distribution of ABV variables
7) Determine if there is a relationship between IBU and its alcoholic content by using a visualization 
8) Use KNN to classify beers as IPAs or Ales, and we used a Naive Bayes classifer to determine this relationship as well
9) We also examined a relationship between IBU and style and determined for specific styles, there is quite an association.

YouTube link: https://youtu.be/N48Fv-QEUrQ

We are confident in the validity of our analysis and hope that Budwiesier determines an appropriate course of action to take based on the work in this repository.

Important variables are brewbystate, beerdat and brewerydat

General conclusions: Full conclusion are contained in Project1.rmd, but below are general conclusions:

In total there are 2410 unique beers, and 558 breweries, containing 100 unique styles.  

Median IBU for all 50 states =33.9, Median ABV=5.6%

Top 10 States by Brewery
Colorado -- 47
California – 39
Michigan -- 32
Oregon -- 29
Texas -- 28
Pennsylvania -- 25
Washington -- 23
Massachusetts -- 23
Indiana -- 22
Wisconsin -- 20

All beers have AVB: 0.10 - 12.80 

50% of beers have an AVB =  5.0 - 6.7

We imputed missing IBU and ABV data by taking average of each beer style and replacing missing values with the generated data per missing entry.

KNN and Naive bayes do an excellent job of classifying IPAs and Ales.

The highest IBU beer comes from Oregon, and the highest ABV comes from Colorado.  Max IBU=138, and max ABV=12.8%

There is a clear relationship between IBU and ABV, and there is also a clear relationship between IBU and Style.


