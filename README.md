# UX review skill

An agent skill for reviewing and improving the UX of a screen or flow on a running product. The agent walks the real app as the person who will use it, forces every state (empty, loading, error, partial, long text, worst-case data), checks what the user expects next, and reports only what it saw, with evidence.

## Install

Copy `skills/ux-review` into your agent's skills folder, for example `~/.claude/skills/ux-review`.

## Use

Ask your agent to review or improve the UX of a screen or flow, or to check user-facing work before calling it done. The skill's steps and rules are in `skills/ux-review/SKILL.md` and its `references/` folder.

## License

MIT
