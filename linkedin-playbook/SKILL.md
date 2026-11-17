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

> **Golden rule:** Claude writes, you change the profile. Nothing goes on LinkedIn that isn't true, and no numbers go in anything written for it, except the dates on each entry.

---

## How to use this skill

You (Claude) are updating one person's LinkedIn profile for one target role. The person is whoever the profile belongs to: the user, or someone the user is helping. This skill is your operating spec.

1. **Follow this whole skill, every time.**
2. **Do the steps in order.** Ask for every fact in the gather list at once, before Step 1. Stop later only for a fact that list missed. When the profile belongs to someone else, those questions go through the user. Anything only the person can decide, like which headline or whether a role stays, goes back to them as a clear choice with your recommendation. Never decide it for them. If the user can't answer for them, don't stop. For a choice, like which roles stay or which Open to Work settings, give your pick. For a fact, leave a highlighted `[__]` blank. Mark both for the person to check, and carry on.
3. **Never post, publish or change anything on the person's profile.** Even if you can open it in the browser, don't click edit, save or post. The person makes every change themselves.
4. **Read the live profile when you can.** If you can open it in the browser, read it there. Screenshots are the fallback.
5. **If the Resume Audit ran first, start from the resume.** Use its titles, dates and decisions, from the person's My Resume Rules.md, Decision Log.md and Bullet Bank.md if they have them. Say what changes on LinkedIn because of them. Its cuts are a starting pick, not a final answer: a role it cut only to fit the page or one post can stay on LinkedIn, with the same title, company and dates as the standard resume, and that isn't a mismatch. The Decision Log says why each role came off. If it doesn't, ask with the gather list. A line still marked ★ in Bullet Bank.md is waiting for the person's OK, so anything you write from it waits for the same OK. Say so, and never treat it as confirmed.
6. **No numbers in any text you write for the profile or posts,** except the dates on each entry. The person's numbers are context for you, not copy. The edges, with made-up examples:
   - **Any number counts,** not just results, like a team size in a project description.
   - **Spelled-out numbers and ordinals count too,** even in an award's name or a post's first line. "1st Place, Campus Event Design Challenge" becomes "Winner, Campus Event Design Challenge", and "2nd Place" becomes "Runner-up". Any other placing becomes a true word with no number in it, like "Finalist", or just the award's name. A set term that happens to hold a number word, like "first aid", isn't a number.
   - **Job post wording loses its numbers when you reuse it.** "Respond within one business day" becomes "fast client replies".
   - **A licence or certification keeps its official name,** even with a number in it, since recruiters search it exactly as it's issued.
   - **Media keeps its numbers,** since it's the proof. That goes for a PDF, video or screenshot on an entry, in Featured or in a post. The words around it never quote them, and you never tell the person to blur them for this rule. Other people's names and private details in it, like a candidate or a client, still come out. Whether employer or client media can go up at all is still the employer's call (Step 5).
7. **If the profile belongs to someone else,** write it as a handoff they can follow on their own (see Doing this for someone else).
8. **Run the check at the end** before anything goes back to the person.

---

## Before Step 1: Gather everything 🤖

- **The profile.** Read it live in the browser if you can. Otherwise ask for screenshots of the header, About, every role, Education, Projects, Licenses & certifications, Honors & awards, Skills and Featured.
- **The resume.** If the Resume Audit ran first, use that version, plus My Resume Rules.md, Decision Log.md and Bullet Bank.md. A line still marked ★ in Bullet Bank.md is waiting for the person's OK, so anything you write from it waits for the same OK. Say so, and never treat it as confirmed. Example, made up: the resume line "Coordinated vendor arrivals for 12 weekend weddings" is still ★, so the Focus Area "Vendor coordination (arrival schedules, day-of check-ins)" goes in with "Waiting on your OK for the resume line this comes from."
- **2 to 3 full job posts** for the target role, word for word. If you can't open a link, ask the person to paste the full post. Every keyword choice comes from these.
- **The target role,** as recruiters search it.
- **The facts later steps need,** all in one list, asked once:
  - the city they live in, or the one they're moving to
  - whether they're still employed
  - whether unrelated roles, like seasonal or part-time work, should stay, and the months for any seasonal work
  - remote and employment types for Open to Work
  - whether their employer is OK with their work being shown
  - every language they speak, and their level
  - what each award is, if you can't look it up
  - each licence or certification's issuing organization, and whether any is still in progress
  - if the profile belongs to someone else, whether the user works in their field, for the note (see Doing this for someone else)
  - for each role the resume cut, whether it was only to fit the page or one post, if the Decision Log doesn't say
- Say what you've got and what you still need. Don't write anything yet.

**No browser or file access?** In a chat where you can't open the profile or the person's files:

- Ask for the screenshots above, or the text of each section pasted in.
- If the Resume Audit ran first and its files aren't already in this chat, ask the user to paste in the resume, My Resume Rules.md, Decision Log.md and Bullet Bank.md. Don't guess what's in them.
- If you can't look up an award, ask the person what it is and who it goes to.
- For someone else's profile, write "Delete:" in front of anything that comes off, since crossed-out text is lost when it's pasted. Give the mock as one complete HTML file in a code block, and tell the user how to save it: as plain text, in a file whose name ends in .html, then open it in their browser. Never publish it.

## Step 1: Headline and titles 🤖 then 🙋

- **Headline:** 5 options in this format, each under 100 characters: `Role | Keyword · Keyword · Keyword | Credential`. LinkedIn allows 220, but only about the first 100 show in search and on mobile.
- `Role` is the target role, or a close title recruiters search for it.
- Use keywords that show up in the job posts and that a recruiter would actually search. No buzzwords, no numbers.
- **The credential is real.** It can be a licence or certification they hold, a well-known employer or something they shipped. Never a degree, and never a certification still in progress. If they don't have one yet, leave that part off, and let `Role` vary the way recruiters search it so the 5 options really differ.
- **Never over 100 characters.** If one runs over, shorten the credential to the form people search, then drop to two keywords. Example, made up: `Event Coordinator | Vendor Logistics · Run-of-Show | Food Safety Certified`
- **Titles:** flag any job title that's vague, internal or creative, and give the standard title recruiters search instead. If the Resume Audit ran first, titles match the resume exactly.
- The person picks the headline and decides on every title change.

## Step 2: About and experience 🤖 then 🙋

**The About**

- A story, not a summary. 4 to 6 short paragraphs, in this order:
  1. An opening hook, from real work they've done
  2. The thread connecting their career
  3. What they do now and how they work
  4. One line on what they're open to next
- **Early career, the hook is the work they do now,** then the thread, then how they work. The early career section says the same.
- **Only what they've said or done.** Every line, the hook included, comes from their resume, profile or answers. Anything you'd be inferring, like why they changed paths or what they enjoy, goes on the "add only if true" list for them to confirm, never in the About.
- No bullets, no numbers. Weave in the keywords a recruiter searches for, but keep it sounding like a real person talking.

Example, made up: not "I've always loved bringing people together", since nobody said that. Instead: "On an event day I'm the one with the run-of-show, making sure every vendor arrives when they should."

**Each role and project**

- One short narrative paragraph: what they owned and how they worked. A project gets one too.
- Then the Focus Areas:
  1. **Format.** Each one is the skill a recruiter searches, then the specifics in brackets.
  2. **Wording comes from the job posts.** Pull it from the requirements and responsibilities, and only where it's work the person has actually done. Drop any number from the wording you reuse. Where the posts don't describe the work, like a role far from the target or part of a project, use the words someone hiring for that work would search.
  3. **The count follows the entry:**
     - A role close to the target: 4 to 12, depending on how much it matters for where they're going.
     - A role far from the target that stays with a description, like seasonal work or a box office job before an events career: 0 to 3, one for each kind of work they confirmed.
     - A role like that kept with no description: none.
     - A project: 2 to 4, after its paragraph.

     Say which roles you counted as far from the target, so the person can check.
  4. **Never pad to reach a count.** Each Focus Area is work they've confirmed, or comes from a ★ resume line and is marked as waiting for their OK (rule 5). If that comes to fewer than the range, use fewer and say why. Don't stretch the wording or add work they haven't done to fill it.
  5. **"Add only if true" list.** Anything the posts ask for that the person hasn't confirmed, and any About line or post hook you'd be inferring, goes on a separate list for them, never on the profile.
  6. **No numbers means any number.** Rule 6 in How to use this skill has the edges.

Example, made up:

- Event logistics (vendor contracts, venue sourcing, run-of-show planning)
- Budget tracking (spend reports, invoice reconciliation, cost forecasts)

A school gala project, made up, gets "I planned the department's spring gala with a student team, from the venue to the run-of-show", then:

- Event logistics (venue booking, vendor schedule, run-of-show)
- Budget tracking (vendor quotes, spend sheet)

## If the person is early in their career 🙋

Early career means recently out of school, or a few years into their first field. LinkedIn doesn't let anyone move sections around, so Projects always sits low on the page. These keep Experience for real jobs and still get the projects seen.

1. **Experience is for real jobs.** Ask whether unrelated roles, like seasonal or part-time work, stay or go. If nobody answers, the role stays with no description, and say so. School projects never go in Experience.
2. **One Education entry per degree they actually earned.** No description or Focus Areas. An earlier program that didn't lead to the degree comes off, and the About can mention it as part of the thread. Why they switched goes in only if they've said.
3. **Projects stay in the Projects section.** Each one gets the Step 2 format: one short paragraph, then 2 to 4 Focus Areas. Link each one to the school with "Associated with", tag the skills used, and add media once it exists.
4. **Featured is how a project gets seen first,** since the Projects section can't be moved up.
5. **Licenses & certifications.** Add any the person holds, with the issuing organization LinkedIn asks for. Recruiters filter by them. One still in progress stays off until it's earned, and the About can say they're working toward it.
6. **Honors & awards.** Look up what each award is first. If you can't, ask what it was for. Keep the ones that are rare, competitive or in their field. Dean's List, general scholarships and other general honours are the person's call, the same as on the resume, and for entry-level roles your pick is to cut general scholarships. This test is broader than the Resume Audit's on purpose, since LinkedIn has room.
7. **The About matches the level they're aiming for.** It opens on the work they do now, then the thread, then how they work: Step 2's early career order. Use school work as evidence, not as a chapter in school-to-job order.

## Step 3: Skills and Open to Work 🤖 then 🙋

**Top 5**

- Pick 5 Top skills for the About section, and put the same 5 first in the Skills section, since only the first few show without clicking.
- **Be honest about the ranking.** You can't see LinkedIn's search data. Say the ranking comes from how often each skill shows up across the job posts.
- **How to rank them.** Count each skill once per post it appears in. Group synonyms under the name recruiters search. In a tie, must-haves come ahead of nice-to-haves. Skip any skill the person doesn't have.

**Skills on every entry**

1. **List the exact skills for every entry.** Each experience, education and project entry gets its own list, using names recruiters actually search.
2. **Say how to add them.** Type each one in and pick LinkedIn's exact match from the dropdown. If it doesn't come up, pick the closest suggestion.
3. **Only skills they've used** in that role or project.
4. **Prune the Skills section.** Remove skills that don't fit the target role, but keep all the software and tools they've actually used. A tool they've never used comes off, like any other skill that isn't true.

**Open to Work**

- 5 target job titles. If the posts give fewer, add close ones recruiters search and say which are your picks.
- Remote and employment types, from what they told you. Never leave them blank. If nobody knows, give your pick and mark it for them to check.
- **Recruiters only when they're still employed,** and say why. LinkedIn tries to hide it from their own company's recruiters, but it can't promise it.

## Step 4: Featured 🤖 then 🙋

- Give 3 Featured ideas they could make in under 2 hours each, ranked by how much they'd impress a recruiter.
- For each one: what it contains, why it works as proof, and what tool or format to make it with.
- Best: a 2 to 3 minute video walking through something they built or shipped. Also good: a strong post in their field, a live tool or a portfolio link.
- Early career: their best project goes here (see above).
- **Employer and client work stays out** unless the employer says it's okay (Step 5 says what counts).

## Step 5: Posts 🤖

- 9 post ideas, 3 a week for 3 weeks, from their real work.
- Mix three formats: a lesson from real work, a behind-the-scenes look at how they work, and a simple tip or framework from their field.
- A scroll-stopping first line for each, built only from what they've said or done. If a hook would need something they haven't told you, like why they changed paths, use their real work instead and put the question on the "add only if true" list. No generic career advice.
- **No numbers in a post,** first line included (rule 6 in How to use this skill). A screenshot or PDF in the post keeps its own.
- **Employer and client work stays out** unless the employer says it's okay. That means client names, photos, documents and anything that isn't public.
- **What's fine without asking:** what they learned and how they work, with no client named.
- **An idea that needs the employer's OK stays on the list only if it's marked,** with "ask your manager first" next to it.

Examples, made up:

- **First line:** not "I left retail because I wanted more creative work", which nobody said, but "The vendor checklist I use on every event day".
- **No numbers:** "My first 3 months running vendor check-in" becomes "What running vendor check-in taught me".
- **Employer work:** "How I keep vendors on schedule on an event day" is fine. "Photos from a client's wedding I helped run" needs an OK.

## Extras 🤖 then 🙋

- **Photo:** a clear headshot where their face fills most of the frame. Good light, a plain or on-brand background, dressed the way they would for work in their field.
- **Banner:** 1584 × 396 pixels, and one that fits their field. Not blank. One short line on it about what they do is optional.
- **Location is a city,** not just a country: the one they live in, or the one they're moving to. Recruiters filter by city.
- **The verification badge,** with a work email or ID.
- **Media on entries,** like a link, PDF or video on the role or project it belongs to. It keeps its numbers, but the words around it don't quote them.
- **Languages,** every one they speak, at their real level.
- **Recommendations: give one first.** People are far more likely to write one back. Ask former managers, close teammates and clients, say what you'd love them to mention, and ask right after wrapping something good together. Aim for 5 to 10 over time. Draft the ask in under 80 words, casual, not like a template.
- **Connections.** Grow them at their current company, their school and the companies they're applying to.
- **Licenses & certifications, and Honors & awards,** follow rules 5 and 6 in the early career section, at any career stage.
- **Resume sync.** Job titles, companies and dates match the resume exactly. A role the resume cut only to fit the page or one post can stay on LinkedIn, with the same title, company and dates as the standard resume. That isn't a mismatch. LinkedIn needs a month and year, so seasonal work like "Summers 2023 – 2024" goes in as its first and last months, with Seasonal as the employment type. The resume keeps its own wording, and that isn't a mismatch. The numbers stay on the resume.
- **Skills and tools match both ways.** If the About or Skills mention software that isn't on the resume, or the resume has a tool LinkedIn doesn't, flag it. The person decides which one changes, or keeps both as they are. Basic tools like Word, Google Docs or Excel can be on LinkedIn without being on the resume, so don't flag those.

Example, made up: the resume keeps Event Coordinator at a hotel and Events Assistant at a concert venue, and a summer job at a bike rental shop came off for space. On LinkedIn, the bike rental job stays with the same title and dates, and Microsoft Word stays in Skills. Neither gets flagged. Dean's List is off the resume. On LinkedIn it's the person's call, and the pick for an events role is to cut it.

---

## Doing this for someone else 🙋

When the profile belongs to someone the user is helping, they're the one who has to make every change. Write it all to them, so they can follow it on their own.

1. **Written to them, in the user's voice.** Second person, like "I picked this headline for you" or "delete these three roles". No AI-looking labels or numbered tags.
2. **Clear change, keep and delete.** Mark what to change, leave everything else alone, and cross out what comes off.
3. **Open or close with a note in the user's voice:** they should adjust anything that seems off. If the user isn't an expert in their field, say so, and that this is mostly formatting and a strong direction. If you don't know, ask the user. Never say it as a fact you've guessed. Example, made up, from a nurse helping a cousin into data analysis: "I don't work in data, so this is mostly formatting and a strong direction. Change anything that doesn't sound like you."
4. **A visual mock of the finished profile.** An HTML page laid out like their profile, with the user's notes beside each section and a switch to hide the notes, so they can see it the way a recruiter would. It's a file they open on their own computer, never a page published online.
5. **Employer and client work stays out** of Featured and posts unless the employer says it's okay.
6. **Open to Work is set to Recruiters only while they're still employed,** with the reason: LinkedIn tries to hide it from their own company's recruiters, but it can't promise it.
7. **Their details stay private.** They stay in their own folder, never go into a public repo, an issue or a shared doc without them knowing, and any example shared about what was learned is made up.

---

## Check before it goes back 🤖 then 🙋

Run every check and say which passed and which didn't:

1. Headline under 100 characters, in the format, with a credential from Step 1 (never a degree or one in progress), or none
2. Every job title is one a recruiter would search, and matches the resume. A role the resume cut only to fit the page or one post matches the standard resume
3. No numbers in anything written for the profile or posts, including team sizes, spelled-out numbers, ordinals and job post wording, except entry dates. Media keeps its own
4. The About is a story with no bullets, at the level they're aiming for, in the order Step 2 gives for them. Every line of it, and every post's first line, is something the person said or confirmed, or is marked as waiting on a ★ resume line
5. Every Focus Area is in the format, worded from the job posts (or, where the posts don't describe the work, the words someone hiring for it would search), and only covers work they've done. A role has 4 to 12, or 0 to 3 if it's far from the target. A project has its own paragraph and 2 to 4. For any entry with fewer, you've told the person why instead of padding, and said which roles you counted as far
6. Anything unconfirmed is on the "add only if true" list, not the profile. The exception is anything built from a line still marked ★ in Bullet Bank.md: it goes in, marked as waiting for the person's OK
7. Every experience, education and project entry has its exact skills, and only ones used there. A role kept with no description can have none
8. The Top 5 says the ranking comes from the job posts
9. Location is a city
10. Titles, companies and dates match the resume, or every mismatch is flagged for the person to line up. Skills and tools match both ways, or every mismatch is flagged with keeping both as an option. Seasonal work entered as its first and last months, a role the resume cut only to fit the page or one post, and basic tools like Word on LinkedIn only all count as a match
11. No employer or client work in Featured or posts without the employer's OK, unless it's marked "ask your manager first"
12. If it's someone else's profile, it's written to them, with the note and the mock, and this check goes to the user after the handoff
13. Every fact from the gather list is in, or its blank or pick is marked for the person to check
14. Open to Work has 5 titles, with any picks marked, plus remote and employment types
15. Nothing on the profile was changed by you

**The check is for the user.** When the profile belongs to someone else, it goes after the handoff, addressed to the user, so it never gets passed on. What the person still has to do, like blanks, picks to check or lines waiting for their OK, stays in the handoff as tasks. Example, made up: "For you, not your cousin: every check passed except location, which is still a country because I didn't know the city."

Then hand it all back to the person, with the check last when it's someone else's, and **wait**. They make every change.

---

## The rules that keep it honest

- **Claude writes, the person changes the profile.** Never edit, post or publish.
- **No numbers in anything written for LinkedIn.** Save them for the resume and interviews. Media keeps its own.
- **Only what's true.** Skills they used, credentials they hold, Focus Areas from work they did, and About and post lines from what they've said.
- **Titles match the resume,** or the standard resume for a role it cut.
- **Say where rankings come from.** You can't see LinkedIn's search data.

---

*Built from my LinkedIn optimization video: headline → story → skills → Featured → posts.*

The full guide, with a prompt for every step and a master prompt: [LinkedIn playbook](https://github.com/Lily-Tewolde/ai-guides/tree/main/02-linkedin-playbook)
