# Latent Semantic Analysis (LSA) Search Engine
[![Python Application CI](https://github.com/laimao19/laimao19-assignment-4/actions/workflows/python-app.yml/badge.svg)](https://github.com/laimao19/laimao19-assignment-4/actions/workflows/python-app.yml)
This project implements a basic search engine using Latent Semantic Analysis (LSA). The search engine allows users to enter a query and retrieves the top 5 documents from the 20 Newsgroups dataset based on cosine similarity. The results include a bar chart visualization of the similarity scores for the top documents.

## Table of Contents
- [Demo](#demo)
- [Features](#features)
- [Technologies](#technologies)
- [Getting Started](#installation)
- [Running the Project Locally](#usage)

## Demo
A live demo of the project can be found at: laimao19.github.io
Alternatively, you can clone the repository and run the application locally by following the Installation and Usage instructions.

## Features
 - Document Retrieval: Users can enter a query, and the system retrieves the top 5 documents from the dataset based on cosine similarity.
 - Visualization: Displays a bar chart showing the cosine similarity scores for the top documents.
 - Responsive User Interface: Dark theme with a clean, modern look, including a scrollable document view.

## Technologies
- Python: Backend language for processing LSA and handling the web server.
- Flask: Web framework for serving the application.
- scikit-learn: Machine learning library for implementing TF-IDF and Singular Value Decomposition (SVD).
- Chart.js: JavaScript library for visualizing cosine similarity scores in a bar chart.
- HTML, CSS, JavaScript: Frontend technologies for creating a responsive, user-friendly interface.


## Installation
Follow these steps to set up the project locally:
1. **Clone the repository**:
   ```bash
   git clone https://github.com/laimao19/laimao19-assignment-4.git
   cd laimao19-assignment-4
2. **Install dependencies**:
   ```bash
   make install
3. **Run the application**:
   ```bash
   make run

## Usage
Once the server is running, open your web browser and navigate to:
http://localhost:3000
From here, you can interact with the Latent Semantic Analysis (LSA) Search Engine.
How to use:
1. Enter a search query into the input field on the main page.
2. Click the Search button to retrieve the most relevant documents.
3. View the top 5 documents, which are displayed along with their cosine similarity scores.
4. Below the results, a bar chart shows the similarity scores for a quick visual comparison.
