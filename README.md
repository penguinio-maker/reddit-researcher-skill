# Reddit Researcher

Reddit Researcher is a reusable AI skill for answering questions with current Reddit discussions instead of relying on generic summaries.

It compares independent posts and comments, separates recurring experiences from isolated opinions, and verifies important factual claims with primary or authoritative sources.

## What it does

- Searches for relevant, recent Reddit discussions.
- Opens the original threads instead of relying only on search snippets.
- Compares recurring experiences, disagreements, and unusual reports.
- Avoids presenting one comment as a Reddit consensus.
- Verifies prices, specifications, safety claims, and other important facts outside Reddit.
- Includes direct source links, confidence levels, and research limitations.

## Install with your AI chatbot

Copy the prompt below and paste it into your AI chatbot:

```text
Download and install the Reddit Researcher skill for your AI assistant from:
https://github.com/penguinio-maker/reddit-researcher-skill

The skill is located in the skills/reddit-researcher directory. Review its files before installing, install it in the correct skills or instructions directory for this AI assistant, and tell me when it is ready to use.

If you cannot download or install files from GitHub, explain the exact manual installation steps for this AI assistant instead.
```

Repository: [penguinio-maker/reddit-researcher-skill](https://github.com/penguinio-maker/reddit-researcher-skill)

After installation, ask your question normally. For example:

```text
Use Reddit Researcher to compare recent Reddit discussions about which paid AI tools people keep subscribing to and which subscriptions they cancel.
```

## Repository structure

```text
reddit-researcher-skill/
├── README.md
├── .gitignore
└── skills/
    └── reddit-researcher/
        ├── SKILL.md
        └── agents/
            └── openai.yaml
```

## Privacy and safety

This repository contains instructions only. It does not include API keys, cookies, credentials, personal information, local user paths, search history, or computer-access tools.
