# Multi-Agent-Research-System
streamlit langchain langchain-core langchain-mistralai python-dotenv tavily-python beautifulsoup4 requests rich lxml
# 🔬 ResearchMind - Multi-Agent AI Research System

## Overview

ResearchMind is a Multi-Agent AI Research Assistant that automates the complete research workflow using LangChain, Mistral AI, Tavily Search, and Streamlit.

The system employs multiple specialized AI agents that collaborate to gather information, extract content, generate reports, and evaluate research quality.

---

## Features

* 🔍 Web Search Agent for finding reliable information
* 📄 Reader Agent for scraping and extracting webpage content
* ✍️ AI Writer Agent for generating structured research reports
* 🧐 Critic Agent for evaluating report quality
* 🎨 Modern Streamlit User Interface
* 📥 Download research reports in Markdown format
* ⚡ Automated end-to-end research pipeline

---

## Tech Stack

* Python
* LangChain
* Mistral AI
* Tavily Search API
* BeautifulSoup
* Requests
* Streamlit

---

## Project Workflow

1. User enters a research topic.
2. Search Agent gathers recent information from the web.
3. Reader Agent extracts detailed content from relevant sources.
4. Writer Agent creates a structured research report.
5. Critic Agent reviews the report and provides feedback.
6. User downloads the final report.

---

## Installation

```bash
git clone <repository-url>

cd ResearchMind

pip install -r requirements.txt
```

Create a `.env` file:

```env
MISTRAL_API_KEY=your_api_key
TAVILY_API_KEY=your_api_key
```

Run the application:

```bash
streamlit run app.py
```

---

## Future Improvements

* PDF Export Support
* Research Report History
* Multi-Source Summarization
* Citation Management
* Advanced Fact Verification
* Multi-Model AI Support

---

## Author

Mohammed Azhar Shaikhsiddiki

AI/ML Engineer
