---
layout: page
title: Kaggle competitions
description: Various ML competitions
img: assets/img/projects/kaggle-logo-transparent-300.png
importance: 5
category: fun
---

I've taken part in several ML competitions on [Kaggle](https://kaggle.com) as well as other ML platforms.

The best achievement have been:

* gold medal as a part of the **International Fit Club** team in the
  [Home Credit Default Risk](https://www.kaggle.com/competitions/home-credit-default-risk)
  competition (see the [post on LinkedIn](https://www.linkedin.com/posts/misha-lisovyi_wow-my-first-kaggle-competition-home-credit-activity-6440726475086786560-3HfJ?utm_source=share&utm_medium=member_desktop));
* silver medal in the [Google Analytics Customer Revenue Prediction](https://www.kaggle.com/competitions/ga-customer-revenue-prediction)
  competition (see the [post on LinkedIn](https://www.linkedin.com/posts/misha-lisovyi_google-analytics-customer-revenue-prediction-activity-6505172744706101248-zJjQ?utm_source=share&utm_medium=member_desktop));

There have been also plenty of various other competitions.
As a result I've developed a python package with a set of tools [Keggler](https://github.com/mlisovyi/Keggler),
in particular:

* [TargetEncoder_KFold](https://github.com/mlisovyi/Keggler/blob/053caa84648b34f8f790ae6323a18674e1e51778/keggler/preprocess/category_encode.py#L83)
  for target-encoding categorical features using cross-validation to reduce over-fitting;
* [StackingClassifier](https://github.com/mlisovyi/Keggler/blob/053caa84648b34f8f790ae6323a18674e1e51778/keggler/ensemble/stacking.py#L288)
  to build stacked models;

The `Keggler` project has no best practices applied, as it has been developed, when I had much less experience 😄