# PROCODER : End-To-End-Multi-Programming-Code-Assistant-App-Using-CodeLlama-LLAMA2-Large-Language-Model

PROCODER is a powerful Streamlit application designed to work as a Code Assistant App. This innovative app offers real-time code suggestions, syntax highlighting, and debugging assistance. With the backing of a Large Language Model Code Llama, it's your indispensable tool for efficient and error-free coding, tailored to your programming needs.

## Features

- **Instant Insights**: Enhance code quality instantly, readability, optimization, fostering efficient and effective coding practices.
- **Code Llama**: IT is an AI model built on top of Llama 2, fine-tuned for generating and discussing code..
- **Secure API Key Input**: Ensures secure entry of Google API keys for accessing generative AI models.

## Getting Started

### Prerequisites

- CodeLlama: This application is built with CodeLlama. Ensure you have Ollama installed in your environment and download CodeLlama.
- Gradio: Front-End of this application is built with Gradio. Ensure you have Gradio installed in your environment.

### Installation

Clone this repository or download the source code to your local machine. Navigate to the application directory and install the required Python packages:

```bash
pip install -r requirements.txt
```

### How to Use

1. **Start the Application**: Launch the Python application by running the command:
    ```bash
    python <path_to_script.py>
    ```
    Replace `<path_to_script.py>` with the path to the script file.

2. **Enter Your Google API Key**: Securely enter your Google API key when prompted. This key enables the application to access Google's Generative AI models.

3. **Upload PDF Documents**: You can upload one or multiple PDF documents. The application will analyze the content of these documents to respond to queries.

4. **Ask Questions**: Once your documents are processed, you can ask any question related to the content of your uploaded documents.

### Technical Overview

- **Gradio**: It is an open-source Python package that allows you to quickly build a demo or web application for your machine learning model, API, or any arbitary Python function.
- **Text Chunking**: Employs the `RecursiveCharacterTextSplitter` from LangChain for dividing the extracted text into manageable chunks.
- **Vector Store Creation**: Uses `FAISS` for creating a searchable vector store from text chunks.
- **Answer Generation**: Leverages `ChatGoogleGenerativeAI` from LangChain for generating answers to user queries using the context provided by the uploaded documents.


### Support
