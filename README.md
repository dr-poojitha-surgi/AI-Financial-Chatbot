# AI Financial Chatbot for Consulting

## Project Overview
This repository demonstrates an end-to-end AI-powered financial analysis solution developed as part of the BCG GenAI Virtual Internship through Forage. The project extracts, analyzes, and summarizes key insights from company 10-K reports, providing actionable recommendations through an interactive chatbot interface.

## Features

- Automated download and parsing of 10-K financial reports.
- Extraction and calculation of fundamental financial metrics (revenue, profit, ratios, risk factors).
- Modular pipelines for data cleaning, transformation, and analysis.
- An LLM-based chatbot that interprets financials and simulates consulting-like insights.
- Sample consulting reports and chatbot conversations.

## Getting Started

### Prerequisites

- Python 3.8+
- Key libraries: pandas, numpy, requests, openai (or relevant LLM package), pytest, Jupyter

### Setup Instructions

1. Clone this repository:
    ```
    git clone https://github.com/your-username/AI-Financial-Chatbot-Consulting.git
    cd AI-Financial-Chatbot-Consulting
    ```
2. Install dependencies:
    ```
    pip install -r requirements.txt
    ```

3. Run data scripts to obtain sample filings:
    ```
    python data/fetch_10k_sec.py
    ```

4. Explore sample analyses:
    - Open `notebooks/eda_financials.ipynb` to see data cleaning and metrics extraction.
    - Try the chatbot demo in `src/chatbot.py` or `notebooks/chatbot_demo.ipynb`.

## Repository Structure

- `/data`: Data ingestion scripts
- `/src`: Core modules (parsing, analysis, chatbot)
- `/notebooks`: Exploratory and demo notebooks
- `/examples`: Output samples and consulting reports
- `/docs`: Diagrams and user/developer guides
- `/tests`: Unit tests

## Example Output

![Architecture Diagram](./docs/architecture.png)
_Sample chatbot conversation and generated consulting report available in `/examples`._

## Consulting Value

By automating the extraction and analysis of 10-K data, this solution enables faster, more accurate financial due diligence and generates insights that support strategic consulting engagements.

## License

MIT License

## Acknowledgments

- BCG GenAI Virtual Internship
- Public SEC EDGAR Database
