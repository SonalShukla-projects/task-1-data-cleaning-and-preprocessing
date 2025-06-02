### TASK 1 - DATA CLEANING AND PREPROCESSING
**Project Title**
Netflix Dataset Cleaning and Preprocessing

**Description**
This project involves cleaning and preparing a raw Netflix dataset to make it ready for analysis. The dataset contains information about shows and movies including type, title, director, cast, country, date added, duration, and genres.

**Dataset**
The data was sourced from Kaggle and contains columns such as show_id, type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, and description.

**Data Cleaning and Preprocessing Steps**
1. Handled missing values by filling or imputing where necessary.

2. Removed duplicate records to maintain data integrity.

3. Standardized text columns by converting to lowercase and stripping whitespace.

4. Converted date_added to datetime format and extracted features like year, month, and quarter added.

5. Split multi-genre columns into lists for better analysis.

6. Extracted numeric values and units from the duration column and created separate columns for these.

7. Converted categorical columns to the ‘category’ datatype for efficient storage and analysis.

8. Dropped unnecessary columns to keep the dataset clean and focused.

**Usage**
Open the Jupyter Notebook (.ipynb) file in JupyterLab or Jupyter Notebook and run the cells to reproduce the cleaning and preprocessing steps.

**Questions**
**1. What are missing values and how do you handle them?**
Missing values are data points that are empty or null. You handle them by removing rows/columns, filling with mean/median/mode, or using advanced methods like interpolation.

**2. How do you treat duplicate records?**
Find duplicates using duplicated() and remove them with drop_duplicates() to ensure data accuracy.

**3. Difference between dropna() and fillna() in Pandas?**

dropna() removes rows or columns with missing data.

fillna() replaces missing values with a specific value like mean or zero.

**4. What is outlier treatment and why is it important?**
Outlier treatment deals with extreme values that can distort analysis. It's important to improve model performance and data quality.

**5. Explain the process of standardizing data.**
Standardizing scales data to have a mean of 0 and standard deviation of 1, making features comparable.

**6. How do you handle inconsistent data formats (e.g., date/time)?**
Convert all values to a consistent format using parsing functions like pd.to_datetime().

**7. What are common data cleaning challenges?**
Missing data, duplicates, inconsistent formats, outliers, and incorrect data types.

**8. How can you check data quality?**
By reviewing missing values, duplicates, data types, summary statistics, and ensuring consistency.
