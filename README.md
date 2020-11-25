# Python_Project
294A- Python Lab Supriya Rani | Qili Zhou
Project Proposal
As a team, we are interested in knowing what are those characteristics which can classify people into those who earn
low levels of annual income from the ones having relatively decent annual income. The reason behind this could be
various, such as, low level of skill (a proxy could be the level of education), persons’ gender, life situation which
adversely affects or favors the individual’s growth, etc. Using this information (given the characteristics associated with
them), we want to be able to predict whether a person will likely have a lower income or income above a threshold.
Also, this would help us in generating a map which would show what income to expect if a person has some given
characteristics. The threshold level of income used is an annual salary of $50,000.
This is interesting to us because if we know what is causing a set of people to have salaries below a threshold level, then
we may be able to help them by providing the required resources like, education, right policy that protect them, etc.
People who may be interested in this question are: Policy makers, government, social activist (simply those who want
to work for the welfare of people with low levels of income).
Data
For this project, we are using Adult Census Income data.
This data set was extracted by Ronny Kohavi and Barry Becker, from the U.S. Census Bureau database- 1994 and 1995,
Current Population Surveys.  It contains the extracted weighted census data and has 41 employment and demographic
related variables. While the original table contained 199,523 rows and 42 columns, the versions that we are using
contain 15 columns and 32,562 rows.
Using Python
We will first split the data into training and test groups and create our classifier object. The classifier object will then be
trained (fitted) using the train data. This, basically, creates the estimator. We can use this estimator to predict whether
the person’s annual income exceed $50,000.
