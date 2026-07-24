# Business Slogan Generator & Industry Classifier with Neural Networks

## Overview
This project applies **natural language processing (NLP)** and **neural networks** to build two models:  
1. A **slogan generator** that creates business slogans based on industry input.  
2. A **classifier** that predicts the industry of a business given its slogan.  

By combining both models, the system demonstrates how sequential modelling can be used for creative text generation and predictive classification in real-world business applications.

---

## Tools & Technologies
- Python 3  
- Jupyter Notebook / Google Colab  
- PyTorch for neural network modelling  
- Scikit-learn for preprocessing and evaluation  
- SpaCy for tokenization  
- Pandas & NumPy for data handling  

---

## Data Preparation
- Loaded dataset containing business slogans and industries.  
- Extracted relevant columns and handled missing values.  
- Tokenized slogans and business names using SpaCy.  
- Encoded industries as numerical categories for model input.  

---

## Model Workflow

### 1. Slogan Generator (LSTM)
- Built an LSTM-based sequential model.  
- Input: industry category (numerical encoding).  
- Output: generated slogan text.  
- Trained on the slogan dataset and tested by generating slogans for different industries.  

### 2. Slogan Classifier
- Built a classification model to predict industry from slogans.  
- Input: tokenized and encoded slogans.  
- Output: predicted industry category.  
- Split dataset into training and testing sets for evaluation.  

### 3. Combined Workflow
- Generated new slogans using the LSTM generator.  
- Passed generated slogans into the classifier.  
- Compared classifier predictions with intended industries to evaluate consistency.  

---

## Key Insights
- The LSTM generator successfully produces industry-specific slogans.  
- The classifier achieves strong accuracy in predicting industries from slogans.  
- Passing generated slogans through the classifier validates the generator’s relevance.  
- Combining generation and classification highlights the synergy between creative and predictive NLP tasks.  

---

## What I Learned
- How to preprocess text data for NLP tasks.  
- How to build and train LSTM models for text generation.  
- How to implement classification models for industry prediction.  
- How to evaluate NLP models using accuracy and consistency checks.  
- How to combine generative and predictive models for end-to-end workflows.  

---

## Future Improvements
- Expand dataset with more industries and slogans.  
- Use advanced architectures (GRU, Transformer-based models).  
- Fine-tune embeddings for better semantic representation.  
- Deploy as a web app where businesses can generate and classify slogans interactively.  

---

## References
- PyTorch documentation on LSTM networks.  
- Scikit-learn documentation on classification models.  
- SpaCy documentation for tokenization.  



