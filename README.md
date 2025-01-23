# Smart-Educational-Chatbot
 A Retrieval-Augmented Generation (RAG)-based chatbot for Bharathiar University, leveraging LangChain, Streamlit, and vector embeddings to provide concise, accurate answers.

# Project Description
 The Smart Education Query chatbot is an AI-powered tool developed for Bharathiar University to streamline access to university-related information. Using state-of-the-art Retrieval-Augmented Generation (RAG) techniques, it processes over 72 PDF documents to provide detailed, summarized, and accurate answers to queries. The chatbot handles questions about affiliated colleges, courses, fees, admissions, scholarships, research initiatives, and more, making it a one-stop solution for prospective students, current students, faculty, and researchers.

# Features
Interactive Q&A: Ask detailed questions about the university and receive precise answers.
Advanced Document Retrieval: Searches for relevant information using vector-based techniques.
Summarized Responses: Generates concise answers to improve user experience.
Document Similarity Search: Explore similar documents and related content through contextual analysis.
Responsive Web Interface: A user-friendly platform built with Streamlit.

# Workflow
Data Loading:
Loads all university-related PDFs from a specified directory.
Preprocessing:
Splits the documents into manageable chunks and creates vector embeddings using Google Generative AI.
User Interaction:
Users input questions via the Streamlit interface.
Document Retrieval:
Retrieves relevant document chunks based on vector similarity.
Response Generation:
Summarizes and delivers precise answers with an option to explore related content.

# Technologies Used
Streamlit: For developing the intuitive web interface.
LangChain: For building retrieval and summarization pipelines.
FAISS (Facebook AI Similarity Search): For high-speed vector-based document retrieval.
Google Generative AI Embeddings: To create document embeddings.
OpenAI ChatGroq: For generating natural, human-like responses.
PyPDFDirectoryLoader: To efficiently load and process multiple PDF documents.
Python: The core programming language for development.

# Usage
1. Open the Streamlit app on your local machine.
2. Enter your question in the input field (e.g., “What is the admission process for MBA?”).
3. View the detailed answer along with a concise summary.
4. Explore related documents using the “Document Similarity Search” feature.

# Project Structure
1. app.py: Contains the Streamlit application code.
2. preprocessing.py: Handles PDF loading, chunking, and vector embedding creation.
3. requirements.txt: Lists all required Python libraries.
4. PDF Folder (BU): Directory containing the university-related PDF documents.

# Key Functionalities
Document Embedding and Retrieval: Creates vector embeddings for documents and retrieves relevant chunks using FAISS.
Conversational AI: Generates responses using OpenAI ChatGroq with multiple prompt options.
Summarization: Delivers clear and concise answers using a summarization pipeline.
Document Similarity Search: Provides additional insights through contextual document analysis.

# Target Audience
Prospective Students: To explore courses, admissions, and scholarships.
Current Students and Faculty: For quick access to academic and departmental details.
University Administration: To automate responses to frequent inquiries.
Researchers: To summarize and extract insights from university-related content.

# Acknowledgments
Streamlit: For the interactive web interface.
LangChain: For orchestrating the RAG framework.
FAISS: For its powerful vector search capabilities.
Google Generative AI Embeddings: For creating document embeddings.
OpenAI ChatGroq: For conversational responses.
