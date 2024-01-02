# Sentiment Analysis and Text Summarization Tool

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview

This repository contains a Flask-based Sentiment Analysis and Text Summarization tool using TextBlob. The application enables users to analyze sentiment, extract key points from text, and provides a user-friendly interface with Bootstrap design.

## Features

- **Sentiment Analysis:** Utilizes TextBlob to assess the sentiment of input text, displaying polarity and subjectivity scores.

- **Text Summarization:** Extracts significant points from the text through noun lemmatization, presented in an easy-to-read list.

- **User-friendly Interface:** Designed with Bootstrap for an intuitive and visually appealing experience.

## How to Use

### Prerequisites

Ensure you have the required dependencies installed:

```bash
pip install Flask flask_bootstrap textblob
```

### Running the Application

Clone this repository:

```bash
git clone https://github.com/your-username/sentiment-analysis-tool.git
```

### Navigate to the project directory:

```bash
cd sentiment-analysis-tool
```

### Run the application:

```bash
python app.py
```

### Access the application at http://localhost:5000 in your web browser.

## Usage
- Enter text in the provided textarea.
- Click the "Submit" button to analyze sentiment and generate a text summary.
- Explore the main points, sentiment scores, and elapsed time.

## Additional Information
Spinner animation indicates ongoing analysis.
Clear and Reset buttons enhance user interaction.
Processing time is displayed for user feedback.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
