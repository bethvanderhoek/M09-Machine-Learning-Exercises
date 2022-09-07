# data-cleaning-for-ml

**Instructions for the Assignment**
1. Import the raw data set into a Pandas DataFrame. Perform some exploratory analysis on the raw data set. Check for the types of data hygiene issues mentioned in the lesson. Whenever you find a possible issue, write some code to fix it. Apply your fixes systematically, not case-by-case. Be sure to include comments to explain your process.
2. Find the number of missing values in each column and each row. Remove rows where at least 50% of the values are missing. Then remove columns where at least 50% of the values are missing.
3. Calculate descriptive statistics for each column. Let's define an outlier as a value at least 3 standard deviations away from the mean. Which columns have outliers? What are those values?
4. With the remaining columns, use scikit-learn to impute missing values. For continuous features, fill in the mean. For categorical features, fill in the mode.
5. Combine the date-related columns into one column with the Pandas to_datetime() method, then use that column to create a numeric Age column (in years). Calculate Age based on today's date; it doesn't have to be a whole number. Once you've created the Age column, remove the other date-related columns, including the one you created with Pandas.
6. Create dummy variables for the categorical features. Drop one level of each feature to end up with k-1 dummies, not k.
7. Save your work up to this point. Mark the end of this exercise in your notebook. If you have questions, reach out to an instructor.
