# social

This skill helps Claude write hooks, short video scripts, captions and carousels for TikTok, Instagram and LinkedIn. It can also turn one idea into posts for all three.

## Example

You type:

> I used AI to plan a week of dinners from what's in my fridge.

You get three hooks and a caption, like:

> **Hook:** "I spent $400 on groceries last month and told myself, mmm, I need to plan a little better."
>
> **Caption:** I asked AI for five dinners from my fridge. Here's exactly what I typed. Save this for grocery day. #ai #mealplanning #budgeting

## How to install it

In the Claude app:

1. Go to Settings > Capabilities and turn on code execution. In newer layouts it's called "Create and edit files".
2. Zip the `social` folder. Zip the folder itself, not just the files inside.
3. Go to Customize > Skills.
4. Click +, then Create skill, then Upload a skill.
5. Pick your zip file and switch the skill on.

In Claude Code, put the folder at `~/.claude/skills/social/`.

## Credit

Adapted from [social](https://github.com/coreyhaines31/marketingskills/tree/main/skills/social) by Corey Haines, MIT license. What I changed:

- Cut it to TikTok, Instagram and LinkedIn. X, Facebook and Telegram are gone.
- Added hook patterns in a casual creator voice.
- Set video scripts to about 60 to 75 seconds.
- Removed links to other skills, so it works on its own.
- Folded the reference files I kept into one SKILL.md.
- Dropped social listening and the X algorithm notes.
