---
title: Lab 1
subtitle: 
author: Daniel Anderson
date: '2022-03-04'
assigned: '2021-04-04'
due: '2021-04-11'
slug: lab-1
categories:
  - Assignments
tags:
  - Labs
  - Assignments
---




The purpose of this lab is to get you working with base R looping functions
while also being careful about data types. Your are welcome to work with a
partner or in a small group of 3-4 people.

## Data structures

```r
set.seed(123) # Set random number generation

m <- lm(mpg ~ hp + cyl + drat, mtcars)

l <- list(a = list(m = matrix(1:12, ncol = 3),
              	   v = 1:7),
          b = data.frame(student = 1:15,
                         score = rnorm(15, 100, 10)))
```

Run the above code

1. From the model results:
	* Extract the qr tolerance (`tol`).
	* Extract the term labels from the model.
		+ hint: Use `str` to inspect the list. This one is tricky and involves
		pulling an attribute from an attribute.

2. From `l`
	+ Use at least two different methods to extract `m`.
	+ Extract the third column of `m`. Maintain the dimensions (matrix structure).
	+ Extract the score for student 7 in the data frame.




## Loops

3. Read in the `insurance_coverage.csv` file, which is in the data folder in the repo. Split the data file by `"age_bucket"` and `"sex_name"`.

4. Use a `for` loop to calculate the mean health care population (`hc_pop`) for each `"age_bucket"/"sex_name"` combination.

5. Replicate this calculation with `lapply`, `sapply`, and `vapply`

6. Produce separate plots showing the change in `hc_pop` from 2014 to 2015 for each `"age_bucket"/"sex_name"` combination (with a single loop). Set the `hc_pop` axis so the limits equal the overall minimum and maximum values for `hc_pop`.

7. Use a `for` loop to save the plots to a folder on your computer






