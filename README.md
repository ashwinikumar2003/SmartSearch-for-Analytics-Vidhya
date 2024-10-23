# Smart Search for Free Courses on Analytics Vidhya

This project provides a smart search feature for finding free courses on the Analytics Vidhya platform using vector embeddings and a language model (Sentence-BERT).

## Project Structure

- `app.py`: Main application file for running the search tool using Streamlit.
- `scraper.py`: Script to scrape free courses from Analytics Vidhya.
- `embedding_model.py`: Module to generate embeddings using Sentence-BERT.
- `search.py`: Functionality for performing searches using embeddings.
- `requirements.txt`: List of dependencies for the project.

## How to Run

1. Clone the repository.
2. Install dependencies:

```bash
pip install -r requirements.txt
```

run the Streamlit app

```bash
streamlit run app.py
```