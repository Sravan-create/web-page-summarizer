# Webpage Text Summarizer

## Overview

This project is a **webpage text summarizer** built using Python. It extracts the main content from a webpage, processes it, and summarizes it into a concise format using a pre-trained model (`facebook/bart-large-cnn`) from the Hugging Face Transformers library.

The summarizer handles long articles by splitting the text into chunks and processes each chunk individually while ensuring coherence and conciseness.

---

## Features

- Extracts main content from a webpage using BeautifulSoup.
- Cleans and preprocesses the text for summarization.
- Splits long articles into manageable chunks based on token limits.
- Summarizes the content using the **BART model**.
- Ensures the final summary is concise (around 300 words) and ends at complete sentences.

---

## Requirements

### Libraries
Install the required dependencies using the command below:
```bash
requirements.txt
text
Copy code
requests
beautifulsoup4
transformers
torch
