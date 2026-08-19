# Girisha — Applied Data Science Portfolio

## About Me

I am an **Applied Data Scientist** focused on **Business Analytics, Machine Learning, Data Visualization, and Generative AI**.

I develop data-driven solutions that transform complex business problems into actionable insights. My work combines analytical thinking, machine learning techniques, Generative AI technologies, and responsible AI practices.

This portfolio contains projects demonstrating my experience across the end-to-end data science lifecycle, including:

* Data cleaning and preparation
* Exploratory data analysis
* Data visualization
* Feature engineering
* Predictive modeling
* Machine learning evaluation
* Generative AI application development
* LLM fine-tuning
* AI observability and experiment tracking
* Responsible AI and governance

---

## Portfolio Website

**Visit my complete portfolio website:**

👉 **[View My Portfolio](https://girishadsc.github.io/Data-Analytics-Portfolio/)**

The website includes:

* About
* Work / Projects
* Contact

👉 **[View All Projects](https://girishadsc.github.io/Data-Analytics-Portfolio/projects.html)**

---

# Featured Skills

## Data Analytics & Visualization

* Python
* Pandas
* NumPy
* Exploratory Data Analysis
* Data Cleaning
* Feature Engineering
* Data Visualization
* Business Analytics
* Power BI
* Tableau

## Machine Learning

* Supervised Learning
* Regression
* Classification
* Random Forest
* Gradient Boosting
* Ridge Regression
* Model Evaluation
* MAE
* RMSE
* R²
* Scikit-learn

## Generative AI & LLMs

* OpenAI API
* Large Language Models
* Prompt Engineering
* LLM Applications
* Fine-Tuning
* LoRA
* GPT-2
* Document Information Extraction
* Question Answering

## AI Engineering & Tools

* MLflow
* Experiment Tracking
* AI Observability
* Hugging Face
* PyTorch
* Google Colab
* Jupyter Notebook
* GitHub

## Responsible AI

* AI Governance
* Privacy
* Bias and Fairness
* Transparency
* Accountability
* Security
* Regulatory Risk
* Responsible Generative AI

---

# Projects

The portfolio contains **10 applied projects** spanning business analytics, machine learning, Generative AI, and responsible AI.

---

## 1. Airbnb NYC Price Prediction

**Focus:** Machine Learning • Regression • Predictive Analytics

Developed an end-to-end machine learning solution using the **AB_NYC_2019** dataset to analyze and predict Airbnb listing prices in New York City.

The project included:

* Data preparation
* Exploratory data analysis
* Feature engineering
* Categorical encoding
* Regression modeling
* Ensemble learning
* Log-price modeling
* Model evaluation

Models evaluated included:

* Ridge Regression
* Random Forest
* Gradient Boosting

### Best Model

The **Random Forest** model achieved the strongest performance among the evaluated models:

| Metric |     Result |
| ------ | ---------: |
| MAE    |  56.176817 |
| RMSE   | 174.733429 |
| R²     |   0.237391 |

The project also highlights the limitations of using a historical 2019 dataset to understand today's Airbnb pricing environment.

👉 **[View Airbnb Project](Airbnb-NYC-Price-Prediction/)**

---

## 2. TSA Complaint Analysis Dashboard

**Focus:** Business Analytics • Data Visualization • Storytelling

Analyzed TSA complaint data to understand passenger dissatisfaction trends across U.S. airports.

The project used analytical techniques and visualizations to identify:

* Complaint patterns
* Geographic differences
* Airport-level trends
* Complaint categories
* Areas requiring further attention

The project demonstrates how analytical results can be transformed into dashboards and visual stories for business and operational decision-making.

**Technologies:**

Python • Power BI • Tableau • Data Visualization

👉 **[View TSA Project](TSA-Complaint-Analysis/)**

---

## 3. Childcare Pricing Analysis

**Focus:** Business Analytics • Exploratory Data Analysis • Visualization

Analyzed childcare pricing data to identify pricing patterns and relationships between childcare costs and relevant characteristics.

The project demonstrates an end-to-end analytical workflow involving:

* Data preparation
* Exploratory analysis
* Visualization
* Pattern identification
* Business interpretation

**Technologies:**

Python • Pandas • Data Visualization • Exploratory Data Analysis

👉 **[View Childcare Project](Childcare-Pricing-Analysis/)**

---

## 4. Titanic Survival Prediction

**Focus:** Classification • Feature Engineering • Kaggle

Developed a supervised machine learning solution for the **Kaggle Titanic competition**.

The workflow included:

* Data exploration
* Missing-value handling
* Feature preparation
* Categorical-variable processing
* Classification
* Prediction
* Kaggle submission

### Kaggle Result

**Kaggle Score: 0.74401**

The project demonstrates practical experience taking a classification problem from raw data through model development and external evaluation.

**Technologies:**

Python • Pandas • NumPy • Scikit-learn • Kaggle

👉 **[View Titanic Project](Titanic-Kaggle/)**

---

## 5. Invoice Information Extraction

**Focus:** Generative AI • Document Processing • Structured Extraction

Developed an AI-assisted workflow for extracting structured information from unstructured invoice content using the OpenAI API.

The project explored:

* Document information extraction
* LLM-based processing
* Structured JSON output
* API integration
* Data transformation
* Practical API limitations

The project demonstrates how Generative AI can be integrated into document-processing workflows to transform unstructured information into structured data.

**Technologies:**

Python • OpenAI API • JSON • LLMs • Document Processing

👉 **[View Invoice Extraction Project](Invoice-Information-Extraction/)**

---

## 6. FIFA World Cup Question-Answering

**Focus:** LLMs • Question Answering • Generative AI

Developed an LLM-based question-answering exercise using information about the **2022 FIFA World Cup**.

The project provided hands-on experience with:

* OpenAI API integration
* Context-based question answering
* LLM prompting
* Knowledge-source processing

An important learning outcome was understanding the distinction between passing an entire document to an LLM and implementing a complete **Retrieval-Augmented Generation (RAG)** architecture.

A production-quality RAG architecture would include:

* Document chunking
* Embedding generation
* Vector indexing
* Similarity search
* Retrieval
* Context-aware generation

This project therefore demonstrates not only LLM application development but also critical evaluation of AI architecture.

**Technologies:**

Python • OpenAI API • LLMs • NLP • Jupyter Notebook

👉 **[View FIFA Project](FIFA-World-Cup-RAG/)**

---

## 7. LoRA Fine-Tuning for GPT-2

**Focus:** LLM Fine-Tuning • LoRA • Hugging Face

Explored **Low-Rank Adaptation (LoRA)** as a parameter-efficient method for adapting a GPT-2 language model.

The project used the **English Quotes** dataset and included:

* Dataset preparation
* Tokenization
* GPT-2 configuration
* LoRA configuration
* Model training
* GPU-based experimentation
* Dependency troubleshooting

The project was moved to a **Google Colab T4 GPU environment** to support more efficient model training.

**Technologies:**

Python • PyTorch • Hugging Face • GPT-2 • LoRA • Google Colab

👉 **[View LoRA Project](LoRA-GPT2-Fine-Tuning/)**

---

## 8. MLflow GenAI Observability

**Focus:** Generative AI • MLflow • Experiment Tracking

Developed an observability workflow for a Generative AI application using the **OpenAI API and MLflow**.

The project established an MLflow experiment named:

`GenAI_book`

The workflow demonstrated:

* MLflow configuration
* Experiment creation
* LLM application execution
* Run tracking
* Experiment history
* Application output inspection

This project demonstrates the importance of tracking Generative AI application behavior rather than treating LLM applications as black boxes.

**Technologies:**

Python • OpenAI API • MLflow • Jupyter Notebook

👉 **[View MLflow Project](MLflow-GenAI-Observability/)**

---

## 9. OpenAI Fine-Tuning Experiment

**Focus:** OpenAI API • Fine-Tuning • LLM Customization

Adapted a course fine-tuning exercise to the **OpenAI API**.

Approximately **50 training examples** were prepared to teach a specific emoji-oriented response behavior.

The project explored:

* Training-data preparation
* Fine-tuning data formatting
* OpenAI API configuration
* Fine-tuning workflow
* Model customization
* API troubleshooting

During development, the fine-tuning workflow encountered an API permission limitation, providing practical experience with the operational requirements of hosted AI services.

**Technologies:**

Python • OpenAI API • OpenAI SDK • LLMs • Fine-Tuning

👉 **[View OpenAI Fine-Tuning Project](OpenAI-Fine-Tuning/)**

---

## 10. Generative AI Risk & Regulatory Challenges

**Focus:** Responsible AI • AI Governance • Regulatory Research

Researched the emerging risks and regulatory challenges associated with Generative AI.

The project examined areas including:

* Privacy
* Bias and discrimination
* Misinformation
* Security
* Intellectual property
* Transparency
* Accountability
* AI governance
* Regulatory uncertainty

The research also examined **Executive Order 14110** and the broader challenge of balancing Generative AI innovation with responsible organizational and regulatory controls.

The project demonstrates an understanding that successful AI adoption requires consideration of technical, ethical, business, and regulatory factors.

**Skills:**

Generative AI • Responsible AI • AI Governance • Regulatory Research • Risk Analysis

👉 **[View GenAI Risk Project](GenAI-Risk-Regulation/)**

---

# Data Science Workflow

Across these projects, I apply a structured data science workflow:

```text
Business / Research Problem
          ↓
       Data
          ↓
Data Cleaning & Preparation
          ↓
Exploratory Data Analysis
          ↓
Feature Engineering
          ↓
Model / AI Development
          ↓
Evaluation & Validation
          ↓
Visualization & Interpretation
          ↓
Business / User Insights
          ↓
Responsible AI Considerations
```

This approach helps connect technical implementation with the original business or research objective.

---

# Responsible AI Perspective

Responsible AI is an important component of my approach to data science and Generative AI.

When developing or evaluating AI solutions, I consider questions such as:

* Is the data appropriate for the intended use?
* Could the model produce biased outcomes?
* Is sensitive information being protected?
* Can the model's behavior be appropriately evaluated?
* Are users able to understand how the system is being used?
* What human oversight is required?
* What risks could result from incorrect predictions or generated content?

My goal is to develop AI and analytics solutions that are not only technically useful but also responsible and explainable.

---

# Repository Structure

```text
Data-Analytics-Portfolio/
│
├── Airbnb-NYC-Price-Prediction/
├── Childcare-Pricing-Analysis/
├── FIFA-World-Cup-RAG/
├── GenAI-Risk-Regulation/
├── Invoice-Information-Extraction/
├── LoRA-GPT2-Fine-Tuning/
├── MLflow-GenAI-Observability/
├── OpenAI-Fine-Tuning/
├── TSA-Complaint-Analysis/
├── Titanic-Kaggle/
│
├── index.html
├── projects.html
└── README.md
```

Each project folder contains project-specific documentation and supporting materials.

---

# Portfolio Website

For the complete visual portfolio experience:

👉 **[Visit Portfolio Website](https://girishadsc.github.io/Data-Analytics-Portfolio/)**

👉 **[View All Projects](https://girishadsc.github.io/Data-Analytics-Portfolio/projects.html)**

---

# Contact

I welcome opportunities to connect regarding:

* Data Science
* Business Analytics
* Machine Learning
* Generative AI
* Responsible AI
* AI Applications

### GitHub

**[github.com/Girishadsc](https://github.com/Girishadsc/Data-Analytics-Portfolio/tree/final-portfolio-submission)**

### LinkedIn

**[Connect with me on LinkedIn](http://www.linkedin.com/in/girisha-lingaiah-a0245163)**

---

## Final Portfolio

This repository represents my applied data science portfolio and demonstrates my progression from data analytics and visualization through predictive modeling, Generative AI, LLM fine-tuning, AI observability, and responsible AI.

**Thank you for reviewing my portfolio.**
