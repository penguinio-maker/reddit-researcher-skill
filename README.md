# Reddit Researcher

Reddit Researcher is a personal Codex skill for answering questions with current Reddit discussions instead of relying on generic summaries.

It compares independent posts and comments, separates recurring experiences from isolated opinions, and verifies important factual claims with primary or authoritative sources.

## What it does

- Searches for relevant, recent Reddit discussions.
- Opens the original threads instead of relying only on search snippets.
- Compares recurring experiences, disagreements, and unusual reports.
- Avoids presenting one comment as a Reddit consensus.
- Verifies prices, specifications, safety claims, and other important facts outside Reddit.
- Includes direct source links, confidence levels, and research limitations.

## Repository structure

```text
reddit-researcher/
├── README.md
├── .gitignore
└── skills/
    └── reddit-researcher/
        ├── SKILL.md
        └── agents/
            └── openai.yaml
```

## Installation

Copy the `skills/reddit-researcher` directory into your Codex skills directory.

Windows PowerShell:

```powershell
Copy-Item -Recurse ".\skills\reddit-researcher" "$env:USERPROFILE\.codex\skills\reddit-researcher"
```

macOS or Linux:

```bash
cp -R ./skills/reddit-researcher "${CODEX_HOME:-$HOME/.codex}/skills/reddit-researcher"
```

Restart Codex or open a new task if the skill does not appear immediately.

## Example prompt

```text
Use $reddit-researcher to analyze recent Reddit discussions about which paid AI tools people continue subscribing to after several months and which subscriptions they cancel.

Compare at least five independent Reddit threads. Separate recurring user experiences from isolated opinions, identify the practical reasons people keep or cancel each tool, and verify current subscription prices using official websites.

Do not invent statistics or present a single comment as a Reddit consensus. Include direct links to the discussions and clearly state the confidence level and limitations of the findings.
```

## Privacy and safety

The skill is instruction-only. It does not provide additional computer, account, or browser permissions.

Its default workflow uses public web sources and information explicitly provided by the user. It instructs the agent not to access local files, private browser sessions, accounts, messages, or connected services merely because the skill was invoked.

No API keys, cookies, credentials, personal information, local user paths, or search history are included in this repository.

