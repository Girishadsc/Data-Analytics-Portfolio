# OpenAI Fine-Tuning Experiment

## Adapting a Language Model to Produce Consistent Emoji-Oriented Responses


## Project Overview

This project adapts a course exercise involving Azure OpenAI fine-tuning to the OpenAI API.

The objective was to understand the workflow involved in preparing training data and creating a fine-tuning job for a language model.

The project used a small custom training dataset designed to teach the model a specific response behavior involving emojis.


## Objective

The project demonstrates the process of:

•	Preparing fine-tuning examples 

•	Formatting training data 

•	Working with the OpenAI API 

•	Configuring a fine-tuning workflow 

•	Understanding model adaptation 

•	Evaluating the practical requirements and limitations of fine-tuning 

## Training Dataset
A set of approximately 50 training examples was prepared for the fine-tuning exercise.
The examples were designed around the desired behavior of producing emoji-oriented responses.
The purpose was not to create a production model, but to demonstrate the mechanics and concepts behind fine-tuning.

## Methodology
The workflow included:

1.	Preparing training examples. 
2.	Formatting the examples for fine-tuning. 
3.	Configuring the OpenAI client. 
4.	Uploading/preparing the training data. 
5.	Attempting to create a fine-tuning job. 
6.	Troubleshooting API access and permissions. 
7.	Evaluating the expected fine-tuned model behavior.
   
## Important Implementation Learning
The project demonstrated that fine-tuning is dependent not only on code but also on:

•	API access 

•	Account permissions 

•	Model availability 

•	Usage limits 

•	Correct training-data formatting 

•	API configuration 

During development, the fine-tuning job creation encountered a PermissionDeniedError, demonstrating an important practical limitation when working with hosted model APIs.

## Technologies

•	Python 

•	OpenAI API 

•	OpenAI Python SDK 

•	Large Language Models 

•	Fine-Tuning 

•	Jupyter Notebook 

## Skills Demonstrated

•	OpenAI API Integration 

•	Training Data Preparation 

•	Fine-Tuning Concepts 

•	Prompt/Response Formatting 

•	API Troubleshooting 

•	Generative AI Development

•	Model Adaptation 

## Key Learning
The project reinforced that fine-tuning is different from prompt engineering.
Prompt engineering changes how an existing model is instructed at inference time, while fine-tuning uses training examples to adapt model behavior.
It also demonstrated the practical importance of API permissions and service availability when deploying hosted AI workflows.

## Project Outcome
This project demonstrates hands-on experience with the OpenAI fine-tuning workflow and the practical challenges associated with implementing hosted LLM customization.
