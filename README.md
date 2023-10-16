# Text-Summarization-of-COVID-19-Medical-Articles-using-DistilBERT 📄


## Project Proposal for CSCE 5290: Natural Language Processing



## Motivation
COVID-19 is a novel virus that has impacted the world significantly. With an increasing number of research articles being published on the subject, it becomes challenging to keep up with the vast amount of information. In order to address this issue, we propose a text summarization model that can summarize COVID-19 related articles, providing concise answers and insights.

## Objective
- Gather articles related to text summarization in the medical domain of COVID-19.
- Develop a model that can summarize the abstracts of COVID-19 articles, aiding in faster access to information during the pandemic.

## Significance
- Provide a time-saving tool for individuals seeking quick and effective solutions to their questions related to COVID-19.
- Benefit developing countries or regions with limited resources by providing accurate answers and minimizing the spread of misinformation.

## Features
- Unsupervised system for comprehending scientific literature and generating precise responses from the CORD-19 corpus of scientific papers.

## Approach
- Develop an unsupervised system that accepts natural language questions with a focus keyword.
- Retrieve precise responses from the CORD-19 corpus of scientific papers using NLP techniques.

## Dataset
- The COVID-19 Open Scientific Dataset (CORD-19) is a collection of over a million research publications related to COVID-19, SARS-CoV-2, and similar coronaviruses.
- The dataset includes over 400,000 full-text articles and is the largest machine-readable coronavirus literature collection available for data mining.
- For this project, a subset of the CORD-19 dataset was used, including attributes such as title, DOI, abstract, publish time, authors, and URL.

## Pre-processing
- Data cleaning steps include dropping null value columns, removing duplicate titles, converting text to lowercase, and considering research papers from the year 2020.
- The abstracts of papers containing terms related to COVID-19 are stored in a DataFrame.
- Text is tokenized, stop words are removed, and a DataFrame is created focusing on the given keywords.
- Sentence similarity using the SpaCy library is utilized to calculate the similarity between given sentences and the summarized answer.

## Model
- NLP libraries such as NLTK, BERT, GPT-2, RNN, Transformer, Seq2seq are utilized for text summarization.
- Cosine similarity is used as a performance measure for the model.



## Usage
- Run the Notebook: `Task_4_bert_summarizer(Harsha_EXP).ipynb`
- Follow the instructions to input your questions and focus keywords.
- The model will generate a summarized answer based on the CORD-19 dataset.


