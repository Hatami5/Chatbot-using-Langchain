📰 News Research Tool 📈

An AI-powered News Research Tool built with Streamlit, LangChain, and OpenAI that lets users input news article URLs and ask natural language questions. The system fetches, processes, and analyzes the content, then provides concise answers with referenced sources.

✨ Features

🔗 Accept up to 3 news article URLs from the sidebar

⚡ Automatically fetch, clean, and split news content

🧠 Embeds content using OpenAI + FAISS for semantic search

❓ Ask natural questions about the content

✅ Get AI-generated answers with proper source citations

💾 Save and reuse embeddings locally (faiss_store_openai.pkl)

🛠️ Tech Stack

Python 3.9+

Streamlit
 – Interactive web app

LangChain
 – LLM framework

OpenAI API
 – GPT + embeddings

FAISS
 – Vector similarity search

Pickle – Persistence of FAISS index

dotenv – Secure API key management

⚙️ Installation

Clone the repository:

git clone https://github.com/your-username/news-research-tool.git
cd news-research-tool


Install dependencies:

pip install -r requirements.txt


Add your OpenAI API key in a .env file:

OPENAI_API_KEY=your_openai_api_key_here


Run the app:

streamlit run app.py

🚀 Usage

Open the app (http://localhost:8501).

Enter up to 3 news article URLs in the sidebar.

Click Process URLs to load and embed content.

Type your question in the input box.

Get an AI-powered answer + sources.

📊 Example

Question:

What is the main takeaway from these articles?

Answer:

The articles highlight the global impact of rising energy prices and inflation trends.

Sources:

https://example-news1.com/...

https://example-news2.com/...

🔮 Future Improvements

Expand to handle more than 3 URLs

Add multi-lingual support

Enable real-time scraping for live news

Deploy on Streamlit Cloud / HuggingFace Spaces

👨‍💻 Author

Developed by Your Name

AI Developer | Data Scientist | Web Scraper | NLP Engineer

⚡ If you like this project, don’t forget to ⭐ star the repo and contribute!
