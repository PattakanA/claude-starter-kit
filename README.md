# Claude Code Starter Kit

Beginner-friendly plugins for Claude Code, with a one-paste setup.

## Fastest way
1. Open Claude Code in any folder.
2. Open `SETUP-PROMPT.md`, copy everything, and paste it into Claude Code.
3. Claude will tell you which commands to run. Type each one yourself in the prompt (they start with `/`).
4. Restart Claude Code, then type `/` to see the new skills.

## What gets installed
| Plugin | Why it helps a beginner |
|---|---|
| `superpowers` | Claude plans before coding, debugs step by step, and checks its work before saying "done" |
| `claude-mem` | Claude remembers past sessions, so you don't re-explain your project |
| `frontend-design` | Better-looking websites and UI, less generic |
| `claude-code-setup` | Recommends automations and settings that fit your project |

## Manual install (same thing, no paste)
```
/plugin marketplace add thedotmack/claude-mem
/plugin install superpowers@claude-plugins-official
/plugin install frontend-design@claude-plugins-official
/plugin install claude-code-setup@claude-plugins-official
/plugin install claude-mem@thedotmack
```
Then restart Claude Code.

## Optional: find-skills (needs Node.js)
Lets Claude search the skills.sh directory and suggest skills for what you're doing.
Run this in a normal terminal (not inside Claude Code), then restart Claude Code:
```
npx skills add vercel-labs/skills --skill find-skills -a claude-code -g -y
```
Source: https://github.com/vercel-labs/skills (MIT). Review any skill before installing it.

## Built-in skills (nothing to install)
- `/code-review`: review your changes for bugs
- `/simplify`: clean up code you just wrote
- `/init`: create a CLAUDE.md describing your project

## Tips
- Start small. Use `superpowers` first and add others when you need them.
- Type `/` to list skills. They can also trigger on their own.
- Only install plugins from sources you trust; they run with your permissions.
