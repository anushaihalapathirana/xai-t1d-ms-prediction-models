# Explainable AI Models for T1D Complications and MS Relapses

## Introduction

This repository contains a collection of explainable AI models designed to predict complications (Severe Hyperglycemia and Diabetic Ketoacidosis) in Type 1 Diabetes (T1D) adults and relapses in Multiple Sclerosis (MS) adults. These predictive models have been developed to aid researchers and medical professionals in assessing the likelihood of potential complications and relapses in patients, enabling timely interventions and personalized treatment approaches.

## Containing Files

- Python notebooks featuring predictive models for assessing Severe Hyperglycemia and Diabetic Ketoacidosis in Type 1 Diabetes, as well as relapses in Multiple Sclerosis (MS).
- Explanations for model predictions to enhance transparency and interpretability, utilizing the SHAP library.
- Preprocessed data of the T1D dataset.


## Usage

### Installation

Clone the repository to your local machine using the following command:

```
git clone https://github.com/anushaihalapathirana/xai-t1d-ms-prediction-models.git
cd xai-t1d-ms-prediction-models
```

### Dependencies

Before running the models, make sure to install the required dependencies by executing the following command:

`pip install -r requirements.txt`

### Example Usage

Navigate to the examples directory for sample Jupyter notebooks showcasing how to use the predictive models.

Run the Jupyter notebook of your choice to see the models in action and understand how to interpret the predictions.

### Data

The sample datasets used in the examples are available in the data directory. Please note that this repository only includes the dataset of T1D,  which is an open dataset accessible [here](https://public.jaeb.org/dataset/536). 

However, the dataset used for relapse prediction is private and not available in this repository.

Researchers can replace these datasets with their own data for personalized predictions.

## License

This project is licensed under the MIT License.