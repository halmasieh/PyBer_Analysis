# PyBer_Analysis

## Project Overview
This project is done as follows: 
   - Inspect data
   - Merge data sets
   - Perform calculations
   - Create data series and dataframes.
   
 Using the software environment Jupyter Notebook and Pandas and applying two-dimensional plotting library Matplotlib, assist us to produce publication quality figures
 and tell a visual story from the data which means to present complex findings in a way that is informative and engaging to all the stackholders. 
 
 In fact, the specific purpose of this analysis to create a summary dataframe of the ride-sharing data by city type and then using pandas and Matplotlib to create 
 a multiple-line graph that shows the total weekly fares for each city type. 
   
  

## Resources
- Data Sources: city_data.csv, ride_data.csv
- Software: [Anaconda(Jupyter Notebook)](https://www.anaconda.com/products/individual), [Matplotlib-Python Plotting](https://matplotlib.org/) 
- Module: Pandas, Numpy, Matplotlib.pyplot

## Results
Looking at the ride-sharing dataframe, we can see:

There is at least one outlier, which is close to 40. This our maximum data point, 39.
The minimum is 12.
The median is 24 or the 50th percentile.
The standard deviation is about 5 because the box upper and lower boundaries represent the upper and lower quartiles.

![here](https://github.com/halmasieh/PyBer_Analysis/blob/main/ride_sharing_data.PNG)

   - The total budget for 15 covered schools is specified with a subtlety of 39170 students.
   - The average grades of the math and reading courses are specified.
   - The percentage of passing math and reading are reported.




2. How is the school summary affected?

As seen in the following DataFrame: 

![here](https://github.com/halmasieh/School_District_Analysis/blob/main/Resources/school_summary.PNG)

   - Information on the total number of students as well as school type is available by school name.
   - The budget allocated to each school and each student is known.
   - The average math score and reading score ia available long with the passing percentage of these courses.  
   
   
   
   
 3. How does replacing the ninth-graders' math and reading scores affect High School's performance relative to the other schools?

As seen in the following DataFrame: 

![here](https://github.com/halmasieh/School_District_Analysis/blob/main/Resources/THS-9th.PNG)

   - The values related to the math and reading scores of ninth-graders have unknown values.
   - lack of the ninth-graders' math and reading scores affects the school average as well as the percentage of passing.
   
 
 
 
4. How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade:
  
  Information on math score and reading score is highlighted below.
  
   ![here](https://github.com/halmasieh/School_District_Analysis/blob/main/Resources/Math-Reading-NaN.PNG)
  
  
  - Scores by school spending:
  
  After replacing all the math and reading scores from the ninth grade at Thomas High School with NaN, "Spending Ranges (Per Student)" has not changed.
  
  ![here](https://github.com/halmasieh/School_District_Analysis/blob/main/Resources/Spending_range_THS.PNG)
  
  
  
  - Scores by school size:
  
  After replacing all the math and reading scores from the ninth grade at Thomas High School with NaN, "School Size" has not changed.
  
  ![here](https://github.com/halmasieh/School_District_Analysis/blob/main/Resources/School_Size.PNG)
  
  
  
  - Scores by school type:
  
  After replacing all the math and reading scores from the ninth grade at Thomas High School with NaN, "School Type" has not changed.
   
  ![here](https://github.com/halmasieh/School_District_Analysis/blob/main/Resources/School_type.PNG)
   

## Summary
After replacing the values of reading and math scores with "NaN"s, the values of the "School Type", "Total Students", "Total School Budget" and "Per Student Budget"
have not changed, and have been influential in associated with math and reading scores
- " Average Math Score" has moved to 83.350937
- " Average Reading Score " has moved to 83.896082 
- " % Passing Math " has moved to 93.185690
- " % Passing reading " has moved to 97.018739
- " % Overall Passing " has moved to 90.630324


![here](https://github.com/halmasieh/School_District_Analysis/blob/main/Resources/Four_Major_Changes.PNG)
