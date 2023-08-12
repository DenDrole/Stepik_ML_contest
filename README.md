# Stepik_ML_contest
Showcasing retention model for stepik ml contest with weird results.
This repository contains incorrect (in one detail) model for https://stepik.org/lesson/226979/step/2?unit=199528. 
This model beats contest winner's roc_auc by 0.0643 (getting 0.9579) because of mistake in it. 
However, correct version of this model gets only 0.8875, placing around top-20 in rankings.
The mistake that improves model's scoring by almost 0.1 is including user_id in prediction. That is an interesting dependency and i'm curious to understand reasons behind it.
