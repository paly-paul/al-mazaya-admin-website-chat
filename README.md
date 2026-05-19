# Mazaya FM Website

Standalone public Next.js website with the customer chat widget.

## Run Locally

```powershell
Copy-Item .env.example .env.local
npm install
npm run dev
```

Open:

```text
http://localhost:3000
```

## Backend URL

Update line 1 in `.env.local`:

```env
NEXT_PUBLIC_API_URL=http://localhost:8000
```

Use your deployed backend URL in production.
