# PdfChat_Application
Application using OpenAI and LangChain to chat with pdfs. This project is my ongoing work.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

> An interactive web application built with Streamlit and LangChain that allows you to chat with your PDF documents.

This project leverages the power of Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG) to create a conversational interface for your PDF files. Upload your documents, and start asking questions!

---
## 🔗 Project Showcase
I also shared this project on LinkedIn – check out the post here:  
👉 [View my LinkedIn post](https://www.linkedin.com/posts/sunny-bhatkar-75793828a_learning-langchain-streamlit-ugcPost-7379156200791212032-rqDa?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEZC-TMBsa58MpxQk5npf_8R0ZZxlpsK600)

## ✨ Features

-   **Upload Multiple PDFs**: Supports uploading one or more PDF documents simultaneously.
-   **Dynamic Q&A**: Ask questions in natural language and get answers based on the content of the uploaded documents.
-   **Built with RAG**: Utilizes a Retrieval-Augmented Generation pipeline to find the most relevant context from the documents to answer your questions.
-   **User-Friendly Interface**: A simple and intuitive web interface powered by Streamlit.
-   **Chat History**: Remembers the context of the current conversation.

---

## 🛠️ Tech Stack

-   **Backend**: Python
-   **Web Framework**: Streamlit
-   **LLM Framework**: LangChain
-   **LLM & Embeddings**: OpenAI
-   **Vector Store**: FAISS (Facebook AI Similarity Search)
-   **PDF Processing**: PyPDF2

---

## 🔧 Setup and Installation

Follow these steps to set up and run the project on your local machine.

### 1. Clone the Repository
Clone this repository to your local machine:
```bash
git clone [https://github.com/Sunny-sketchs/PdfChat_Application.git](https://github.com/Sunny-sketchs/PdfChat_Application.git)
cd PdfChat_Application
```

###2. Create a Virtual Environment
It is highly recommended to use a virtual environment to manage dependencies.
# For Windows
```bash
python -m venv venv
venv\Scripts\activate

# For macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

###3. Install Dependencies
Install all the required Python packages using the requirements.txt file.
```bash
pip install -r requirements.txt
```

###4. Set Up Environment Variables
You need an OpenAI API key to run this application.
Create a file named .env in the root of your project folder.
Add your OpenAI API key to the file as follows:

```python
OPENAI_API_KEY="sk-YourSecretApiKeyHere"
```

###5. Run the Application
Launch the Streamlit application with the following command:

```bash
streamlit run app.py
```

📖 How to Use
Launch the application using the command above.

Upload your PDF file(s) using the file uploader in the sidebar.

Click the "Process" button and wait for the document processing to complete.

Start asking questions! Type your questions into the chat input box at the bottom of the page and get instant answers.
