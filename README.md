# ChatbotusingLangchain
A simple Chatbot is made using Langchain that reads a pdf uploaded in it and then answers questions regarding text in the pdf.


How any User can create their own ChatBot 

-Clone the repository.
-Navigate to the project directory.
-Install the required packages: pip install -r requirements.txt.
-Create a .env file based on .env.example and add their own API keys.
-Place their own PDF files in the backend/data/ folder.
-Run the ingest script to create the vector database: python backend/ingest_database.py.
-Run the chatbot app: python frontend/chatbot.py
