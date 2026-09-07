# Blog-Writing-Agent

An AI-powered blog writing agent that uses **LangChain, LangGraph, and Groq LLMs** to generate structured and high-quality blog posts from a given topic.

## Features

* Generates blog outlines automatically
* Creates content section by section
* Uses an LLM for content generation
* Orchestrates the workflow using LangGraph
* Produces structured blog content

## Tech Stack

* Python
* LangChain
* LangGraph
* Groq
* LLMs
* dotenv

## Project Structure

```text
Blog-Writing-Agent/
│
├── .env
├── requirements.txt
├── blog_agent.py
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/omkar9284580612/Blog-Writing-Agent.git
cd Blog-Writing-Agent
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate it:

**Windows:**

```bash
.venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Environment Variables

Create a `.env` file and add your Groq API key:

```env
GROQ_API_KEY=your_api_key_here
```

## Usage

Run the application:

```bash
python blog_agent.py
```

Provide a topic, and the agent will generate a structured blog post.

## Workflow

```text
Topic
  ↓
Planning
  ↓
Section Generation
  ↓
Content Processing
  ↓
Final Blog
```

## Future Improvements

* Add web research
* Add fact checking
* Add SEO optimization
* Add multiple writing styles
* Add a Streamlit interface

## Author

**Omkar Kale**
