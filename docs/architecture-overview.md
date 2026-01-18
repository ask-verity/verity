# Verity Architecture Overview (High-Level)

This document describes the high-level conceptual architecture of Verity.
It intentionally avoids implementation details.

## Core Concepts

Verity is built around five conceptual layers:

1. User interaction (natural language questions)
2. Semantic understanding of metrics and dimensions
3. Intent translation into structured queries
4. Execution on the connected data source
5. Result transformation into charts and explanations

## Design Principles

- Conversation-first, not dashboard-first
- Operates directly on existing data warehouses
- No unnecessary data duplication
- Designed for real, production-grade analytics
- Clear separation between intent, query, and visualization

This architecture allows Verity to reason about data
rather than simply retrieve numbers.
