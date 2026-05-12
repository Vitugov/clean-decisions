# Clean Decisions

A thinking partner for decisions you'll live with for years.

## Install

Download [`clean-decisions.zip`](./clean-decisions.zip).

**Claude.ai:** Customize → Skills → **+** → upload the ZIP.

**ChatGPT:** Profile → Skills → **+** → upload the ZIP.

**Claude Code, Codex CLI, Cursor, Gemini CLI, Antigravity, Windsurf:** follow your platform's standard Agent Skills installation. Clean Decisions follows the open [Agent Skills standard](https://agentskills.io), so the same ZIP works everywhere the standard is supported.

## Use

After installing, the skill activates in two ways:

**Automatic.** When you bring up a real decision — something you're stuck on, doubting, or wrestling with — the skill triggers itself based on context.

**Explicit.** Type *"activate clean decisions"* in any conversation to start a session directly. Works on every platform that supports the skill.

Starts in English by default. Will ask once which language you'd like to use, then continue in that one.

## Alternative: use without installing

If your platform doesn't support Agent Skills, or you'd rather not install anything:

1. Open [`clean-decisions.md`](./clean-decisions.md).
2. Copy its contents.
3. Paste into Project Instructions / Custom Instructions / system prompt.
4. Start a new conversation.

Works in claude.ai Projects, ChatGPT Custom Instructions, and any interface that accepts a system prompt. In this mode the prompt is always active — no trigger phrase needed.

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

The skill can keep a small `memory.md` file with observations about your patterns — what energizes you, what drains you, the criteria you return to, the loops you fall into. It's written as **hypotheses**, never as facts, and it's primarily a mirror for you, not a database for the model. Everything proposed for memory is confirmed before being written.

## Deeper

[`PHILOSOPHY.md`](./PHILOSOPHY.md) explains *why* the tool is built this way: the three levels of effect (operational, systemic, long-term), why a smart model without this prompt produces something different, what success looks like over time, and where the tool's limits are. Read it if you want the longer story; skip it if practical use is enough.

## Design notes

Built for [Claude Opus 4.7](https://www.anthropic.com/news/claude-opus-4-7) and similarly capable models. Smaller models may need more explicit scaffolding — feedback welcome.

The prompt is deliberately short. The hardest work in its design was removing structure, not adding it.

## License

[MIT](./LICENSE). Use it, modify it, share it, fold it into your own tools. Attribution appreciated but not required.

## Author

Built by Max Vitugov ([@vitugov](https://github.com/vitugov)). Designing management systems, now with AI inside.
