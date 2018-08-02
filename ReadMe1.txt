I will be working with the heart disease dataset for my capstone project. In order to retrieve these datasets, 
I have to download four separate medical datasets from Cleveland, Hungary, Switzerland and Long Beach. All the 
datasets have been reprocessed for data accuracy. I started by working with the Cleveland dataset. I downloaded 
the data in csv format, and opened it in Python. 

The first step I took was to create a column list to append to the data. I described the dataset and looked for 
missing values. Although there were no missing values to be reported, I did see ‘?’ entries where there should 
have been a 0 or a 1. I replaced these entries with a blank space for them to count as missing values. Although 
they have been replaced, the info function does not recognize them as missing values. If the missing values appear 
in variables that I intend to use as a core measure in my analysis, and I believe that it might drastically impact 
my analysis, I might choose to drop them, otherwise, I could fill in the missing values with the previous or following 
entries. This also depends on how many missing variables there are. 

I proceeded to study the data to make sure that the data described matches the criteria. For example, for categorical 
variables with 1 and 0 entries, I would check to make sure the min and max entries are indeed, 0 and 1. 

After studying the data I proceeded to plot the data in a variety of forms in order to better understand the 
distribution as we as look for outliers and consider whether they would have a significant impact on my analysis. 

After completing the analysis on the Cleveland dataset, I will proceed with a similar data wrangling approach 
with the remaining datasets. After cleaning all datasets, I will append the datasets together and use them to 
complete my inferential statistical analysis.  
