# nextjs-ai-chatbot-jokes

A customised fork of Vercel's open-source `ai-chatbot` template. Appears to have been modified with a jokes theme/personality on top of the standard chat SDK scaffold.

**Status:** Paused — exploration/learning project  
**Local path:** `~/Developer/paused/nextjs-ai-chatbot-jokes`  
**GitHub:** https://github.com/culturaleliteTKH/nextjs-ai-chatbot-jokes (public)

## What it is
Vercel's Chat SDK starter with Auth.js, Neon Postgres, Vercel Blob storage, and multi-model AI support (xAI/Grok default, switchable to OpenAI/Anthropic etc). Full chat history persistence, user auth, artifacts (code, text, sheets, images).

## Why it's here
Likely used to explore the Vercel AI SDK and understand how to build chat interfaces. The underlying template is high quality and worth referencing when building anything LLM-powered.

## Run locally
Requires env vars: `AI_GATEWAY_API_KEY`, Neon Postgres connection string, Vercel Blob token, Auth.js secret. See the [Chat SDK docs](https://chat-sdk.dev).

```bash
pnpm install
pnpm dev
```

## Worth knowing
The Vercel AI SDK patterns in this codebase (streaming, tool calls, artifacts) are reusable reference material for other AI projects.
