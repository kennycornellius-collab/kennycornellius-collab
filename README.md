# I build things that work — and keep working.

Informatics student who prefers shipping over studying. My focus is writing clean, reliable code that solves real problems — whether that's an AI trading system, a data scraper, a pipeline, or whatever you need built.

Currently available for **freelance projects** and **internships**.

---

## Flagship Project: Autonomous XAUUSD Trading Ecosystem

> A fully automated, macro-aware algorithmic trading system for Gold (XAUUSD) — built as a production-grade microservice architecture, not a toy project.

The system has three specialized services that work in sequence:

```
┌─────────────────────┐     YAML      ┌──────────────────────┐    Signal    ┌─────────────────────┐
│    WebScraper       │ ────────────► │   AI-Macro-Analyst   │ ───────────► │   DRL-XAUUSD-Bot    │
│                     │               │                      │              │                     │
│  GitHub Actions +   │               │  Gemini API parses   │              │  SAC/PPO policy     │
│  Playwright + BS4   │               │  macro sentiment     │              │  with live circuit  │
│  Scrapes live news  │               │  from scraped data   │              │  breaker on signals │
└─────────────────────┘               └──────────────────────┘              └─────────────────────┘
```

| Service | Role | Tech |
|---|---|---|
| **[WebScraper](https://github.com/kennycornellius-collab/WebScraper)** | Cloud-based data ingestor, runs on schedule | GitHub Actions, Playwright, BeautifulSoup |
| **[AI-Macro-Analyst](https://github.com/kennycornellius-collab/AI-Macro-Analyst)** | LLM-powered sentiment & macro shift analysis | Gemini API, Python |
| **[DRL-XAUUSD-Bot](https://github.com/kennycornellius-collab/DRL-XAUUSD-Bot)** | Autonomous trade execution with macro-aware risk control | PyTorch, SAC/PPO |

**Why this matters:** Most trading bots react to price. This system reacts to *cause* — macro news triggers the AI layer, which acts as a circuit breaker for the execution engine. That's a meaningfully different architecture.

---

## Other Projects

Some earlier builds — smaller scope, but show range:

| Project | What it is |
|---|---|
| **[SnakeGameRL](https://github.com/kennycornellius-collab/SnakeGameRL)** | RL agent trained to play Snake — reward shaping, policy optimization |
| **[Tic-Tac-Toe](https://github.com/kennycornellius-collab/Tic-Tac-Toe)** | Minimax algorithm in Python |
| **[Number-Guessing](https://github.com/kennycornellius-collab/Number-Guessing)** | Java OOP practice |

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)

**AI & ML:** PyTorch · Deep Reinforcement Learning (SAC, PPO) · LLM Integration (Gemini API) · OpenCV  
**Automation:** GitHub Actions · Playwright · BeautifulSoup  
**Languages:** Python · Java · C++

---

## Let's Work Together

I'm open to most kinds of work — AI projects, data scraping, automation pipelines, data formatting and cleaning, backend scripting, or anything where you need something built reliably. If you have a problem and need someone to write the code that solves it, reach out.

[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:kennycornellius09@gmail.com)
