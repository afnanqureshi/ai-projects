# AI Resume Critiquer

This is a Streamlit app that allows you to upload your resume (PDF or TXT) and receive AI-powered feedback tailored to your target job role.

## Features
- Upload your resume in PDF or TXT format
- Specify a target job role for personalized feedback
- Get structured, actionable feedback powered by OpenAI's GPT models

## Setup Instructions

1. **Clone the repository and navigate to the project directory:**
   ```sh
   git clone <repo-url>
   cd "ai-projects/Resume Critiquer"
   ```

2. **Create a virtual environment and activate it:**
   (You can use `uv`, `venv`, or your preferred tool)
   ```sh
   uv venv .venv
   source .venv/bin/activate
   ```

3. **Install dependencies:**
   ```sh
   uv pip install -r requirements.txt
   # or, if using pyproject.toml
   uv pip install .
   ```

4. **Create a `.env` file in the `Resume Critiquer` directory:**
   Add your OpenAI API key to the file:
   ```env
   OPENAI_API_KEY=sk-...
   ```

5. **Run the Streamlit app:**
   ```sh
   uv run streamlit run main.py
   ```

## Notes
- Make sure your `.env` file is **not** tracked by git (it's in the .gitignore by default).
- You need a valid OpenAI API key to use this app.

