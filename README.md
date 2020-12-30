# wine_quality_classification_ML

Source : https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009

This dataset comes from Kaggle and is based on physicochemical tests (input variables). The target (quality) is a sensory variable and a score between 0 and 10.
I set a cutoff between good quality wine (score >= 7) and low quality wine (score < 7).
To predict the quality, I used two classifiers, KNN and Decision Tree and tuned the hyperparameters with GridSeachCV.
