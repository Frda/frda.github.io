---
title       : Womens Weight Estimator App
subtitle    : 
author      : Frkwad
job         : Estimator
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [bootstrap, quiz]             #{mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides

---
### Womens Height app

Womens Weight app. Is an Application Developed to provide the user with the average weight of a woman for a given height. It also calculates the kilogram value for the given weight in pounds(lbs)

### Data Source
- Womens Weight application is based on the womens data package located R data package
- Womens data package contains data for average weight (lbs) and height(in) for a number of women

### Reason for using "womens"" data package in R
- Two column data structure 
- Application can be used for men once data becomes available
Below is a summary of Data from the womens Dataset




---
### Potential uses of womens weight app.

- Forencis: Incases where a murder has occured and the only clue left is a skeleton
  The womens app can be used to estimate the weight of the dead person. This will allow    the investigators to come up with a description of the dead.
  
- Health care: womens weight appliaction can be used by individuals to help plan either    weight gain or weight loss regiment for their given hight in conjuction with their       doctor

summary data from womens table

```r
summary(women)
```

```
##      height         weight     
##  Min.   :58.0   Min.   :115.0  
##  1st Qu.:61.5   1st Qu.:124.5  
##  Median :65.0   Median :135.0  
##  Mean   :65.0   Mean   :136.7  
##  3rd Qu.:68.5   3rd Qu.:148.0  
##  Max.   :72.0   Max.   :164.0
```

---
### Demo  womens weight app
<iframe src="https://frkwad.shinyapps.io/shine/" width=100%, height=600></iframe>



--- &radio
## Buy Now 

Buy women weight app for only -$9.99, but wait there is more, you can now get mens weight app for free when you Buy womens weight app for the price of -$500. But hurry supplies are limited and I'm almost done with Coursera :)

please pick a selection to show how awesome this application is also to satisfy the question of having r code that works in sladify. 


How will you rate this app

1. _Very awesome_
2. _very Very awesome_
3. _The best app ever made_
4. This app is not good

*** .hint
number 4 is wrong all the rest are correct cus this app is awesome :)

*** .explanation
Its Sunday and its nice outside, but I'm in doors working on this project. I just got to have some fun with it :) hopefully it does not cause me to have to retake it. 1 through 3 are correct, 4 is not
