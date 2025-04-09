# Web Search Application

This application allows you to search the web using AI models (Claude, Gemini, or OpenAI) to extract and analyze text content from web pages.

## Prerequisites

- Python 3.8 or higher installed on your system
- An API key for at least one of the following AI providers:
  - Claude (Anthropic)
  - Gemini (Google)
  - OpenAI

## Getting Started

### Step 1: Install Python

If you don't have Python installed, download and install it from [python.org](https://www.python.org/downloads/).

### Step 2: Run the Application

1. Simply double-click the `.bat` file in the project directory
2. This will install all required dependencies and start the server

### Step 3: Access the Web Interface

1. Open your browser and go to [http://localhost:7860](http://localhost:7860)
2. You will see the Langflow interface with a workflow already set up

### Step 4: Using the Application

1. In the workflow, locate the "Local Search API Caller" component
2. Enter your API key in the appropriate field
3. Select one of the supported models:
   - `claude` for Anthropic's Claude models
   - `gemini` for Google's Gemini models
   - `openai` for OpenAI's GPT models
4. Enter your search query
5. Set the number of results you want to retrieve
6. Run the workflow

## Troubleshooting

- If the batch file doesn't start, try running it as administrator
- Make sure no other application is using port 7860
- Check that your API key is correct and has the necessary permissions

## Note

This application uses the browser-use library to automate web browsing and extraction. The server runs locally on your machine and does not share your API keys with any external service.
