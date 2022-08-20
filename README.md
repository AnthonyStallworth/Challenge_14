# Challenge_14


# Module-14-Challenge

## Establish a Baseline Performance

In this section, you’ll run the provided starter code to establish a baseline performance for the trading algorithm. To do so, complete the following steps.
Open the Jupyter notebook. Restart the kernel, run the provided cells that correspond with the first three steps, and then proceed to step four.
Import the OHLCV dataset into a Pandas DataFrame.
Generate trading signals using short- and long-window SMA values.
Split the data into training and testing datasets.

Use the SVC classifier model from SKLearn's support vector machine (SVM) learning method to fit the training data and make predictions based on the testing data. Review the predictions.
Review the classification report associated with the SVC model predictions.
Create a predictions DataFrame that contains columns for “Predicted” values, “Actual Returns”, and “Strategy Returns”.
Create a cumulative return plot that shows the actual returns vs. the strategy returns. Save a PNG image of this plot. This will serve as a baseline against which to compare the effects of tuning the trading algorithm.
Write your conclusions about the performance of the baseline trading algorithm in the README.md file that’s associated with your GitHub repository. Support your findings by using the PNG image that you saved in the previous step.

## Tune the Baseline Trading Algorithm

In this section, you’ll tune, or adjust, the model’s input features to find the parameters that result in the best trading outcomes. (You’ll choose the best by comparing the cumulative products of the strategy returns.) To do so, complete the following steps:
Tune the training algorithm by adjusting the size of the training dataset. To do so, slice your data into different periods. Rerun the notebook with the updated parameters, and record the results in your README.md file. Answer the following question: What impact resulted from increasing or decreasing the training window?

HINT

Tune the trading algorithm by adjusting the SMA input features. Adjust one or both of the windows for the algorithm. Rerun the notebook with the updated parameters, and record the results in your README.md file. Answer the following question: What impact resulted from increasing or decreasing either or both of the SMA windows?
Choose the set of parameters that best improved the trading algorithm returns. Save a PNG image of the cumulative product of the actual returns vs. the strategy returns, and document your conclusion in your README.md file.

## Evaluate a New Machine Learning Classifier

In this section, you’ll use the original parameters that the starter code provided. But, you’ll apply them to the performance of a second machine learning model. To do so, complete the following steps:
Import a new classifier, such as AdaBoost, DecisionTreeClassifier, or LogisticRegression. (For the full list of classifiers, refer to the Supervised learning page (Links to an external site.) in the scikit-learn documentation.)
Using the original training data as the baseline model, fit another model with the new classifier.
Backtest the new model to evaluate its performance. Save a PNG image of the cumulative product of the actual returns vs. the strategy returns for this updated trading algorithm, and write your conclusions in your README.md file. Answer the following questions: Did this new model perform better or worse than the provided baseline model? Did this new model perform better or worse than your tuned trading algorithm?

## Create an Evaluation Report

In the previous sections, you updated your README.md file with your conclusions. To accomplish this section, you need to add a summary evaluation report at the end of the README.md file. For this report, express your final conclusions and analysis. Support your findings by using the PNG images that you created.
Requirements

## Establish a Baseline Performance (25 points)

To receive all points, you must:

Use the SVC classifier model from SKLearn's support vector machine (SVM) learning method to fit the training data and make predictions based on the testing data. (6 points)
Review the classification report associated with the SVC model predictions. (5 points)
Create a predictions DataFrame that contains columns for “Predicted” values, “Actual Returns”, and “Strategy Returns”. (6 points)
Create a cumulative return plot that shows the actual returns vs. the strategy returns. (6 points)
Save a PNG image of the cumulative return plot that shows the actual returns vs. the strategy returns. (1 point)
Write your conclusions about the performance of the baseline trading algorithm in the README.md file that’s associated with your GitHub repository. Support your findings by using the PNG image that you saved in the previous step. (1 point)


## Tune the Baseline Trading Algorithm (10 points)

To receive all points, you must:

Tune the training algorithm by adjusting the size of the training dataset. To do so, slice your data into different periods. Rerun the notebook with the updated parameters, and record the results in your README.md file. (4 points)
Tune the trading algorithm by adjusting the SMA input features. Adjust one or both of the windows for the algorithm. Rerun the notebook with the updated parameters, and record the results in your README.md file. (4 points)
Choose the set of parameters that best improved the trading algorithm returns. Save a PNG image of the cumulative product of the actual returns vs. the strategy returns, and document your conclusion in your README.md file. (2 points)

## Evaluate A New Machine Learning Classifier (25 points)

To receive all points, you must:

## Import a new classifier, such as AdaBoost, DecisionTreeClassifier, or LogisticRegression. (5 points)
Using the original training data as the baseline model, fit another model with the new classifier. (10 points)
Backtest the new model to evaluate its performance. Save a PNG image of the cumulative product of the actual returns vs. the strategy returns for this updated trading algorithm, and write your conclusions in your README.md file. (10 points)

## Create an Evaluation Report (10 points)

To receive all points, you must:

Add a summary evaluation report at the end of the README.md file. For this report, express your final conclusions and analysis. Support your findings by using the PNG images that you created. (10 points)
Coding Conventions and Formatting (10 points)

To receive all points, you must:

## Place imports at the top of the file, just after any module comments and docstrings, and before module globals and constants. (3 points)
Name functions and variables with lowercase characters, with words separated by underscores. (2 points)
Follow DRY (Don't Repeat Yourself) principles, creating maintainable and reusable code. (3 points)
Use concise logic and creative engineering where possible. (2 points)
Deployment and Submission (10 points)


+