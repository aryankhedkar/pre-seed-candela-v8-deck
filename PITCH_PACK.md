# Candela · v8 · Problem & Product Pack

**Scope:** twenty slides on problem and product only. Team, market, model, competition, secrets, ask, and close from [v7](https://github.com/aryankhedkar/pre-seed-candela-v7-deck) stand as-is; this pack replaces the product story under them.

**Format:** seven-minute walkthrough plus open Q&A. The slide cadence is one beat per slide for problem (slides 1–7), one slide per product primitive (slides 8–19), and the close (slide 20).

**Deck:** open `index.html` in any browser, or run `python3 -m http.server 5180` in this directory. Arrows or space to navigate, type a slide number to jump, append `?print=1` for a stacked print mode.

---

## Part 1 — The 7-Minute Walkthrough

Read the ruled lines aloud, in order. Italic lines are delivery cues for you; the spoken lines sit above them. Rehearsed pace lands around 6:30; nerves take it to 7:00 in the room.

---

### Slide 1 — Cover · the equation [0:00 → 0:20]

CV plus take-home plus interview theatre equals work the candidate did not do. That is the equation hiring is running today. The whole loop is full of artefacts, and none of them are the work.

*Cue: Open on this. No "thanks for having me." Read the equation top to bottom, then pause on the result line.*

---

### Slide 2 — The frame [0:20 → 0:50]

AI changed how engineering work gets done, and the hiring loop is still pretending it didn't. The candidate sends a CV, the recruiter scans it for keywords, the hiring manager runs a take-home any frontier model can finish in twenty minutes, and both sides come out of that tired, with neither having learned anything about whether this person can do the job. The whole hiring loop is a proxy for the work, and none of it is the work.

*Cue: Even pace. The "proxy for the work" line lands harder if you let the silence before it sit.*

---

### Slide 3 — The signal problem [0:50 → 1:25]

Look at what each artefact in hiring really proves. A CV is supposed to prove who the candidate is and what they have done; in practice it proves they can write a CV. A GitHub graph is supposed to show how they work; it shows they committed something, somewhere. A personal site is supposed to demonstrate taste; it demonstrates they bought a Vercel domain. A take-home is supposed to prove they can build the thing; today it proves Claude can build the thing. A LeetCode round is supposed to test reasoning; it tests memorisation. A behavioural interview is supposed to surface how they collaborate; it surfaces how they rehearsed. None of these are the work.

*Cue: Pace the rows. The room reads ahead of you on a table this dense; let them catch up before the closing line.*

---

### Slide 4 — The CV [1:25 → 1:50]

A recruiter spends six seconds on a CV. That is enough to scan for school, company logos and a couple of keywords. It is not enough to learn anything about how the candidate thinks or what they could ship on a Tuesday. Eighty-four percent of CVs get filtered by an ATS keyword match before any human reads them. The document about engineering has zero lines of code on it. A CV tells the employer what the candidate sat through, and none of it is the work.

*Cue: Slow on "zero lines of code." Let that one land.*

---

### Slide 5 — The take-home [1:50 → 2:15]

Take-homes were the closest hiring came to real work. Then frontier models made it cheap to ship a clean PR overnight without thinking through any of the trade-offs. Authorship is gone, because a submitted PR looks identical whether the candidate sat with it for four hours or piped the brief into Cursor. Effort is invisible, because the path the candidate took to reach the artefact is lost. Comparison breaks down, because each candidate gets a slightly different brief with a different bar. Hiring managers know this. They keep shipping the take-home because they have nothing better.

*Cue: "Nothing better" is the line that sets up the product. Read it without flinching.*

---

### Slide 6 — The portfolio [2:15 → 2:40]

GitHub graphs and personal sites stopped telling employers anything. The portfolio used to be the proof the CV could not give, until the bar for shipping one dropped to a Cursor prompt and a Vercel deploy, and the medium got cheap enough to be invisible. READMEs nobody reads, polished sites that look the same as the next polished site, commit graphs that are shape without story: the portfolio became wallpaper that looks nice and tells the hiring manager nothing.

*Cue: Land "wallpaper." It is the bridge into what people really want.*

---

### Slide 7 — What they want [2:40 → 3:10]

What hiring managers want is to see the candidate do the work itself: the thing they would build on their first day, and a record of how they thought their way through it. Three properties make that readable on the page. It has to be real, in the sense that the task lives inside the job the candidate would do. It has to be comparable, with the same brief and the same rubric across applicants. It has to be time-bound, because the clock is what makes the artefact a signal again. A founder whiteboarding three features the team needs to ship this quarter already knows the shape of the test they want to run, and they have no way to run it.

*Cue: Slow on the founder line. That is the audience for the rest of the deck.*

---

### Slide 8 — The reframe [3:10 → 3:30]

So what if the application was the work. The candidate ships Day 1 of the job before they apply, the hiring manager reads the work and the reasoning behind it, and the offer turns into paperwork. Both sides start the job before either side commits to it.

*Cue: This slide is the pivot. Read it slower than you want to. Let "Both sides start the job before either side commits to it" sit.*

---

### Slide 9 — The product [3:30 → 4:00]

Candela v8 is the hiring loop, rebuilt as work. A founder pastes a job description, the platform turns it into a real project, a candidate finds the role and ships it on the clock, and the hiring manager reads the scored submission and decides whether to interview. Three primitives carry it. Job-as-project, where any JD becomes a real project the candidate can build. Live build, where candidates build inside Candela on a visible clock. AI shortlist, where submissions are scored against the rubric the JD generated and the hiring manager reads only the top of the stack.

*Cue: The three primitives are the spine of the rest of the deck. Say them in order; the next ten slides drill into each one.*

---

### Slide 10 — Paste a JD [4:00 → 4:20]

For the hiring manager: paste a job description, any job description, the version already living in your ATS, the LinkedIn post you copy-pasted yesterday, the Google Doc the team argued over for two weeks. One paste, no rewriting. The platform reads the role on the left, and the project a strong candidate would ship is about to come out on the right.

*Cue: Point at the left pane. The right pane is intentionally still loading; the reveal comes next.*

---

### Slide 11 — The reveal [4:20 → 4:50]

Out comes the project a strong candidate would ship to prove they can do the job. From the founding engineer JD: ship a Postgres-backed ledger reconciler from a sample feed. Milestone one, parse the sample CSV ingest and write to a typed Postgres schema. Milestone two, implement the reconciler against a second feed with deliberate mismatches and log the trade-offs you chose. Milestone three, write the README the next engineer needs to take this on call without a meeting. The whole thing is scored against reasoning depth, scope discipline, code quality, communication and iteration honesty. What the platform returns is a real project the candidate can fork, build, and ship in a window the hiring manager set.

*Cue: This is the demo moment Nadal reacted to. Move slowly through the right pane. Land the "real project" line and let it sit.*

---

### Slide 12 — The brief [4:50 → 5:15]

Each project ships with milestones, starter scaffolding, and a scoring rubric. The output is a structured project: three slices in sequence, where the first proves the candidate can stand the project up, the second exposes the trade-off the role will face on the job, and the third tests how they ship it for the next hire. The repo skeleton, the sample input, and the README stub mean the candidate starts where the role starts. The rubric weighs reasoning depth, scope discipline, code quality, communication, and iteration honesty by role, and the same rubric scores all applicants for that role.

*Cue: Slow on the rubric. It is the part hiring managers ask about first.*

---

### Slide 13 — Your portal [5:15 → 5:35]

Publish to a company portal that looks like yours. The link is the discovery surface. Your logo, your hiring brief, your open roles, the projects students would ship for them. Shareable to a careers office, an investor list, a Slack DM. LinkedIn replaced by a page that says something about how the work gets done here.

*Cue: Point at the role rows. Each one is a project the candidate would ship.*

---

### Slide 14 — For the candidate [5:35 → 5:55]

For the candidate. A recent graduate hears about Candela from their careers office, at Imperial first, then Oxbridge, then any technical university. They open the company's portal page and read the role, with the project they would build laid out alongside the salary and the build window. The application is the work itself, and the clock has not started yet.

*Cue: Read the role title and the salary as you point. The clock hasn't started yet is the line that flips the page.*

---

### Slide 15 — The clock [5:55 → 6:15]

Twenty-four hours, headphones on, build. The candidate starts the project and the clock starts with it, with the brief, the workspace, the thinking partner, and the rubric in view, and the submission window as the only other piece of chrome on the screen.

*Cue: This is the candidate's beat. Say it like the candidate. Then pause.*

---

### Slide 16 — The build [6:15 → 6:30]

The candidate builds inside Candela's workspace, with the thinking partner beside them, and the reasoning log capturing how they think. The IDE, the thinking partner, and the reasoning log already exist in Candela v1. v8 repurposes them as the application surface for hiring. The candidate builds the same way a Candela student builds.

*Cue: Point at the coach pane. Read the coach question aloud. That is the magic the rest of the platform extends to hiring.*

---

### Slide 17 — Submit [6:30 → 6:45]

Submit, and the work gets frozen and scored. The files and the reasoning log both lock, and the submission appears on the hiring manager's pipeline within seconds, scored against the rubric the JD generated and ranked against the other submissions before the founder's coffee lands.

*Cue: One sentence per pillar. Move quickly.*

---

### Slide 18 — The pipeline [6:45 → 7:00]

Sixteen applied, eleven are building, four have submitted, and two cleared the bar. Each role has four columns, and each card carries a face, a name, a score, and a pull-quote from the candidate's reasoning log, where the recruiter used to read a CV and a cover letter. The hiring manager reads the column that matters.

*Cue: Read the column counts in the title. Then point at the flame-bordered column on the right.*

---

### Slide 19 — The filter [7:00 → 7:20]

Three submissions cleared the bar this morning. Read the work. The hiring manager opens Candela and sees the column that matters. Sixteen applicants became three reads by the time the morning coffee landed. Each card lifts the strongest excerpt from the candidate's reasoning log, with a link to the frozen project behind it. From sixteen CVs to three reads, by the time the founder's coffee lands.

*Cue: Read one of the reasoning excerpts aloud. That is the texture the rest of the loop is built to surface.*

---

### Slide 20 — The close [7:20 → 7:40]

When the application is the work, hiring is no longer theatre. The candidate already did Day 1, the hiring manager already read their reasoning, and the offer turns into paperwork. That is what Candela v8 is for. Paste a JD into candela-ed.com, watch it become a real project, and read the work it pulls back. Try it before you say no.

*Cue: Stop on "That is what Candela v8 is for." Do not add a thank-you on top. Let the silence do the work.*

---

## Part 2 — Top Questions and Answers

The Q&A picks up where the deck leaves off. Answer short, answer first, then stop.

---

### Q1. "How is this different from a take-home?"

A take-home is private, asymmetric, and uncomparable across candidates. A Candela project is public to the candidate, generated from the role, scored on the same rubric across applicants, and runs against a visible clock. Authorship is captured by the reasoning log as the candidate builds, so the hiring manager can read how they got there alongside what they shipped. The output is a ranked stack with reasoning excerpts attached, where the hiring manager used to be handed twenty take-homes in a folder.

---

### Q2. "What stops the candidate from prompting Claude for the whole thing?"

Two things. First, the reasoning log captures the path the candidate took alongside the artefact they landed on, the rubric scores iteration honesty alongside code quality, and a candidate who handed the build to a model without thinking through the trade-off shows up in the log. Second, the thinking partner asks the question that makes the candidate weigh the trade-off before accepting whatever the model offered first. The platform is built around frontier models in the room with the candidate, and the signal is what the candidate did with that model.

---

### Q3. "Why would a hiring manager trust the AI score?"

The score is a triage layer, with the decision to interview still sitting with the hiring manager, who reads the work of the candidates who cleared the bar. The rubric is generated from the JD they wrote, so the criteria are theirs. The scorer is the same across applicants, so it is a fairer first cut than the recruiter scan it replaces. The decision to interview is still human.

---

### Q4. "What's the wedge into employer adoption?"

The paste-a-JD flow is the wedge. The hiring manager pastes a job description they already wrote, gets a real project back in seconds, and sees a shareable link to a portal page that looks like theirs. No procurement cycle, no integration, no rewriting. The free public version of the JD translator on the marketing site, with a "see how this would look on your Candela page" CTA, drives the funnel.

---

### Q5. "Does the candidate still pay £29 a month?"

Yes, for the up-skill side: full workspace, thinking partner, project history, public profile. The hiring side is free for the candidate; per-role submissions count toward their plan. Employers pay per role published, with placement fees on hires. The candidate model from v7 stands.

---

### Q6. "What if the candidate finishes the task in two hours? Or runs out of the window?"

Both are signal. A two-hour ship gets reviewed against the rubric like any other submission, and a clean small ship can rank above a sprawling twenty-hour one. A window timeout submits whatever the candidate had committed at the deadline, with the reasoning log frozen at that point. The hiring manager sees both the artefact and the trajectory.

---

### Q7. "How does this connect to the v7 candidate product?"

It is the same product, applied to hiring. The IDE, the thinking partner, the reasoning log, the scorer, the credentialed projects all exist in v1.0. v8 reuses them as the application surface and adds the job-to-project translator, the per-job pipeline, and the company portal page on top. The shipped projects on the candidate side become the body of work the hiring manager reads when they meet a new Candela user.

---

## Part 3 — Numbers to Know Cold

| Beat | Number | Source |
|---|---|---|
| Problem | Recruiter scan time per CV | **6 seconds** | Eye-tracking research, major UK + US firms |
| Problem | CVs filtered by ATS before a human reads | **84%** | Jobscan ATS research, 2024 |
| Problem | Lines of code on a CV | **0** | The point |
| Product | Time from paste to generated project | **~15 seconds** | Claude Haiku for metadata, Sonnet for the brief |
| Product | Build window per role | **24 hours, configurable** | Set by the hiring manager |
| Product | Rubric criteria | **5, weighted from the JD** | Reasoning depth, scope discipline, code quality, communication, iteration honesty |
| Product | Candidate-side platform | **Existing Candela v1.0** | IDE, thinking partner, reasoning log, scorer |
| Product | Demo pipeline cohort | **3 companies, 10 candidates each** | Helia (energy), Ferrum (banking), Vexel (deeptech) |

---

## Part 4 — Before You Walk In

- **Rehearse the paste-the-JD beat hardest.** Slide 10 to 11 is the moment Nadal reacted to. The pause between the loading dots and the reveal is the moment that lands the product.
- **Have the live URL ready to share.** Slide 20 closes on "paste a JD into candela-ed.com." Be ready to do it in the room if the meeting goes long.
- **The candidate beat is in the second half.** Slides 14 to 17 are the recent-graduate story. Tell it like a story.
- **End on the close.** "That is what Candela v8 is for" is the last sentence you say out loud. The CTA panel underneath is for them to take with them.
- **If you overrun,** the cuts are slide 4 (CV stats) or slide 6 (portfolio). The product half does not bend.
