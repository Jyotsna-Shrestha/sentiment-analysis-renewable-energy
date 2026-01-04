# Renewable Energy Sentiment Analysis — Reddit Comments (VADER vs RoBERTa)

This project analyzes public sentiment toward **hydro, solar, and wind energy**
based on Reddit discussion data. It combines:

- Reddit data collection using PRAW API
- Two sentiment models:
  - **VADER** — rule-based baseline  
  - **RoBERTa** — transformer-based model
- Comparative data analysis & visualization
- Insights about how people discuss renewable energy online

## Project Objectives

- Collect real-world discussion data from Reddit
- Apply two different sentiment-analysis approaches
- Compare model behavior & results
- Visualize trends and interpret insights
- Explore emotional intensity and controversy levels across topics

## Installation

1. Clone the repository:
  ```bash
  git clone https://github.com/Jyotsna-Shrestha/sentiment-analysis-renewable-energy.git
  cd Sentiment-analysis-renewable-energy
  ```

2. Install Python dependencies:
  ```bash
  pip install -r requirements.txt
  python -m spacy download en_core_web_md
  ```

3. Set up Reddit API credentials using environment variables in .env file:
  ```bash
  REDDIT_CLIENT_ID=xxxx
  REDDIT_CLIENT_SECRET=xxxx
  REDDIT_USER=xxxx
  REDDIT_PASSWORD=xxxx
  ```