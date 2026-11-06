# linkedin-playbook

This skill helps Claude rewrite your LinkedIn profile so recruiters can find you. It's the skill version of my [LinkedIn playbook guide](https://github.com/Lily-Tewolde/ai-guides/tree/main/02-linkedin-playbook), and it follows the same 5 steps:

1. Headline and job titles
2. About and experience, written as a story with no metrics
3. Top skills and Open to Work
4. Featured section
5. 9 post ideas for your first 3 weeks of posting

It also covers:

- your photo
- your banner
- recommendations
- keeping your resume and LinkedIn in sync

## How it works

Claude asks for:

- your resume
- screenshots of your profile
- the role you want
- 2 to 3 real job posts

Then you pick step by step or all at once. It won't invent numbers or experience, and it keeps your job titles truthful.

Don't skip Step 5. Posting took my search appearances from around 40 a week to over 200 in a month.

## How to install it

In the Claude app:

1. Go to Settings > Capabilities and turn on code execution. In newer layouts it's called "Create and edit files".
2. Zip the `linkedin-playbook` folder. Zip the folder itself, not just the files inside.
3. Go to Customize > Skills.
4. Click +, then Create skill, then Upload a skill.
5. Pick your zip file and switch the skill on.

In Claude Code, put the folder at `~/.claude/skills/linkedin-playbook/`.

## Credit

The Extras are adapted from Param Choudhary's [linkedin-profile-optimizer](https://github.com/Paramchoudhary/ResumeSkills/tree/main/skills/linkedin-profile-optimizer) skill, MIT license.
