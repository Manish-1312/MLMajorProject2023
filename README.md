
# Duplicate Question Pair

Mulyankan is an NLP (Natural Language Processing) project meticulously crafted to discern duplicate question pairs embedded within datasets. It operates at the core by scrutinizing the resemblance between pairs of questions indexed by question1 and question2 columns, culminating in the prediction of their duplicity, as signified by the is_duplicate column.

This project stands as a pivotal asset across diverse domains:

Information Retrieval: Elevating search engines by sieving out redundant or akin queries.

Community Forums and Q&A Platforms: Augmenting user experience through the amalgamation of akin inquiries.

Machine Learning and NLP Research: Standing as a benchmark for comprehending and managing duplicate textual pairings.

Key Components:

Data Structure: Anchored around the central columns: question1, question2, and is_duplicate.

Models Utilized: Harnesses the prowess of Random Forest and XGBoost algorithms for classification tasks.

Evaluation Metrics: Predominantly measures model efficacy through the lens of accuracy.

The operational workflow navigates through distinct phases:

Data Preparation: Delving into data cleaning, preprocessing, and dataset structuring for subsequent model training.

Model Training: Harnessing the potential of Random Forest and XGBoost models for adept training on the meticulously prepared dataset.

Evaluation: Assessing model accuracy and efficacy against predefined metrics.

Application: Enabling the deployment of trained models for the precise identification of duplicate question pairs.

## Installation

Before running the .ipynb file
Install my-project with pip3

```bash
  pip3 install -r requirements.txt
```
    
## Dataset

We have used the Quora Question Pair Dataset in this problem statement

Downloaded from Kaggle this Dataset is diverse and can be accessed by anyone by enrolling in the competition by Quora

Following is th link

```
https://www.kaggle.com/competitions/quora-question-pairs/data

```

## Training And Evaluation


Data Preparation
Ensure your dataset is formatted correctly with columns question1, question2, and is_duplicate. Preprocess the data by handling missing values, cleaning text, and structuring it appropriately for training.

Model Training Steps
Loading the Dataset:

Use functions or scripts provided within the project to load the dataset into your environment.
Splitting Data:

Divide the dataset into training and testing sets to evaluate model performance accurately.
Initializing Models:

Instantiate Random Forest and XGBoost models using appropriate configurations or hyperparameters.
Model Training:

Train the models using the prepared training dataset.
Utilize functions or scripts to fit the models to the data.

Metrics Used For Evaluation

Accuracy: Assess the correctness of model predictions concerning duplicate question pairs.

Model Evaluation:

Utilize the loaded models to make predictions on the test data.
Measure model accuracy by comparing predicted values with the actual is_duplicate labels.

Assessing Performance:

Calculate and present the accuracy achieved by each model.
Discuss any differences or notable observations between the models.


## Results

Results Summary

Random Forest Accuracy: Achieved an accuracy of 0.78 on the test dataset.

XGBoost Accuracy: Achieved an accuracy of 0.79 on the same test dataset.

Comparison: While both models performed well, XGBoost demonstrated slightly higher accuracy in this instance.


Observations

Key Findings: The models effectively distinguished duplicate question pairs, but further fine-tuning may enhance accuracy.

Challenges Faced: Dealing with semantic nuances and context in some question pairs posed challenges for accurate identification.

Next Steps: Explore advanced feature engineering or utilize more sophisticated NLP techniques to improve model performance.

## Contributing

We closely worked on this project and monitered every result together. We made sure work is evenly distributed and results and next steps be discussed always.

Harshit Kumar - 12310680
Manish Rai - 12310790




## License

[MIT](https://choosealicense.com/licenses/mit/)

