## 👤 Author

## Subham Chaudhary

## Computer Science @ Caldwell University
ML | Data Engineering | Full-Stack Development
## 🔍 Key Insights
- Translation may improve performance when:
  - data is highly informal  
  - multilingual models struggle with nuance  
- Direct models may perform better when:
  - translation introduces noise  
- Performance varies across **domains (Twitter vs YouTube)**

---

## 🧪 Tech Stack
- Python  
- PyTorch  
- Hugging Face Transformers  
- Pandas / NumPy  
- Scikit-learn  
- tqdm  

---

## 📂 Project Structure

├── data/
├── translation/
├── models/
├── results/
├── notebooks/
├── README.md
└── requirements.txt


---

## ⚡ How to Run

```bash
pip install -r requirements.txt
python translation/translate_nllb.py
python models/direct_finetune.py
python models/translate_classify.py
📌 Key Research Question

Can translation into English improve classification performance for Nepali social media text compared to direct multilingual modeling?

🧠 Future Improvements
Fine-tune larger models (XLM-R Large, mT5)
Use domain-adaptive pretraining
Improve translation quality for code-mixed text
Deploy as an API (real-time inference)

