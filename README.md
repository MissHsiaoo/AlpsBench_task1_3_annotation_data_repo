# AlpsBench Task1-3 Annotation Data

This repository contains the filtered task1-3 session packet dataset for annotation.

- Total sessions: 2272
- Chunk size: 20
- Chunk count: 114
- Required tasks per session: task1, task2, task3

## Layout

`chunks/chunk_0001/` contains up to 20 `sess_*.json` files plus a chunk-level `manifest.json`. The final chunk may contain fewer than 20 sessions.

Use the root `manifest.json` for the complete chunk index.
