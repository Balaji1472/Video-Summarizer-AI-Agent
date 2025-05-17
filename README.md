
# 🎬 Video Summarizer AI Agent

**Multimodal AI Agent** that leverages **Google Gemini Flash 2.0**, **Phidata**, and **Streamlit** to analyze and summarize video content interactively with natural language queries.

> 💡 Built to help users extract meaningful insights from video files using state-of-the-art AI.

---

## 🔧 Tech Stack

- 🧠 **Google Gemini Flash 2.0** – Multimodal LLM for video understanding
- ⚙️ **Phidata Framework** – Lightweight agent orchestration with tools like DuckDuckGo
- 🎈 **Streamlit** – Interactive UI for uploading videos and asking questions
- 🌐 **DuckDuckGo Tool** – For real-time web context augmentation
- 🔐 **dotenv** – API key management via `.env` file

---

## 🚀 Features

- 📤 Upload `.mp4`, `.mov`, or `.avi` video files
- 🧠 Ask natural language questions about the video
- 🌍 Combines video understanding with web search using DuckDuckGo
- ✨ Uses Gemini's multimodal capability via `phidata` to analyze and respond
- 💬 Interactive UI with Streamlit

---

## 📦 Installation

1. **Clone the repository**  
```bash
git clone https://github.com/Balaji1472/Video-Summarizer-AI-Agent
cd Video-Summarizer-AI-Agent
```

2. **Create and activate virtual environment**  
```bash
python -m venv venv
source venv/bin/activate  # For Linux/macOS
venv\Scripts\activate     # For Windows
```

3. **Install dependencies**  
```bash
pip install -r requirements.txt
```

4. **Set up environment variables**  
Create a `.env` file and add your Google API key:

```
GOOGLE_API_KEY=your_google_gemini_api_key
```

---

## ▶️ Usage

Run the Streamlit app:

```bash
streamlit run app.py
```

Then open [http://localhost:8501](http://localhost:8501) in your browser.

---

## 📂 File Structure

```
├── app.py                # Main Streamlit app
├── .env                  # Environment file (add your API key here)
├── requirements.txt      # Python dependencies
└── README.md             # You're here
```

---


## 🧠 Example Queries

- "Summarize the main topics discussed in this video."
- "What are the key moments or highlights?"
- "Did the speaker mention any companies or statistics?"
- "What’s the overall tone of the video?"

---

## 📜 License

This project is licensed under the MIT License.

---

## 🙋‍♂️ Acknowledgements

- [Phidata](https://docs.phidata.com/) – for powerful agent orchestration
- [Google Generative AI](https://ai.google.dev) – for Gemini multimodal models
- [Streamlit](https://streamlit.io) – for intuitive web app UI
