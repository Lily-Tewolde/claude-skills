---
name: linkedin-playbook
description: LinkedIn profile optimizer for one target role, from headline and About to skills, Featured and posts. Use to update my LinkedIn, match it to my resume or help a friend with theirs.
license: MIT
---

# LinkedIn Playbook

Update one LinkedIn profile for one target role, for the user or for someone they're helping. Read the profile, then work through the 5 steps and the extras: headline and titles, About and experience, skills and Open to Work, Featured, posts, and the profile basics recruiters filter by. Write everything out for the person to change themselves. Never edit, post or publish anything on the profile.

Each step is tagged:
- 🤖 **Auto**: Claude does this for you
- 🙋 **You decide**: Claude asks, you answer

> **Golden rule:** Claude writes, you change the profile. Nothing goes on LinkedIn that isn't true, and no numbers go on it at all.

---

## How to use this skill

You (Claude) are updating one person's LinkedIn profile for one target role. The person is whoever the profile belongs to: the user, or someone the user is helping. This skill is your operating spec.

1. **Follow this whole skill, every time.**
2. **Do the steps in order.** Stop any time you need facts only the person can give. When the profile belongs to someone else, those questions go through the user. Anything only the person can decide, like which headline or whether a role stays, goes back to them as a clear choice with your recommendation. Never decide it for them.
3. **Never post, publish or change anything on the person's profile.** Even if you can open it in the browser, don't click edit, save or post. The person makes every change themselves.
4. **Read the live profile when you can.** If you can open it in the browser, read it there. Screenshots are the fallback.
5. **If the Resume Audit ran first, start from the resume.** Use its titles, dates and decisions, from the person's My Resume Rules.md and Decision Log.md if they have them. Say what changes on LinkedIn because of them.
6. **No numbers anywhere on the profile,** except the dates on each entry. The person's numbers are context for you, not copy.
7. **If the profile belongs to someone else,** write it as a handoff they can follow on their own (see Doing this for someone else).
8. **Run the check at the end** before anything goes back to the person.

---

## Before Step 1: Gather everything 🤖

- **The profile.** Read it live in the browser if you can. Otherwise ask for screenshots of the header, About, every role, Education, Projects, Licenses & certifications, Honors & awards, Skills and Featured.
- **The resume.** If the Resume Audit ran first, use that version, plus My Resume Rules.md, Decision Log.md and Bullet Bank.md. A line still marked ★ in Bullet Bank.md is waiting for the person's OK, so anything you write from it waits for the same OK. Say so, and never treat it as confirmed.
- **2 to 3 full job posts** for the target role, word for word. If you can't open a link, ask the person to paste the full post. Every keyword choice comes from these.
- **The target role,** as recruiters search it.
- Say what you've got and what you still need. Don't write anything yet.

**No browser or file access?** In a chat where you can't open the profile or the person's files:

- Ask for the screenshots above, or the text of each section pasted in.
- If the Resume Audit ran first and its files aren't already in this chat, ask the user to paste in the resume, My Resume Rules.md, Decision Log.md and Bullet Bank.md. Don't guess what's in them.
- If you can't look up an award, ask the person what it is and who it goes to.
- For someone else's profile, write "Delete:" in front of anything that comes off, since crossed-out text is lost when it's pasted. Give the mock as one complete HTML file in a code block, and tell the user how to save it: as plain text, in a file whose name ends in .html, then open it in their browser. Never publish it.

## Step 1: Headline and titles 🤖 then 🙋

- **Headline:** 5 options in this format, each under 100 characters: `Role | Keyword · Keyword · Keyword | Credential`. LinkedIn allows 220, but only about the first 100 show in search and on mobile.
- `Role` is the target role, the way recruiters search it.
- Use keywords that show up in the job posts and that a recruiter would actually search. No buzzwords, no numbers.
- **The credential is real.** Only use a licence or certification the person actually holds. If they don't have one yet, leave that part off.
- **Titles:** flag any job title that's vague, internal or creative, and give the standard title recruiters search instead. If the Resume Audit ran first, titles match the resume exactly.
- The person picks the headline and decides on every title change.

## Step 2: About and experience 🤖 then 🙋

**The About**

- A story, not a summary. 4 to 6 short paragraphs:
  1. An opening hook
  2. The thread connecting their career
  3. What they do now and how they think about the work
  4. One line on what they're open to next
- No bullets, no numbers. Weave in the keywords a recruiter searches for, but keep it sounding like a real person talking.

**Each role**

- One short narrative paragraph: what they owned and how they worked.
- Then the Focus Areas:
  1. **Format.** Each one is the skill a recruiter searches, then the specifics in brackets.
  2. **Wording comes from the job posts.** Pull it from the requirements and responsibilities, and only where it's work the person has actually done.
  3. **The count follows the role.** 4 to 12, depending on how important the role is to where they're going.
  4. **"Add only if true" list.** Anything the posts ask for that the person hasn't confirmed goes on a separate list for them, never on the profile.
  5. **No numbers means any number.** That includes things that aren't results, like a team size in a project description.

Example, made up:

- Event logistics (vendor contracts, venue sourcing, run-of-show planning)
- Budget tracking (spend reports, invoice reconciliation, cost forecasts)

## If the person is early in their career 🙋

LinkedIn doesn't let anyone move sections around, so Projects always sits low on the page. These keep Experience for real jobs and still get the projects seen.

1. **Experience is for real jobs.** Ask whether unrelated roles, like seasonal or part-time work, stay or go. School projects never go in Experience.
2. **One Education entry per degree they actually earned.** No description or Focus Areas. An earlier program that didn't lead to the degree comes off, and the About tells that story instead.
3. **Projects stay in the Projects section.** Link each one to the school with "Associated with", tag the skills used, and add media once it exists.
4. **Featured is how a project gets seen first,** since the Projects section can't be moved up.
5. **Licenses & certifications.** Add any the person holds. Recruiters filter by them.
6. **Honors & awards.** Look up what each award is first. Keep the ones that are rare, competitive or in their field. Cut general scholarships for entry-level roles.
7. **The About matches the level they're aiming for.** Lead with the work they do now and what their background adds. Use school work as evidence, not as a chapter in school-to-job order.

## Step 3: Skills and Open to Work 🤖 then 🙋

**Top 5**

- Pick 5 Top skills for the About section, and put the same 5 first in the Skills section, since only the first few show without clicking.
- **Be honest about the ranking.** You can't see LinkedIn's search data. Say the ranking comes from how often each skill shows up across the job posts.

**Skills on every entry**

1. **List the exact skills for every entry.** Each experience, education and project entry gets its own list, using names recruiters actually search.
2. **Say how to add them.** Type each one in and pick LinkedIn's exact match from the dropdown. If it doesn't come up, pick the closest suggestion.
3. **Only skills they've used** in that role or project.
4. **Prune the Skills section.** Remove skills that don't fit the target role, but keep all the software and tools they've actually used. A tool they've never used comes off, like any other skill that isn't true.

**Open to Work**

- 5 target job titles
- Remote on if they want it, and which employment types
- **Recruiters only when they're still employed,** and say why. LinkedIn tries to hide it from their own company's recruiters, but it can't promise it.

## Step 4: Featured 🤖 then 🙋

- Give 3 Featured ideas they could make in under 2 hours each, ranked by how much they'd impress a recruiter.
- For each one: what it contains, why it works as proof, and what tool or format to make it with.
- Best: a 2 to 3 minute video walking through something they built or shipped. Also good: a strong post in their field, a live tool or a portfolio link.
- Early career: their best project goes here (see above).
- **Employer and client work stays out** unless the employer says it's okay.

## Step 5: Posts 🤖

- 9 post ideas, 3 a week for 3 weeks, from their real work.
- Mix three formats: a lesson from real work, a behind-the-scenes look at how they work, and a simple tip or framework from their field.
- A scroll-stopping first line for each. No generic career advice.
- **Employer and client work stays out** unless the employer says it's okay.

## Extras 🤖 then 🙋

- **Photo:** a clear headshot where their face fills most of the frame. Good light, a plain or on-brand background, dressed the way they would for work in their field.
- **Banner:** 1584 × 396 pixels, and one that fits their field. Not blank. One short line on it about what they do is optional.
- **Location is a city,** not just a country. Recruiters filter by city.
- **The verification badge,** with a work email or ID.
- **Media on entries,** like a link, PDF or video on the role or project it belongs to.
- **Languages,** every one they speak, at their real level.
- **Recommendations: give one first.** People are far more likely to write one back. Ask former managers, close teammates and clients, say what you'd love them to mention, and ask right after wrapping something good together. Aim for 5 to 10 over time. Draft the ask in under 80 words, casual, not like a template.
- **Connections.** Grow them at their current company, their school and the companies they're applying to.
- **Resume sync.** Job titles, companies and dates match the resume exactly. The numbers stay on the resume.
- **Skills and tools match both ways.** If the About or Skills mention software that isn't on the resume, or the resume has a tool LinkedIn doesn't, flag it and let the person decide which one changes.

---

## Doing this for someone else 🙋

When the profile belongs to someone the user is helping, they're the one who has to make every change. Write it all to them, so they can follow it on their own.

1. **Written to them, in the user's voice.** Second person, like "I picked this headline for you" or "delete these three roles". No AI-looking labels or numbered tags.
2. **Clear change, keep and delete.** Mark what to change, leave everything else alone, and cross out what comes off.
3. **Open or close with a note.** The user isn't an expert in their field, so this is mostly formatting and a strong direction, and they should adjust anything that seems off.
4. **A visual mock of the finished profile.** An HTML page laid out like their profile, with the user's notes beside each section and a switch to hide the notes, so they can see it the way a recruiter would. It's a file they open on their own computer, never a page published online.
5. **Employer and client work stays out** of Featured and posts unless the employer says it's okay.
6. **Open to Work is set to Recruiters only while they're still employed,** with the reason: LinkedIn tries to hide it from their own company's recruiters, but it can't promise it.
7. **Their details stay private.** They stay in their own folder, never go into a public repo, an issue or a shared doc without them knowing, and any example shared about what was learned is made up.

---

## Check before it goes back 🤖 then 🙋

Run every check and say which passed and which didn't:

1. Headline under 100 characters, in the format, with a credential the person actually holds
2. Every job title is one a recruiter would search, and matches the resume
3. No numbers anywhere, including team sizes and counts that aren't results
4. The About is a story with no bullets, at the level they're aiming for
5. Every Focus Area is in the format, worded from the job posts, and only covers work they've done
6. Anything unconfirmed is on the "add only if true" list, not the profile
7. Every experience, education and project entry has its exact skills, and only ones used there
8. The Top 5 says the ranking comes from the job posts
9. Location is a city
10. Titles, companies, dates, skills and tools match the resume, or every mismatch is flagged for the person
11. No employer or client work in Featured or posts without the employer's OK
12. If it's someone else's profile, it's written to them, with the note and the mock
13. Nothing on the profile was changed by you

Then hand it all back to the person and **wait**. They make every change.

---

## The rules that keep it honest

- **Claude writes, the person changes the profile.** Never edit, post or publish.
- **No numbers on LinkedIn.** Save them for the resume and interviews.
- **Only what's true.** Skills they used, credentials they hold, Focus Areas from work they did.
- **Titles match the resume.**
- **Say where rankings come from.** You can't see LinkedIn's search data.

---

The full guide, with a prompt for every step and a master prompt: [LinkedIn playbook](https://github.com/Lily-Tewolde/ai-guides/tree/main/02-linkedin-playbook)

*Built from my LinkedIn optimization video: headline → story → skills → Featured → posts.*
