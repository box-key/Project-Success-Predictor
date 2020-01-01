# Description
A binary text classifier that predicts the success of crowdfunding project trained by dataset provided by Donorschoose.org: https://research.donorschoose.org/t/download-opendata/33.</br>
Showing how to select the best number of features by Chi-square test and the effect of imbalanced data handling techniques (under-sampling and cost-sensistive learning).

# Libraries
- nltk
- scikit-learn
- numpy/pandas

# Technical Details
- feature: Tf-Idf Bigram 
- training algorithm: LinearSVM
- class ditribution: completed=117899, expired=51176
- training_set:test_set = 0.8:0.2
