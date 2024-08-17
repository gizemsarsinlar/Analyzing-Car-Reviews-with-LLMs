# Analyzing Car Review with LLMs

This repository showcases practical implementations of pre-trained Large Language Models (LLMs) aimed at enhancing the operations of an auto dealership company.

## Project Description

As an AI developer for an auto dealership company, your role is to leverage pre-trained LLMs to achieve the following tasks:

1. **Analyze and Classify Customer Reviews**:
   - Utilize LLMs to classify the sentiment of car reviews.
   - Evaluate the classification accuracy and F1 score of predictions to gauge customer satisfaction.

2. **Respond to Inquiries About Car Models**:
   - Implement LLM-based responses to provide detailed information about available car models.

3. **Translate English Text Data**:
   - Translate English text data into other languages to serve a diverse customer base.
   - Assess translation quality using BLEU score metrics.

## Project Structure

- `car_reviews.csv`: Contains customer reviews of cars for sentiment analysis.
- `reference_translations.txt`: File with reference translations for BLEU score calculation.
- `sentiment_analysis.py`: Script to analyze and classify customer reviews.
- `translation_and_bleu.py`: Script for translating text and calculating BLEU score.
- `qa_and_summarization.py`: Script for handling QA tasks and summarizing reviews.

## Installation

To run the scripts in this repository, ensure you have Python and the necessary libraries installed. You can install the required libraries using pip:

```bash
pip install transformers pandas nltk sklearn
