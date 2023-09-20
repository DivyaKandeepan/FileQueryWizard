# Multi-file-chatbot

This is a simple Streamlit-based chatbot application that allows you to upload and process various types of documents, such as PDFs, DOCX files, and text files, and then interactively chat with the chatbot to retrieve information or answers from these documents. The chatbot uses language models and embeddings for document retrieval and answering questions.

## Getting Started

To run this chatbot application, you need to have Python installed on your system. Follow these steps to get started:

1. Clone or download this repository to your local machine.

2. Install the required Python libraries. You can do this using `pip` and the provided `requirements.txt` file. Open a terminal or command prompt, navigate to the project directory, and run:
`pip install -r requirements.txt`

3. Create a `.env` file in the project directory and define your environment variables.

This will start the Streamlit application, and you should see it open in your web browser.

## How to Use

### Uploading Documents

1. In the Streamlit web application, you will see a file uploader on the left sidebar labeled "Your documents." You can upload multiple files of different types, including PDFs, DOCX files, and text files. Simply click on the "Upload your files here" button and select the documents you want to process.

2. After uploading your documents, click on the "Process" button. The chatbot will process the documents, extract text from them, and prepare them for further interactions.

### Asking Questions

3. In the main section of the application, you will find a text input box labeled "Ask a question about your documents." Enter your question or query related to the uploaded documents in this input box.

4. Click on the "Submit" button, and the chatbot will provide a response based on the content of the uploaded documents. You will see the chat history displayed in the main section of the application, with user and bot messages.

### Handling CSV Files

5. If you uploaded a CSV file among your documents and have a question related to it, the chatbot can also answer questions from CSV data. Enter your question in the input box and click Enter. The chatbot will use a Hugging Face table-question-answering pipeline to provide answers based on the CSV data.

## Features

- Upload and process multiple types of documents, including PDFs, DOCX files, and text files.
- Chat interactively with the chatbot to retrieve information or answers from the uploaded documents.
- Handle CSV files and answer questions related to tabular data within them.
- Uses Hugging Face language models and embeddings for document retrieval and question answering.


