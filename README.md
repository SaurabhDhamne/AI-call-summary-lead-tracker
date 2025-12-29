# AI Call Summary & Lead Tracker (Offline & Free)

## 📌 Overview
This project is an end-to-end AI system that analyzes customer call recordings and automatically generates structured insights such as call summaries, customer intent, and lead classification (Hot/Warm/Cold).

The system is designed to work with **real WhatsApp call recordings (AAC/M4A)** and is built using **completely free and open-source AI models**, without relying on paid APIs.

---

## 🚀 Key Features
- 🎧 Multilingual speech-to-text from call recordings  
- 📝 Automatic call summarization  
- 🎯 Customer intent classification  
- 🔥 Lead scoring (Hot / Warm / Cold)  
- 📊 Visual lead analytics (bar chart)  
- 📄 Automatic data storage in Google Sheets  
- 🖥️ Interactive Gradio dashboard for live demo  

---

## 🧠 Tech Stack
- Python  
- :contentReference[oaicite:0]{index=0} – Speech to Text  
- :contentReference[oaicite:1]{index=1} Transformers – NLP models  
- :contentReference[oaicite:2]{index=2} – Web dashboard  
- :contentReference[oaicite:3]{index=3} – Data storage  
- Pandas & Matplotlib – Data processing and visualization  
- :contentReference[oaicite:4]{index=4} – Development environment  

---

## 🏗️ System Architecture

+-------------------------------+
|  Call Recording               |
|  (AAC / M4A / MP3 - WhatsApp) |
+---------------+---------------+
                |
                v
+-------------------------------+
|  Speech-to-Text               |
|  Whisper (Multilingual ASR)   |
+---------------+---------------+
                |
                v
+-------------------------------+
|  NLP Processing               |
|  - Call Summary               |
|  - Intent Detection           |
+---------------+---------------+
                |
                v
+-------------------------------+
|  Lead Classification          |
|  Hot / Warm / Cold            |
+---------------+---------------+
                |
                v
+-------------------------------+
|  Google Sheets Storage        |
|  (Automatic Logging)          |
+---------------+---------------+
                |
                v
+-------------------------------+
|  Analytics & Visualization    |
|  Lead Distribution Bar Chart  |
+-------------------------------+


---

## 📂 Supported Call Types
- Sales inquiry calls  
- Customer support calls  
- Complaint calls  
- Follow-up and purchase confirmation calls  
- Multilingual calls (English, Hindi, Hinglish, regional languages)

---

## ▶️ How to Run the Project
1. Open the notebook in **Google Colab**
2. Install required libraries
3. Authenticate Google access for Sheets
4. Upload a call recording (AAC/M4A/MP3)
5. Run the notebook cells
6. Launch the Gradio dashboard
7. View call insights and lead analytics

---

## 📊 Output Generated
For each call, the system generates:
- Call transcript  
- Short call summary  
- Detected customer intent  
- Lead type (Hot / Warm / Cold)  
- Entry saved automatically in Google Sheets  
- Updated lead distribution plot  

---

## 🎓 Project Highlights
- Fully **offline and cost-free** AI solution  
- Works with **real-world WhatsApp audio data**  
- Designed with **business and CRM use cases** in mind  
- Easy to extend with sentiment analysis or CRM integration  

---

## 🔮 Future Enhancements
- Sentiment analysis (positive / neutral / negative)  
- Call quality scoring  
- CRM integration  
- Automated WhatsApp or email follow-ups  

---

## 👤 Author
Saurabh Narendra Dhamne
B.Tech – Artificial Intelligence and data Science

