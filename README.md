# Natural Copy Editor

A small, cross-agent skill for revising Chinese public-facing copy that feels generic, overly polished, or visibly AI-templated.

It is intended for WeChat articles, Xiaohongshu posts, event pages, community communications, and career content. It preserves facts and authorial intent while removing interchangeable openings, forced “takeaway” structures, inflated claims, excessive emoji, and unrelated calls to action.

## Install

Copy `SKILL.md` to one of the following locations:

```text
~/.codex/skills/natural-copy-editor/SKILL.md
~/.claude/skills/natural-copy-editor/SKILL.md
```

Then ask the agent to use `$natural-copy-editor` when drafting or revising audience-facing Chinese copy.

For a normal ChatGPT conversation, upload or paste `SKILL.md` into the chat and ask it to follow the skill for the current draft. ChatGPT does not automatically read files from your local skills directory.

## What it does not do

This is an editorial skill, not an AI-detector bypass. It does not fabricate specificity, alter facts, or turn private and approval-controlled events into public lead-generation content.

## License

MIT
