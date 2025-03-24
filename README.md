# FinGuru Chatbot
FinGuru Chatbot is a simple finance coaching chatbot built with Flask that uses the Gemini API for generating financial advice in an engaging manner. The chatbot provides users with well-structured responses on budgeting, investing, and overall finance in the Indian context (with amounts in Rupees by default). It supports markdown formatting for rich text responses.

## Features
- **Interactive Chat Interface**: Users can ask finance-related questions and get detailed responses.
- **Gemini API Integration**: Leverages the Gemini API to generate personalized financial advice.
- **Markdown Support**: Responses include markdown formatting (bold text, lists, etc.) which can be rendered on the client side.
- **CORS Enabled**: Easily integrate with front-end applications developed on separate servers.
- **Deployment Ready**: Configured for deployment on Vercel.

## Tech Stack 
- **Python** : The core application logic is built using Python.
- **Flask** : Flask is used to create the web server, handle routing, render templates, and process API requests.
- **API Integration**: Gemini API
- **Cross-Origin Resource Sharing**: Flask-CORS
- **Frontend**: HTML, CSS, JavaScript
- **WSGI Server (Production)**: Gunicorn is used as a production-grade WSGI server to efficiently run the Flask app.
- **Vercel**: the project is deployed as a serverless function on Vercel using a custom configuration.

[Deployed Link](https://finguru.vercel.app/)
---
## preview :
![image](https://github.com/user-attachments/assets/178fac15-64a7-454e-aedf-7a1154d3bab3)
