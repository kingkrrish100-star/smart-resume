# Smart Resume - MVP

This is a minimal AI resume builder, ready to deploy.
App name: Smart Resume
Theme: Blue & White
Features: Resume generation, Cover letter generation

## Quick start (backend)
- Copy backend/.env.example to backend/.env and set OPENAI_API_KEY
- Install dependencies:
  pip install -r backend/requirements.txt
- Run:
  uvicorn backend.app.main:app --reload --port 8000

## Quick start (frontend)
- Install dependencies:
  cd frontend
  npm install
- Run:
  npm run dev

## Deployment
- Push this repository to GitHub.
- Deploy frontend with Vercel, backend with Render.
- Set VITE_API_URL to your backend URL in Vercel environment variables.
- Set OPENAI_API_KEY in Render environment.