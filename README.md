# AI_for_Medicine
Here I am sharing all the notes of the most perfect Coursera course created by the combination of medicine and artificial intelligence :)


# Course 1: AI For Medical Diagnosis - Learning Objectives : 

[![Certificate](https://img.shields.io/badge/Certificate-%23F7931E.svg?style=plastic&logo=Coursera&logoColor=white)](https://www.coursera.org/account/accomplishments/certificate/SCFWL98MCVWF)

Data pre-processing: checking for data leakage
Preprocess images properly for the train, validation and test sets
Implement a weighted loss function to address class imbalance.
Set up a pre-trained neural network to make disease predictions on chest x-rays.



## Week 1:

Introduction: A conversation with Andrew Ng

Diagnosis examples

Model training on chest X-Rays

Training, prediction, and loss

Class imbalance

Binary cross entropy loss function

Resampling methods

Multi-task loss

Transfer learning and data augmentation

Model testing


## Week 2:

Introduction: A conversation with Andrew Ng

Evaluation metrics

Accuracy in terms of conditional probability

Sensitivity, specificity, and prevalence

Confusion matrix

ROC curve

Threshold (operating point)

Confidence intervals

Width of confidence intervals and sample size

Using a sample to estimate the population


## Week 3:

Introduction: A conversation with Andrew Ng

Representing MRI data

Image registration

2D and 3D segmentation

3D U-Net

Data augmentation for segmentation

Loss function for image segmentation

Soft dice loss

External validation

Retrospective vs. prospective data

Working with cleaned vs. raw data

Measuring patient outcomes

Algorithmic bias

Model influence on medical decision-making



# Course 2: AI For Medical Prognosis


## Week 1:

Introduction: A conversation with Andrew Ng

Examples of prognostic tasks

Patient profile to risk score

Risk score for atrial fibrillation

Liver disease mortality

Calculate 10-year risk of heart disease

Risk score computation

Evaluating prognostic models

Concordant pairs

Risk ties

Permissible pairs

C-index interpretation


## Week 2:

Decision trees for prognosis

Predicting mortality risk

Dividing the input space

Non-linear associations

Class boundaries of a decision tree

Random forest

Ensemble methods

Survival data

Problems with dropping incomplete rows

Dropping incomplete case changes the distribution

Imputation

Mean imputation

Regression imputation


## Week 3:

Survival function

Censoring

Collecting time data

Heart attack data

Estimating the survival function

Using censored data

Chain rule of conditional probability

Derivation

Calculating probabilities from the data

Comparing estimates

Kaplan Meier Estimate


## Week 4:

Hazard functions

Survival to hazard

Cumulative hazard

Individualized predictions

Individual vs. baseline hazard

Smoker vs. non-smoker

Effect of age on hazard

Factor risk increase or decrease

Survival trees

Nelson Aelen estimator

Mortality score

Evaluating survival models

Permissible pair examples

Harrell’s concordance index


# Course 3: AI For Medical Treatment

## Week 1:

Treatment effect estimation

Randomized control trials

Average risk reductio

Individualized treatment effect

T-Learner and S-Learner

C-for-benefit


## Week 2:

Information extraction from medical reports

Rules-based label extraction

Text matching

Negation detection

Dependency parsing

Question-Answering with BERT


## Week 3:

Machine Learning Interpretation

Interpret CNN models with GradCAM

Aggregate and Individual feature importance

Permutation Importance

Shapley Values

Interpret random forest models
