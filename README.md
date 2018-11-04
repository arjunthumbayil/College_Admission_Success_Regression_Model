# US College Admission Success

## Business Objective:

    1. Build a smart Predictive tool that can assess the chances of a Student's entry into multiple Tier US Tech Schools.
    2. Develop a prototype model that uses Student data to produce admission probability for each student.
    3. Explore historical student data, using statistical analysis and Machine Learning, to understand and identify factors that may affect a Student's success at getting into their dream University.


## Motivation:

After observing many of my friends trying hard and not getting into the University of their choice in the US, I was intrigued to know whether the admission process that seems to be a black-box can be broken down using Analytical tools. Anxiety can be caused by low GRE and TOEFL scores. So, I shall look whether they play an important role or are there other factors than can quantitatively outweigh Standardized Test Scores. Furthermore, this tool can help students in building a stronger Profile.l
 

## Workflow :

   1. **Importing Libraries**
      
   2. **Data Pre-Processing**
        - 2.1 Reading Data from the csv file:
        ```python
admission = pd.read_csv("Admissions.csv")
                ```
  
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

Using a very simple Linear Regression model, the prediction of getting into a University is quite good. It is too be seen that TOEFL score is quite insignificant factor in deciding the admissibility of a student to any University. Whereas, GRE scores, University Tier, Letter of Recommendation and Previous Research can play an important role in predicting the admissibility.
    
