# DuplicateQuestion

We modifed the code from https://github.com/tensorflow/models/tree/master/skip_thoughts and trained our model for the task of duplicate question detection.

The code for our model is in code/skip_thoughts/skip_thoughts_model.py. By combining some handcrafted features and training another Gradient Boosting classifier on the top, we achieved a test accuracy of 86.9%, where the test data is a random split of 5000 examples left out from the Quora training dataset. See our report for more details.
