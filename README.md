# School_District_Analysis
Module 4 Anaconda

## Overview of the School District Analysis

The School_District_Analysis data shows testing results, for math and reading, by schools within the district.  We are able to show how each school is performing by grade level, type and size.

A recent discovery shows that the testing data for 9th graders at Thomas High School is not accurate.  We need to redo the overall analysis project by changing all of their scores to NaN (null) and recalculating the results.




## Results

### How is District Summary affected?

We first had to modify the data for 9th graders at Thomas High School.  This was done by replacing all the math and reading scores with a Null value (np.NaN)

![Modify Data](https://github.com/ckbauman/School_District_Analysis/blob/main/Modify_Data_1-4.png)

The results show that the data has been modified.

![Modify Output](https://github.com/ckbauman/School_District_Analysis/blob/main/Modify_Data_Output.png)

We then needed to make adjustments to the District Summary and recalculate the total student count.

First we determined how many students are in 9th grade at Thomas High School.  Then we calculated an adjusted student count subtracting the 9th graders.  We found count totals:

- Total District Students: 39,170
- Thomas High School 9th:  461
- Adjusted Total Students: 38,709

![Modify Count](https://github.com/ckbauman/School_District_Analysis/blob/main/Modify_Student_Count.png)

Next we adjusted the passing percentages, for math and reading, using the adjusted total.  We also modified an overall percentage for both together.


![Modify percent](https://github.com/ckbauman/School_District_Analysis/blob/main/Modify_Student_Percent.png)

The following shows results of the modification:

- Original District Summary:

![summary original](https://github.com/ckbauman/School_District_Analysis/blob/main/Dist_Summary_original.png)


- Adjusted District Summary:

![summary modified](https://github.com/ckbauman/School_District_Analysis/blob/main/Dist_Summary_modified.png)

Results show little impact on the overall totals, especially rounded to the whole number.


### How is School Summary affected?

We also broke out the data to show a summary by school.  We were able to show the results for Thomas High School (THS) before we modified the summary.

![THS summary original](https://github.com/ckbauman/School_District_Analysis/blob/main/THS_summary_original.png)

To adjust the data, first we had to determine how many students are in 10-12 grade at Thomas High School since we will not be using 9th grade scores.

![THS student count](https://github.com/ckbauman/School_District_Analysis/blob/main/THS_student_count.png)

Next we determined how many THS students were passing math and reading individually as well as overall for both.  Passing is a score greater then 70.

![THS student passing](https://github.com/ckbauman/School_District_Analysis/blob/main/THS_student_passing.png)

Then we determined what percent of THS students were passing math and reading.  We calculated this using the adjusted THS Total.

![THS student percent](https://github.com/ckbauman/School_District_Analysis/blob/main/THS_Student_Percent.png)

Once we adjusted everything, we needed to update the School Summary to reflect the adjustements for Math, Reading and Overall.

![THS student replacement](https://github.com/ckbauman/School_District_Analysis/blob/main/THS_student_replacement.png)

The results show the Modifed School Summary

![THS summary modified](https://github.com/ckbauman/School_District_Analysis/blob/main/THS_summary_modified.png)

### How does replacing the 9th graders' math and reading scores affect Thomas High School's performance relative to other schools?

The THS adjustments made minimal impact with comparison to other schools.

- District Original top 5 output

![Dist top 5](https://github.com/ckbauman/School_District_Analysis/blob/main/Dist_top_5.png)

- Modified District top 5 output

![THS summary high](https://github.com/ckbauman/School_District_Analysis/blob/main/THS_summary_high.png)

As you can see, THS now has an Overall Passing rate of 90.63% which leaves them in the top 5 schools in the District.  There is minimal impact if rounded to a whole number.

## Summary

### How does replacing THS 9th grade scores affect math and reading scores by grade?

Math and Reading scores per school reflect that the THS 9th grade scores were modified to a Null value indicated by NaN in the Analysis. Overall Math and Reading Averages showed minimal impact by changing THS null values.

![THS summary math](https://github.com/ckbauman/School_District_Analysis/blob/main/THS_summary_math.png)
![THS summary reading](https://github.com/ckbauman/School_District_Analysis/blob/main/THS_summary_reading.png)


### How does replacing THS 9th grade scores affect scores by school spending?

Summaries for school spending ranges shows no changes to the results.  Overall, there was little impact on the scoring because of the removal of the 9th grade values.

- District spending Original output
![Dist spending original](https://github.com/ckbauman/School_District_Analysis/blob/main/Dist_spending_original.png)

- Modified District spending output
![THS spending modified](https://github.com/ckbauman/School_District_Analysis/blob/main/THS_spending_modified.png)

### How does replacing THS 9th grade scores affect scores by school size?

Summaries for school spending ranges shows no changes to the results.  Overall, there was little impact on the scoring because of the removal of the 9th grade values.

- District Size Original output
![Dist size original](https://github.com/ckbauman/School_District_Analysis/blob/main/Dist_size_original.png)

- Modified District size output
![THS size modified](https://github.com/ckbauman/School_District_Analysis/blob/main/THS_size_modified.png)


### How does replacing THS 9th grade scores affect scores by school type?

Summaries for school spending ranges shows no changes to the results.  Overall, there was little impact on the scoring because of the removal of the 9th grade values.

- District type Original output

![Dist type original](https://github.com/ckbauman/School_District_Analysis/blob/main/Dist_type_originial.png)

- Modified District type output

![THS type modified](https://github.com/ckbauman/School_District_Analysis/blob/main/THS_type_modified.png)

