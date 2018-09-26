# Classification-on-Autism-Dataset

Use case - Doctors and specialists can focus directly on positive cases reported by this machine learning model on the Autism Spectrum Disorder(ASD) due to high accuracy of such prediction systems. ASD is a disorder of brain development. ASD patients can progress in life with special care and attention. Hence, accurate identification of characteristics for the disease is crucial.

As it is said, the model is as good as the data; Keeping that in mind, the dataset used for the project is a curated UCI dataset which contains responses of patients on the initial doctor's forms. The system aims to detect possible cases of having ASD based on the history and form data thus removing true negatives from the picture.

Dataset contains 704 instances and 21 features, which is mix of numerical and categorical values.

Mostly discrete and numerical with a few attributes being continuous. 

The target class is a boolean value as YES/NO which determines if the patient is likely to have ASD or not.

Though the the dataset is relatively clean, still data pre-processing is essential. 

Model Building -
The following different supervised machine learning algorithms are used to build and evaluate the performance of the model.
1. Decision Trees
2. Random Forests
3. Logistic Regression
4. Multi-Layer Perceptron (MLP)
5. MLP with K-Folds


Use confusion matrix to detect false positives, true positives, false negatives and true negatives. Please check the images for the confusion matrices for 3 models in the repo files.
