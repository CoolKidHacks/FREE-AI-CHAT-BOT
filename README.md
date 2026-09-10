# Omni — Free AI Chat Bot

A free, multi-model AI chat studio. Talk to **real** Claude Fable, GPT, Grok, Gemini, Kimi, and DeepSeek models — not simulated labels — with **no API key**.

Powered by [Puter.js](https://developer.puter.com) (sign in with a free Puter account).

## Go live on GitHub Pages (one-time)

GitHub needs you to flip Pages on once:

1. Open **[Settings → Pages](https://github.com/CoolKidHacks/FREE-AI-CHAT-BOT/settings/pages)**
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**
3. Branch: **main** · Folder: **/ (root)** · **Save**

After a minute the app is at:

**https://coolkidhacks.github.io/FREE-AI-CHAT-BOT/**

## How to use

1. Open the site.
2. Click **Sign in free** (Puter popup — allow popups if asked).
3. Pick a **real model** and effort.
4. Type a message and press Enter.

Chats stay in this browser (`localStorage`). Nothing is stored on a server we control.

## Features

- Real streaming replies via `puter.ai.chat()` (each dropdown item is a real Puter-hosted model)
- Claude Fable 5.1 / 5, Opus, Sonnet, GPT-5.6 Luna, GPT-4o, Grok 4.6, Gemini, Kimi K3, DeepSeek, plus extra models loaded live from Puter
- Thinking traces and work effort (low → max)
- Multi-chat sidebar, local history, search, delete
- Image attach, stop generation, copy, regenerate
- Dark studio UI that works on phones

## Deploy your own

This is a single-file app. Copy `index.html`, enable GitHub Pages on `main` / root.

## Credit

AI runs through [Puter.js](https://developer.puter.com).
