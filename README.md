# Moksh Aggarwal

**AI engineer in San Jose.** I build AI products end to end and test them like systems: the answer key is written before the code it scores.

MS, Applied Data Intelligence, San José State University (May 2026) · 20 months of backend work at TCS on a UK bank's real-time fraud-scoring path.

**Open to** AI Engineer, Forward Deployed Engineer and ML Engineer roles · Bay Area or remote
[LinkedIn](https://linkedin.com/in/aggarmoksh) · [Email](mailto:aggarmoksh@gmail.com)

---

## Featured work

| Project | What it does | Proof | Links |
|---|---|---|---|
| **[CareCircle](https://github.com/aggarmoksh/carecircle)** | Family care coordinator on real WhatsApp. Reads discharge sheets, pill-organiser photos and voice notes in Hindi, Punjabi and English into one shared medication schedule. | 78/78 discharge-sheet fields exact · 12/12 voice notes · 14/14 organiser compartments on 8/8 real photos · 210 tests | [Replay](https://aggarmoksh.github.io/carecircle/replay.html) · [Video](https://youtu.be/4g2Ha4-6-xU) |
| **[GraphDispatch](https://github.com/aggarmoksh/GraphDispatch)** | Emergency dispatch on a San Jose road graph in FalkorDB, with 6 typed MCP tools, deployed on AWS. | 24/24 correct unit sets vs 10/24 for an LLM given the same facts · 48 ms p95 vs 1,585 ms | [Live](https://d445nmo1mzx5s.cloudfront.net/) · [Video](https://youtu.be/b8IXhbINeBA) |
| **[GuardLine](https://github.com/aggarmoksh/guardline)** | Phone agent for credit unions on two real US numbers. A fixed policy makes every decision; the LLM only interprets and phrases. | 30 cases pre-registered · 0 impostors verified and 0 PII leaks across 90 runs · 155 tests | Cal Hacks 13.0 |
| **[FirstResponder Relay](https://github.com/aggarmoksh/firstresponder-relay-M)** | Multilingual 911-overflow triage: callers speak their own language, dispatchers see calls ranked on a live map. | **Top 3 Finalist**, Social Impact Track, Berkeley AI Hackathon 2026 · 27/30 urgency · 30/30 language | Built solo in 24 hours |
| **[Recall](https://github.com/aggarmoksh/recall-bee)** | Turns lectures a Bee wearable hears into spoken spaced-repetition quizzes, written and graded on Amazon Bedrock. | Working prototype | Amazon Developer Hackathon 2026 |
| **[Computer-Use Automation](https://github.com/aggarmoksh/computer-use-automation)** | An LLM works out a browser task once; the saved artifact replays with zero model calls and escalates failures to a human. | Take-home with REPORT.md trade-offs | |

**Also:** [FDRPay](https://github.com/aggarmoksh/FDRPay) (federated fraud detection with Flower and PyTorch) · [Tennis Analytics Warehouse](https://github.com/aggarmoksh/ace-the-data) (Airflow, S3, Snowflake, dbt) · [Conceptle](https://github.com/aggarmoksh/conceptle), published as a negative result: word embeddings measure co-occurrence, not concepts, and playtesting proved it (0 wins in 10 sessions).

## How I build

- **Code decides, the model reads.** Plain code owns state, timing and anything irreversible; the model drafts, classifies and phrases.
- **Evals before code.** Answer keys are committed before the code they score, and failures are reported next to passes.
- **Open about AI assistance.** I use Claude Code and Cursor daily. I write the specs, schemas and evals, and review every change.

## Experience

**Tata Consultancy Services** · Assistant System Engineer, Backend and Distributed Systems · Oct 2021 to Jun 2023
Real-time payment authorization for a Tier-1 UK bank: wrote the Protocol Buffers and Python gRPC client that moved fraud scoring to a C++ service (p99 52 ms to under 15 ms), and worked on Kafka and PySpark pipelines that kept risk profiles under 2 seconds stale.

## Stack

Python · SQL · C++ · TypeScript · FastAPI · PyTorch · Kafka · PySpark · Airflow · dbt · Snowflake · Redis · FalkorDB · AWS · Docker · Claude · Amazon Bedrock · MCP