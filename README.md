# Claude skills

Popular open-source Claude skills I've adapted so they're easier to use if you don't code. Every one credits the person who made the original, and each folder keeps its original license.

## Skills

| Skill | What it does | Adapted from |
|---|---|---|
| [humanizer](humanizer/) | Makes AI-written text sound like a person wrote it | [humanizer](https://github.com/blader/humanizer) by Siqi Chen (MIT) |
| [prompt-master](prompt-master/) | Turns a rough idea into a prompt for Claude, ChatGPT, Lovable or an image tool | [prompt-master](https://github.com/nidhinjs/prompt-master) by Nidhin Joseph Nelson (MIT) |
| [social](social/) | Hooks, short video scripts and captions for TikTok, Instagram and LinkedIn | [social](https://github.com/coreyhaines31/marketingskills/tree/main/skills/social) by Corey Haines (MIT) |
| [frontend-design](frontend-design/) | Helps your app or site not look like every other AI app | [frontend-design](https://github.com/anthropics/skills/tree/main/skills/frontend-design) by Anthropic (Apache-2.0) |

## What's a skill?

A skill is a folder of instructions that Claude reads when your request matches what the skill is for. Once it's installed, you don't have to paste a long prompt every time.

## How to install one

In the Claude app:

1. Go to Settings > Capabilities and turn on code execution. In newer layouts it's called "Create and edit files".
2. Download the skill's folder and zip it. Zip the folder itself, not just the files inside.
3. Go to Customize > Skills.
4. Click +, then Create skill, then Upload a skill.
5. Pick your zip file and switch the skill on.

In Claude Code, put the folder in `~/.claude/skills/`.

## Licenses

Each skill keeps the license it came with, inside its own folder. What I changed in each one is listed at the bottom of its README.

---

Know a skill I should add? [Open an issue](https://github.com/Lily-Tewolde/claude-skills/issues) and tell me why you love it.

Made by [Lily Tewolde](https://github.com/Lily-Tewolde). Find me on TikTok at [@lilytewolde](https://www.tiktok.com/@lilytewolde) and on Instagram at [@promptesss](https://www.instagram.com/promptesss).
