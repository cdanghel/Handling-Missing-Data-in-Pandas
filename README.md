# Handling Missing Data in Pandas

Welcome to the Handling Missing Data project! This project aims to assess the existing gaps in data by evaluating what is missing, determining the percentage of missing data for each feature, and exploring strategies to effectively address these gaps.

## Disclaimer
1. This code is not original and was developed by following instructions from the Udemy course
   "Python for Machine Learning & Data Science Masterclass" by Jose Portilla.
2. The course covers various topics related to Machine Learning and Data Science and it spans 44 hours on-demand video.
3. In some cases, modifications or adaptations have been made to the original code to fit specific requirements or enhance functionality.
4. To access the original course materials and learn more, please refer to the "Python for Machine Learning & Data Science Masterclass". available here (https://www.udemy.com/course/python-for-machine-learning-data-science-masterclass/)

## Project Structure
1. Initially, we import the libraries pandas, numpy, matplotlib, and seaborn. Then, we upload the CSV file "Ames_outliers_removed.csv" and remove the PID unique identifier since we already have an index.

2. Subsequently, we inspect the dataset for NaN values and proceed to eliminate both features and rows. We have two alternatives: either remove the rows entirely or fill in the missing data points.

3. Certain features in the dataset exhibit missing data in only one or two rows. As per our description in the .txt file, it would be more convenient to fill in these particular missing data points.
