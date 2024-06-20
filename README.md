# PDF Question Answering AI
Objective:
The PDF Question Answering AI project aims to develop an intelligent system that can extract text from PDF documents and answer user questions based on the extracted text. The system leverages Natural Language Processing (NLP) techniques and transformer models to provide accurate and contextually relevant answers.

Features:
PDF Text Extraction: Automatically extracts text from uploaded PDF documents.
Text Preprocessing: Cleans and tokenizes the extracted text for efficient processing.
Contextual Embeddings: Uses BERT-based models to generate contextual embeddings.
Question Answering: Provides accurate answers to user questions based on the extracted text.
User-Friendly Interface: Streamlit-based interface for easy interaction and query submission.

Requirements:
numpy
nltk
transformers
torch
PyMuPDF
streamlit
protobuf (latest version to avoid compatibility issues)

Installation:
To install the necessary libraries, run the following commands:
```pip install numpy nltk transformers torch PyMuPDF streamlit
   pip install --upgrade protobuf
```
Usage:
1. Download NLTK Data:
Ensure necessary NLTK data is downloaded:

```python
  import nltk
  nltk.download('punkt')
```
2. Run the Application:
To run the Streamlit application, use the following command:
```python
streamlit run app.py
```
3. Upload PDF and Ask Questions:

Open the Streamlit application in your browser.
Upload a PDF document.
Enter a question in the text input field.
Click the "Get Answer" button to retrieve the answer based on the PDF content.

Future Improvements:
1. Enhance text preprocessing to handle complex document structures better.
2. Fine-tune the BERT model on domain-specific datasets for improved accuracy.
3. Integrate additional NLP features such as summarization and entity recognition.
