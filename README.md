# School District Analysis

## Overview of Project
The purpose of this project is to use Python and Pandas to analyze testing data from 15 specific schools within a district. In order to perform the analysis, we needed to clean and format the data to achieve uniformity across the dataset. The stakeholders have requested that we then use the cleaned data to provide various metrics broken down from the overall district to individual schools and grades. This analysis will assist the school board in decisions regarding future funding for each school as well as spot trends, correlations and discrepencies within the school district.

## Analysis Results

After performing the first analysis, the school board spotted a discrepency within the 9th grade scores at Thomas High School. It was determined that these scores would need to be thrown out, which in turn, changed the overall results.

### District Results
As seen in the tables below, after removing the scorse for Thomas High School freshman, the average reading and math passing rate dropped by roughly 1%

**District Summary Prior to removing Thomas High School 9th Grade scores:**

![District Summary](https://github.com/Ian-T-Dixon/School_District_Analysis/blob/main/Resources/district_summary_old.PNG)

**District Summary After changing Thomas High School 9th Grade Scores to NaN:**
![District Summary](https://github.com/Ian-T-Dixon/School_District_Analysis/blob/main/Resources/district_summary_new.PNG)

### School Results
As seen in the tables below after changing the Thomas 9th grade scores to NaN, the overall pass % for the school dropped significantly. However, by removing the 9th graders scores from the dataset, the average scores revert back to a level more similiar to the original data. Additionally, we can see that by changing the 9th graders scores to Nan, it drops Thomas High School into the bottom 5 schools in the district.

**School Summary Prior to changing Thomas High School 9th Grade scores:**
![School Summary](https://github.com/Ian-T-Dixon/School_District_Analysis/blob/main/Resources/per_school_summary_old.PNG)

**School Summary After changing Thomas High School 9th Grade Scores to NaN:**
![School Summary](https://github.com/Ian-T-Dixon/School_District_Analysis/blob/main/Resources/per_school_summary_new.PNG)

**School Sumamry After Changing Thomas High School 9th Grade Scores:**
![Thomas School Summary](https://github.com/Ian-T-Dixon/School_District_Analysis/blob/main/Resources/per_school_summary_thomas_new.png)

**School Summary After Removing Thomas High School 9th Grade Scores:**
![Less 9th Grade Thoams Scores](https://github.com/Ian-T-Dixon/School_District_Analysis/blob/main/Resources/per_school_summary_less9_new.PNG)

**Math Scores by Grade Prior to changing Thomaas High School 9th Grade Scores:**

![math scores old](https://github.com/Ian-T-Dixon/School_District_Analysis/blob/main/Resources/math_scores_by_grade_old.PNG)

**Math Scores by Grade After changing Thomaas High School 9th Grade Scores:**

![math scores new](https://github.com/Ian-T-Dixon/School_District_Analysis/blob/main/Resources/math_scores_by_grade_new.PNG)

**Reading Scores by Grade Prior to changing Thomaas High School 9th Grade Scores:**

![reading scores old](https://github.com/Ian-T-Dixon/School_District_Analysis/blob/main/Resources/reading_scores_by_grade_old.PNG)

**Reading Scores by Grade After to changing Thomaas High School 9th Grade Scores:**

![reading scores new](https://github.com/Ian-T-Dixon/School_District_Analysis/blob/main/Resources/reading_scores_by_grade_new.PNG)


**Scores by School Spending Prior to changing Thoams High School 9th Grade Scorse**

![school spending old](https://github.com/Ian-T-Dixon/School_District_Analysis/blob/main/Resources/scores_by_spending_old.PNG)

**Scores by School Spending After to changing Thoams High School 9th Grade Scorse**

![school spending new](https://github.com/Ian-T-Dixon/School_District_Analysis/blob/main/Resources/scores_by_spending_new.PNG)

**Scores by School Size Prior to changing Thoams High School 9th Grade Scorse**

![school size new](https://github.com/Ian-T-Dixon/School_District_Analysis/blob/main/Resources/scores_by_school_size_old.PNG)

**Scores by School Size After to changing Thoams High School 9th Grade Scorse**

![school size new](https://github.com/Ian-T-Dixon/School_District_Analysis/blob/main/Resources/scores_by_school_size_new.PNG)

**Scores by School Type Prior to changing Thoams High School 9th Grade Scorse**

![school type old](https://github.com/Ian-T-Dixon/School_District_Analysis/blob/main/Resources/scores_by_schooltype_old.PNG)

**Scores by School Type After to changing Thoams High School 9th Grade Scoores**

![school type new](https://github.com/Ian-T-Dixon/School_District_Analysis/blob/main/Resources/scores_by_school_type_new.PNG)

