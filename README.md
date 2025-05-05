Final Project for COMP 255: AI/ML

This project extracts text from a PDF of my COMP 318: Algorithms textbook, tokenizes it, and prepares the dataset created for fine-tuning a Masked Language Model or other NLP tasks. It uses Hugging Face Transformers, PyTorch, and structured dataset chunking (specifically, stride-based overlap) to maintain context while processing text.

Key Features:

✅ Extracts text from specified page ranges of a PDF.

✅ Tokenizes the text using a pretrained Hugging Face model.

✅ Splits the text into overlapping chunks for better context retention.

✅ Fine-tunes an NLP model on the processed dataset.

The model does take a very, very long time to train.

After training, the model can take a user-entered question (about algorithms) and produce a good answer. This model is already helping me study for my Algorithms final!


