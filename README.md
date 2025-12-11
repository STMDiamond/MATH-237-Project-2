# MATH-237-Project-2
Hi and welcome to the page for my data science project in MATH 237. Using the Student Performance data from the UCI Machine Learning Repository, my project's main goal is studying how specific factors and features can impact or influence a student's academic performance in the form of a final grade. As such, these aspects are:
1. The total amount of time that a student takes to travel from their home toward school in minutes on a daily basis.
2. The total amount of time that a student spends studying for class in hours on a weekly basis.
3. The total number of times that a student has failed a class from the past.
4. The total number of times that a student has been absent from their school.
5. The total number of points that a student has earned as their final grade.
---
In order to investigate whether the first four points directly affect the fifth one or not, I follow the steps below to answer all my research questions:
1. Data Preparation – Import the libraries that are necessary, insert the dataset into the notebook, and view the variables.
2. Missing Data – Search for any missing values and then only focus on these five features by removing the remaining ones.
3. Feature Engineering – Use a mix of one-hot encoding, binning, scaling, and interactions to transform these features.
4. Data Plots – Generate bar plots and boxplots to feature the first two variables while making histograms as well as scatterplots to show the next two variables.
5. Multiple Linear Regression – Break up the data by dividing it into the usual 80-20 split, create a correlation matrix, scale both sets, train the entire model, examine every coefficient in detail, and test the accuracy of the two new sets with a few examples.
6. Ethical Concerns and Data Limitations – Discuss and go over potential problems with certain data that was collected from students while adding ways in which the dataset was flawed.
* **Note:** For both the "Feature Engineering" and "Data Plots" parts, I used the following color key below to distinguish between four of the variables in the graphs.
* Neon Red, Yellow, Green, and Blue – The time taken traveling from home to school in minutes per day.
* Darker Red, Yellow, Green, and Blue – The time spent on studying for school outside of class in hours per week.
* Purple – The total number of failures for a previous class.
* Pink – The total number of absences from school throughout the year.
