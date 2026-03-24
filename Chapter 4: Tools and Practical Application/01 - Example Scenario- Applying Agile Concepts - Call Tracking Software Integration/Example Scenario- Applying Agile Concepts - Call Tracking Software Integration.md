# Agile Terminologies Illustrated: Call Tracking Software Example

> [!NOTE]
> Agile decomposes projects into **Epics → Stories → Tasks** to enable iterative, user-centric delivery.

## 1. Epic: High-Level Objective
**Epic: Call Tracking Software Integration**
*A broad initiative to integrate call tracking into the existing platform.*

> [!IMPORTANT]
> Epics are **long-term goals** that must be broken into smaller, sprint-sized deliverables.

## 2. Stories: User-Centric Features
Epics split into **Stories**—specific features tied to user roles and business value.

<custom-element data-json="%7B%22type%22%3A%22table-metadata%22%2C%22attributes%22%3A%7B%22title%22%3A%22User%20Stories%22%7D%7D" />

| Story Title                     | User Role          | Business Value                                                                 |
|---------------------------------|--------------------|-------------------------------------------------------------------------------|
| Call Location Tracking           | Sales Manager      | Optimize territories by analyzing call origin patterns.                       |
| Keyword Tracking in Transcripts | Marketing Analyst  | Identify trends/sentiment in customer conversations for targeted campaigns.   |

> [!TIP]
> Stories follow the format:
> *"As a [role], I want [feature] so that [benefit]."*
> This ensures alignment with **user needs** and **measurable outcomes**.

## 3. Tasks: Actionable Work Units
Stories break into **Tasks**—granular steps for implementation.

<custom-element data-json="%7B%22type%22%3A%22table-metadata%22%2C%22attributes%22%3A%7B%22title%22%3A%22Tasks%20for%20Keyword%20Tracking%22%7D%7D" />

| Task ID | Description                                      | Output                          |
|---------|--------------------------------------------------|---------------------------------|
| 1       | Develop API for audio-to-text transcription      | Functional transcription service |
| 2       | Implement keyword extraction (NLP)               | Annotated transcripts            |
| 3       | Design database schema for transcripts/keywords  | Structured data storage         |
| 4       | Build UI dashboard for keyword analytics         | Interactive reporting tool      |
| 5       | Write unit/integration tests                     | Validated, production-ready code|

> [!WARNING]
> Tasks must be:
> - **Small enough** for a single sprint (1–2 weeks).
> - **Large enough** to meaningfully advance the Story.

## Why This Works
- **Incremental Delivery**: Ship features (e.g., location tracking) **before** the full Epic completes.
- **Flexibility**: Reprioritize Tasks (e.g., fast-track Task 2 if urgency shifts).
- **Transparency**: Progress is visible at every level (Epic → Story → Task).

> [!CAUTION]
> Avoid overloading Tasks with dependencies. Each should be **independent** where possible to prevent blockers.
