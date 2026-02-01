# Goldstonian Concordance Bible Library (Canonical Read-Only)

This repository contains the canonical dataset, schemas, and indices for the Goldstonian Concordance Bible.
It is designed to be machine-readable and stable for human study and agent learning.

## Principles
- Read-only canonical surface (protect `main`)
- Structured indices for navigation
- Controlled vocabulary for consistent semantics
- Crosswalks to join passages, themes, books, and citations
- Releases are versioned and citable (Zenodo/Figshare placeholders until published)

## Key folders
- `canonical-index/` — machine navigation (series/books/chapters/passages)
- `vocab/` — controlled vocabulary
- `themes/` — themes & semantic layer
- `citations/` — references and citation map
- `schema/` — validation and structured web metadata
- `agents/learn-goldstonian-concordance-bible/` — agent learning curriculum & eval prompts

## Operating mode
Humans and agents should treat this repository as a library:
- **Read-only**
- **No secret data**
- **No operational integrations**
