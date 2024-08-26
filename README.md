# PDF Conversational Retrieval Application

This project is a conversational retrieval application that allows users to interact with PDF documents using natural language queries. 
Built with Streamlit, LangChain, FAISS, and Google Generative AI, the application enables users to upload multiple PDF files, process their contents into text chunks, 
and then ask questions to extract specific information. The system is designed to answer questions with a high degree of accuracy based on the content of the uploaded PDFs. 
It also has the capability to format extracted information as JSON, providing structured output for easy integration into other applications.

## Features

- **PDF Text Extraction**
- **Text Chunking**
- **FAISS Vector Store**
- **Conversational AI**
- **Information Extraction**
- **Streamlit Interface**

## Technologies Used

- Streamlit
- LangChain
- FAISS
- Google Generative AI
- PyPDF2
- Python

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/MontassarbellahAbdallah/Chat-with-multiple-pdfs-using-Gemini.git
    cd Chat-with-multiple-pdfs-using-Gemini
    ```

2. **Create a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the dependencies**:
    ```bash
    pip install -r req.txt
    ```

4. **Set up the environment variables**:
    - Create a `.env` file in the root directory and add your Google API key:
    ```plaintext
    GOOGLE_API_KEY=your_google_api_key
    ```

5. **Run the Streamlit app**:
    ```bash
    streamlit run main.py
    ```

## Usage

1. Upload PDF files using the sidebar menu in the Streamlit app.
2. Enter your question related to the PDF content in the input box.
3. The app will process the PDFs, create a FAISS index, and then answer your question based on the document content.
4. The response, including any extracted information, will be displayed in JSON format.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request with your changes.

## License

This project is not for commercial use.

## Contact

For any inquiries or support, please contact [montassar.bellah.abdallah@gmail.com].
