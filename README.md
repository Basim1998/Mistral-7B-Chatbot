### Job Interview Prep ChatBot
The Job Interview Prep ChatBot is a ] tool designed to assist users in preparing for job interviews by providing accurate and helpful responses to their questions using advanced natural language processing (NLP) models and frameworks.
The project leverages Streamlit for the user interface
LangChain for building applications with large language models (LLMs) and community-contributed models from LangChain Community
HuggingFace's sentence-transformers/all-MiniLM-L6-v2 for creating vector representations of text
CTransformers with the **mistral-7b-instruct-v0.1.Q4_K_M.gguf** model for generating responses. 
FAISS is used for efficient similarity search and retrieval of relevant text chunks from loaded PDF documents processed by PyPDFLoader and DirectoryLoader
Which are then split into manageable chunks using RecursiveCharacterTextSplitter. 

The chatbot maintains a conversation history and provides a user-friendly interface through Streamlit and streamlit_chat, ensuring personalized and relevant information to enhance users' interview skills.
This integration of modern NLP with an accessible interface creates an engaging and effective tool for job interview preparation.

![Screenshot (257)](https://github.com/user-attachments/assets/de514674-7512-4bab-ac39-ea09844bb3d0)
