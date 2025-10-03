# Kaleam-like Prototype

## Server
cd server
npm install
cp .env.example .env
# edit .env and set JWT_SECRET
npm run dev

## Client
cd client
npm install
npm run dev

Open http://localhost:5173

Notes:
- The server uses a simple JSON file (db.json) for storage (prototype only). Replace with a real DB for production.
- For payments/subscriptions integrate Stripe server-side and create endpoints for checkout / webhooks.
- To enable saving projects from client, register/login first (token stored in localStorage).
