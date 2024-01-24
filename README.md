# PISA_cross_country_comparison
Analysis of Global PISA scores and economic school factors

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Data cleaning and Preperation](#data-cleaning-and-preperation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results and Findings](#results-and-findings)
- [Recommendations](#recommendations)


### Project Overview

|Analysis Steps|Tools|
|--------------|-----|
|Data Cleaning|Excel, Python|
|Data Preperation|Excel, Python|
|Data Analysis|SQL, Python, Tableau|
|Findings and Recommendations|Tableau|


### Data Sources

All sources came from [kaggle.com](https://www.kaggle.com)

-pisa2009train.csv
-capstonewithglobalschoolinfo.csv
-PISAmeanperformancescores2015.csv

### Data cleaning and Preperation

In the intial data preperation phase, we performed the following tasks:
1. Data loading and inspection
2. Handling null values
3. Data cleaning and formatting

### Exploratory Data Analysis

EDA involved in exploring U.S. and Global PISA Scores

- How do scores compare around the world?
- What factors influence higher or lower scores?
- What can the U.S. do to improve PISA scores?

### Data Analysis

For this analysis, I initially intended on looking specifically at parental factors that influence the Program for International Student Assessment (PISA) scores. The PISA focuses on math, reading and science among 15-year-olds around the world. There were significant differences in students’ scores pertaining to the mothers’ and fathers’ education and work levels. However, a considerable portion of the father-related data had an absence of at least 10% or more. For that reason, I chose not to focus only on parental factors for influence. 

My second approach was to look at a global comparison of PISA scores. I also wanted to evaluated select economic school factors from the Organization for Economic Cooperation and Development (OECD). My assumption was that certain factors play a roll in how students score on the PISA around the world. I also wanted to comparatively evaluate the United States to see where US scores fall in relation to other countries. 
For global economic factors and average scores associated with schools I used a PISA&OECD 2018 global school info data set along with global mean performance scores from 2015. For further information on US PISA scores and influential factors, I looked at a 2009 American PISA Evaluation data set. The data sets coming from different time frames is not ideal. However, I feel this information still indicates what global scores look like today. 
Through my analysis I identified the Top 3 countries with the highest Mean Performance Scores on the PISA and evaluated 3 economic school factors: student to teacher ratio, computer to student ratio, and the average number of extra-curricular activities offered in schools within that country.

![image](https://github.com/lilligubran/PISA_cross_country_comparison/assets/155771979/5bb552cf-d3e4-45a2-a613-3296783bd5c8)

![image](https://github.com/lilligubran/PISA_cross_country_comparison/assets/155771979/5079312b-2811-4947-9558-4cc12f64986a)

![image](https://github.com/lilligubran/PISA_cross_country_comparison/assets/155771979/af80586a-1f46-4284-9e22-648f36f7c604)


### Results and Findings

I then evaluated the US and compared values associated with the different factors. When it comes to computers and extra-curriculars (ECs), the US is on par and even ahead with 2.8 ECs on average per school and a computer to student ratio of 94.4%. The top 3 scoring countries operate with student to teacher ratios of 10-14 students per teacher.  The US operates with a student to teacher ratio of 17 students (on average) per teacher. This seems to be where the US falls short, and our mean performance scores reflect it. 

Looking more closely at the US with the PISA 2009 data set for American students I identified other areas our teachers and parents can improve to benefit students. When looking at ethnic groups of students, there are groups that score significantly less than others. Black and American Indian/Alaska Native students score about 100 points less on average than Asian and White students. These students may not be receiving the same attention from teachers as others or may require more attention than they currently receive. Females also tend to score lower than males. When I took a closer look at parental factors, I found 2 to be significant. Students whose mothers finished high school scored about 50 points higher on average than those whose mothers did not finish high school. Also, students who plan to attend college scored almost 100 points higher on average than those who don’t plan on attending college. 

### Recommendations

In conclusion, there are several areas for improvement within the US to raise PISA scores. Some of them start at home. If you want to be a parent, make sure you finish high school, and your child may be better off. Parents should also consider having a college plan for their kids. If students plan on attending college, they tend to score higher. Within US schools the student to teacher ratio should not exceed 15 students per teacher. Nation-wide block scheduling could be a potential solution. Lastly, we need to make sure that every student receives the same support within US schools. Whether your male, female, or ethnically diverse every student deserves the same amount of support while learning. 



