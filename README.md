# Project 1: SAT & ACT Analysis Overview

### Contents:
- [Problem Statement](#Problem-Statement)
- [Executive Summary](#Executive-Summary)
- [Data Dictionary](#Data-Dictionary)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)

### Problem Statement 

Participation on the SAT and ACT tests is a key element in the established process of admissions to colleges and universities across the nation. *This project will aim to analyze the trends in SAT and ACT participation and its relationship with the scores that participants have achieved across the nation.* 

Perhaps in the future with more data. We could review the conditions of the states that reached 100% participation, analyze how and what they did to reach that goal, and design a strategy that can be applied to increase participation on states with lower levels of participation and also increase scores across the board for all states.

### Executive Summary

This notebook will be importing, cleaning and processing for data analysis of the 2017, 2018 and 2019 participation & score data files for both the SAT and ACT across all the states of the nation. After we pass the stages of reviewing, fixing, and preparing or cleaning the data, exploratory analysis will be done. Mostly based on the plots of the datasets for all those years and the specific variables of participation and scores. In addition a few external resources will be used to understand our analysis and support our conclusions. Such as: The results statewide of Students for college admissions. Ref. https://www.testive.com/state-sat-act/

### Data Dictionary

The following Datasets since the contain the data of ACT and SAT test scores per state and level of participation for each state will be choosen, prepared and used for our analysis.
Feature	Type	Dataset	Description
state, participation, scores	object, floats	ACT	Data Frame act_2017
state, participation, scores	object, floats	ACT	Data Frame act_2018
state, participation, scores	object, floats	ACT	Data Frame act_2019
state, participation, scores	object, floats	SAT	Data Frame act_2017
state, participation, scores	object, floats	SAT	Data Frame act_2018
state, participation, scores	object, floats	SAT	Data Frame act_2019

### Usage

The associated Project-1-v1.pynb Jupyter Notebook files has all the processing of the data, for cleaning and preparing it, processing and visual results. These code could be refactor to be used with any data on similar format - like other years - and for the same purpose.


### Conclusions and Recommendations

States with a high levels of participation have low scores. The relationship between Participation and Score ( performance ) is Inverted. Meaning, the Higher the Participation the Lower the Scores accomplished. States with a mandatory test such as ACT and SAT got the higher scores, yet students did not have any other option, even if they were not planning attending to college. In contrast, states in which test was not mandatory, the few participants got higher score probably, because these were hightly motivated students that wanted to go college or university in their state or in a different state.

State funding impacted on student participation. Include cost of tests, class preparation materials and class courses. Extension of funding to another states most likely will increase participation. <br>

Class preparation for tests. A well structured class covering the areas to be evaluated with practice tests, would definitely will create the conditions to increase the score of the participants. <br>

Free or low cost study materials preparation for tests. Associated with precious point, support with study materials could benefit score marks for the participants.<br>
