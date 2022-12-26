# bootcamp-final-assignment_using_CNN
## Eye Gender Classification
In this project, we aim to build a model to classify the gender of a person based on the image of their eye. The dataset contains eye images of males and females, and the task is to predict the gender of the person for a given eye image.

## Problem Statement
The anthropometric analysis of the human face is an essential study for performing craniofacial plastic and reconstructive surgeries. Facial anthropometrics are affected by various factors such as age, gender, ethnicity, socioeconomic status, environment, and region. Plastic surgeons who undertake the repair and reconstruction of facial deformities find the anatomical dimensions of the facial structures useful for their surgeries. These dimensions are a result of the physical or facial appearance of an individual. Along with factors like culture, personality, ethnic background, age, eye appearance and symmetry contribute majorly to the facial appearance or aesthetics.

Our objective is to build a model to scan the image of an eye of a patient and classify the gender of the patient as male or female.

## Data
The dataset can be downloaded from [this link](https://drive.google.com/file/d/1f7uslI-ZHidriQFZR966_aILjlkgDN76/view?usp=sharing).
. After downloading and extracting the zip file, you will get four files:

- train: Contains all the images that are to be used for training the model.
- Training_set.csv: Contains the labels for the training images.
- test: Contains 9000+ images. For these images, you are required to make predictions.
- Testing_set.csv: Contains the order of the predictions for each image that is to be submitted on the platform.
- sample_submission.csv: This is the sample submission file for the data sprint.

## Submission guidelines
1. The predictions file is a CSV and its first row (i.e. header field) is 'label'.
2. I uploaded the .ipynb notebook file as a solution to the question.

## Evaluation Metric
The accuracy score is used for evaluating model predictions.

## Additional guidelines
Submissions are evaluated using the accuracy score, and the score displayed on the leaderboard is 100 * accuracy score.

## Getting Started Notebook
A getting started notebook is available [here](https://aiplanet.com/notebooks/2866/dphi_official/5-week-deep-learning-bootcamp-final-assignment-getting-started-notebook).

## Acknowledgement
The dataset is sourced from Ruskino RU. We thank PavelBiz for this dataset.
