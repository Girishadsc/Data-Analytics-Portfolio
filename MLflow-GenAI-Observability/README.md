# Generative AI Application Observability with MLflow

## Tracking and Monitoring LLM Application Experiments


## Project Overview

This project explores the use of MLflow for experiment tracking and observability in a Generative AI application.

The project was based on a Generative AI book/question-answering workflow using the OpenAI API and MLflow tracking.

The purpose was to understand how AI application runs can be recorded and reviewed rather than treating an LLM application as a black box.

## Objective
The project demonstrates how to:

•	Configure MLflow tracking 

•	Create an MLflow experiment 

•	Connect an LLM application to MLflow 

•	Record application runs 

•	Review experiment history 

•	Inspect model/application outputs 

## Implementation
The application was configured with:

•	An OpenAI client 

•	An MLflow tracking URI 

•	An MLflow experiment named GenAI_book 

The notebook used MLflow to track the Generative AI workflow and retrieve recorded runs.
The experiment history could be examined using MLflow's run-search functionality.
## Observability Workflow
The overall workflow included:
1.	Initialize the OpenAI client. 
2.	Configure MLflow tracking. 
3.	Set the GenAI_book experiment. 
4.	Execute Generative AI interactions. 
5.	Record experiment/run information. 
6.	Review the recorded runs. 
7.	Compare and inspect experiment results. 
## Why MLflow?
Generative AI applications can produce different outputs for similar prompts, making experiment tracking particularly important during development.
MLflow provides a structured way to organize experiments and review historical runs.
## Technologies

•	Python 

•	OpenAI API 

•	MLflow 

•	Jupyter Notebook 

•	Generative AI 

•	Experiment Tracking 

## Skills Demonstrated

•	LLM Application Development 

•	API Integration 

•	MLflow 

•	Experiment Tracking 

•	AI Observability 

•	Debugging 

•	Application Monitoring Concepts 

•	Reproducible Experiment Management 

## Key Learning
A major learning outcome was understanding that Generative AI applications require more than simply calling an API.
Developers need ways to observe and compare application behavior, track experiments, and maintain a history of runs so that changes can be evaluated systematically.
## Project Outcome
This project demonstrates hands-on experience applying MLflow concepts to a Generative AI workflow and provides an example of how experiment tracking can support the development and evaluation of LLM applications.
