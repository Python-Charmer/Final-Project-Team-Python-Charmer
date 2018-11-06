# Final-Project-Team-Python-Charmer
M.S. Data Science at Indiana University | Python I590 | Final Project | Team Python Charmer

# Final Project, Phase 1 (30%)
See also on Final Project Module. Please read the entire announcement.

 

Note: Week 12 you will be provided with a notebook practice constructing KMeans clusters.

Please do NOT discuss your solutions or request answers about Final Project. Your instructors provided you with exhaustive information on functions usage and helpful suggestions. If you run into an issue, consider consulting available resources in pandas, scikit, matplotlib online manuals. [If some of you have a strong background in python and feel that this project is not challenging, note this course is meant to be for beginners  and we need to accommodate the final project to the appropriate level.]

 

During the first week, you need to complete following data analysis tasks.

Download the data and load it in Python
Impute missing values
Plot basic graphs
Compute data statistics
 

Detailed information:

You will work with breast cancer data (see attached data in Final project Module Phase 1)
Make sure github is set as public
Create one folder for data, one folder for code, one readme file to report your contributions for three phases. 
- Readme file should be automatically created when you initiate your github project
- You can edit readme file on github by selecting edit. If you do not know Markdown syntax, use simple style, see an example below. Commit changes - you can add to commit message "update readme file"
You can work using notebook for the entire final project. Place your notebook into your code folder. Note you need to use a correct path for your project file which will be in data folder
You can use Github Desktop to upload and sync your files
On Canvas - submit a link to github and upload your notebook report. You can select a team leader to upload files on your group behalf.
Example for Readme file on github

# Phase 1

Name 1: contribution....

Name 2: contribution....

Name 3: contribution....

# Phase 2

# Phase 3

 

Detailed Instructions and Additional Help with tasks:

Make sure to import using the correct path with your dataset in data folder. Use '../data/Breast-Cancer-Wisconsin.csv' for a path. Remember to keep dataset in data folder and notebook in code folder.
* Replace '?' by NaN in column A7. Use ____.replace('?', np.NaN) - but properly specify A7 column.
* After replacement - your column needs to be converted back to numeric. Apply pandas function pd.to_numeric() to column A7
* Report how many NaN. Use isnull() function applied to the dataframe. Then you can use arithmetic sum()
* Replace NaN values with the mean of column A7. Use fillna() - find how to calculate mean of the column, add a parameter skipna=TRUE. * Apply this function to the entire df - you do not need to specify here column A7
* Provide the summary statistics - you can use describe() function
* Find number of columns and number of rows - hint use ___.shape[] - use a proper index for column and row (consult pandas). Report how many observations (row) and columns
* Report how many unique id values (column Scn) - hint the length of unique ids
* Draw histograms for columns A2-A10. Note: you need to subset your dataframe - slice only columns A2-A10. Use histogram function, add a color of your choice. Note you need to run hist() function on your dataframe with selected columns only. It will output all 9 columns as subplots. Here do not worry about individual titles, y and x axis. You could adjust bins and alpha (opacity) on your histograms
* Draw a bar plot for CLASS - you can use groupby to see counts of  benign and malignant values or you can count values directly using pd.value_counts() function and apply it to plot.bar() function.
* Draw a scatterplot of any two columns. 
* Summarize by reporting which values might need standardization in the future (too much variation) and any other observations that you may discover as a Data Scientist.

##Grading criteria - 30 pts

 * Data cleaning - report Number of NaN, replace ?, impute NaN by the column mean. 5 pts
* Data Stats 5pts
* Plotting Scatterplot and Bar Plot must have titles,y axis and x axis names, non-default colors. 9 histograms (subfigures) do not have to have titles. 5pts
* Import libraries, Proper data import 5pts
* Github set up with one folder for code and one folder for dataset 5pts
* Readme file with contributions 5pts

 

Let us know if you have any questions related to 1) instructions, 2) submission, 3) grading. We will not be answering your questions about specific coding and errors. Only general questions will be answered.

