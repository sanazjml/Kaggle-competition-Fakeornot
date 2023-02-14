# Kaggle competition (Fake or not!)

I participated in a  Kaggle competition as the final project of my Advanced ML course at University of Helsinki, 2021. Here are the instructions and my project solution is presented in "project_notebook". To see the results of the competition you could go to the following link as well.

### Project description:

The project for the course consists of a prediction task whether news source was from a reputable media (reuters) or an opinionated source (headlines taken from news articles that were deemed false by politifact).

#### Data

The data consists of original text files for training, and also processed files with some extracted features. You can either use the files with the extracted features, work directly with the text file, and/or modify the feature extraction code.

The following files are provided

    train_fake.txt, original headlines from questionable sources
    train_true.txt, original headlines from reuters
    test.txt, headlines for testing with no labels
    train_fake_bow.csv, processed headlines from questionable sources
    train_true_bow.csv, processed headlines from reuters
    test_bow.csv, processed headlines for testing with no labels
    preprocess.py, script used to process headlines
    sample.csv , example of submission file for kaggle

#### Competition

Student should try at least 3 genuinely different classification approaches for this problem. The methods should be truly different, for example, applying regularization doesn't count. However, for example, boosting a classifier does count. The classifier can be something that was taught during the course, or something else.

To see how well the classifier worked, see the following link:

https://www.kaggle.com/c/uh-aml-2021/leaderboard?tab=public
