---
name: resume-audit
description: Resume builder and resume tailoring for one job post. Use to tailor my resume, audit a resume or help a friend with theirs. Checks the fit, maps the post to proof and keeps it to one page.
license: MIT
---

# Resume Audit

Tailor a resume to one job post, for the user or for someone they're helping. Check the fit, map the post to proof, swap in the best bullets, fit it to one page and run the checks before anything goes out. Each person gets their own folder with their own **My Resume Rules.md**, so nobody's facts get mixed up. The first time, help fill that file in, and if there's no bullet bank yet, start with a first build.

Each step is tagged:
- 🤖 **Auto**: Claude does this for you
- 🙋 **You decide**: Claude asks, you answer

> **Golden rule:** The facts don't move. Claude chooses and orders approved bullets, and nothing gets uploaded or sent without an OK.

---

## How to use this skill

You (Claude) are tailoring one person's resume to one job post. The person is whoever the resume belongs to: the user, or someone the user is helping. This skill is your operating spec.

1. **Follow this whole skill, every time.** Then read My Resume Rules.md in the person's folder. The written rules outrank anything you remember.
2. **If My Resume Rules.md doesn't exist yet,** make it in the person's folder from the blank template in this skill's `templates` folder, or with the same sections if the template isn't there: direction, standard resume, template, bullet bank, story bank, folder for tailored versions, canonical numbers, never write, titles, names I can't share and house style. Help fill it in before you tailor anything.
3. **If there's no bullet bank yet,** do the first build below once Step 2 says the role is a fit, before Step 3.
4. **Do the steps in order.** Stop after Step 2 if the role isn't a fit. Stop any time you need facts only the person can give. When the resume belongs to someone else, those questions go through the user. If the user can't answer, don't stop: leave a highlighted `[__]` blank and a comment asking the person, and carry on. Anything only the person can approve, like new wording, stays ★ until they OK it. Never mark it approved for them.
5. **If the person keeps a Decision Log.md,** add an entry for every decision made: the date, the decision and why. Always keep one when the resume belongs to someone else, because the handoff is built from it.
6. **Keep the person's details in their own folder** (see Keeping it private).
7. **If the resume belongs to someone else,** finish with the handoff below, so they can carry on without the user.
8. **Never upload, submit or send anything.** Show the PDF and wait.

---

## The person's folder

One folder per person, even when the resume is your own:

```
Job search/
├── resume-audit.md
└── [Person's name]/
    ├── My Resume Rules.md
    ├── Bullet Bank.md
    ├── Decision Log.md       (optional)
    ├── Story bank
    ├── Standard resume.docx
    └── [Company]/
        └── version history/
```

Blank versions of My Resume Rules.md, Bullet Bank.md and Decision Log.md are in this skill's `templates` folder.

**No file access?** In a chat where you can't read or save the person's files:

- Ask the user to paste in every file the person already has: My Resume Rules.md, Bullet Bank.md, Decision Log.md and their story bank. Never start a blank one over one that exists.
- Ask for the resume as pasted text. Say plainly that you can't build the .docx or check the page here. Give the resume back as text, in the order of the person's template, for them to put into it, and mark the one-page check as theirs to do.
- Google Docs comments become a numbered list of questions, each with the line it's about, for the user to add.
- If you can't open a job post link, ask for the full post pasted in.
- At the end, give them the full text of every file you made or changed, so they can save it.

## Keeping it private

When the resume belongs to a friend or family member:

1. Their details stay in their own folder, next to their My Resume Rules.md.
2. Their details never go into a public repo, an issue or a shared doc without them knowing.
3. Any example you share about what you learned is made up.

---

## First build: no bullet bank yet 🤖 then 🙋

"Swap, don't rewrite" needs a bank of approved bullets. The first time, there isn't one, so once Step 2 says the role is a fit, build it from the resume the person already has. If it's only a PDF, start with the PDF steps in Step 1.

1. Rewrite every bullet into X-Y-Z (see Step 5).
2. Put a highlighted `[__]` blank wherever a number is missing. Never guess a number. The same goes for any other missing fact, like a role's location or a LinkedIn link. If a line has no result at all, the outcome is a blank too: ask what changed because of the work, and never make one up.
3. Mark every line ★, because none of them are approved yet.
4. Ask the person for the missing numbers and facts, and for their OK on each line.
5. Save it all as their Bullet Bank.md, grouped by role and tagged with what each bullet proves.
6. Write the summary in the summary shape (Step 5), mark both lines ★ and save it at the top of Bullet Bank.md. An old objective or summary doesn't count as approved.

Every tailor after this one is a swap, and the summary only changes its labels and nouns.

## Step 0: Pick a direction 🙋

Only when the person is aiming at more than one kind of role, like two master resumes with two different objectives.

- Compare the paths on pay, licensing and which title each one leaves on their LinkedIn.
- Recommend one direction and one title, and say why.
- The person decides. Write the direction in My Resume Rules.md.

## Step 1: Gather everything 🤖

- Save the full job post word for word in the company folder, because postings come down.
- **If you can't open the link,** ask the person to paste the full post into the chat, or to open it in their browser so you can read it there. Then save it word for word. Don't work from a summary or a partial copy.
- Read My Resume Rules.md and Bullet Bank.md before touching anything.
- Use the standard resume .docx as the base unless the person says otherwise. Check it's the right file by its size and date, not its name.
- **Only a PDF?** That's enough to start:
  1. Pull the text out of the PDF now.
  2. Once Step 2 says the role is a fit, build the editable .docx from the template the person chose (see Step 8). If they don't have one, ask them to pick one. Never make one up.
  3. Don't type anything in by hand. The new version starts as an exact copy of the PDF text, and the rewriting happens in the first build.

  Don't build anything else yet. Once Step 2 says the role is a fit, do the first build.
- Ask what the recruiter said they want, if anything. One line from a recruiter can change which bullets lead.
- If there's an application form, check what it asks before drafting.
- Note anything else the post asks for, like a cover letter, a transcript or references.
- Say what you've got and what you still need. Don't edit yet.

## Step 2: Check the fit 🙋

Before checking the must-haves, confirm:

1. **The post is still open** and taking applications.
2. **The location works,** whether it's on site, hybrid or remote.
3. **The person can work there,** including any work authorization or visa the post asks for.

If any of these fail, stop and tell the person. Don't map, tailor or build anything.

Then:

- Check the must-haves against the person's real background. Years can flex by about a year.
- If the core of the role is a domain or stack that isn't anywhere on the resume, say so and suggest skipping it.
- Say whether the standard resume is good enough or tailoring gives a real edge, and why. The person decides.

## Step 3: Map the post to proof 🤖

- **Make a coverage table.** Every requirement and every responsibility in the post, word for word, one row each. Must-haves, nice-to-haves and responsibilities all go in.
- **Mark each row covered, partial or gap,** with the bullet that covers it.
- **Gaps become questions for the person.** They never become new lines on the page, especially in a field you don't know well enough to judge what's too senior to claim. Don't add any line that admits a gap either.
- Flag gaps that might be work the person did but never wrote down. Those are questions too, not guesses.
- Flag it if the base leans the wrong way for this post.
- **Back every skill.** Every skill on the skills line needs a bullet somewhere on the page that shows it. Basic tools like Excel are the exception.

Example, made up:

| From the post | Status | Proof on the page |
|---|---|---|
| Coordinate vendor contracts for events | Covered | Cut vendor costs 12% by renegotiating catering and AV contracts across 40 events a year |
| Manage event budgets | Partial | Tracked spend on a $20K conference, with the budget owned by the director |
| Experience with event registration software | Gap | Question for the person |

## Step 4: Mirror the true keywords 🤖

- Pull the exact title, the phrases in the must-haves and every tool named.
- Mirror them only where they're true, in 4 places:
  1. The first summary label
  2. The summary nouns
  3. The skills lines
  4. The nouns inside a bullet
- If a phrase would sound weird said out loud across a table, leave it out.
- Fallback: list the words the post repeats with how many times each shows up, and check which ones are missing. The true ones go in the 4 places above.

## Step 5: Swap the bullets 🤖

- **Swap, don't rewrite.** Pick from the bullet bank and order them. The facts don't move. No bank yet? Do the first build.
- **Counts:** current role 4 to 5, earlier roles 2 to 3. Never 6, never a single-bullet role.
- **Order:** inside each role, the best match for this post goes first.
- **Bullets stay inside their own role.**
- **X-Y-Z:** outcome and number first, then how.
- **Two lines max,** no periods at the end, no I, me, my, we or our.
- **Strongest opening verb,** and no two bullets in a row with the same one, across roles too. Fix a repeat by reordering, not rewording.
- **Weak openers to replace:** Caught, Scored, Ran, Helped, Supported, Assisted, Worked on. Lead with the real outcome instead: "Caught 7 pricing errors" becomes "Blocked 7 pricing errors from shipping".
- **Nouns can change** to match the post's wording. Facts can't.
- **New bullets:** write them X-Y-Z from the story bank or the person's facts, mark them ★ in the bank, and show the person before they go on anything.
- **Stars stay in the bank.** The ★ never shows on the resume itself.
- **New grads:** school and capstone projects go under a Projects section, not Experience, unless they were paid. That way the only job titles on the page are real ones that match LinkedIn.
- **Don't claim more authority than the person had.** For junior or regulated roles, bullets say what they actually did. An engineer in training prepares and checks the work, and the engineer of record signs off. A staff accountant prepares the statements, and the CPA signs them.
- **Skills:** rebuild the categories around the post's wording. Every skill listed needs a bullet that shows it (Step 3).

**Any field, not just product**

- **Section names follow the field,** like Engineering Experience and Engineering Projects for engineers, or Clinical Experience for nurses.
- **Licences go with Education,** written the same way as the school line.
- **Awards stay only if they're in that field.** Things like a driver's licence don't go on at all.

**The summary**

- Exactly 2 bullets, each with a short bold label that names a kind of person, like "Growth Product Manager" or "Technical Builder". If a label runs long, cut it.
- The first label matches the post's title.
- The first bullet opens with who the person is, like "Bilingual operations lead".
- High level, no numbers. Each one can run 2.5 to 3 lines.
- Never repeat a bullet from further down the page.
- Only swap the two labels and the nouns. Leave the rest of each sentence exactly as it is. Rewriting the clauses reopens wording that's already approved, and that's where tailored summaries start to read strangely.

## Step 6: Fit the page 🤖 then 🙋

- **Always one page.** Check the page count in the final format, Google Docs or the PDF, whichever is going out. Different apps lay out pages a little differently, so a .docx that fits can spill over once it's converted. Don't guess. If you can't open the final format, say the page count is unchecked and ask the person to check it. Never mark it passed.
- **When it runs over, fix it in this order:**
  1. Tighten the spacing
  2. Tighten the wording, never the facts
  3. Cut the weakest bullet, from the bottom of a role
- **Never shrink the font** below the person's minimum in My Resume Rules.md, or 10pt if they haven't set one.
- No two bullets that tell the same result twice, and no bullet without a number on the version that goes out.
- If the only way to fit is choosing between two roles, show the person the options with the page result of each and let them pick.

## Step 7: Keep the titles 🙋

- Titles stay the same as LinkedIn and the standard resume. You can suggest a change and say why, but don't make it.
- When a title or date is unclear, check LinkedIn.
- Flag any internal or level title a recruiter wouldn't type into a search bar.
- Use the role exactly as posted in the file name: `Firstname Lastname - <Company> (<Role as posted>).pdf`

## Step 8: Format the page 🤖

- **Build from the person's own template .docx,** never a made-up layout.
- **Build in the .docx first.** Only convert it to a Google Doc afterwards, if that's where it's going to live. Right-aligned dates need tab stops, and those don't come through when you build in Google Docs from scratch.
- Follow the house style below, plus anything My Resume Rules.md sets differently.
- For cold applications through a job board: single column, no tables, nothing in the header or footer.
- Check the version that's going out, not the working copy.

## Step 9: Check, save and show 🤖 then 🙋

Run every check and say which passed and which didn't:

1. One page, checked in the final format (Google Docs or the PDF, whichever is going out). If you couldn't open it, this is unchecked, not passed
2. No heading stranded at the bottom of a page
3. No em dashes, and en dashes only in date ranges
4. Numbers match the canonical numbers in My Resume Rules.md
5. Nothing from the Never write list
6. Every ★ bullet has the person's OK, and no ★ shows on the page. On a draft going back to the person, every line still waiting for their OK has a comment asking them to check it
7. No names from the Names I can't share list
8. No repeated opening verbs in a row, across roles too
9. No periods at the end, no first person, no experience bullet over 2 lines
10. Summary unchanged except the labels and nouns, and it follows the summary shape in Step 5. On a first build the summary is new, so it's ★ instead
11. Font no smaller than the person's minimum, and any overflow fixed in order: spacing, then wording, then the weakest bullet
12. No `[__]` blank on the version that goes out. On a draft going back to the person, every blank is still highlighted
13. Every requirement and responsibility from the post is in the coverage table, and every gap went to the person as a question, not onto the page
14. Every skill on the skills line has a bullet that shows it, except basic tools like Excel

Then:
- Save the .docx and .pdf in the company folder, and move any older version to `version history/`. In Google Docs, edit in place instead
- Add new bullets to the bank and new facts to the story bank
- If there's a Decision Log.md, check every decision from this tailor is in it
- Show the person the PDF and **wait**. Don't upload or send anything until they say so

**Then match LinkedIn**, after the person has seen the PDF. In a handoff, these go into the next steps on the second tab instead:

1. If the linkedin-playbook skill is installed, offer to run it next to update the profile to match. If it isn't, or for someone doing it on their own, point them to the [LinkedIn playbook](https://github.com/Lily-Tewolde/ai-guides/tree/main/02-linkedin-playbook) guide and its file, linkedin-playbook.md. Both start from this resume's decisions and say what changed because of them.
2. Check the job titles, companies and dates match the resume exactly.
3. Check skills and tools both ways. If the About or Skills on LinkedIn mention software that isn't on the resume, or the other way around, flag it and let the person decide which one changes.
4. Move school and capstone projects into LinkedIn's Projects section, the same way they stay out of Experience on the resume. Link each one to the school with "Associated with", tag the skills and add media. LinkedIn sections can't be moved, so the best project also goes in Featured.

---

## Handing it off to someone else 🙋

When the resume belongs to someone the user is helping, it doesn't end with a finished draft. They need to be able to carry on and check their own resume without the user.

1. **Open or close with a note.** In the user's voice: they're not an expert in this person's field, so this is mostly formatting and a strong direction, and the person should adjust anything that seems off.
2. **Comments ask them to do the work.** Write "Add it if you've done it", never "Tell me and I'll add it".
3. **A second tab in the doc** (or a separate doc, if it isn't in Google Docs) that:
   - explains every decision and why, from the Decision Log.md
   - teaches them how to write and check their own X-Y-Z bullets
   - ends with what they need to do next, including every ★ line waiting for their OK and anything else the post asks for, like a cover letter

   Example next steps, made up:
   - Fill in the 3 blanks marked `[__]` with real numbers
   - Check every ★ bullet in your Bullet Bank.md is true, then remove the star
   - Update your LinkedIn headline to match the new title
4. **Their details stay private** (see Keeping it private).

## If the draft lives in Google Docs

- Build in the .docx first and convert it afterwards (see Step 8).
- **Edit in place.** Edit that one doc instead of making new copies. Docs already keeps the version history.
- **Recheck highlighted blanks after every edit.** Editing text can strip the highlight from a `[__]` blank that's waiting for the person, and then it's easy to miss.
- Put open questions in as comments anchored to the line they're about. One overall comment on the name first, then one comment per fix.
- Afterwards, read the comments back and check every anchor landed on the right text. A comment can land on the wrong line if the page scrolls while you're typing.
- When a .docx gets imported, check for stray rules or empty bullets under the headings.

## House style

The default for everyone. Anything set in My Resume Rules.md wins.

1. **Length:** always one page (Step 6)
2. **Font and margins:** whatever My Resume Rules.md says. If it's blank, 10pt body in a standard font, like Calibri, with 10pt as the minimum. Never shrink below the person's minimum to make something fit
3. **Header:** name, then one contact line: phone • email • LinkedIn. No location. Email and LinkedIn as live links, the phone as plain text
4. **Colour:** one accent colour, only on the name and the section headings. Nothing else is coloured except the links
5. **Section headings:** all caps and bold, with a thin rule the full text width underneath. Make the rule a paragraph bottom border, not a drawn line, so it moves with the text. Set every heading to keep with the next line
6. **Role block:** role title bold on the left with the dates bold and right-aligned on the same line, then the company in italics on the left with the location in italics and right-aligned on the same line, then the bullets
7. **Dates:** an en dash in date ranges (June 2022 – Present). No em dashes anywhere
8. **Summary:** 2 bullets, each opening with a bold label and a colon
9. **Skills:** bulleted, with bold category labels
10. **Education:** school bold on the left, degree right-aligned on the same line
11. **No periods at the end** of any bullet, summary line or skills line
12. **Cold applications through job boards:** keep it simple so the parsing software reads it the way a person would
    - single column
    - no tables
    - standard section headings
    - no text in headers or footers
    - abbreviations spelled out once

## Mistakes to watch for

These keep coming up. Check for them before anything goes back to the person.

1. **Rewriting the summary** instead of only the labels and nouns
2. **Reordering while making a swap.** A request for one swap shouldn't come back with a reorder too. Propose reorders separately
3. **The same opening verb back to back,** often across a role boundary
4. **A stranded heading** at the foot of a page
5. **AI-sounding trailing clauses.** When one gets fixed on one version, it's often still sitting in the others
6. **Number drift.** A figure from one role creeping into another, or an old master with numbers that contradict the current one
7. **Periods at the end** creeping back
8. **Weak openers** like Caught and Scored
9. **Pointer clauses** that only refer back to something earlier in the bullet
10. **Too much mechanism** that belongs in the interview
11. **Inherited false claims.** A wrong line in one document gets copied into the next ones before anyone checks it
12. **Trusting a filename** to say what's inside
13. **Reusing a tailored base without re-weighting it** for the new post
14. **New bullets that lead with the activity** instead of the outcome
15. **Claiming what the post lists but the person hasn't done**
16. **Tailoring before checking the fit**

---

## The rules that keep it honest

- **The facts don't move.** Choose and order, don't invent.
- **No gaps on the page, and no lines admitting them.**
- **Never change a title** without the person saying so.
- **New bullets need the person's OK** before they go anywhere.
- **Someone else's details stay in their folder,** and they get a handoff they can follow on their own.
- **Never upload, submit or send.** The person does that.

---

The full guide, with a prompt for every step and a made-up worked example: [Resume Audit](https://github.com/Lily-Tewolde/ai-guides/tree/main/04-resume-audit)

*Built from my own job search: check the fit → map it to proof → swap the bullets → fit the page → check before it goes out.*
