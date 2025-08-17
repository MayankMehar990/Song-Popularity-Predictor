🎵 Predicting Song Popularity Using Machine Learning

This project explores Hit Song Science™ — the task of predicting whether a song will become popular using machine learning and music information retrieval (MIR) techniques. Using a dataset of over 160k tracks (Spotify API), the project builds models that can:

Regression → Predict a song’s popularity score.

Classification → Predict whether a song will be popular or not.

🔧 Methodology

Data preprocessing: cleaning, merging, handling categorical variables, and exploratory analysis (histograms, box plots, correlations).

Feature set: audio features (danceability, loudness, tempo, valence, etc.) and artist/genre metadata.

Models used: Linear Regression, Decision Trees, Logistic Regression, SVM, Random Forests, and Ensemble methods (Voting Classifiers, AdaBoost, Gradient Boosting).

Hyperparameter tuning: Bayesian optimization for improving model performance.

📊 Key Findings

Popularity can be predicted reasonably well, though some popular songs are misclassified as non-popular.

Tree-based and ensemble algorithms (Random Forest, Voting Classifiers) achieved strong performance.

Boosting methods offered better recall and F1-scores, while parallelizable ensembles proved efficient.

📂 Dataset

Spotify dataset (1921–2020, ~160k tracks) — available on Kaggle.
