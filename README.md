# US College Admission Success

## Business Objective:

   1. Build a smart Predictive tool that can assess the chances of a Student's entry into multiple Tier US Tech Schools.
   2. Develop a prototype model that uses Student data to produce admission probability for each student.
   3. Explore historical student data, using statistical analysis and Machine Learning, to understand and identify factors that may affect a Student's success at getting into their dream University.


## Motivation:

After observing many of my friends trying hard and not getting into the University of their choice in the US, I was intrigued by the admissions, which from outside looks like a black-box, could actually be broken down using Analytics and be predicted by Machine Learning. When a candidate gets a low GRE or TOEFL score, it causes much anxiety and tension. So, I look whether they play as much an important role, or there are other factors that can quantitatively outweigh Standardized Test Scores. Furthermore, this tool can help students in building a stronger Profile.
 

## Workflow :

   1. **Importing Libraries**
      
   2. **Data Pre-Processing**
        - 2.1 Reading Data from the csv file.
        - 2.2 Dummification of categorical Variables

   3. **Data Modeling**
        - 3.1 Statistical Learning
            - Building a statistical Regression Model to find statistically significant factors.
            - 3.1.1 Interpret the p-values (Set 5% as level of significance) 
                 - Analyzing important Factors with significance lower than 0.05.
        - 3.2 Machine Learning
            - Making a Machine Learning model that will finally yield the prediction.
  
## Results:

|    **Model**     |    **Percentage RMSE**    | **R square**   | **Adjusted R-square**|
|:------------:|:-----------------------------:|:----------------------:|:----------------------:|
| `Linear Regression`| 9.84 |74.3|72|

## Conclusion:

Using a very simple Linear Regression model the prediction of getting into a University is quite good. It is seen that TOEFL score is quite insignificant factor in deciding the admit of a student to any University. Whereas, GRE scores, University Ranking, Letter of Recommendation and Previous Research can play an important role in predicting the admit.
    
