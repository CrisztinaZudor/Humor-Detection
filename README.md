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

## How to Run the Code

### Running the Code in Google Colab
You can easily run the code in Google Colab with the following steps:
1. **Open in Colab**: Navigate to the `OutlierDetection.ipynb` notebook in this repository. You will find an "Open in Colab" button at the top of the notebook. Click this button to open the notebook directly in Google Colab.
2. **Running the Notebook**: Once the notebook is open in Google Colab, you can execute the code:
    - Run all cells in sequence by clicking on `Runtime` in the menu bar, then selecting `Run all`.
    - Alternatively, run each cell individually by clicking the play button on the left side of each code cell.
    - 
### Running Locally
If you prefer to run the notebook locally:
1. **Download the Notebook**: Click on `OutlierDetection.ipynb` in the GitHub repository and download it by clicking on `Raw`, then right-clicking and choosing "Save as" to download the file to your local machine.
2. **Upload to Colab**: Go to [Google Colab](https://colab.research.google.com/), and select `Upload notebook` from the `File` menu to upload the downloaded `.ipynb` file.
3. **Run the Notebook**: Follow the same steps as above to run the notebook cells sequentially or individually.


## Installation

To set up this project locally, you can follow these steps:

git clone https://github.com/your-github-username/humor-detection-distilbert <br>
cd humor-detection-distilbert<br>
pip install -r requirements.txt<br>


## Usage

To run the model on your data, execute:

python classify_humor.py



