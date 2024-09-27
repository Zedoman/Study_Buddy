# ChatGPT Flask Application

This repository contains a simple Flask web application that interacts with OpenAI's GPT-3.5 API. It provides a chatbot interface that allows users to input a message and receive a conversational response from the GPT-3.5 language model.

## Features
- Flask-based web server for handling HTTP requests.
- Renders a basic HTML template (`chat.html`) that serves as the user interface.
- Accepts user input via a POST request and sends it to OpenAI's GPT-3.5 API.
- Returns the chatbot response in real-time via a JSON object.

## Prerequisites

To run this project, ensure that you have the following installed:
- Python 3.x
- Flask
- OpenAI Python client library

## Setup and Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-repo/chatgpt-flask-app.git
   cd chatgpt-flask-app
