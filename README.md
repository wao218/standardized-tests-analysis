<img src="http://imgur.com/1ZcRyrc.png" style="float: left; margin: 20px; height: 55px">

# Project 1: Standardized Test Analysis

---
## Problem Statement

The Steppingstone Foundation recently established their program in the state of California in the 10 largest public school districts. Over the past few years they've noticed a problem with some students ability to gain acceptance into private schools. They want to know within each district, which public high schools would be potential candidates to explore as recommendations for students and their families, if they wanted to send students to the top 50 ranked US colleges or universities.


## Data Dictionary

#### SAT By College Data Dictionary 
|Feature|Type|Dataset|Description|
|---|---|---|---|
|**school**|*object*|SAT by College|Name of each indiviual school|
|**low_score**|*float*|SAT by College|Lowest possible score to be considered for admittance|
|**high_score**|*float*|SAT by College|High score to be considered for admittance|

([data source](https://www.compassprep.com/college-profiles/))

#### 2019 California High School SAT Data Dictionary ([source](https://www.compassprep.com/college-profiles/))

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**school_name**|*object*|2019 California High School SAT Scores|Name of high school|
|**district_name**|*object*|2019 California High School SAT Scores|Name of district|
|**county_name**|*object*|2019 California High School SAT Scores|Name of county|
|**enrollment11**|*float*|2019 California High School SAT Scores|Enrollment of Grade 11|
|**num_testtakers11**|*float*|2019 California High School SAT Scores|Number of Test Takers Grade 11|
|**num_erwbenchmark11**|*float*|2019 California High School SAT Scores|The number meeting the Evidence-Based Reading & Writing (ERW) benchmark established by the College Board for Grade 11|
|**pct_erwbenchmark11**|*float*|2019 California High School SAT Scores|The percent of students who met or exceeded the benchmark for Evidence-Based Reading & Writing (ERW) test for Grade 11|
|**num_mathbenchmark11**|*float*|2019 California High School SAT Scores|The number of students who met or exceeded the benchmark for the SAT Math test for Grade 11|
|**pct_mathbenchmark11**|*float*|2019 California High School SAT Scores|The percent of students who met or exceeded the benchmark for SAT Math test for Grade 11|
|**total_num_bothbenchmark11**|*float*|2019 California High School SAT Scores|The total number of students who met the benchmark of both Evidence-Based Reading & Writing (ERW) and Math Grade 11|
|**pct_bothbenchmark11**|*float*|2019 California High School SAT Scores|The percent of students who met the benchmark of both Evidence-Based Reading & Writing (ERW) and Math Grade 11|

([data source](https://www.cde.ca.gov/ds/sp/ai/)) |
([*source for California data dictionary descriptions*](https://www.cde.ca.gov/ds/sp/ai/reclayoutsat19.asp))


## Summary of Analysis

In my analysis I found the top 50 ranked colleges / universities and found their SAT admission score ranges. From their I figured out in each district which schools had 60% or more students who participate in taking the SAT. From those schools I found which schools had 60% or more of their students meet or exceed the SAT benchmarks for both sections stated by the College Board.

## Conclusions and Recommendations

The key take aways from my analysis are there are only 7 out of the 10 districts with schools who have more than 60% of their students take the SAT. The remaining districts have schools who have more than 40% of their students take the SAT. I recommend further investigation into Capistrano Unified district, Corona-Norco Unified district, San Juan Unified district as to see potentially why these districts have low SAT participation rates. Maybe these districts have more ACT participation rates. Out of the 10 largest districts I recommend investigating further into these top schools in each district:

* Elk Grove Unified
    * Valley High
* Fresno Unified
    * University High
    * Design Science Middle College High
* Los Angeles Unified
    * Dr. Richard A. Vladovic Harbor Teacher Preparation Academy
    * Los Angeles Center for Enriched Studies
    * High Tech LA
    * Sherman Oaks Center for Enriched Studies
* San Bernardino City Unified
    * Middle College High
* San Diego Unified
    * Scripps Ranch High
    * Preuss School UCSD
* San Francicsco Unified
    * Lowell High
* Long Beach Unified
    * Eunice Sato Academy of Math & Science
    * California Academy of Mathematics and Science
* Capistrano Unified
    * San Clemente High
    * Aliso Niguel High
    * Tesoro High
* Corona-Norco Unified
    * John F. Kennedy High
    * Santiago High
* San Juan Unified
    * Rio Americano High