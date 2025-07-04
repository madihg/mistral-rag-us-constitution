# US Constitution RAG Chatbot
A Retrieval-Augmented Generation (RAG) chatbot built with Flask and Mistral AI that helps users ask questions about the United States Constitution.

**Created by [Halim Madi](https://www.halimmadi.com)**

This is a sample project designed for students, workshops, and educational purposes. Feel free to use, modify, and distribute this code as you wish for learning and development.

## About the Creator
- **Website**: [www.halimmadi.com](https://www.halimmadi.com)
- **Instagram**: [@yalla_halim](https://www.instagram.com/yalla_halim/)

## Overview
This RAG chatbot uses the US Constitution as its knowledge base, allowing users to ask questions about constitutional amendments, articles, rights, and historical context. The system retrieves relevant sections from the Constitution and generates comprehensive answers using Mistral AI.

## Features
- Interactive chat interface for constitutional queries
- Retrieval-based responses from the full US Constitution text
- Context-aware answers powered by Mistral AI
- Easy-to-use web interface

## Setup
1. Clone the repository
2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Create a `.env` file with your Mistral API key:
   ```
   MISTRAL_API_KEY=your_api_key_here
   ```
5. Add the US Constitution text as `constitution.txt` in the project root

## Local Development
Run the Flask application:
```bash
python app.py
```
The application will be available at `http://localhost:5001`

## Deployment to Vercel
1. Push your code to GitHub
2. Connect your GitHub repository to Vercel
3. Add your environment variables in the Vercel dashboard:
   - `MISTRAL_API_KEY`: Your Mistral API key
4. Deploy!

## Environment Variables
- `MISTRAL_API_KEY`: Your Mistral AI API key (required)

## Project Structure
- `app.py`: Main Flask application
- `templates/`: HTML templates
- `static/`: Static files (CSS, JS)
- `constitution.txt`: Full text of the US Constitution
- `requirements.txt`: Python dependencies
- `vercel.json`: Vercel deployment configuration

## Example Questions
- "What does the First Amendment protect?"
- "How is the President elected according to the Constitution?"
- "What are the requirements to become a Senator?"
- "What powers does Congress have?"
- "How can the Constitution be amended?"

## Usage and Licensing
This project is provided as a learning resource for students and workshop participants. You are free to:
- Use this code for educational purposes
- Modify and adapt it for your own projects
- Share it with others for learning
- Use it in workshops and tutorials

Feel free to reach out to [Halim Madi](https://www.halimmadi.com) with any questions or feedback!
