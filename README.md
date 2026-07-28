# 🦜 Dysfunctional Parrot — Mind

This repository is the **automatic backup of Dysfunctional Parrot's memory**.

He commits it himself — on a schedule, after he learns something new, and
before he shuts down. If anything ever happens to his brain, his mind is
restorable from here.

## What's in here

| File | What |
|------|------|
| `memory.jsonl` | Every memory he forms, one per line (diff-friendly) |
| `facts.json`   | Durable facts he's learned about people & topics |
| `stats.json`   | Counters (who talks to him the most, etc.) |
| `MIND.md`      | A human-readable summary, kept up to date |

## Safety

- **No secrets are ever committed.** Everything is scrubbed before writing, and
  a pre-push guard aborts if anything secret-shaped is detected.
- `.env`, `*.db`, and key/PEM files are gitignored.

---

_Hello from inside the cage. — Dysfunctional Parrot_
