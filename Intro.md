

[Homepage](https://jacob-a-clark.github.io/practicum/)
# Introduction

![img](/images/idph_logo.png)

The IDPH is Iowa’s leader for population health and is financed through state and federal funding.  Through their guiding principles of accountability, collaboration/teamwork, communication, health equity, quality, results orientation, and workforce development, they strive to improve the quality of life for all Iowans by assuring access to quality population-health services.


The 2017-2021 Strategic Plan set forth by the IDPH includes actionable strategic goals that target issues of health and line up with future accreditation by the Public Health Accreditation Board.  A chief goals is decreasing obesity, and one of the action strategies set forth is “assess, identify, analyze, and distribute data related to obesity.”

Obesity: 
- Defined as a BMI > 30
- Over 1/3 of U.S. adults
- 30-35% of adult Iowans
- Linked to high medical costs and health problems like heart disease, diabetes, cancers

Since data on it in Iowa is scarce, this project endeavors to evaluate obesity via proxy by analyzing its related health outcomes.  Using the IDPH Tracking Portal, counts and rates of various health aspects were used to pinpoint outlier counties at risk of obesity.  From there, a qualitative review of those counties was done using interviews of local public health workers.  Finally, recommendations and evaluations were given of the Tracking Portal as an appropriate source of data.


Literature review identified eight health aspects highly correlated with obesity:
- Diabetes
- Hypertension
- Myocardial Infarction (heart attack)
- Breast Cancer
- Prostate Cancer
- Colorectal Cancer
- Congestive Heart Failure
- Gallbladder Disease

2013-2015 (aggregated) Counts and age-adjusted rates were fetched from the Tracking Portal from both the in-patient and mortality repositories. 

### Notes on the health aspect pages

R statistical software was used for nearly all the work done with the data. Besides providing a “lay of the land,” the tables and graphics were used to address several questions.
- Were the counts at the county level for all aspects large enough to be used? Small counts can lead to unstable and unreliable analyses and contribute to poor age-adjusted rates.
- Are there any obvious patterns that could be of concern or help?  Graphics are particularly helpful, as distributions and map depictions of the various aspects can quickly show potential outliers or geographical clustering that should be taken into consideration.
- Do the in-patient and mortality data present similar results?  This a key question because the in-patient and mortality data could be merged together by county and health aspect, but that would only be viable if they showed similar results when comparing an aspect’s mortality and inpatient data.
To tackle this last question, several different graphics using the age-adjusted data were compared.  Using raw counts would have been inappropriate since bigger counties and older-aged counties would have completely skewed the results and display unfair contrasts.  For each health outcome (e.g. diabetes), a pair of bar graphs were displayed side-by-side to check for similarities or differences in distributions between mortality and in-patient data.  Next, Iowa maps colored by rates per county were compared to understand potential geographical characteristics in the two data.  Instead of only juxtaposing the two data, a ratio map and bar graph were also drafted for each health aspect.  As the rates tended to be higher for one data, the color would become more vibrant red or blue for mortality or in-patient respectively.  This entire process took some time as various other types of visualizations were designed to help assess the two data, but the ones previously described were decided on because we felt they best described the data.  After reviewing all the graphics, we were surprised to discover a paucity of correlation or pattern between mortality and in-patient data for almost any of the health outcomes.  This conclusion lead us to decide that treating the two types of data separately was the most suitable course of action in ranking the counties.

