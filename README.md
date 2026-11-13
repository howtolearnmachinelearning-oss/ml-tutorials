# Machine Learning Tutorials 🦉

Hey friends! Learn machine learning by running code, exploring charts, and trying small challenges.

These guided notebooks accompany the tutorials at [How to Learn Machine Learning](https://howtolearnmachinelearning.com/).

## Start here: Classification Threshold Tuning

What happens when a missed case costs more than a false alarm?

Through seven guided steps, you’ll:
- Train a classifier and explore its predictions.
- Change decision thresholds and error costs.
- Compare confusion matrices, precision, and recall.
- Choose a cutoff using validation data.
- Evaluate your final choice on untouched test data.

[▶ Open in Colab](https://colab.research.google.com/github/howtolearnmachinelearning-oss/ml-tutorials/blob/main/classification-threshold-tuning.ipynb)

[📖 Read the full tutorial](https://howtolearnmachinelearning.com/articles/classification-threshold-tuning/)

## ROC AUC vs PR AUC 🦉

Why can a classifier have a good ROC AUC but produce mostly false alarms?

Explore seven guided steps, four charts, and mini-challenges covering:
- Class imbalance and precision.
- ROC and precision-recall curves.
- Average precision versus trapezoidal PR AUC.
- Experiments with prevalence and thresholds.

[▶ Open in Colab](https://colab.research.google.com/github/howtolearnmachinelearning-oss/ml-tutorials/blob/main/roc-auc-vs-pr-auc.ipynb)

[📖 Read the full tutorial](https://howtolearnmachinelearning.com/articles/roc-auc-vs-pr-auc/)

## Probability Calibration in Python 🦉

When a model predicts an 80% chance, how often does the event happen? Check its forecasts against real outcomes in a synthetic dataset, fit a sigmoid calibrator, and compare reliability diagrams and Brier scores.

[Open in Colab](https://colab.research.google.com/github/howtolearnmachinelearning-oss/ml-tutorials/blob/main/probability-calibration.ipynb) · [Read the tutorial](https://howtolearnmachinelearning.com/articles/probability-calibration-python/)

## Learning Curves in Python 🦉

How few training examples can you use and still meet the error target? Choose a linear or cubic model, predict its validation error from the learning curve, and use feedback from each attempt to find the smallest training set that works.

[Open in Colab](https://colab.research.google.com/github/howtolearnmachinelearning-oss/ml-tutorials/blob/main/learning-curves.ipynb) · [Read the tutorial](https://howtolearnmachinelearning.com/articles/learning-curves-python/)

### 5. Permutation Feature Importance

Which of four sensors would you monitor? Make a prediction, shuffle one sensor at a time, then try a pair. Does your first pick still hold up? Worked answers are at the end.

[Open in Colab](https://colab.research.google.com/github/howtolearnmachinelearning-oss/ml-tutorials/blob/main/permutation-feature-importance.ipynb) · [View notebook](./permutation-feature-importance.ipynb) · [Read the article](https://howtolearnmachinelearning.com/articles/permutation-feature-importance-python/)

### 6. Bootstrap Confidence Intervals

Would you switch models for a small drop in prediction error? Compare two models on the same 300 cases, predict what happens when you break the pairs, and use a bootstrap interval to make your call. Worked answers are at the end.

[Open in Colab](https://colab.research.google.com/github/howtolearnmachinelearning-oss/ml-tutorials/blob/main/bootstrap-confidence-intervals.ipynb) · [View notebook](./bootstrap-confidence-intervals.ipynb) · [Read the article](https://howtolearnmachinelearning.com/articles/bootstrap-confidence-intervals-python/)

## How to use the notebook

1. Open it in Colab.
2. Run the cells from top to bottom.
3. Pause at the questions and predict the results.
4. Try the mini-challenges!

The notebook generates its own synthetic dataset.

## Keep learning

- [Model evaluation guide](https://howtolearnmachinelearning.com/articles/evaluating-machine-learning-models/)
- [Free 90-Day Machine Learning Roadmap](https://how-to-learn-machine-learning.kit.com/7a25f667cb)
