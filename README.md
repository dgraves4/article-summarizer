# Final Project: Article Summarizer

This repository hosts the code and resources for the Article Summarizer, a final project for the course "Web Mining and Applied NLP." The project involves building an application that automatically summarizes articles using web scraping and natural language processing (NLP) techniques by following along with guided questions and prompts.

## Questions answered:

* (Question 1) Article html stored in separate file that is committed and pushed: 1 pt
* (Question 2) Polarity score printed with an appropriate label: 1 pt
* (Question 2) Number of sentences printed: 1 pt
* (Question 3) Correct (or equivalent in the case of multiple tokens with same frequency) tokens printed: 1 pt
* (Question 4) Correct (or equivalent in the case of multiple lemmas with same frequency) lemmas printed: 1 pt
* (Question 5) Histogram shown with appropriate labelling: 1 pt
* (Question 6) Histogram shown with appropriate labelling: 1 pt
* (Question 7) Cutoff score seems appropriate given histograms: 2 pts (1/score)
* (Question 8) Summary contains a shortened version of the article (less than half the number of sentences): 1 pt
* (Question 8) Summary sentences are in the same order as they appeared in the original article: 1 pt
* (Question 9) Polarity score printed with an appropriate label: 1 pt
* (Question 9) Number of sentences printed: 1 pt
* (Question 10) Summary contains a shortened version of the article (less than half the number of sentences): 1 pt
* (Question 10) Summary sentences are in the same order as they appeared in the original article: 1 pt
* (Question 11) Polarity score printed with an appropriate label: 1 pt
* (Question 11) Number of sentences printed: 1 pt
* (Question 12) Thoughtful answer based on reported polarity scores: 1 pt
* (Question 13) Thoughtful answer based on summaries: 1 pt

### Objectives

The primary objectives of this project are to:

- Develop skills in web scraping to fetch articles from the internet.
- Utilize NLP techniques to process and summarize text content.
- Document and share the developed code and results in a comprehensive manner.

### Getting Started

#### Prerequisites

Ensure you have Python installed on your system. You can download Python from [here](https://www.python.org/downloads/).

#### Fork and Clone Repository

- Fork this repository by clicking the "Fork" button on the top right of this page.
- Clone your forked repository to your local machine:

```bash
git clone https://github.com/your_username/article-summarizer.git
cd article-summarizer
```

#### Set up and activate virtual environment

```bash
py -m venv .venv
source .venv/scripts/activat
```

#### Install requirements

- requests for fetching web pages.
- beautifulsoup4 (bs4) for parsing HTML content.
- spacy for advanced NLP processing.
- sumy for summarization algorithms.
- matplotlib for plotting and visualization.

```bash
pip install -r requirements.txt
```

### Sources

Original forked assignment found at: [denisecase/620-mod6-web-scraping](https://github.com/denisecase/620-mod6-web-scraping)
