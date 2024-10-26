# Mwene-translate: Sabiny Translation Collection Project

## Overview

This project aims to create a dataset of English-to-Sabiny translations to support the development of a machine learning model for translating English into Sabiny. Since Sabiny has limited digital resources, this community-driven approach will help document and preserve the language while enabling future applications in language technology.

## Table of Contents
- [Project Overview](#overview)
- [Goals](#goals)
- [Data Collection](#data-collection)
- [How to Contribute](#how-to-contribute)
- [Technical Setup](#technical-setup)
- [Contact](#contact)

## Goals
- To build a parallel corpus of English-Sabiny translations.
- To develop a machine learning model that can accurately translate English sentences into Sabiny.
- To preserve and digitally document the Sabiny language for future generations.

## Data Collection

### Requirements
- **Languages**: English (source language) and Sabiny (target language).
- **Format**: Each entry consists of an English sentence, the Sabiny translation, optional pronunciation notes, and any additional comments.

### Structure
The dataset will have the following format:

| **English Sentence** | **Sabiny Translation** | **Pronunciation Notes** | **Additional Comments** |
|----------------------|------------------------|-------------------------|--------------------------|
| "How are you?"       | "Ndakwo kwesi?"        | n-da-kwo kwe-si         | Common greeting          |
| "Thank you."         | "Wabale."              | wa-ba-le                |                          |

### Submission Tool
To streamline data collection, we are using a Google Form where contributors can enter translations directly. The form fields include:
- **English Sentence** (Required)
- **Sabiny Translation** (Required)
- **Pronunciation Notes** (Optional)
- **Additional Comments** (Optional)

> [Submit Translations via Google Form](https://forms.gle/v25b5Pa5WRG5FMAS7)

## How to Contribute

1. **Submit Translations**:
   - Use the Google Form to enter translations, pronunciation notes, and any other relevant information.
2. **Review**:
   - Review translations for accuracy and consistency.
3. **Invite Others**:
   - Share the Google Form link with other native speakers or linguists who can help build a robust dataset.

### Guidelines for Contributors
- **Accuracy**: Ensure that translations are accurate and use the most common form of Sabiny.
- **Consistency**: Follow the same spelling and structure for commonly used phrases.
- **Context**: Add comments if certain phrases are only used in specific contexts.

## Technical Setup

### 1. Tools and Libraries
This project is primarily managed in Google Sheets. The following tools and libraries will help in further processing the data for model training:
- **Python** (for data preprocessing and model training)
- **Pandas** (to process the collected data)
- **TensorFlow/Keras** (for building and training the machine learning model)

### 2. Preprocessing and Model Training
After collecting sufficient data, the following steps will be conducted:
1. **Data Cleaning**: Remove duplicates, standardize spellings, and ensure consistency.
2. **Tokenization**: Split sentences into individual words and convert words to integers for model training.
3. **Padding**: Pad sequences to a uniform length.
4. **Model Training**: Train a sequence-to-sequence neural network with an attention mechanism on the preprocessed data.

### 3. Evaluation and Deployment
The model's performance will be evaluated using BLEU score or similar metrics, and, if successful, deployed in a mobile or web application for real-time translation.

## Contact
If you have questions about the project or would like to contribute in another way, please contact:
- **Project Lead**: CHEPTOYEK BILL
- **Email**: billcheptoyek60@gmail.com
