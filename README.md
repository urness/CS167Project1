# CS 167 Project 1: 
## Learning Objectives: 
For this project, you will use the scikit-learn library to conduct a machine learning experiment, and your write-up will ask you to explain what you did and interpret the results. This directly addresses two of the course learning objectives stated in the syllabus:
- Students will be able to create software which utilizes machine learning programming libraries in order to conduct machine-learning-based data analysis.
- Students will be able to develop and conduct machine-learning-based data analysis experiments, and they will be able to interpret and explain the results.

## Project Description:
For this project, I'm giving you a choice of what dataset you would like to use. The options are:
- [Ramen Ratings](https://www.kaggle.com/residentmario/ramen-ratings)
- [Chocolate Ratings](https://www.kaggle.com/rtatman/chocolate-bar-ratings)
- [World Happiness Data](https://www.kaggle.com/unsdsn/world-happiness)
- [Heart Failure Prediction](https://www.kaggle.com/fedesoriano/heart-failure-prediction)

I've cleaned some of the data for you and uploaded the results to the Blackboard datasets folder. 

I have provided a skeleton of what I want your project to look like, but the rest of the experiment is up to you. This project should read more like a lab report than a coding assignment. I want to be able to see what you are thinking and how you are going about solving the problem that you state using the data and the tools that you have learned in this class so far. There are some basic guidelines as to what I want to see laid out below, but you are the machine learning engineer and it is your job to draw some meaningful conclusions about the data. 


## Project Expectations: ☑️
You will create a Colab notebook that includes your code and results to document your experiment. Most importantly, you will use text cells in the notebook to explain what you did, interpret the results, and make your recommendations. The written markdown protions must include the followint things:
1. **Name**: Include your name at the top of the notebook. 
2. **Problem**: Which dataset are you going to use? What questions are you going to ask about this dataset? Make sure that you can answer the question using ML models. What are your predictor variables and target variable?
3. **Data Preparation**: Explain your data preparation. What did you have to do to get your data in shape for your experiments - creation of dummy variables, filling in missing values, etc. 
4. **Metrics**: Identify which metrics you will be using to test your model, and say why they are appropriate. 
5. **Baseline Performance**: Identify a baseline for your metrics - what would you expect to happen with this particular data if you always guessed the average or if you guessed randomly? What did some of the unsuccessful machine learning algorithms yield?
6. **Model Planning and Execution**: Identify which learning algorithms you will try and which important parameters you will tune for each one. 
7. **Results**: After you conduct your learning experiment, summarize the results you got. Include visualizations as appropriate. 
8. **Bumps in the Road**: What challenges did you encounter? How did you overcome these challenges? Did you have to adapt your strategy to account for these challenges? Why or why not?
9. **Conclusions:** What insights/recommendations do you have? What did you find that was interesting? Which model was your best model, which models didn't work well? Why do you think this is? In general, I want a discussion of your experiment, the results, and what they mean.

### Your Experiments should Include:
- A **k Nearest Neighbors** model with a graph of at least 1 tuned parameter
- A **weighted k Nearest Neighbors** model with a graph of at least 1 tuned parameter
- A **Decision Tree** model with a graph of at least 1 tuned parameter
- A **Random Forest** model with a graph of at least 1 tuned parameter and feature importance chart
- **Normalize your data** and try the above models again (no need to tune your parameters this time unless you want to). 

## Notes, Tips and Tricks

### What does it mean to tune parameters?
Tuning parameters means that you try your model with different values for that parameter and record how well the resulting model performs on the test set 📈. This is what you did in Notebook 3 when you tried different k, graphed them and found the value of k that resulted in the best model. You found the best k for k-NN, so that means you tuned k. For this project, you are strongly encouraged to try tuning more than one parameter for each model. You should make sure to pick a parameter that actually has an important effect on your model/data, and explain why you chose the parameters you chose in your text description.

### Where should I start?
Copy and paste the above 10 items into a markdown cell, and begin answering the questions that you can answer before you even start coding.

Use the template for building and testing a scikit-learn model. Start by doing the following:
- Change that example code to work with your new data
- Look for the appropriate documentation for the scikit-learn modules for the machine learning algorithms we have discussed in class: http://scikit-learn.org/stable/modules/classes.html .
- Try to produce a plot like the one you did in Notebook 3, but use scikit-learn like in the example for random forests

# Rubric and Grading
| **Description/Writing**  |**Points Awarded** (1 point each)  |**Notes** |
| ------------------------------- | ------------------- | --------- |
| 1: Name                         |        |    |
| 2: Problem                      |        |    | 
| 3: Data Prep                    |        |    |
| 4: Metrics                      |        |    | 
| 5: Baseline Performance         |        |    |
| 6: Model Planning and Execution |        |    |
| 7: Results                      |        |    |
| 8: Bumps in the Road            |        |    | 
| 9: Conclusions                  |        |    |
| <b>Total                        |       /9 | </b>   |


| **Code**  | **Points Awarded**  (1 point each) | **Notes** |
| --------- | ------------------- | --------- |
| knn                             |        |    |
| graph of knn parameter          |        |    | 
| weighted knn                    |        |    |
| graph of weighted knn parameter |        |    | 
| decision tree                   |        |    |
| graph of decision tree parameter|        |    | 
| random forest                   |        |    |
| graph of random forest parameter|        |    |
| feature importances chart       |        |    | 
| normalized knn                  |        |    |
| normalized weighted knn         |        |    |
| normalized decision tree        |        |    | 
| normalized random forest        |        |    |
| <b>Total      |       /13 | </b>   |

| **Written Portion**  | **Code Portion**   | **Total** |**Notes** |
| --------- | ------------------- | --------- |--------- |
|         /9  |                 /13    |        /22   |           |

