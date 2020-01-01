# Description
A binary text classifier that predicts the success of a crowdfunding project based on its project description, trained on dataset provided by Donorschoose.org: https://research.donorschoose.org/t/download-opendata/33.</br>
Showing how to select the best number of features by Chi-square test and the effect of imbalanced data handling techniques (under-sampling and cost-sensistive learning).

# Libraries
- nltk
- scikit-learn
- numpy/pandas

# Technical Details
- Feature => Tf-Idf Bigram 
- Training algorithm => LinearSVM
- Class ditribution => completed=117899 instances, expired=51176 instances
- Training_set:test_set => 0.8:0.2
