# Humor Detection in Text Using Deep Learning (DistilBERT)

Humor detection in text represents a fascinating challenge at the intersection of natural language processing and human communication. As a fundamental aspect of human interaction, humor serves to create comfort, ease tension, and foster positive environments. Research has shown that humor can have significant beneficial effects on human health and mood, making its computational understanding particularly valuable for human-centered AI systems like chatbots and virtual assistants.  The challenge of automatically detecting humor is multifaceted. Humor varies significantly across cultures, regions, and individuals, making standardization difficult. Different forms of humor, including irony, wordplay, metaphor, and sarcasm, often require extensive contextual and cultural knowledge to understand.

## Project Description

Humor detection in text is a complex challenge at the intersection of natural language processing and human interaction. This project utilizes the DistilBERT model, a streamlined version of the BERT transformer, to classify short texts based on their humor content. The model processes a dataset of 200,000 labeled texts, which include both humorous and non-humorous examples, to learn and predict the nuances that differentiate humorous interactions.

## Dataset

The dataset, titled "200k Short Texts for Humor Detection," sourced from Kaggle, comprises an equal distribution of humorous and non-humorous short texts. These texts were preprocessed to ensure consistency and balanced linguistic features, providing a robust foundation for training the classification model.

## Model

The model uses the `DistilBertForSequenceClassification` from Hugging Face's transformers library, fine-tuned on our specific dataset. The configuration includes dropout for regularization and the AdamW optimizer for effective learning rate adjustment.

## Key Features

- **Preprocessing**: Integration of data cleaning, tokenization, and preparation steps to standardize input data.
- **Training**: Utilization of PyTorch and Hugging Face libraries for model training, with metrics monitoring to prevent overfitting.
- **Evaluation**: Detailed performance analysis using accuracy, precision, recall, and F1-score metrics.
- **Visualization**: Training and validation progress visualizations, alongside word clouds and sentiment analysis for deeper insights into dataset characteristics.

## Installation

To set up this project locally, you can follow these steps:

bash
git clone https://github.com/your-github-username/humor-detection-distilbert
cd humor-detection-distilbert
pip install -r requirements.txt


## Usage

To run the model on your data, execute:

python
python classify_humor.py

