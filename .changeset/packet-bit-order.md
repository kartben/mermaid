---
'mermaid': minor
---

feat: add a `bitOrder` option to packet diagrams. It defaults to `ascending`, which is the current
behaviour, and `descending` mirrors every row so it reads from its most significant bit down to
bit 0 — the convention used for hardware register diagrams. Fields are still declared lowest bit
first and keep their width, so switching a diagram between the two conventions only means changing
`bitOrder`.
