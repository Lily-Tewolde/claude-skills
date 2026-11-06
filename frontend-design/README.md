# frontend-design

This skill helps Claude design pages and apps that don't look like the default AI template. It asks which vibe you want, so you don't need design words.

## The vibes

- **Soft**: calm and light, gentle type, muted colours, lots of room.
- **Editorial**: polished like a magazine, strong headlines, mostly neutral colours, a clean grid.
- **Playful**: fun and bright, chunky type, cheerful colours, loose layout.
- **Bold**: loud and confident, huge heavy type, high contrast, big blocks.
- **Cozy**: warm and homey, soft readable type, earthy colours, comfortable spacing.

Or describe your own, or name a site you like.

## How to install it

In the Claude app:

1. Go to Settings > Capabilities and turn on code execution. In newer layouts it's called "Create and edit files".
2. Zip the `frontend-design` folder. Zip the folder itself, not just the files inside.
3. Go to Customize > Skills.
4. Click +, then Create skill, then Upload a skill.
5. Pick your zip file and switch the skill on.

In Claude Code, put the folder at `~/.claude/skills/frontend-design/`.

## Credit

Adapted from [frontend-design](https://github.com/anthropics/skills/tree/main/skills/frontend-design) by Anthropic, Apache-2.0 license.

What I changed:

- Added a "Pick a vibe" section with five starter vibes.
- Told Claude to ask which vibe you want if you haven't said.
- Added one sentence about vibes to the skill description.
- Swapped em and en dashes for other punctuation.
