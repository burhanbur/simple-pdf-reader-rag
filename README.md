# Simple PDF Reader with RAG

A streamlined PDF reader application that implements Retrieval-Augmented Generation (RAG) using DeepSeek R1 and Ollama. This application allows users to upload PDF documents and ask questions about their content, receiving accurate, context-aware responses.

## Features

- 📄 PDF document upload and processing
- 🔍 Semantic chunking for better context understanding
- 🧠 RAG implementation using DeepSeek R1 model via Ollama
- 💡 Interactive Q&A interface
- 🎨 Clean and intuitive user interface with Streamlit

## Technologies Used

- [Streamlit](https://streamlit.io/) - Web interface
- [LangChain](https://python.langchain.com/) - RAG implementation
- [Ollama](https://ollama.ai/) - Local LLM integration
- [FAISS](https://github.com/facebookresearch/faiss) - Vector storage
- [PDFPlumber](https://github.com/jsvine/pdfplumber) - PDF processing
- HuggingFace Embeddings - Text embeddings

## Prerequisites

- Python 3.x
- Ollama installed with DeepSeek R1 model

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd simple-pdf-reader-rag
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

3. Make sure you have Ollama installed and the DeepSeek R1 model pulled:
```bash
ollama pull deepseek-r1:1.5b
```

## Usage

1. Start the application:
```bash
streamlit run app.py
```

2. Open your web browser and navigate to the provided local URL (typically http://localhost:8501)

3. Upload a PDF file using the file uploader

4. Ask questions about the document in the text input field

## Features in Detail

- **Semantic Chunking**: Uses advanced semantic chunking to split documents intelligently
- **Vector Storage**: Implements FAISS for efficient similarity search
- **Context-Aware Responses**: Provides responses based on the actual content of your documents
- **User-Friendly Interface**: Clean, intuitive design with clear instructions and feedback

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

[Add your license here]