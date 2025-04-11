# 🧾 Legal Document Simplifier with LLMs

An AI-powered web app that demystifies legal documents by generating structured summaries, glossaries, verdict predictions, and custom Q&A — all driven by **open-source Large Language Models (LLMs)**. Built with **Gradio** and deployed on **Hugging Face Spaces**.

---

## 🚀 Features

✅ **Multi-Format Upload** – Accepts `.pdf`, `.docx`, and `.txt` documents  
✅ **Smart Summarization** – Extracts key facts, legal issues, parties, and arguments  
✅ **Glossary of Legal Jargon** – Explains complex terms in simple, understandable language  
✅ **AI-Predicted Verdict** – Infers likely case outcomes using contextual reasoning  
✅ **Ask Your Own Questions** – Interact with the document using a natural-language Q&A  
✅ **Exportable Report** – Download all results as a clean `.txt` summary file  
✅ **Smooth UI** – Built with Gradio for a responsive and user-friendly experience  

---

## 🧠 How It Works

This app uses open-source models from Hugging Face:

- 📝 `google/pegasus-xsum` – for high-quality abstractive summarization  
- 📘 `MBZUAI/LaMini-T5-738M` – for glossary building, verdict generation, and Q&A  

It processes legal documents using:
- `pdfplumber` for PDF parsing  
- `python-docx` for DOCX handling  
- Plain text reading for `.txt` files  

Then, intelligently prompts the LLMs for insights and generates structured outputs.

---

## 🛠️ Tech Stack

| Layer             | Tool / Framework                        |
|-------------------|------------------------------------------|
| Interface         | Gradio                                   |
| Language Models   | Pegasus XSum, LaMini-T5-738M             |
| Text Processing   | pdfplumber, python-docx                  |
| Backend           | Python                                   |
| Hosting           | Hugging Face Spaces                      |

---

## 📁 Project Structure


---

## 📦 Getting Started

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/legal-doc-simplifier
cd legal-doc-simplifier
pip install -r requirements.txt
python app.py

Open your browser and go to:
📍 http://localhost:7860

🌐 Live Demo
Try the live version on Hugging Face Spaces:https://huggingface.co/spaces/rajaneeshp609/LEGAL-DOCS-LLMS
🔗 Launch App

📋 Example Output
🧾 Summary
"This case involves a contractual dispute between a vendor and a software provider over breach of delivery terms and data security concerns."

📚 Glossary
Prima facie – Based on first impression

Amicus curiae – A non-party offering legal insight

Jurisprudence – Legal theory or philosophy

⚖️ Verdict (AI Inference)
“The case may be dismissed due to insufficient jurisdiction.”

💬 Q&A Example
Q: "What was the main issue raised in this case?"
A: "The plaintiff claimed a violation of the contract terms regarding timely delivery and data confidentiality."

🎓 Internship & Acknowledgements
Developed as part of an academic internship at Neubalitics Tech Pvt. Ltd., in collaboration with Sathyabama Institute of Science & Technology, Chennai.

👨‍🏫 Mentored by: Nethaji N.

👨‍💼 Coordinated by: Danush Rajaram

Special thanks to:

🤗 Hugging Face community

🧠 Open-source contributors

💼 Neubalitics AI R&D Team

📜 License
This project is licensed under the MIT License.
Feel free to use, modify, and build upon this project for any purpose.
