# University Academic Support Chatbot

## About
A simple AI-powered chatbot that answers university-related academic questions.

## Tech Stack
- Frontend: React, Tailwind CSS
- Backend: FastAPI (Python)
- AI: OpenAI GPT-4-turbo API

## How to Run

### Backend
1. Move to `backend/`
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Create a .env file with your OpenAI API key:
   ```bash
   OPENAI_API_KEY=your_openai_api_key_here
   ```
4. Run FastAPI server
```bash
    uvicorn main:app --reload
```

### Frontend
1. Move to `frontend/`
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the Frontend Server
   ```bash
   npm start
   ```

### Notes
- backend server must run on http://localhost:8000
- Make sure you have your OpenAI API key

### License
MIT License

### Python
pycache/
*.pyc
.env

### Node
node_modules/
build/
dist/