In this part, I will be demonstrating the Decision Tree: one of the most common and popular machine learning algorithms for classification problems.
First to understand the basic of decision tree, I strongly suggest you to go through the following link and have a clear concept about decision tree before going to the code part.

https://www.geeksforgeeks.org/decision-tree-introduction-example/

Once you have a clear concept then you can go through the "Decision Tree.ipynb" code file for understanding how the code works.

The dataset.csv is a dataset collected from kaggle.com and basically a dataset where there is 26 attribute for 1470 employee of a particular office. Every column is an employee attribute like MonthlyIncome, Job level etc. The column "Attrition" tell us that whether the particular employee stayed in the company or not (YES or NO). So Depending on the 25 attribute we have to make a decision tree and train our model for the output class (attrition). The model will predict for a new employee (with 25 attribute) whether he/she will going to stay or not.

If we demonstrate our approach, the following tree is generated.  

![](/Decision%20Tree/tree_plot.png)

And we got a decent accuracy of 86.4 %
 

