# VBA of Wall Street

## Overview of Project

This project is basically a simple analysis of two years of stock performance using visual basic for applications. The project tries to find out two things:

    - Whether the initial assessment of choosing DAQO as a good stock based on stock performance was ok; &
    - Whether refactoring the code used to analyze the stock performance yields better result 

## Results

Looking over the analysis, it can be said that DAQO was a good company to invest in for 2017, as it showed a return of almost 200%. Other stocks except TERP seemed to enjoy a favorable year. However, 2018 seems to be a bad year for almost all the stocks except ENPH and RUN, which had positive results. Considering overall results, it would be better to go with ENPH stocks as it has the most favorable result (132% & 82% over two years.)
<img src = resources/2017_result.png></img> <img src= resources/2018_result.png></img>

As for the refactoring of the script, this improved the performance by almost 80%, as the previous code took 0.63 seconds whereas the new code takes only 0.10 seconds approximately for both years. So, it is better using the refactored code.

Result Comparison 2017

<img src = resources/2017_run_old_system.png></img> <img src= resources/VBA_Challenge_2017.png></img>

Result Comparison 2018

<img src = resources/2018_run_old_system.png></img> <img src= resources/VBA_Challenge_2018.png></img>


## Summary

When doing a repetitive task with a set format, it will always be better to refactor codes. This allows for simple execution for the user, without having an extensive background knowledge. With proper documentation and procedures set, anyone can have a set refactored code for their work and minimize execution time. However, if there is any change in the data set (formatting, value of variables), it might be hard for people other than the creator to retask the code to work.

In terms of this particular analysis it really improved the result when we refactored the code as it improved by a whooping 80%. However, if we change the dataset structure or insert any columns in between, it will show incorrect results as the information it is picking up is hardcoded and thus will not reflect what the user needs.  

