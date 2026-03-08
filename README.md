# Aimery — The World's First AI Memory Library

> *Give your AI a memory. Across every platform. Forever.*

---

## The Problem

Every time you start a new AI chat, it forgets everything.

Your context. Your projects. Your preferences. Your history. Gone.

You spend the first 10 minutes of every session re-explaining who you are, what you're building, and where you left off — before any real work gets done.

And it gets worse: your memory is **trapped** inside each platform separately.

- Your Claude conversations don't know what you told ChatGPT
- Your Grok sessions don't know what you built with Gemini
- Every AI you use meets you as a stranger — every single time

---

## The Insight

AI doesn't need to *remember* the way humans do.

It just needs the information **in context.**

A plain `.txt` file containing your conversation history — compressed, clean, stripped of UI noise — can be read by any AI in **under one second.** Not because AI reads fast. Because it doesn't "read" at all in the human sense. The entire file exists in its awareness simultaneously.

A photograph of your lunch: **3MB.**
A full month of AI conversations compressed to plain text: **~50KB.**

60x smaller. Infinitely more meaningful.

---

## The Solution

**Aimery** is a chat memory extractor.

Paste any raw AI conversation → get a clean, compressed `.txt` file → upload it to your next chat → your AI picks up exactly where you left off.

Works with **Claude, ChatGPT, Grok, Gemini, Meta AI** — any platform.

No API. No subscription. No server. No database.

Just a `.txt` file you own, control, and carry with you.

---

## How It Works

**Step 1 — Extract**
Open any AI chat. Select All (`Ctrl+A`). Copy. Paste into Aimery.

**Step 2 — Clean**
Aimery strips all the UI noise — buttons, timestamps, nav text, system labels — and compresses your conversation into a clean `YOU / AI` script format.

**Step 3 — Save**
Download your `.txt` file. Name it. Store it. It's yours.

**Step 4 — Remember**
Start a new chat on any platform. Upload your `.txt` file. Say *"here's our previous conversation."*

Your AI now has full context — projects, preferences, history, decisions — in seconds.

---

## Why Plain Text?

Every other "AI memory" solution stores your context in:
- Vector embeddings
- Graph databases
- Proprietary cloud formats

You can't read those files. You can't edit them. You can't move them. You don't own them.

Aimery stores everything as **human-readable plain text.**

- ✅ You can open it in Notepad
- ✅ You can edit it
- ✅ You can share it
- ✅ You can move it between platforms freely
- ✅ You know exactly what your AI knows about you

That's not just a simpler implementation. That's a different philosophy. **Transparent memory. User-owned. Portable forever.**

---

## The Math

| | Size |
|---|---|
| Average long AI conversation | ~5,000 words |
| Compressed to `.txt` | ~30KB |
| Claude's context window capacity | ~700,000 words |
| Full past conversations you could inject | **140+** |

A power user could carry a rolling memory bundle — every significant AI conversation from the past year — in a single file under 1MB. Smaller than most image files. Readable by any AI in milliseconds.

---

## File Structure (Folder Vision)

```
AI Memory/
  ├── Claude/
  │     ├── chat-memory-2026-01-15.txt
  │     ├── chat-memory-2026-02-03.txt
  │     └── chat-memory-2026-03-08.txt
  ├── ChatGPT/
  │     ├── chat-memory-2026-01-20.txt
  │     └── chat-memory-2026-02-14.txt
  ├── Grok/
  │     └── chat-memory-2026-03-07.txt
  └── master-memory.txt  ← combined bundle for full cross-platform context
```

Total folder size for 1 year of heavy AI usage: **under 3MB.**

---

## Use Cases

**Developers** — carry your full codebase context, decisions, and architecture notes across sessions

**Founders** — keep every product idea, feedback session, and strategy conversation alive and searchable

**Students** — build a growing knowledge base that compounds across months of research

**Writers** — maintain character, plot, and world-building context across long projects

**Anyone** — stop re-explaining yourself to an AI that should already know you

---

## What's Next

Aimery is currently a browser-based extractor. The roadmap:

- [ ] **Chrome Extension** — auto-extract on chat close, zero manual steps
- [ ] **Cross-platform folder sync** — one memory bundle across all your devices  
- [ ] **Smart compression** — auto-summarise old chats to keep bundles lean
- [ ] **Memory search** — search across all your AI conversations ever
- [ ] **Master bundle builder** — merge multiple `.txt` files into one context drop

---

## Built By

[@heisborony](https://github.com/heisborony) — Lagos, Nigeria 🇳🇬

*Built in one day. Shipped the same night. Because the best solutions are always obvious in hindsight.*

---

## License

MIT — free to use, fork, and build on.

---

*"The labs built vector databases. We built a .txt file. Turns out the .txt file works better."*
