# GeminiFileWiz

GeminiFileWiz is a powerful file summarization tool built with Streamlit and Google Gemini API. It allows users to upload various types of documents (PDF, Word, PowerPoint, Excel, CSV) and interact with them by asking questions. The app uses the Google Gemini API to summarize the contents of the uploaded files and provide relevant responses based on the user's queries.

## Features
- Supports file formats: PDF, Word, PowerPoint, Excel, and CSV.
- Summarizes documents using Google Gemini API.
- Allows users to interact with the uploaded files and ask questions related to the content.
- Uses FAISS (Facebook AI Similarity Search) for efficient document similarity search.
- Built with Streamlit for an interactive web interface.

## Prerequisites
Before running the project, make sure you have the following installed:

- Python 3.8 or higher
- pip (Python package installer)

## Installation

### Clone the repository:

```bash
git clone https://github.com/DadvaiahPavan/GeminiFileWiz.git
cd GeminiFileWiz
Create a virtual environment:
bash
Copy code
python -m venv venv
Activate the virtual environment:
For Windows:
bash
Copy code
venv\Scripts\activate
For macOS/Linux:
bash
Copy code
source venv/bin/activate
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Setup Google Gemini API:
Get your Google Gemini API key from the Google Cloud Console.
Create a .env file in the root directory of the project and add your API key:
makefile
Copy code
GOOGLE_API_KEY=your_api_key_here
Running the App
Once the dependencies are installed and the API key is set up, you can run the app using the following command:

bash
Copy code
streamlit run app.py
This will launch the app in your browser, where you can upload documents and interact with them.

Usage
Upload Documents: In the sidebar, click on "Upload your Documents" to upload files. Supported formats include PDF, Word, PowerPoint, Excel, and CSV.
Ask Questions: After uploading the files, you can type your questions in the input field to get relevant responses based on the uploaded documents.# GeminiFileWiz
