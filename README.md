# School_District_Analysis
Module 4: School District Analysis

## Overview
Having been given two data sets, one holding school information and one holding student information, the analysis was approached from a variety of angles. After cleaning the data by correcting unwanted prefixes and suffixes that could affect reporting integrity, a basic analysis was run to understand school budgets in relation to score averages and overall passing percentages. This was expanded on by pulling budget per student and compiling with per school averages and passing percentages. Following those analysis we were able to identify the top five and bottom five performing schools. The analysis was finalized by completing analysis to group information by spending ranges and school sizes, this helps present the information in a more meaningful way, that can be considerd for decision making, rather than a simple chart or dataframe presentation that would require some interpretation. Upon review, it was noticed that there was academic dishonesty among nonth graders for Thomas High School, therefore these grades were removed and new analysis rendered.

#### Resources
    -schools_complete.csv
    -Students_complete.csv
    -Python, Anaconda, Jupyter Notebook
    
#### Process
With the initial analysis complete and approved, the adjustments required us to only use the tenth, eleventh, and twelfth grades scores from Thomas High School rather for analysis.

## Results
##### DISTRICT SUMMARY
![original_district_summary](https://github.com/RachelRautenberg/School_District_Analysis/blob/main/Resources/original_district_summary.PNG)
![adjusted_district_summary](https://github.com/RachelRautenberg/School_District_Analysis/blob/main/Resources/adjusted_district_summary.PNG)

The adjustment made to account for the academic dishonesty resulted in slightly lower average math scores and passing percentages in math, reading, and overall. The only area that does not show as being affected by the adjustment is average reading. 

##### PER SCHOOL SUMMARY
Because the adjustment was made specifically for Thomas High School, the only change was to the averages and percentages for Thomas High School; while the student count does remain the same, the average and passing information shows slight variation compared to the initial analysis. Thomas High initial results are included below. The other schools remain, understandably, not affected by the adjusted analysis.  The image below is of the final adjusted, since the other schools results were the same as the initial analysis.

![thomas_high_initial](https://github.com/RachelRautenberg/School_District_Analysis/blob/main/Resources/thomas_high_initial.PNG)
![adjusted_per_school](https://github.com/RachelRautenberg/School_District_Analysis/blob/main/Resources/adjusted_per_school_summary.PNG)

##### REMOVAL OF THOMAS HIGH NINTH GRADE DATA
    -


