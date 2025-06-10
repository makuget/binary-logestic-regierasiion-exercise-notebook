# binary-logestic-regierasiion-exercise-notebook



1, Data exploration and visualization
2, Average numbers for all columns
3,From above table we can draw following conclusions,

**Satisfaction Level**: Satisfaction level seems to be relatively low (0.44) in employees leaving the firm vs the retained ones (0.66)
**Average Monthly Hours**: Average monthly hours are higher in employees leaving the firm (199 vs 207)
**Promotion Last 5 Years**: Employees who are given promotion are likely to be retained at firm
4,Impact of salary on employee retention
5, Above bar chart shows employees with high salaries are likely to not leave the company
6, Department wise employee retention rate
7, From above chart there seem to be some impact of department on employee retention but it is not major hence we will ignore department in our analysis
8, From the data analysis so far we can conclude that we will use following variables as independant variables in our model
**Satisfaction Level**
**Average Monthly Hours**
**Promotion Last 5 Years**
**Salary**
9, Tackle salary dummy variable

Salary has all text data. It needs to be converted to numbers and we will use dummy variable for that. Check my one hot encoding tutorial to understand purpose behind dummy variables.
10, Now we need to remove salary column which is text data. It is already replaced by dummy variables so we can safely remove it
11,accuracy of model
