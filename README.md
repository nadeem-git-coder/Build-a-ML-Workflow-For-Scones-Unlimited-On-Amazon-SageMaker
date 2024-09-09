

# Build a Machine Learning Workflow for Scones Unlimited on Amazon SageMaker

## Overview

This project demonstrates building an end-to-end machine learning pipeline for Scones Unlimited using Amazon SageMaker. The goal is to create an image classification model to identify delivery vehicles (bicycles or motorcycles) and optimize routing for the company's scone delivery operations.

## Workflow

1. **Data Preparation:** Stage and preprocess data.
2. **Model Training & Deployment:** Build, train, and deploy the model using SageMaker.
3. **Lambda & Step Functions:** Integrate AWS Lambda functions and Step Functions for workflow orchestration.
4. **Testing & Evaluation:** Evaluate model performance and test the entire pipeline.
5. **Cleanup:** Properly clean up AWS resources to avoid unnecessary charges.

## Getting Started

To get started with this project, clone the repository and navigate to the project directory:

```bash
git clone https://github.com/nadeem-git-coder/Build-a-ML-Workflow-For-Scones-Unlimited-On-Amazon-SageMaker.git
cd Build-a-ML-Workflow-For-Scones-Unlimited-On-Amazon-SageMaker
```

## Prerequisites

Ensure you have the following prerequisites:

- **AWS CLI** with access to Amazon SageMaker
- **Python 3.7+**
- **Jupyter Notebook or JupyterLab**

## Usage

1. **Run Notebooks:** Explore the data, train the model, and evaluate results using the notebooks in the `notebooks` directory.
2. **Deploy the Model:** Utilize the scripts in the `sagemaker_pipelines` directory to deploy the trained model on Amazon SageMaker.
3. **Run the Pipeline:** Execute the entire machine learning pipeline with the provided SageMaker scripts.

## Results

- **Model Accuracy:** 96%
- **Endpoint Cost:** $0.119 per hour

## Contributing

Contributions are welcome! If you have improvements or new features to add, please submit a pull request with your changes.
