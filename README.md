# LLM-Financial-Advisor: Fine-Tuning a LLM with Finance Data in AWS

## Overview
This project explores the application of generative AI in enhancing customer experience through the fine-tuning of a large language model (Meta Llama 2 7B) using Amazon SageMaker and AWS tools. The aim is to develop a domain expert model capable of generating informative, accurate, and contextually relevant text responses for specific domains such as finance (already fine-tuned), medical, or IT.

## Objective
The goal is to train (fine-tune) the Meta Llama 2 7B foundation model to become proficient in a chosen domain, functioning as a knowledgeable consultant for generating text content that aids internal and customer-facing activities.

## Technologies Used
- **Amazon SageMaker**: For model training, testing, and deployment.
- **AWS IAM**: For managing permissions and access to AWS services.
- **Jupyter Notebook**: For executing Python code and model training scripts.
- **Python**: Programming language used for model training and evaluation.

## Setup Instructions
1. **Configure AWS Environment**:
   - Set up an AWS SageMaker IAM Role with necessary permissions.
   - Create a SageMaker Notebook Instance using the created IAM role.
   - Ensure the region is set to US-west-2 (Oregon).

2. **Download Project Files**:
   - Clone the repository and navigate to the `Notebooks` directory.
   - Start the SageMaker Notebook instance and open JupyterLab to upload the notebook files.

3. **Run the Notebooks**:
   - Use the Model_Evaluation.ipynb to deploy and evaluate the pre-trained model.
   - Use the Model_FineTuning.ipynb to fine-tune the model on your selected domain-specific dataset.

## Project Steps
1. **Select the Dataset**: Choose a dataset from the `Datasets` directory relevant to your chosen domain.
2. **Fine-tune the Model**: Utilize the notebook to fine-tune the model using the selected dataset, already fine-tuned on financial dataset.
3. **Deploy and Evaluate the Model**: Deploy the fine-tuned model and evaluate its performance on domain-specific tasks.
4. **Documentation and Submission**: Document the process, challenges, and outcomes in the Project Documentation Report.

## Budget Management
- Ensure to manage AWS resource usage within your limit by stopping instances and deleting unnecessary resources.

