# FIFA
The goal is to predict the market value of a football player based on his characteristics. The dataset consists of 2000 players.

In 1_explore we explore the data and perform some cleaning, and in 2_predict we train several models and evaluate them.

In 3_pipeline_run we implement a more rigourous approach where we deploy a pipeline to train various models with hyperparameter optimization. First we call 4_pipeline_functions and 5_pipeline_clean, then we call 6_pipeline_num, 7_pipeline_num_ord and 8_pipeline_num_ord_cat in order to get pipelines adapted to numerical, ordinal and categorical features.

Finally, in 9_pipeline_best_model we re-create the best model and see how well it generalizes to different train-test splits.
