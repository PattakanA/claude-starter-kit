I'm new to Claude Code. Help me set up a starter kit of plugins.

Please walk me through installing these, one at a time. Plugin installs are
slash commands that I have to type myself, so give me each command to copy,
and wait for me to say it worked before the next one:

1. /plugin marketplace add thedotmack/claude-mem
2. /plugin install superpowers@claude-plugins-official
3. /plugin install frontend-design@claude-plugins-official
4. /plugin install claude-code-setup@claude-plugins-official
5. /plugin install claude-mem@thedotmack

Optional last step, only if Node.js is installed (check with `node -v`).
This is a terminal command, not a slash command, so have me run it in a
normal terminal, not in this prompt:
6. npx skills add vercel-labs/skills --skill find-skills -a claude-code -g -y
7. npx skills add superagent-ai/skills --skill skill-security -a claude-code -g -y
   (also needs Python 3; it checks skills for safety before I install them)

If one fails, help me debug it (e.g. check /plugin for the marketplace list).
When all are installed, tell me to restart Claude Code, then explain in 5
short lines what each plugin does and give me one beginner exercise to try.
