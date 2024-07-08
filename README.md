# Document Genie: Unlock Insights from Your PDFs with AI

This repository provides a user-friendly Streamlit application called "Document Genie" - a powerful tool for extracting knowledge from your PDF documents using Google's Generative AI technology. You can run this repository here: [Document Genie]()

## 1. Key Features

- **Leverages Google's Generative AI:** Employs the advanced capabilities of Google's Gemini-PRO model for accurate and comprehensive information retrieval.
- **Retrieval-Augmented Generation (RAG):** Utilizes a cutting-edge approach that combines document retrieval with AI-powered generation to deliver precise answers to your questions.
- **Efficient PDF Processing:** Handles multiple PDF uploads at once, breaking them down into manageable chunks for efficient analysis.
- **Searchable Vector Store:** Creates a searchable index of your documents using AI-powered embeddings, enabling rapid information access.
- **Conversational Interface:** Interact with your documents through a user-friendly interface where you can ask questions and receive relevant answers directly from the content.

## 2. How it Works

1. **Upload Your Documents:** Select and upload your PDF files (multiple uploads are supported) using the dedicated file uploader in the sidebar.
2. **Process Documents:** Click the "Submit & Process" button to initiate the document processing stage. The application will analyze your uploaded PDFs, extracting and indexing the content.
3. **Ask Your Questions:** Once processing is complete, a text input field will appear. Feel free to ask any questions related to the information contained within your documents. 
4. **Get Instant Answers:** Document Genie employs its AI capabilities to search through the processed content and provide insightful answers directly related to your queries.

## 3. Requirements

- Python 3.x
- Streamlit (`pip install streamlit`)
- PyPDF2 (`pip install PyPDF2`)
- langchain (`pip install langchain`)
- langchain-google-genai (`pip install langchain-google-genai`)
- langchain-community (`pip install langchain-community`)
- dotenv (`pip install python-dotenv`)
- A Google Cloud Project with a Generative AI API enabled (and a valid API Key)

## 4. Getting Started

1. Clone or download this repository.
2. Install the required libraries (`pip install -r requirements.txt`).
3. Create a file named `.env` in the project's root directory and add the line `GOOGLE_API_KEY=<YOUR_API_KEY>` (replace `<YOUR_API_KEY>` with your actual Google Cloud Generative AI API Key).
4. Run the application using `streamlit run main.py`.

## 5. Note

- A valid Google Cloud Project with a Generative AI API enabled and a corresponding API Key are necessary for the application to function.
- This is a demonstration of the RAG approach. Consider exploring more advanced text processing techniques for further refinement.

## 6. Further Enhancements

- Implement document summarization capabilities alongside question answering.
- Integrate document visualization tools for highlighting relevant passages based on user queries.
- Allow users to specify search filters or focus areas within the documents.
