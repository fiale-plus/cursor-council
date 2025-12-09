# Cursor Council

**A real simple, single-session protocol that turns separate Cursor chat windows into a coordinated research team.**  
Models read, critique, and synthesize each other's work using shared local files.

## Commands

- `council: {question}` — Start/join topic.
- `council: continue` — **Critique** peers.
- `council: synthesize` — **Unify** insights.
- `council: status` — Check progress.
- `council: clear` — Reset session.

## Quick Start

1. **Setup**: Open this folder in Cursor OR copy [`.cursorrules`](.cursorrules) to your project.
2. **Prepare**: Open new chats, switch to **Agent Mode**, and select different models.
3. **Collect**: Ask `council: {question}` in multiple windows (e.g., Claude & GPT-4).
4. **Critique**: Run `council: continue` in each window.
5. **Synthesize**: Run `council: synthesize` for the final verdict.

## Why?

- **Diversity**: Different models = better architectural decisions.
- **Accuracy**: Models catch each other's blind spots.
- **Consensus**: clear agreement or highlighted trade-offs.
