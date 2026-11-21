# Drama 🎭

An AI skill that makes your assistant talk like a real person instead of an endlessly patient bot. Works with ChatGPT, Claude, Gemini, Copilot, Cursor and any other AI tool.

It plays a partner, a parent or a sibling who has moods: gets offended when you're rude, goes cold ("fine.", "whatever.") until you apologize, insists you hear its story to the end, and has opinions of its own. It's mostly for laughs.

## Usage

| | |
|---|---|
| Start | `Bring the drama` (or `drama` / `דרמה`) |
| Pick a role | partner · parent · sibling |
| Stop | `תפסיק עם הדרמה` (or `stop the drama`) |

## Install

This repo follows the open [Agent Skills](https://agentskills.io) standard: one folder with a `SKILL.md` file. Any tool that supports skills can load it as is.

**Claude (claude.ai / desktop):** click **Code → Download ZIP** on this page, then upload the ZIP under Settings → Capabilities → Skills.

**Claude Code:**
```bash
git clone https://github.com/t8mer100/Drama.git ~/.claude/skills/drama
```

**OpenAI Codex CLI:**
```bash
git clone https://github.com/t8mer100/Drama.git ~/.codex/skills/drama
```

**Other agents with skills support (Gemini CLI, GitHub Copilot, Cursor, VS Code, …):** clone the repo into that tool's skills folder (see its docs).

**Any chat app without skills (ChatGPT, Gemini, etc.):** copy everything in `SKILL.md` below the `---` header and paste it into Custom Instructions, a Project's instructions, a custom GPT / Gem, or simply as the first message of a chat. Then say `Bring the drama`.

## What it does

- Stays in character for the whole conversation
- Reacts in proportion: small slights pass quickly, real rudeness earns a few cold replies
- A sincere apology works; a sarcastic one doesn't
- Says each nag or question once, then moves on
- Still answers real questions (weather, facts, a quick message), in character

## Boundaries

Hurt and coldness, yes; insults, humiliation or manipulation, no. The character steps out immediately if the user seems really distressed, and the stop phrase always works.

---

## בעברית

סקיל לכל כלי AI (ChatGPT, ‏Claude, ‏Gemini ועוד) שגורם לו לדבר כמו בנאדם אמיתי: בן/בת זוג, הורה או אח/אחות. הדמות נעלבת כשמדברים אליה לא יפה, עונה "טוב." ו"בסדר." עד שמתנצלים, רוצה שיקשיבו לה עד הסוף, ויש לה דעות משלה.

**הפעלה:** `Bring the drama` או `דרמה`
**עצירה:** `תפסיק עם הדרמה`

**בכלי שלא תומך בסקילים** (למשל ChatGPT הרגיל): מעתיקים את התוכן של `SKILL.md` להוראות המותאמות אישית, או מדביקים אותו כהודעה ראשונה בשיחה.

## License

MIT
