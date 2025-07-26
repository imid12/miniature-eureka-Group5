# ITAI2373-NewsBot-Midterm - miniature-eureka-Group5
#### HCC NLP Summer Course Group 5
---

# NewsBot System

## Overview

NewsBot System is an intelligent news aggregator and chatbot designed to deliver personalized, real-time news updates and insights to users. Leveraging the latest in natural language processing and data aggregation, NewsBot curates news from multiple sources, summarizes key points, and interacts with users through a conversational interface.

This project was developed as part of the Group 5 midterm assignment for the ITAI-2373 at Houston Community College.

---

## Features

- **Automated News Aggregation:** Collects news articles from multiple reputable sources in real time.
- **Intelligent Summarization:** Uses NLP to summarize lengthy articles into concise news bites.
- **Personalized Feed:** Delivers news based on user preferences, topics, and regions.
- **Conversational Interface:** Users can interact with NewsBot via chat to request news, ask questions, or get summaries.
- **Sentiment Analysis:** Analyzes the tone and sentiment of news articles.
- **Daily/Weekly Digests:** Sends periodic digests to subscribed users.

---

## Technologies Used

- **Backend:** Python (Flask/FastAPI)
- **Frontend:** React.js / HTML5 / CSS3
- **Database:** MongoDB / PostgreSQL
- **NLP:** spaCy / NLTK / OpenAI GPT APIs
- **APIs:** NewsAPI, Google News, Custom Scrapers
- **Deployment:** Docker, Heroku/AWS/GCP

---

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/imid12/miniature-eureka-Group5.git
   cd miniature-eureka-Group5
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   # and/or
   npm install
   ```

3. **Set up environment variables:**
   - Create a `.env` file and add relevant API keys and configuration.

4. **Run the application:**
   ```bash
   # For backend
   python app.py

   # For frontend
   npm start
   ```

---

## Usage

- **Chat with NewsBot:** Access the chatbot interface via the web app.
- **Get Personalized News:** Set your preferences and let NewsBot curate your feed.
- **Request Summaries:** Ask NewsBot to summarize specific articles or topics.
- **Subscribe to Digests:** Receive daily or weekly news digests via email.

---

## Team Members

- [Name 1] — Backend Developer
- [Name 2] — Frontend Developer
- [Name 3] — NLP Specialist
- [Name 4] — Project Manager/Tester


---

## Project Structure

```
miniature-eureka-Group5/
│
├── backend/
│   ├── app.py
│   ├── news_aggregator.py
│   └── ...
├── frontend/
│   ├── src/
│   └── ...
├── requirements.txt
├── package.json
└── README.md
```

---

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for more information.

---

## Acknowledgements

- [NewsAPI](https://newsapi.org/)
- [spaCy](https://spacy.io/)
- [OpenAI GPT](https://openai.com/)
- [Kaggle](https://kaggle.com/)
- ITAI-2373

---
