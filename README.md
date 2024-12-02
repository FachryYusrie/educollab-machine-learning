# educollab-machine-learning

Machine Learning related stuff for EduCollab, A mobile-based application to recap student grade reports with features that can predict student performance and can perform sentiment analysis on comments that teachers give on student grade reports..

## Dataset
We using dataset from [keagle](https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression) to predict performance student and we make [our own custom-made dataset](https://github.com/dennyrianto/asterisk-machine-learning/blob/main/data/dataset_final.parquet), to sentiment analysis, we using ChatGPT and Gemini to collect data to train model.:

## Data Preprocessing
For the preprocessing step, you can check to this below:
- [Model_train_feature_one](data/label.py).
- [Model_train_feature_two]().

## Model
For the model architecture, we built a model from scratch using neural networks and Natural Language Processing (NLP) from TensorFlow and fine tuned the model. We trained the model using our dataset. The model produces several outputs corresponding to different sentiment aspects. Then we converted our model to Tensorflow.js format for deployment.

- [Model_feature_one File (SavedModel Format)](https://drive.google.com/file/d/1iu_hIZLIFaDeruR8wB_3Cwn-gv5IgKEw/view?usp=drive_link)
- [Model_feature_twi File (SavedModel Format)](https://drive.google.com/file/d/1iu_hIZLIFaDeruR8wB_3Cwn-gv5IgKEw/view?usp=drive_link)
