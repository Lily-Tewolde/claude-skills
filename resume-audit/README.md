# resume-audit

This skill helps Claude tailor your resume to one job post and check it before it goes out. It's the skill version of my [Resume Audit guide](https://github.com/Lily-Tewolde/ai-guides/tree/main/04-resume-audit), so there's no file to download and drop in each time. It follows the same steps:

0. Pick one direction, if you're aiming at more than one kind of role
1. Gather the job post, your rules, your bullet bank and your resume
2. Check the post is still open, the location works and the role is a real fit
3. Map every requirement and responsibility to proof, and turn the gaps into questions
4. Mirror the post's true keywords
5. Swap in your best bullets, outcome and number first
6. Fit it to one page
7. Keep your titles the same as LinkedIn
8. Format it in your own template
9. Run the checks, save, and show you before anything goes out

It also covers:

- a first build when you don't have a bullet bank yet, even from just a PDF
- helping a friend or family member, with a handoff they can finish on their own
- drafts that live in Google Docs
- matching your LinkedIn afterwards

## How it works

Say something like: "Tailor my resume for [ROLE] at [COMPANY]. Here's the job post: [PASTE JOB POST]"

Claude asks for:

- the full job post
- your resume, as a .docx or just a PDF
- your My Resume Rules.md and Bullet Bank.md, if you have them

The first time, it helps you fill in My Resume Rules.md from the blank templates in the `templates` folder. It won't invent numbers or claim anything you haven't done, and nothing gets uploaded or sent without your OK.

It works best where Claude can read and save files, like Claude Code or Cowork. In a plain chat, it asks you to paste your files in, gives you the resume as text to put into your template, and hands back the updated files to save at the end. You check the page length yourself.

## How to install it

In the Claude app:

1. Go to Settings > Capabilities and turn on code execution. In newer layouts it's called "Create and edit files".
2. Zip the `resume-audit` folder. Zip the folder itself, not just the files inside.
3. Go to Customize > Skills.
4. Click +, then Create skill, then Upload a skill.
5. Pick your zip file and switch the skill on.

In Claude Code, put the folder at `~/.claude/skills/resume-audit/`.

## What's different from the guide

- The blank My Resume Rules.md, Bullet Bank.md and Decision Log.md come inside the skill, in `templates`.
- If Claude can't read or save files, it asks you to paste them in, gives you the resume as text to put into your template, turns its comments into a list of questions, and hands back every updated file.
- Everything else matches resume-audit.md in the guide.
