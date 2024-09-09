

# Build a Machine Learning Workflow for Scones Unlimited on Amazon SageMaker


## Overview

This repository contains the code and resources for building a machine learning workflow for Scones Unlimited using Amazon SageMaker. The project demonstrates how to construct a robust, end-to-end machine learning pipeline on AWS, from data preprocessing to model deployment.

## Project Introduction

Image classifiers are crucial in computer vision, identifying the content of images across various industries, including autonomous vehicles, augmented reality, eCommerce, and diagnostic medicine. 

As a Machine Learning Engineer at Scones Unlimited, a scone-delivery-focused logistics company, you are tasked with building and deploying an image classification model. This model will optimize operations by identifying the type of vehicle delivery drivers use, such as bicycles or motorcycles, and routing them accordingly. Assigning bicycle deliveries to nearby locations and motorcycle deliveries to farther locations can significantly enhance operational efficiency.

The goal is to create a scalable and safe model that other teams can use on-demand. The model must scale to meet demand, and safeguards should be in place to monitor and control for performance degradation or drift. This project involves using AWS SageMaker to build the model, deploying it, integrating AWS Lambda functions to create supporting services, and using AWS Step Functions to compose these components into an event-driven application. By the end of this project, you will have created a portfolio-ready demo that showcases your ability to build and compose scalable, ML-enabled AWS applications.

## Project Steps Overview

1. **Data Staging:** Prepare and stage the data for model training.
2. **Model Training and Deployment:** Train the image classification model using SageMaker and deploy it.
3. **Lambdas and Step Function Workflow:** Develop AWS Lambda functions and integrate them with AWS Step Functions to create a cohesive workflow.
4. **Testing and Evaluation:** Test the entire pipeline and evaluate the model's performance.
5. **Optional Challenge:** Explore additional features or improvements as a challenge.
6. **Cleanup Cloud Resources:** Properly clean up all AWS resources to avoid unnecessary charges.

## Table of Contents

- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Pipeline Architecture](#pipeline-architecture)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)


## Getting Started

To get started with this project, clone the repository to your local machine:

```bash
git clone https://github.com/aniketjain12/Build-a-ML-Workflow-For-Scones-Unlimited-On-Amazon-SageMaker-.git
cd Build-a-ML-Workflow-For-Scones-Unlimited-On-Amazon-SageMaker-
```

## Prerequisites

Before running the project, ensure you have the following installed:

- AWS CLI
- AWS Account with access to SageMaker
- Python 3.7+
- Jupyter Notebook or JupyterLab


## Usage

1. **Run the notebooks:**
   
   Navigate to the `notebooks` directory and run the Jupyter notebooks to explore the data, train the model, and evaluate the results.

2. **Deploy the model:**
   
   Use the provided scripts in the `sagemaker_pipelines` directory to deploy the trained model to Amazon SageMaker.

3. **Execute the pipeline:**
   
   Run the complete machine learning pipeline using the provided SageMaker pipeline scripts.

## Pipeline Architecture


The pipeline includes the following stages:

1. **Data Preprocessing:** Data cleaning and feature engineering using AWS Glue and Amazon S3.
2. **Model Training:** Model training using Amazon SageMaker.
3. **Model Evaluation:** Model evaluation using SageMaker Processing.
4. **Model Deployment:** Deploying the model to an endpoint using SageMaker.
5. **Monitoring and Logging:** Continuous monitoring of the deployed model.

## Results

- **Model Accuracy:** 96%
- **Endpoint Cost:** $0.119 per hour

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
