# LinkedIn AI Post Generator

A Generative AI application that helps users generate LinkedIn post drafts based on selected topics, post length, and language.

## Features

- Generate LinkedIn post drafts using an AI language model.
- Select topics, post length, and language.
- Interactive web interface built with Streamlit.
- Uses LangChain to connect the application with an AI language model.
- Uses the Groq API for AI-powered text generation.

## Technologies Used

- Python
- Streamlit
- LangChain
- Groq API
- GPT-OSS 120B

## Project Structure

```text
project-genai-post-generator/
│
├── data/
├── resources/
├── main.py
├── post_generator.py
├── llm_helper.py
├── few_shot.py
├── preprocess.py
├── requirements.txt
├── README.md
└── .gitignore
```

## Installation and Setup

### 1. Clone the Repository

```bash
git clone YOUR_REPOSITORY_URL
cd YOUR_REPOSITORY_FOLDER
```

### 2. Create a Virtual Environment

```bash
python -m venv red
```

### 3. Activate the Environment (Windows)

```powershell
red\Scripts\activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Configure the Groq API Key

Create a `.env` file in the project directory and add:

```env
GROQ_API_KEY=your_groq_api_key
```

Replace the placeholder with your actual Groq API key.

**Important:** Never upload your `.env` file or expose your API key publicly.

### 6. Run the Application

```bash
streamlit run main.py
```

## My Contributions

This is an adapted learning project based on the original Codebasics project.

My contributions include:

- Setting up the Python virtual environment and project dependencies.
- Configuring the application to use GPT-OSS 120B through the Groq API.
- Updating the language model configuration after the original model was decommissioned.
- Successfully running and testing the application locally.

## Acknowledgements

Original project and tutorial: Codebasics.

The original project authors retain credit for their work. Refer to the original repository for licensing and attribution requirements.