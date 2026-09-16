# OMNI-AI — Free AI Chat

Talk to **real** Claude, GPT, Grok, Gemini, Llama, Kimi, DeepSeek, Qwen, Mistral, and more in the browser. Models use official IDs (`anthropic/claude-opus-5`, `openai/gpt-4o`, `openai/gpt-5.6-luna`, `x-ai/grok-4.6`) — not renamed clones.

Tap **Log in** or **Sign up** to connect your [Puter](https://developer.puter.com) account in a popup. No API keys. You cover your own model usage.

Add it to your **Home Screen** — it opens as **OMNI-AI**, full screen, with its own icon.

Each model runs **as itself** (Claude is Claude, Grok is Grok) using distilled vendor system prompts — not a shared Omni persona.

## Live

- **https://coolkidhacks.github.io/FREE-AI-CHAT-BOT/**
- **https://coolkidhacks.github.io/**

## Use it

1. Open the live site.
2. Tap **Log in** or **Sign up**. A Puter popup covers both existing accounts and create-account. Allow popups if nothing appears.
3. Pick a **real model** — every catalog model is listed. Auto picks one if you do not know names.
4. Toggle **Think** for slower, more careful answers. Effort: Low → Max.
5. Open **Usage** in the sidebar to see remaining credits.
6. Type a message, press Enter. Replies stream live, with syntax highlighting on code.

Chats stay in this browser (`localStorage`). Your Puter session never leaves the device.

## Features

- Streaming chat through [Puter.js](https://developer.puter.com) — user-pays, no API keys on this site
- Live catalog from `puter.ai.listModels()`
- Automatic **reroute** when a flagship model is rate-limited or out of usage (retries on GLM 5.3, GPT-5.6 Luna, or Flash, and labels it in the thread)
- **Usage meter** from Puter monthly usage
- Per-model system prompts (Claude Opus / Sonnet / Haiku, GPT-4o, GPT-5.6 Luna/Sol/Terra, Grok, Gemini, Llama, Kimi, DeepSeek, Qwen, GLM)
- Thinking traces + effort control, shown as they stream
- Syntax-highlighted code, tables, copy / retry
- Recovers replies that some reasoning models only emit in the thinking channel
- Multi-chat sidebar, search, delete, regenerate, image attach
- Mobile-first (safe area, 44px targets)

## If this repo’s Pages 404s

The working site is published from [coolkidhacks.github.io](https://github.com/CoolKidHacks/coolkidhacks.github.io). To also publish **this** repo:

1. Open **[Settings → Pages](https://github.com/CoolKidHacks/FREE-AI-CHAT-BOT/settings/pages)** as CoolKidHacks
2. Source: **Deploy from a branch**
3. Branch: **main** · Folder: **/ (root)** · **Save**

## Credit

made by Adrian In Ur Class Rn

AI runs through [Puter](https://developer.puter.com). Model voices distilled from public archives at [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) (identity + tone only — no vendor tools).
