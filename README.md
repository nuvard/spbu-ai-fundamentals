# spbu-ai-fundamentals
Materials for the practicum for "AI Fundamentals" course  at SpbU

## Practicum 1
We study basic tools necessary for the rest of the course: python, numpy, matplotlib and pandas. It is assumed that a student has some decent knowledge of python though he/she is not very experienced in it.

## Practicum 2

We continue studying pandas and get familiar with data preprocessing techniques (filtering, imputing etc.).

## Practicum 3

We study the scikit-learn architecture.

## Practicum 4

We make use of scikit-learn classes for data preprocessing.

## Practicum 5

We study basic techniques for feature engineering (encoding of categorial features) and feature selection (variance threshold).

## Practicum 6

We study linear models for regression and classification problems.

## Practicum 7

We continue studying logistic regression and introduce decision trees.

## Practicum 8

We continue studying decision trees and also get familiar with kNN for classification and regression problems.

## Practicum 9

We study random forest.

## Practicum 10

We introduce boosting methods.

## Practicum 11

We study basic recommendation methods (TBD).

## Project
Your task is to work on a project dedicated to some ML problem. 
Examples of previous years themes: prediction of car accidents, prediction of crimes, prediction of winning team for game X, prediction of X quality, prediction of X rating, etc.

The requirements for project:
1) You need to find some dataset or collect by your own. The dataset must not be trivial (it must need some feature engineering and/or cleaning, it may be collected from multiple sources or be too big to use standart technics). Generally, the harder is the problem the better. The theme and dataset must be approved by the teacher. 
2) You need to provide EDA for your dataset.
3) Theme must be appropriate (do not violate the law or the university's ethics rules) but may be funny or dedicated to some "questionable" topic or smth if you don't promote it :) ). I hope you can balance fun and rules by yourself. If theme is interesting to you, everyone will be happy.
4) If your task was not included into the course outline (like NLP or recommendation systems) you need to ensure that you can answer questions about your method during the defence.
6) For each stage of working with data, you must create an artifact added to the project's "design document" in a fairly free form, describing the choice of methods, etc. An example of the structure of such a document:

| Section | Contents |
|------------------|-------------------------------------------|
| Goal and Metrics | What we're solving, how we measure success, and why |
| Data | Sources, amount of data, key feachures, and limitations |
| Validation draft | How we will validate the model and why |
| Approach | Features + Baseline Model |
| Training | Models, hyperparameters + Error analysis |
| Validation | Residual Analysis, Model Calibration |
| Model selection | Final model, 2-3 Main Risks or limitations of your approach |
| Deploy | How to make this model work online, how ofthen it needs to be retrained, interface, infrastructure |

5) Up to 2 people can participate in the project. You may participate alone. There is no difference in scoring system, in case of team scores will be balanced based on the contribution of teammates (e.g. you can get 10/10, 10/5 or 6/7). The only difference that data/model simplicity will impact teams scores more.

6) Only classical methods can be used; neural networks can only be used to construct embeddings AFTER APPROVAL. Otherwise, if the project is found to have used neural networks during the defense, it will receive a minimum score.

7) Project will be defended with the oral presentation (around 10 minutes per team). You must provide final code in github repo and all design/experiment artifacts before the defence.

8) You may change the project or team up to the defence date, but it will be more convenient if you finalize it as early as possible.
9) Application (webpage, bot, dashboard or smth) will be an advantage but you may omit it.


## Grading
The grading system is something like that:
$score = 30 * homeworks + 10 * tests + 60 * project$, there each part is normalized from 0 to 1 depending on number of assignments and their difficulty for given task.

Grade is something like (intervals may be shifted if the score distribution is too skewed):
| e   | d   | c   | b   | a    |
|-----|-----|-----|-----|------|
| 60% | 70% | 80% | 90% | 100% |

You will get extra scores for some tasks (like first place in the competion or hard task in homework).
## Datasets

* Kaggle House Prices: https://drive.google.com/file/d/15QWu8QWhDmJC34ZiNYxdMlC1NWqGsXpJ/view?usp=sharing
