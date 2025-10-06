# Text-Summarizer
# AI-Powered Text Summarizer

A simple Python application that summarizes text articles into 3 key sentences using natural language processing techniques.

## Features

- **Text Summarization**: Summarizes any input text into 3 key sentences
- **URL Support**: Can extract and summarize content from news articles and blog posts
- **Interactive Interface**: Easy-to-use command-line interface
- **Educational Purpose**: Demonstrates basic NLP concepts

## How It Works

The summarizer uses an extractive approach:

1. **Text Preprocessing**: Tokenizes text into sentences and cleans the data
2. **Word Frequency Analysis**: Identifies important words based on frequency (excluding stop words)
3. **Sentence Scoring**: Scores sentences based on the important words they contain
4. **Summary Generation**: Selects the top 3 most important sentences while maintaining readability

## Installation

1. Clone this repository:
```bash
git clone <your-repo-url>
cd text-summarizer
