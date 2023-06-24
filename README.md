# Question-WITH-PDF
This repository contains a question-answering system with PDF context, implemented using Streamlit, LangChain, and GPT-3. The system allows users to upload a PDF document and ask questions related to its content. The model utilizes advanced language processing techniques to extract relevant information and provide accurate answers

## Key Features:

Streamlit UI: The project offers a user-friendly interface powered by Streamlit, making it easy for users to interact with the question-answering system.

PDF Context: Users can upload PDF documents, which serve as the context for the question-answering task. The system leverages the content within the PDF to generate accurate responses.

LangChain Integration: LangChain, a powerful natural language processing library, is used to process the PDF content and prepare it for question answering. It handles tasks such as text extraction, language understanding, and context representation.

GPT-3 Question-Answering: The system employs GPT-3, a state-of-the-art language model, to generate answers to user queries. GPT-3 excels at understanding and generating human-like text, enhancing the accuracy and quality of the responses.

### Usage:

Clone the repository: git clone ```https://github.com/sanket98a/Question-WITH-PDF.git```


Install the required dependencies: ```pip install -r requirements.txt```

Obtain API keys: To use LangChain and GPT-3, you'll need to obtain API keys and set them up as environment variables.

Run the Streamlit application: ```streamlit run app.py```

Access the application in your web browser: Open http://localhost:8501 and start uploading PDF documents and asking questions related to the context.
