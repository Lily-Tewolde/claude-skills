# prompt-master

This skill turns a rough idea into a prompt you can paste into Claude, ChatGPT, Lovable, or an image tool like Midjourney. It asks a few quick questions first, in plain words.

## Example

You type:

> make me a picture of a cozy coffee shop for my instagram story

It asks which tool you're using. You say Midjourney. You get:

```
cozy corner coffee shop, latte on a wooden table, morning light through the window, warm film photo style, calm mood, close-up --ar 9:16 --no text, watermark
```

## How to install it

In the Claude app:

1. Go to Settings > Capabilities and turn on code execution. In newer layouts it's called "Create and edit files".
2. Zip the `prompt-master` folder. Zip the folder itself, not just the files inside.
3. Go to Customize > Skills.
4. Click +, then Create skill, then Upload a skill.
5. Pick your zip file and switch the skill on.

In Claude Code, put the folder at `~/.claude/skills/prompt-master/`.

## Credit

Adapted from [prompt-master](https://github.com/nidhinjs/prompt-master) by Nidhin Joseph Nelson, MIT license. What I changed:

- Cut the tools down to Claude, ChatGPT, Lovable, and image tools
- Took out coding tools like Cursor and anything that assumes you code
- Took out the model-by-model settings
- Rewrote the questions it asks in plain words
- Rewrote the Lovable part so you never pick a tech stack
- Put everything in one file instead of separate reference files
- Swapped the emoji labels for plain text

The core method stays the same.
