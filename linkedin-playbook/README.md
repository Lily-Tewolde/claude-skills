# linkedin-playbook

This skill helps Claude update your LinkedIn profile so recruiters can find you. It's the skill version of my [LinkedIn playbook guide](https://github.com/Lily-Tewolde/ai-guides/tree/main/02-linkedin-playbook), so there's no file to download and drop in each time. It follows the same 5 steps:

1. Headline and job titles
2. About and experience, written as a story with no numbers, and Focus Areas worded from the job posts
3. Top skills, the exact skills for every entry, and Open to Work
4. Featured section
5. 9 post ideas for your first 3 weeks of posting

It also covers:

- early career profiles: Experience, Education, Projects, licenses and honors
- your photo and banner
- the profile basics recruiters filter by, like a city for your location
- recommendations
- keeping your resume and LinkedIn in sync, skills and tools included
- helping a friend or family member, with a handoff written to them and a private mock of their finished profile
- a check before anything comes back to you

## How it works

Say something like: "Update my LinkedIn for [TARGET ROLE]. Here's my profile [LINK OR SCREENSHOTS], my resume and 2 to 3 job posts: [PASTE JOB POSTS]"

Claude asks for:

- your profile, as a link or screenshots
- your resume
- the role you want
- 2 to 3 real job posts

If you ran the [resume-audit](../resume-audit/) skill first, it starts from your new resume. It writes everything out for you to change yourself and never edits, posts or publishes anything on your profile. It won't put any numbers on LinkedIn except your dates, or claim anything you haven't done.

It works best where Claude can open your profile in your browser and read your files, like Claude Code or Cowork. In a plain chat, it asks for screenshots and for your files pasted in, and gives you the mock as HTML to save and open yourself.

Don't skip Step 5. Posting took my search appearances from around 40 a week to over 200 in a month.

## How to install it

In the Claude app:

1. Go to Settings > Capabilities and turn on code execution. In newer layouts it's called "Create and edit files".
2. Zip the `linkedin-playbook` folder. Zip the folder itself, not just the files inside.
3. Go to Customize > Skills.
4. Click +, then Create skill, then Upload a skill.
5. Pick your zip file and switch the skill on.

In Claude Code, put the folder at `~/.claude/skills/linkedin-playbook/`.

## What's different from the guide

- If Claude can't open your profile or read your files, it asks for screenshots and for your resume files pasted in, asks about any award it can't look up, marks what comes off with "Delete:" so it survives a paste, and gives you the mock as one HTML file with steps to save and open it yourself.
- Everything else matches linkedin-playbook.md in the guide.

## Credit

The Extras are adapted from Param Choudhary's [linkedin-profile-optimizer](https://github.com/Paramchoudhary/ResumeSkills/tree/main/skills/linkedin-profile-optimizer) skill, MIT license.
