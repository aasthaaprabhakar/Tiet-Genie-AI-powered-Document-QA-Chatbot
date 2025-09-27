# 🤖 Tiet‑Genie

An AI‑powered assistant for Thapar Institute that answers questions from uploaded academic documents or embedded institute PDFs. Developed using Streamlit, LangChain, FAISS, and Together AI.

---

## 🚀 Live Demo  
👉 [Try it here](https://tiet-genie-gjminmpfjsp4vy3zvqm235.streamlit.app)  
---

## ⚙️ Features  
- 📂 Upload supported formats: PDF, DOCX, PPTX, TXT, MD  
- 🔍 Semantic search using Sentence Transformers + FAISS  
- 🤖 Conversational Q&A powered by Together AI (DeepSeek-V3)  
- 📄 Bundled institute docs: `rules.pdf` & `AcademicRegulations.pdf`  
- 📤 Export history as TXT or PDF  

---

## 🧭 Tech Stack & Architecture

| Component              | Technology                            |
|------------------------|----------------------------------------|
| UI                     | Streamlit                              |
| Embeddings             | HuggingFace sentence‑transformers      |
| Vector Database        | FAISS                                  |
| Document Loading       | LangChain Loaders                      |
| LLM Agent              | Together AI | `ChatTogether` wrapper    |
| File Uploads           | Streamlit file uploader + temp storage |
| PDF/Text Generation    | FPDF                                   |
| Configuration          | `.env`, Secrets on Streamlit Cloud     |

---

## 🛠️ Setup & Usage

1. **Clone & Install Dependencies**
   ```bash
   git clone https://github.com/aasthaaprabhakar/Tiet-Genie.git
   cd Tiet-Genie
   pip install -r requirements.txt
