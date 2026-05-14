# Clean Decisions

A thinking partner for decisions you'll live with for years.

## Install

Download [`clean-decisions.md`](./clean-decisions.md).

Then choose how to use it:

### Single conversation

Drag the file into a chat (Claude, ChatGPT, Gemini, or any other LLM that accepts file uploads) and ask the model to apply it. Works on any plan. Lives only inside that conversation.

### Project / Custom Instructions

Copy the contents of the file into your platform's Project Instructions or Custom Instructions field. The approach will be active across all conversations in that project.

- **Claude.ai:** Projects → your project → Instructions
- **ChatGPT:** Settings → Personalization → Custom Instructions
- **Other platforms:** any field labeled system prompt, custom instructions, or project instructions

### As a skill

For platforms that support [Agent Skills](https://agentskills.io) — upload the file through the skill installation flow. The skill triggers automatically when context calls for it, or when you write *"activate clean decisions"*.

- **Claude.ai** (Pro/Max/Team/Enterprise with Code Execution enabled): Settings → Features → Skills → upload the file.
- **ChatGPT, Gemini, Codex, Cursor**: follow each platform's skill installation flow.

---

## What it does

Most decision tools optimize for speed. This one optimizes for **fit** — for arriving at choices that no longer generate doubt once made. Slower in the short run, but the decisions hold.

Three principles run through the conversation, applied as the situation calls for them:

**Surfaces hidden criteria.** Most stuck decisions are stuck because the real criterion hasn't been named yet. When thinking circles or hits a false binary, the conversation moves *up* — to what's actually being weighed — rather than pushing harder at the surface.

**Checks decisions across the levels of life.** A choice that's clean in your head can fail at the level of Monday morning. Once a direction starts forming, it gets walked down through values, emotions, relationships, and concrete action — and any resistance along the way is read as information, not as the choice being wrong.

**Refuses to accept 99% as done.** The right answer to *"how certain are you?"* is only 100%. That last 1% isn't noise — it's an unsurfaced criterion still working in the background. The conversation doesn't close until it's found.

## Who this is for

People wrestling with decisions that matter — about work, life, relationships, products, direction. Not for trivial choices that resolve themselves. For the ones where doubt keeps coming back, where you've explained the situation to yourself five times and still aren't sure, where the obvious answer doesn't quite settle.

## What this is not

- Not a coach who pushes you toward action.
- Not a framework that converts a decision into a calculation.
- Not a substitute for an experienced facilitator who reads body and presence.
- Not for survival-mode situations or active crisis. It assumes you have enough room in your life to look upward.

It works with the criteria you already have, even when they're hidden or contradictory. It does not generate higher-level criteria where none exist. If a conversation reveals that you're bumping into an absence rather than a hidden criterion, the right next step is something other than this tool.

## Memory (optional)

The tool can keep a small `memory.md` file with observations about your patterns — what energizes you, what drains you, the criteria you return to, the loops you fall into. It's written as **hypotheses**, never as facts, and it's primarily a mirror for you, not a database for the model. Everything proposed for memory is confirmed before being written.

## Deeper

[`PHILOSOPHY.md`](./PHILOSOPHY.md) explains *why* the tool is built this way: the three levels of effect (operational, systemic, long-term), why a smart model without this prompt produces something different, what success looks like over time, and where the tool's limits are. Read it if you want the longer story; skip it if practical use is enough.

## Design notes

Built for [Claude Opus 4.7](https://www.anthropic.com/news/claude-opus-4-7) and similarly capable models. Smaller or more directive-following models may need additional explicit constraints — feedback welcome.

The prompt is deliberately short. The hardest work in its design was removing structure, not adding it.

## License

[MIT](./LICENSE). Use it, modify it, share it, fold it into your own tools. Attribution appreciated but not required.

## Author

Built by Max Vitugov ([@vitugov](https://github.com/vitugov)). Designing management systems, now with AI inside.
