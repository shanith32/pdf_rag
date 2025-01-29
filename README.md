# pdf_rag

Based on: https://dev.to/ajmal_hasan/setting-up-ollama-running-deepseek-r1-locally-for-a-powerful-rag-system-4pd4

## Running Locally
1. Have deepseek-r1 running locally, install ollama from the website: https://ollama.com/ and run the following command:
```bash
ollama run deepseek-r1:1.5b
```

2. Setup a virtual environment
```bash
python3 -m venv .venv
source venv/bin/activate
```

3. Install python pagckages
```bash
pip install -U langchain langchain-community
pip install streamlit
pip install pdfplumber
pip install semantic-chunkers
pip install open-text-embeddings
pip install faiss
pip install ollama
pip install prompt-template
pip install langchain
pip install langchain_experimental
pip install sentence-transformers
pip install faiss-cpu
```

4. Run the streamlit app
```bash
streamlit run app.py
```