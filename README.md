# Machine-Learning-Models-on-Healthy-Pizza-Dataset-
The aim of this project is to predict the calories of pizza. After loading all the relevant libraries along with some additional ones, I loaded the data set and named the data frame as pizza.  This data set consists of the components of Pizza which makes it healthy in which there are 300 rows and 9 columns present.

Here is the project synopsis in the form of a youtube video: 

https://www.youtube.com/watch?v=vCclufJJdEs&ab_channel=RaghvendraSinghShaktawat

Some of the key features of this project are:
• Visualized the data present in the form of histograms, line graphs, box plots, and density plots
• Inserted some NA values into a new data frame so that I can perform mean imputation
• Performed mean imputation to take care of the missing values
• Performed the hot-encoding for all the different brands of pizza present in the dataset.
• For indicating the initial overview of the data and to show different groups of data with different colors I used pairs.panels by using the Psych package. Thus, each individual plot is going to show the relationship between the variables in the horizontal and vertical grid.
• For checking the normality of each column, I used the Shapiro-Wilk normality test.
• Represented the correlation between the different columns of the pizza data frame by using Pearson’s method.
• Visualized how every column of the pizza dataset looks through a univariate visualization which shows histograms of each attribute.
• Performed the z score standardization by calculating the z score for each column. I used the minimum-maximum scaling method to normalize the values where the data values have a range from 0 to 1.
• Performed the splitting of the data set in the ratio of 80:20 where 80% of the data represents the training set and the remaining 20% represents the validation set.
• MODEL 1: LOGISTIC REGRESSION MODEL
• MODEL 2: RANDOM FOREST MODEL
• MODEL 3: K-NEAREST NEIGHBORS MODEL
• MODEL 4: SUPPORT VECTOR MACHINE MODEL
• Compared the results of all these models using dotplot
• Created model ensemble
