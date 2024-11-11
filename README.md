# GeminiFileWiz

Welcome to **GeminiFileWiz**! This is a file summarization and question-answering application that allows users to upload various document types (PDF, Word, PowerPoint, Excel, CSV) and ask questions based on the document content. It uses the power of Google Gemini API to summarize documents and provide accurate answers to user queries

## Web UI

![Web UI](images/Screenshot%202024-11-11%20133917.png)

## Features

- Supports multiple file formats (PDF, Word, PowerPoint, Excel, CSV)
- Summarizes the uploaded files using the Google Gemini API
- Allows users to ask questions based on the content of the documents
- Provides fast document searching using FAISS (Facebook AI Similarity Search)
- Simple, user-friendly interface built with Streamlit

## Technologies Used

- Streamlit: The project uses Streamlit to create a web-based user interface.
- Google Gemini API: Utilized for summarizing the content of the uploaded documents.
- FAISS: Employed for fast document similarity searches.
- PyPDF2: Used for extracting text from PDF files.
- python-docx: Used for extracting text from Word documents.
- python-pptx: Used for extracting text from PowerPoint presentations.
- Pandas: Used for handling Excel and CSV file operations.
- dotenv: Used for managing environment variables securely.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/DadvaiahPavan/GeminiFileWiz.git
```

2. Create a virtual environment:

```bash
python -m venv venv
```

3. Activate the virtual environment:

- For Windows:

```bash
venv\Scripts\activate
```

- For macOS/Linux:

```bash
source venv/bin/activate
```

4. Install the required dependencies:

```bash
pip install -r requirements.txt
```

5. Set  Google Gemini API:
- Obtain your Google Gemini API key from the Google Cloud Console.
- Create a .env file in the root directory of the project and add your API key as follows:

```bash
GOOGLE_API_KEY=your_api_key_here
```

6. Start the application:

```bash
streamlit run app.py

```

7. Open your web browser and visit `http://localhost:5000` to access the Application.

## Supported File Formats

- PDF: Extracts text from PDF files
- Word (.docx): Extracts text from Word documents
- PowerPoint (.pptx): Extracts text from PowerPoint presentations
- Excel (.xlsx, .xls): Extracts text from Excel files
- CSV: Extracts text from CSV files

## Authors
- Dadvaiah Pavan

## Contribution

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to create an issue or submit a pull request.



## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Contact

For any inquiries or further information, please contact [Pavan Dadvaiah] via email at [pavannetha219@gmail.com].

---
