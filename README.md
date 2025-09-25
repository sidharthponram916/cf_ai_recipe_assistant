# Cloudflare Recipe Assistant

<img width="1470" height="799" alt="Screenshot 2025-09-25 at 6 55 09 PM" src="https://github.com/user-attachments/assets/6dae729b-16dc-47ab-b1b3-69b25c86b641" />

## Features

- **Ingredient-based recipes** → enter ingredients, get back creative dish ideas.
- **Step-by-step instructions** → each recipe includes a name, description, and clear cooking steps.
- **Smart substitutions** → suggests alternatives if you’re missing key ingredients.
- **Persistent memory** → remembers past inputs using Cloudflare KV/Durable Objects.
- **Modern UI** → redesigned, responsive chat interface with Tailwind CSS.
- **Extensible tools** → ready for API integrations (nutrition, shopping lists, etc.).

---

## Tech Stack

- **Frontend**: React + Tailwind CSS (Cloudflare Pages)
- **Backend**: Cloudflare Workers + Agents SDK
- **AI**: OpenAI GPT (`gpt-4o-mini` / `gpt-4o`)
- **State Management**: Cloudflare KV / Durable Objects

---

## Setup

### 1. Clone and install

```bash
git clone https://github.com/your-username/recipe-assistant.git
cd recipe-assistant
npm install
```

## Process

I started with the Cloudflare Agents starter, walking through and analyzing the code to understand how it worked. From there, I tailored it to my use case by redesigning the UI with TailwindCSS and implementing GPT4o and refining the system prompt to generate recipes based on a user's given ingredients. It’s a simple project, but it taught me a lot about how Cloudflare Agents and Workers function, as well as state management with Durable Objects.
