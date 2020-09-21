---
title: Data Science Venn Diagram
type: exercise
creator:
    name: Alexander Combs
    city: NYC
---

# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png)  Data Science Venn Diagram

 This is a team-based competition. The goal is to create the best performing model on a hold-out sample of data.

This will be a constrained optimization. The idea is that for any project you can have any two of these. You can have good work done cheap, but it will take a long time. You can have good work done fast, but it won't be cheap. Or you can have work done fast and on the cheap, but it won't be good.

![](https://berkonomics.com/wp-content/uploads/2015/11/goodfastcheap1-1.png)

You will be given a dataset and teams will be randomly assigned to one constraint: samples, features or algorithm.

---

- Team member: Laura Luo, Mikhail Lenko, Patrick Wales-Dinan
- We are Team Sample Constraint
- Steps:
1. Data Cleaning and EDA
2. Modeling (with Visualization since it performs better than Modeling with OverSampling)
3. Modeling with OverSampling
- Conlusions: 
1. SVC(or AdaBoostClassifier) is the model who performs the beter
2. Accuracy Score: training 0.87, testing 0.86, cross-validation 0.85
- Descriptions of the data can be found [here](https://archive.ics.uci.edu/ml/datasets/adult). 
 
 ---

The task is to predict if a person's income is in excess of $50,000 given certain profile information, and more specifically to generate predicted probabilities of income being **above** $50,000 for each row in the test set. This will simply be a csv with a single column of the probability  **_with 'wage' as a header_**.
