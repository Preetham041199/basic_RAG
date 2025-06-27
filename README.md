# LLM Application using LangChain and Google's Generative AI

This project demonstrates how to build a **Large Language Model (LLM) powered application** combining **LangChain** and **Google Generative AI (Gemini)** for document handling, question answering, and conversational AI.

## Features

- Uses **LangChain** for document loading, splitting, embedding, and retrieval.
- Leverages **Google Generative AI (Gemini Pro)** for content generation and chat-based interactions.
- Integrates **ChromaDB** as a vector store for efficient retrieval.
- Supports PDF ingestion and contextual Q&A.

## Tech Stack

- Python
- Jupyter Notebook
- LangChain
- Google Generative AI (Gemini Pro)
- ChromaDB

## Main Components

- **PyPDFLoader** — Load and process PDF documents.
- **RecursiveCharacterTextSplitter** — Chunk large texts for embeddings.
- **GoogleGenerativeAIEmbeddings** — Create vector embeddings from text.
- **ChatGoogleGenerativeAI** — Enable conversational AI.
- **RetrievalQA** — Build a question-answering system.

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd <repo-directory>
   ```

2. Install dependencies:
   ```bash
   pip install langchain google-generativeai chromadb ipython
   ```

3. Set your API key:
   Replace `'ur api key'` in the notebook with your actual **Google Generative AI API key**.

4. Run the notebook:
   Open `app.ipynb` in Jupyter and execute the cells.

## Notes

- Ensure that you have a valid Google Generative AI API key.
- Example queries include comparing models, explaining concepts (e.g., ZKPs), and recipe generation.

## License

This project is for educational/demo purposes.
