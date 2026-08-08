# Legaliz AI Frontend

React/Vite frontend connected to the Legaliz AI FastAPI backend.

## Run

1. Start the FastAPI backend on `http://127.0.0.1:8000`.
2. Copy `.env.example` to `.env` if needed.
3. Run `npm install`.
4. Run `npm run dev`.

The frontend calls `/upload`, `/analyze`, `/chat`, `/contracts`, `/contracts/{contract_id}`, and `/report/{contract_id}`.
