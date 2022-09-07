# cscib522_data_mining_project

A continuation of the [Linear Regression project that I did for my CSCIB500 course](https://github.com/cheddahz/cscib500_nba_linear_regression), I utilized
the skills I had learned during my Data Mining course (CSCIB522) to further look into the relationship the Player efficiency rating (PER) has with the rest of 
the recorded statistics.

To do this,  I had to convert the comma-seperated values (CSV) file previously used for the testing into a attribute-relation file format (ARFF) so that the
information could be usable in the Weka environment, where I used a linear regression algorithm and ran multiple tests to see if there was any correlation 
with the PER statistic and the rest of the dataset.

After running the tests and looking at the visualizations of the linear regression algorithms, I compared the correlation coefficient, mean absolute error, 
root squared error, relative squared error, and the root relative squared error results and see if the amount of folds (test) affects the results.
