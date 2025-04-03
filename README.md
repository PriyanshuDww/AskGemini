
# AskGemini 🧠📄

AskGemini is an AI-powered document question-answering system that allows users to ask questions based on the content of uploaded documents (like PDFs). It uses embeddings, semantic search (via FAISS), and a language model to generate intelligent responses grounded in the document context.

---

## 🚀 Features

- 🔍 Contextual document search using FAISS
- 📄 Upload and query documents in natural language
- 🧠 Uses vector embeddings for accurate semantic matching
- 🤖 Language model-powered responses
- 🧪 Includes test scripts and index handling

---

## 🛠️ Tech Stack

- **Python**
- **FAISS** – for semantic document indexing
- **Langchain / OpenAI** – for embedding + language generation (assumed from common usage)
- **pickle** – for saving and loading the index
- **Streamlit / CLI** – (can be added if there's a front-end; not present yet)

---

## 📁 Folder Structure

\`\`\`
AskGemini/
├── chatpdf1.py              # Main app logic
├── test.py                  # Test script
├── requirements.txt         # Python dependencies
├── faiss_index/
│   ├── index.faiss          # FAISS index file
│   └── index.pkl            # Associated metadata
├── Business Overview.docx   # High-level project summary
├── Technical Overview.docx  # Architecture and implementation details
\`\`\`

---

## 🧪 Getting Started

### 1. Clone the repository
\`\`\`bash
git clone https://github.com/your-username/AskGemini.git
cd AskGemini
\`\`\`

### 2. Install dependencies
\`\`\`bash
pip install -r requirements.txt
\`\`\`

### 3. Run the script
\`\`\`bash
python chatpdf1.py
\`\`\`

> Note: If you're using OpenAI or Hugging Face APIs, make sure to set up your API keys as environment variables or inside the script.

---

## 📄 Business Use Case

The goal of AskGemini is to assist users in extracting and understanding information from large documents in a natural, conversational way — useful in domains like legal, healthcare, or academic research.

---

## 📌 Future Improvements

- Add UI with Streamlit or Flask
- Support for multiple documents
- API integration
- Improved error handling

---

## 👤 Author

Your Name  
[GitHub Profile](https://github.com/your-username)  
[LinkedIn](https://linkedin.com/in/your-linkedin) *(optional)*

---

## 🪪 License

This project is open source and available under the [MIT License](LICENSE).
