# Verity

Verity is a conversational analytics agent for business data.

It allows founders, marketers, and analysts to ask questions in natural language
and receive charts, explanations, and insights directly from their own data,
without building dashboards.

Verity works on top of existing data warehouses such as SQL databases and
Google BigQuery, and is designed for real, production-grade analytics.

---

## What problem does Verity solve?

Traditional business intelligence tools rely on pre-built dashboards.
Every new question requires a new report, a new chart, or help from an analyst.

This creates friction:
- Dashboards become outdated
- Questions change faster than reports
- Business users are dependent on technical teams

Verity replaces dashboards with a conversation-first approach to analytics.

Instead of navigating reports, users ask questions like:
- “Why did revenue drop last week?”
- “Which channels drive profitable growth?”
- “How does this month compare to last month?”

Verity answers with charts, metrics, and clear explanations.

---

## What is a conversational analytics agent?

A conversational analytics agent is an AI system that:
- Understands business questions in natural language
- Interprets metrics, dimensions, and time ranges
- Translates questions into executable queries
- Executes those queries on your own data
- Returns visualizations and explanations, not just raw numbers

Verity is not a chatbot on top of dashboards.
It is designed to reason about data, context, and intent.

---

## How Verity works (high-level)

At a conceptual level, Verity follows this flow:

1. A user asks a question in natural language  
2. The question is interpreted using a semantic understanding of the data  
3. The intent is translated into structured queries (e.g. SQL)  
4. Queries are executed on the connected data source  
5. Results are transformed into charts and explanations  

All analysis happens on the user’s own data.

---

## What Verity is designed for

Verity is built for:
- Business data exploration
- Ad-hoc analysis without dashboards
- Metric comparison over time
- Understanding *why* numbers change, not just *what* changed

Typical users include:
- Founders and leadership teams
- Marketing and growth teams
- Data and analytics teams

---

## What this repository contains

This repository does **not** contain production code.

It exists to document:
- The concept behind Verity
- High-level architecture ideas
- Example questions and interpretations
- Design principles for conversational analytics

The actual product implementation is private.

---

## Example question

**Question**  
“Why did revenue decrease compared to last month?”

**Interpretation**
- Metric: revenue
- Time comparison: last month vs previous month
- Breakdown: channel

**Result**
- A chart showing revenue by channel
- A textual explanation highlighting the main drivers of the change

---

## Status

Verity is currently in private development.

This repository represents the conceptual and product-level view of the system,
not a finished or publicly released API.

---

## Philosophy

Verity is built on a simple idea:

> Business users should be able to understand their data by asking questions,
> not by building dashboards.

---

## License

This repository is provided for informational purposes only.
All rights reserved.
