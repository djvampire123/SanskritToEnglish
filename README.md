# SanskritToEnglish Translation Project

Welcome to the SanskritToEnglish translation project! This repository contains code for a machine learning model that translates Sanskrit text into English. It utilizes state-of-the-art Natural Language Processing (NLP) techniques, with models trained on a rich dataset of Sanskrit and English sentence pairs.

## Project Structure

- `SanskritToEnglish.ipynb`: The main Jupyter notebook containing all the preprocessing, model training, and evaluation code.
-  Used Dataset provided by huggingface rahular/itihasa
- `nmt_weights.h5`: Saved model weights for easy reuse without retraining.

## Setup and Installation

To set up this project on your local machine, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/SanskritToEnglish.git
   cd SanskritToEnglish
2. **Install dependencies:**
    ```bash
    pip install torch torchvision torchaudio fasttext
3. **Extract and prepare the dataset:**
    ```bash
    tar -xzvf "/content/drive/MyDrive/aclImdb_v1.tar.gz" -C /path/to/destination
    
4. **Mount Google Drive (if using Google Colab):**
    ```python
    from google.colab import drive
    drive.mount('/content/drive')
