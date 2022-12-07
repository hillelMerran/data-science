# Classification project - binary classification of sonar signals

This directory contains a project using several models in order to classify sonar signals.
We'll focus on training 8 models at once with a pipeline, and optimizing the hyper parameters for each model with GridSearchCV.

## Data Description
Data source: [UCI Machine learning Repository](https://archive-beta.ics.uci.edu/dataset/151/connectionist+bench+sonar+mines+vs+rocks).

This dataset is originally used by Gorman and Sejnowski in their study of the classification of sonar signals using a neural network.
Their task was to train a network to discriminate between sonar signals bounced off a metal cylinder and those bounced off a roughly cylindrical rock.

The dataset contains 208 patterns obtained by bouncing sonar signals off a metal cylinder (111 patterns) and rocks (97 patterns) at various angles and under various conditions.

Each pattern is a set of 60 numbers in the range 0.0 to 1.0. Each number represents the energy within a particular frequency band, integrated over a certain period of time.

The label associated with each record contains the letter "R" if the object is a rock and "M" if it is a mine (metal cylinder).
