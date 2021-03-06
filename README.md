# Stock-Analysis

## Overview of Project

### Purpose

The purpose of this project was to analyze stock performance using data from 12 different stocks in 2 different years. The data contained volume, opening, closing, high, and low prices for every market day of the year for each stock. Using VBA for Excel, macros were created to quickly run analysis for all 12 stocks such as total daily volume and percentage return for the year.

## Results

### Analysis of Stocks

![Performance_2017.PNG](Resources/Performance_2017.PNG)
![Performance_2018.PNG](Resources/Performance_2018.PNG)

As seen above, stock performance in 2017 was better than stock performance in 2018 almost across the board. Some stocks were traded in greater volumes in 2017 than in 2018 and vice versa. But overall, the percentage returns in 2017 were far greater than the percentage returns in 2018.

### Refactored Code

Original code runtime for 2017:

![Original_2017.PNG](Resources/Original_2017.PNG)

Refactored code runtime for 2017:

![VBA_Challenge_2017.PNG](Resources/VBA_Challenge_2017.PNG)

Original code runtime for 2018:

![Original_2018.PNG](Resources/Original_2018.PNG)

Refactored code runtime for 2018:

![VBA_Challenge_2018.PNG](Resources/VBA_Challenge_2018.PNG)

As seen above, the refactored code was able to cut runtime by approximately 75% in each year. The main improvement made to the code was using an incrementing tickerIndex when looping through all the rows instead of using nested for loops to loop through the tickers and then the rows. 

## Summary
These results show that refactoring code can have many advantages such as reducing runtime, reducing memory usage, and making code more organized. There are disadvantages to refactoring code as well. The refactoring process can take a lot of time, especially for someone who wasn't previously familiar with the code. On an industrial scale, the benefits of refactoring code may not be worth the time and money used to refactor it.

In the case of this project, refactoring the code was absolutely worth it overall. The time spent refactoring was minimal and there was a significant reduction in runtime.
