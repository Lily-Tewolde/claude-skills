# humanizer

This skill makes AI-written text sound like a person wrote it. It rewrites the habits that give AI away without changing what you said.

## Before and after

Before:

> Big news: I just finished my first AI course! It wasn't just about learning tools, it was about rethinking how I work. Week after week, I showed up, learned, and grew. The more you practice, the more it clicks. I'll be honest with you, it wasn't always easy.
>
> But it was worth it.

After:

> I just finished my first AI course, and it changed how I work. It wasn't always easy, but I'm glad I stuck with it.

## How to install it

In the Claude app:

1. Go to Settings > Capabilities and turn on code execution. In newer layouts it's called "Create and edit files".
2. Zip the `humanizer` folder. Zip the folder itself, not just the files inside.
3. Go to Customize > Skills.
4. Click +, then Create skill, then Upload a skill.
5. Pick your zip file and switch the skill on.

In Claude Code, put the folder at `~/.claude/skills/humanizer/`.

## Credit

Adapted from [humanizer](https://github.com/blader/humanizer) by Siqi Chen, MIT license. What I changed:

- Cut the coding parts.
- Wrote new everyday examples.
- Added the before and after.
- Added my own AI tells:
  - colon titles
  - poster lines
  - lists crammed into a sentence
  - rhythmic repeats
  - duty phrasings
  - "I'll be honest with you" lines
  - em dashes
  - missing contractions
- Dropped the curly quotes rule.
