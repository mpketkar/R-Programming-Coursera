# R-Programming-Coursera

Question 1: The R language is a dialect of which of the following programming languages?
S	
Correct	1.00	
R is a dialect of the S language which was developed at Bell Labs.

Question 2
The definition of free software consists of four freedoms (freedoms 0 through 3). Which of the following is NOT one of the freedoms that are part of the definition?
The freedom to sell the software for any price.	
Correct	1.00	
This is not part of the free software definition. The free software definition does not mention anything about selling software (although it does not disallow it).
The freedom to redistribute copies so you can help your neighbor.			

Question 3
In R the following are all atomic data types EXCEPT
list	
Correct	1.00	
'list' is not an atomic data type in R.

Question 4
If I execute the expression x <- 4 in R, what is the class of the object `x' as determined by the `class()' function?
numeric	
Correct	1.00	

Question 5
What is the class of the object defined by x <- c(4, TRUE)?
numeric	
Correct	1.00	
The numeric class is the "lowest common denominator" here and so all elements will be coerced into that class. R does automatic coercion of vectors so that all elements of the vector are the same data class.

Question 6
If I have two vectors x <- c(1,3, 5) and y <- c(3, 2, 10), what is produced by the expression cbind(x, y)?
a 3 by 2 numeric matrix	
Correct	1.00	
The 'cbind' function treats vectors as if they were columns of a matrix. It then takes those vectors and binds them together column-wise to create a matrix.

Question 7
A key property of vectors in R is that
elements of a vector all must be of the same class	
Correct	1.00	

Question 8
Suppose I have a list defined as x <- list(2, "a", "b", TRUE). What does x[[1]] give me?
a numeric vector of length 1.	
Correct	1.00	

Question 9
Suppose I have a vector x <- 1:4 and y <- 2:3. What is produced by the expression x + y?
an integer vector with the values 3, 5, 5, 7.	
Correct	1.00	

Question 10
Suppose I have a vector x <- c(3, 5, 1, 10, 12, 6) and I want to set all elements of this vector that are less than 6 to be equal to zero. What R code achieves this?
x[x < 6] <- 0	
Correct	1.00	
You can create a logical vector with the expression x < 6 and then use the [ operator to subset the original vector x.

Question 11
In the dataset provided for this Quiz, what are the column names of the dataset?

Ozone, Solar.R, Wind, Temp, Month, Day	
Correct	1.00	
You can get the column names of a data frame with the `names()' function.

Question 12
Extract the first 2 rows of the data frame and print them to the console. What does the output look like?
  Ozone Solar.R Wind Temp Month Day
1    41     190  7.4   67     5   1
2    36     118  8.0   72     5   2
Correct	1.00	
You can extract the first two rows using the [ operator and an integer sequence to index the rows.

Question 13
How many observations (i.e. rows) are in this data frame?
153	
Correct	1.00	
You can use the `nrow()' function to compute the number of rows in a data frame.

Question 14
Extract the last 2 rows of the data frame and print them to the console. What does the output look like?
    Ozone Solar.R Wind Temp Month Day
152    18     131  8.0   76     9  29
153    20     223 11.5   68     9  30
Correct	1.00	
The `tail()' function is an easy way to extract the last few elements of an R object.

Question 15
What is the value of Ozone in the 47th row?
21	
Correct	1.00	
The single bracket [ operator can be used to extract individual rows of a data frame.

Question 16
How many missing values are in the Ozone column of this data frame?
37	
Correct	1.00	
The `is.na' function can be used to test for missing values.


Question 17
What is the mean of the Ozone column in this dataset? Exclude missing values (coded as NA) from this calculation.
42.1	
Correct	1.00	
The `mean' function can be used to calculate the mean.

Question 18
Extract the subset of rows of the data frame where Ozone values are above 31 and Temp values are above 90. What is the mean of Solar.R in this subset?
212.8	
Correct	1.00	
You need to construct a logical vector in R to match the question's requirements. Then use that logical vector to subset the data frame.


Question 19
What is the mean of "Temp" when "Month" is equal to 6?
79.1	
Correct	1.00	

Question 20
What was the maximum ozone value in the month of May (i.e. Month = 5)?
115	
Correct	1.00
