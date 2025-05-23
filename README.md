# Fahrasa

 
Fahrasa is a lightweight, high-performance inverted index search engine written in Go.  
Designed for fast and efficient full-text search over large datasets, it supports tokenization, Boolean queries, phrase searches, and scalable indexing.

---

## Features

- Build and maintain inverted indexes from large text collections
- Tokenization with normalization and stopword removal
- Boolean query support: AND, OR, NOT
- Phrase search via positional indexes
- RESTful API and CLI interfaces (configurable)
- Persistent storage of indexes and documents
- Designed with concurrency and scalability in mind

---

## Why Fahrasa?

Traditional databases struggle with fast text search over massive datasets.  
Fahrasa leverages inverted indexes for lightning-fast lookup and supports flexible query semantics, making it ideal for:

- Search engines
- Document repositories
- Log analytics
- Any application requiring efficient text lookup

---

## Getting Started

### Prerequisites

- Go 1.20 or higher installed

### Installation

```bash
git clone https://github.com/yourusername/Fahrasa.git
cd Fahrasa
go build ./cmd/Fahrasa
```

### Usage:
- Add documents to the index via CLI or REST API
- Query the index using Boolean expressions
- Persist and load indexes for quick startup

### Structure
``` bash
/cmd            - CLI and server entry points
/internal       - Core libraries (tokenizer, index, store, search, api)
/tests          - Unit and integration tests
```
