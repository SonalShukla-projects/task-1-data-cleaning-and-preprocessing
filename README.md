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
