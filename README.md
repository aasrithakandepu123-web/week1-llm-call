# Week 1 - First LLM API Call

This project connects a Python program to Google's Gemini LLM using the official `google-genai` SDK and securely manages API keys via environment variables.

## Project Structure
```text
week1-llm-call/
├── .env                  # API credentials (git-ignored)
├── .gitignore            # Git ignore file for secrets and environments
├── main.py               # Main application code to call the Gemini API
├── requirements.txt      # Project dependencies
└── README.md             # Project documentation
```

## Setup & Execution

1. **Activate the Virtual Environment:**
   ```powershell
   .\.venv\Scripts\Activate.ps1
   ```

2. **Install Dependencies:**
   ```powershell
   pip install -r requirements.txt
   ```

3. **Configure Environment Variables:**
   Create a `.env` file in the root directory:
   ```env
   GEMINI_API_KEY=your_gemini_api_key_here
   ```

4. **Run the Program:**
   ```powershell
   python main.py
   ```
