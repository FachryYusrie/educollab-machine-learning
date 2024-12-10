# Educollab Machine Learning

Machine Learning related stuff for EduCollab, A mobile-based application to recap student grade reports with features that can predict student performance and can perform sentiment analysis on comments that teachers give on student grade reports..

## Dataset
We using dataset from [keagle](https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression) to predict performance student and we make [our own custom-made dataset](https://github.com/FachryYusrie/educollab-machine-learning/blob/main/Data/teacher_reviews_student_performance_train.csv), to sentiment analysis.

## Data Preprocessing
For the preprocessing step, you can check to this below:
- [Student_Performance_Prediction_Model](https://github.com/FachryYusrie/educollab-machine-learning/blob/main/Student_performance_prediction_model.ipynb).
- [Teacher_Sentiment_Analysis_Model](https://github.com/FachryYusrie/educollab-machine-learning/blob/main/teacher_sentimen_analysis_model.ipynb).

## Model
For the model architecture, we built a model from scratch using neural networks and Natural Language Processing (NLP) from TensorFlow and fine tuned the model. We trained the model using our dataset. The model produces several outputs corresponding to different sentiment aspects. Then we converted our model to Tensorflow.js format for deployment.

- [Model_feature_one File (SavedModel Format)](https://github.com/FachryYusrie/educollab-machine-learning/blob/main/student_performance__fix_model.h5)
- [Model_feature_two File (SavedModel Format)](https://github.com/FachryYusrie/educollab-machine-learning/blob/main/teacher_sentiment_analysis_fix_model.h5)
