# LLM Benchmarking and Evaluation Using News Data

## Project Overview

This project is designed to benchmark and evaluate Large Language Models (LLMs) within the framework of Retrieval-Augmented Generation (RAG) approaches. The project utilizes news articles sourced from the [NewsCatcher API](https://newscatcherapi.com/) to generate questions and assess how effectively RAG models can handle these questions. The aim is to analyze the performance of different RAG methods in providing relevant answers based on real-world news data.

## Objectives

- **Scrape News Articles:** Collect a diverse set of news articles using the NewsCatcher API.
- **Generate Questions:** Create questions based on the content of the scraped news articles.
- **Evaluate RAG Models:** Test the performance of various RAG models in answering the generated questions.
- **Analyze Results:** Interpret the evaluation results to provide insights and recommendations.

## Getting Started

To get started with the project, follow these steps:

### Prerequisites

- Python 3.x
- An API key from NewsCatcher API
- Required Python packages (listed in `requirements.txt`)

### Setup

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/llm-benchmarking-news-scraper.git
   cd llm-benchmarking-news-scraper
   ```
2. **Create a virtual environment**
   
  ```bash
  python -m venv venv
  source venv/bin/activate   # On Windows use `.venv\Scripts\activate`
  pip install -r requirements.txt
  ```
3. **Install the required packages**
  
  ```bash
  pip install -r requirements.txt
  ```
 
4. **Set up your NewsCatcher API key**
   Obtain an API key from [NewsCatcher API](https://newscatcherapi.com/) and store it in a `.env` file or configure it as an environment variable.

  ### Example of `.env` file:
  
  ```bash
  NEWS_CATCHER_API_KEY=your_api_key_here
  ```
5. **Run**

  ```bash  
  python scrape_news.py
  ```
