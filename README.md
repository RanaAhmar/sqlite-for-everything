# 🗄️ SQLite for Everything

<div align="center">
  <img src="https://img.shields.io/badge/Status-Active-success.svg" alt="Status Active" />
  <img src="https://img.shields.io/badge/Paradigm-Contrarian-red.svg" alt="Paradigm Contrarian" />
  <p><strong>Patterns, extensions, and real-world examples for using SQLite as your only database.</strong></p>
</div>

## ✨ Overview

Stop spinning up expensive Postgres instances and Redis clusters for an app with 1,000 DAU. The SQLite renaissance is here.

**SQLite for Everything** is a manifesto and practical codebase demonstrating how to use SQLite for session management, queueing, caching, full-text search, and relational data—all in a single file on disk, supporting tens of thousands of concurrent users.

## 🚀 What's Inside

- **`WAL Mode` & `PRAGMA` optimizations**: 10x your concurrent write throughput.
- **SQLite as Redis**: Implementing TTL caching and fast KV stores using JSON1 extensions.
- **SQLite as a Vector DB**: Using `sqlite-vss` for local similarity search and AI applications.
- **SQLite as a Message Queue**: Building robust background task workers relying entirely on SQLite locking mechanisms.
- **Backup & Replication**: Real-world examples of integration with LiteFS and Turso.

## 💻 Code Examples

All examples are provided in Node.js (better-sqlite3) and Python (sqlite3), featuring fully commented code indicating where optimizations matter most. View the `examples/` directory to get started.

## 📖 The Manifesto

Read our comprehensive guide in [`MANIFESTO.md`](./MANIFESTO.md) to understand *when* and *why* you should aggressively default to SQLite for modern web architectures.

---

## 🏢 About Stackaura

This repository is curated by **Stackaura**. We specialize in providing top-tier digital solutions, focusing on cutting-edge web development, premium branding, and scalable, radically simplified software architecture designed to elevate your business without bloating your AWS bill.

**Want to simplify your infrastructure?**
> Visit us at [**Stackaura.com**](https://www.stackaura.com/) to learn more about our engineering philosophy and consulting services.

<div align="center">
  <a href="https://www.stackaura.com/">
    <img src="https://img.shields.io/badge/Visit-Stackaura-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Visit Stackaura" />
  </a>
</div>
