# GeminiFileWiz

GeminiFileWiz is a powerful file summarization tool built with Streamlit and Google Gemini API. This project allows users to upload various types of documents (PDF, Word, PowerPoint, Excel, CSV) and interact with them by asking questions. The app uses the Google Gemini API to summarize the contents of the uploaded files and provide relevant responses based on the user's queries.

## Features
- **Supports multiple file formats**: PDF, Word, PowerPoint, Excel, and CSV.
- **Summarization using Google Gemini API**: Summarizes uploaded files and extracts meaningful information.
- **Document-based question answering**: Users can ask questions about the content of the uploaded documents.
- **Efficient search**: Uses FAISS (Facebook AI Similarity Search) for fast document similarity search.
- **User-friendly interface**: Built with Streamlit for an interactive web interface.

## Tools and Technologies Used
- **Streamlit**: Web framework for creating interactive applications.
- **Google Gemini API**: Used to generate summaries and embeddings for document content.
- **FAISS**: Efficient vector search library used to store and retrieve document embeddings.
- **Python Libraries**:
  - `PyPDF2`: For reading and extracting text from PDF files.
  - `python-docx`: For reading Word documents.
  - `python-pptx`: For reading PowerPoint presentations.
  - `pandas`: For handling Excel and CSV files.
  - `langchain`: For integrating language models, text splitting, and document embeddings.

## Prerequisites
Before running the project, make sure you have the following installed:
- **Python 3.8 or higher**
- **pip** (Python package installer)

## Installation

### Clone the repository
To get started, first clone the repository:

```bash
git clone https://github.com/DadvaiahPavan/GeminiFileWiz.git
cd GeminiFileWiz
Set up a virtual environment
It is recommended to create a virtual environment for the project:

bash
Copy code
python -m venv venv
Activate the virtual environment
For Windows:
bash
Copy code
venv\Scripts\activate
For macOS/Linux:
bash
Copy code
source venv/bin/activate
Install the required dependencies
Once the virtual environment is activated, install the dependencies using the following command:

bash
Copy code
pip install -r requirements.txt
Setup Google Gemini API
Obtain your Google Gemini API key from the Google Cloud Console.
Create a .env file in the root directory of the project and add your API key as follows:
makefile
Copy code
GOOGLE_API_KEY=your_api_key_here
Running the App Locally
Once the setup is complete, you can run the application locally with the following command:

bash
Copy code
streamlit run app.py
This command will launch the app in your default web browser. You can now interact with the uploaded documents and ask questions based on the content.

Usage
Upload Documents: In the sidebar, click on "Upload your Documents" to upload files. Supported formats include PDF, Word, PowerPoint, Excel, and CSV.
Ask Questions: After uploading the files, type your questions in the input field to get responses based on the content of the uploaded documents.
