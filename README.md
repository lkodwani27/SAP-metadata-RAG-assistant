# SAP Metadata RAG Assistant
An AI-Powered Enterprise Data Discovery Assistant Using RAG that turns static metadata catalogs into conversational, semantic search experience.

Built by an SAP practitioner with "12+ years of enterprise data experience", applying modern GenAI patterns to a problem I've watched clients struggle with for over a decade.

# why this Project
After 12 years across SAP ECC and S/4HANA I've seen the same pain everywhere: 
- Business users can't find the right table
- Analysts waste hours in SE16N/SE11
- Data catalogs are static and keyword-based
- Tribal kno knowledge doesn't scale

This project uses **Retrieval-Augmented Generation (RAG)** to make enterprise metadata searchable in plain English,

# Sample Queries
"Which dataset contains customer revenue?"
"Find tables related to employee attendance which datasets are missing ownership info?"
"Explain the customer orders table."

# How It works
User Query -> Embedding -> FAISS Search -> Retrieved Metadata -> FLAN-T5 ->  Grounded Answer

# Tech Stack
- Python, Pandas, NumPy
- Sentence-Transformers (embeddings)
- FAISS (vector search)
- FLAN-T5 (LLM)
- Hugging Face Transformers

# Run It
1. Open the notebook in Google Colab
2. Upload `enterprise_metadata_catalog.csv'
3. Run all cells


