LangChain Vector Stores with ChromaDB
A hands-on Jupyter Notebook project demonstrating how to use Vector Stores with ChromaDB and LangChain for semantic search and document retrieval.

📌 What is This Project?
This project covers the concept of Vector Stores — a core component in LLM-based applications used to store and retrieve text as embeddings (numerical representations of meaning).
Using ChromaDB as the vector store and LangChain as the orchestration framework, this notebook shows how to:

Convert text/documents into embeddings
Store them in ChromaDB
Perform similarity search to retrieve relevant information


🛠️ Tech Stack
ToolPurpose🦜 LangChainLLM orchestration framework🟣 ChromaDBLocal vector store database🤖 OpenAIEmbeddings & language model📄 PyPDFPDF document loading🐍 PythonProgramming language

📦 Libraries Used
bashpython -m pip install langchain chromadb openai tiktoken pypdf langchain_openai langchain-community

🚀 Getting Started
1. Clone the Repository
bashgit clone https://github.com/waseemmalik82/LangChain_VectorStores_ChromaDB.git
cd LangChain_VectorStores_ChromaDB
2. Create Virtual Environment
bashpython -m venv venv
3. Activate Virtual Environment
bash# Windows (Command Prompt)
venv\Scripts\activate.bat

# Mac/Linux
source venv/bin/activate
4. Install Dependencies
bashpython -m pip install langchain chromadb openai tiktoken pypdf langchain_openai langchain-community
5. Set Your OpenAI API Key
Create a .env file in the root directory:
OPENAI_API_KEY=your_api_key_here
6. Open the Notebook
Open LangChain_VectorStores_ChromaDB.ipynb in VS Code or Jupyter and run the cells!

📚 Key Concepts Covered

Embeddings — Converting text into vectors
Vector Store — Database that stores and searches embeddings
Similarity Search — Finding relevant documents by meaning
ChromaDB — Fast, local vector database
Document Loaders — Loading PDFs and text files into LangChain


🗂️ Project Structure
LangChain_VectorStores_ChromaDB/
│
├── LangChain_VectorStores_ChromaDB.ipynb   # Main notebook
├── requirements.txt                         # Dependencies
├── .env                                     # API keys (not pushed to GitHub)
├── .gitignore                               # Ignored files
└── README.md                                # This file

⚠️ Important Notes

Never push your .env file or API keys to GitHub
Make sure your venv/ folder is in .gitignore
OpenAI API key is required for embeddings


👨‍💻 Author
Waseem Malik
GitHub: @waseemmalik82

📄 License
This project is open source and available under the MIT License.
