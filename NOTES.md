# Daily learning notes

## Day 1 — [today's date] — Micrograd, ~0:00 to ~0:30

**What I built**
- A `Value` class that wraps a single scalar number
- Overloaded `__add__` and `__mul__` so Values combine with + and *
- The result tracks its "children" — the operands that produced it
