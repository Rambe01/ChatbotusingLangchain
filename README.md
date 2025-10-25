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


Prompt Design:
First the Backend has to be made and the requirements.txt has to be run. 
We can use either OpenAI or MistralAI , just the keys and code has to modified accordingly. 
The LLM chosen will read the pdf uploaded and then respond to the questions given to it about the pdf given, if any other question is asked, it will fetch an error.
The frontend will use the AI chosen and launch it via Gradio and then the questions can be asked on the link given.

Issues Faced:
Sometimes there can be issues faced while fething the data from the pdf if the AI Key assigned to it does not have any credit to it or if the name given is not correct. We should stick to OPEN_AI_KEY or MISTRAL_AI_KEY to avoid any such issues. 
