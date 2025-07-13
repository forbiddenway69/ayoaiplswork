# ForbiddenWay Chatbot on Vercel

This folder contains a complete deployable version of ForbiddenWay (AI Chatbot + Music + Backend Proxy) hosted on **Vercel**.

## ✅ What’s Included

- `index.html` - Your full chatbot UI
- `/api/chat.js` - Secure backend proxy for OpenRouter API (no CORS issues)
- `vercel.json` - Deployment config

## 🌐 Steps to Deploy on Vercel

1. Go to [https://vercel.com](https://vercel.com)
2. Import this folder as a new GitHub repo (name it e.g. `forb1den`)
3. In your Vercel dashboard, add this environment variable:

```
OPENROUTER_API_KEY = your-openrouter-key-here
```

4. Deploy! Your site will be live at:

```
https://your-project-name.vercel.app
```

Frontend will call `/api/chat` to talk to OpenRouter securely.

