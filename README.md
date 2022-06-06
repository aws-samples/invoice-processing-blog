
# Automated Invoice Information Extraction Using Amazon Textract and Amazon Comprehend

## Introduction 

This repository contains Jupyter notebook, AWS CloudFormation template and datasets to train and evaluate the custom model that extracts guest names from synthetically 
generated hotel invoices. 
For this automated invoice information extraction usecase, we programmatically generated three types of hotel invoices beforehand (100 invoices per each type) with different 
invoices details (invoice number and date, guest name and expenses). 

## Deployment

To create resources, complete the following steps:
1.	Sign in to the AWS CloudFormation console in the target Region.
2.	Choose Launch Stack:
3.	Choose Next.
4.	For Stack name, enter invoice-processing.
5.	Choose Next.
6.	On the next page, choose Next.
7.	Review the details on the final page and select I acknowledge that AWS CloudFormation might create IAM resources.
8.	Choose Create stack.

## Run Automated Invoice Information Extraction

1. Sign in to the Amazon SageMaker console in the target Region.
2. Choose Notebook instances.
3. Choose Open Jupyter for invoice-processing-notebook Notebook instance.
4. Open invoice_processing.ipynb Jupyter notebook and following through the steps.

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.