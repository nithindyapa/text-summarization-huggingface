# Text Summarization using Hugging Face

## Project Overview
This project uses a pretrained Transformer model to generate concise summaries from longer text. It demonstrates an abstractive text summarization application using the Hugging Face Transformers library.

## Technologies Used
- Python
- Hugging Face Transformers
- PyTorch
- Google Colab

## Model Used
`sshleifer/distilbart-cnn-12-6`

## Features
- Generates summaries from input paragraphs
- Reduces lengthy text into concise content
- Uses a pretrained Transformer model
- Allows users to experiment with different input texts

## How It Works
1. Load the pretrained summarization model.
2. Provide an input paragraph.
3. Pass the text to the summarization pipeline.
4. Generate and display the summary.
5. Compare the original text with the generated summary.

## Example
**Input:** A paragraph explaining how Artificial Intelligence is transforming healthcare, education, and business.

**Output:** A shorter summary highlighting the major applications and challenges of AI.

## How to Run
1. Open `text_summarization.ipynb` in Google Colab.
2. Run the installation cell.
3. Execute the remaining cells.
4. Change the input paragraph to experiment with summarization.

## Repository Structure
```text
text-summarization-huggingface/
│
├── text_summarization.ipynb
└── README.md
```

## Learning Outcome
Learned how to implement abstractive text summarization using pretrained Transformer models and Hugging Face pipelines.
