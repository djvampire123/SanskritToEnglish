# SanskritToEnglish Translation Project

Welcome to the SanskritToEnglish translation project! This repository contains code for a machine learning model that translates Sanskrit text into English. It utilizes state-of-the-art Natural Language Processing (NLP) techniques, with models trained on a rich dataset of Sanskrit and English sentence pairs.

## Overview
Language translation from Sanskrit to English is a fascinating and complex task. Sanskrit, one of the oldest languages in the world, has a rich heritage and an intricate grammar structure. Translating it into English, a modern and widely spoken language, requires a deep understanding of both languages' nuances, cultural contexts, and linguistic intricacies.

## Motivation
The primary motivation for translating Sanskrit to English lies in preserving and disseminating ancient knowledge. Sanskrit texts encompass a vast range of subjects, including philosophy, science, medicine, mathematics, and literature. By translating these texts into English, we make this treasure trove of wisdom accessible to a global audience. This endeavor also helps bridge cultural gaps and fosters a greater appreciation of ancient Indian heritage.

## Contribution
In this work, we explore advanced methodologies for translating Sanskrit texts into English. Specifically, we employ a combination of linguistic analysis and modern computational techniques to enhance the accuracy and efficiency of translations. Our approach leverages:

- **Morphological Analysis:** Breaking down complex Sanskrit words into their root forms and grammatical components to understand their meanings better.
- **Syntax Parsing:** Analyzing the sentence structure to preserve the original context and intent.
- **Semantic Mapping:** Ensuring that the translated text conveys the same meaning as the original by considering the cultural and contextual nuances.
- **Machine Learning Models:** Utilizing neural networks and natural language processing (NLP) techniques to automate and refine the translation process.

Through this framework, we aim to produce translations that are not only accurate but also fluent and readable in English.

## Highlights
- **Linguistic Precision:** Ensuring high accuracy in translating complex grammatical structures and poetic expressions.
- **Cultural Context:** Maintaining the cultural and contextual integrity of the original Sanskrit texts.
- **Automated Translation:** Leveraging state-of-the-art machine learning models to enhance translation speed and consistency.
- **Comprehensive Dataset:** Using a large corpus of Sanskrit-English parallel texts for training and validation of our models.

## Method
Our translation framework involves two primary stages:

### Stage A: Linguistic Pre-Processing
- **Morphological Analysis:** Decomposing Sanskrit words into their roots and affixes.
- **Syntax Parsing:** Constructing parse trees to understand the grammatical structure of sentences.
- **Semantic Analysis:** Mapping Sanskrit semantics to English equivalents.

### Stage B: Machine Learning Translation
- **Model Training:** Using a parallel corpus of Sanskrit-English texts to train NLP models.
- **Translation Generation:** Employing neural networks to generate translations.
- **Post-Processing:** Refining translations through human-in-the-loop feedback and additional linguistic rules.

## Results Compared with Benchmarks
Our translation system has been benchmarked against existing methods, showing significant improvements in both accuracy and fluency. Key performance metrics include:

- **BLEU Score:** Achieving a BLEU score of 23.19, which is a substantial improvement over traditional rule-based methods.
- **Translation Accuracy:** 67% accuracy in preserving the meaning and context of original Sanskrit texts.
- **Fluency:** High fluency in the generated English translations, with minimal grammatical errors.

## Generation Consistency and Replication Dataset
To ensure consistency and replicability, our translation models have been tested on multiple datasets, including:

- **Digital Corpus of Sanskrit:** A comprehensive collection of Sanskrit texts for training and validation.
- **Itihasa Test Set:** A dataset containing English translations of Sanskrit manuscripts, used for benchmarking our model's performance.

## Project Structure
- `SanskritToEnglishTransformer.ipynb`: The main Jupyter notebook containing all the preprocessing, model training, and evaluation code.
- Used Dataset provided by Hugging Face: [rahular/itihasa](https://huggingface.co/datasets/rahular/itihasa)
- `nmt_weights.h5`: Saved model weights for easy reuse without retraining.(For Initial LSTM based model)

## Setup and Installation
To set up this project on your local machine, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/SanskritToEnglish.git
    cd SanskritToEnglish
    ```
2. **Install dependencies:**
    ```bash
    pip install datasets tokenizers torch
    ```
3. **Mount Google Drive (if using Google Colab):**
    ```python
    from google.colab import drive
    drive.mount('/content/drive')
    ```

## Usage
1. Open the `SanskritToEnglishTransformer.ipynb` notebook in Jupyter or Google Colab.
2. Follow the steps in the notebook to preprocess the data, train the model, and evaluate the translations.

## Acknowledgments
We would like to thank the creators of the datasets and the open-source community for their invaluable contributions.
