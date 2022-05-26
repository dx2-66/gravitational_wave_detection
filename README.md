# Kaggle G2Net Gravitational Wave Detection

This is an old competition, ended over half a year ago, yet the subject is very appealing to me so I picked it up.
I participated in BOINC Einstein@Home distributed calculations program back then when the gravitational waves were first detected in 2015, I remember LIGO first success report and how much it inspired me, so here we are:

This is a deceptively simple binary classification task (balanced synthetic dataset) with some caveats:

- The dataset is huge (60GB training data).
- Signal processing is in fact very similar to image processing, with a few extra tricks, see more inside!

Since the competition is extremely tight (people reportedly happened to stack *137* models just to improve their leaderboard position), we'll try to find a good balance between performance and metrics rather than maximizing the accuracy at a disparate cost.

**Required units:**

- pandas
- scikit-learn
- PyTorch
- skorch
- numpy
- scipy
- Matplotlib
- Seaborn
