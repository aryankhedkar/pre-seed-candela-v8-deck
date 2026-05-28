# Candela · v8 · Problem & Product Pack

**Scope:** twenty slides on problem and product only. Team, market, model, competition, secrets, ask, and close from [v7](https://github.com/aryankhedkar/pre-seed-candela-v7-deck) stand as-is; this pack replaces the product story under them.

**Format:** seven-minute walkthrough plus open Q&A. The slide cadence is one beat per slide for problem (slides 1–7), one slide per product primitive (slides 8–19), and the close (slide 20).

**Deck:** open `index.html` in any browser, or run `python3 -m http.server 5180` in this directory. Arrows or space to navigate, type a slide number to jump, append `?print=1` for a stacked print mode.

---

## Part 1 — The 7-Minute Walkthrough

Read the ruled lines aloud, in order. Italic lines are delivery cues for you; the spoken lines sit above them. Rehearsed pace lands around 6:30; nerves take it to 7:00 in the room.

---

### Slide 1 — Cover · the equation [0:00 → 0:20]

Junior candidate, plus Claude in their pocket, plus a polished application, equals you hiring on vibes. That is the equation today, and nothing left in the funnel tells you who can do the job without the model.

*Cue: Open on this. No "thanks for having me." Read the equation top to bottom, and slow down on the result line before you move on.*

---

### Slide 2 — The frame [0:20 → 0:55]

Your junior is using Claude shamelessly. How do you know which of them can do the job? By the time the candidate reaches your inbox, Claude has written the CV, shipped the take-home, deployed the portfolio site, and rehearsed the answers for the final round. Each artefact you once used to judge competence now arrives polished from the same model, and nothing left in the funnel tells you which of the candidates in front of you could ship anything without it. Hiring needs to watch the candidate work with the model in the room.

*Cue: Land the question in the headline before you read the lede. Look at the audience when you ask it. The closing line is the bridge into the rest of the deck; let the room sit with it.*

---

### Slide 3 — The signal problem [0:55 → 1:25]

Look at what each artefact in hiring promised, and what it proves now. A CV promised to tell an employer who the candidate was and what they had done, and it proves they can write a CV. A GitHub graph promised to show how the candidate works, and it shows they committed something, somewhere. A personal site promised to demonstrate taste, and it demonstrates a Vercel deploy. A take-home promised the candidate could build the thing, and it now proves Claude can. A LeetCode round was supposed to test reasoning, and it tests memorisation. A behavioural interview was supposed to surface how a candidate collaborates, and it surfaces how they rehearsed. None of these are the work itself.

*Cue: Pace the rows. The room reads ahead of you on a table this dense; let them catch up before the closing line.*

---

### Slide 4 — The CV [1:25 → 1:50]

A recruiter spends six seconds on a CV. That window is enough to read a school name, a couple of company logos, and three or four keywords from the role on file, and far too short to learn anything about how the candidate thinks or what they could ship on a Tuesday. Eighty-four percent of CVs are filtered by an ATS keyword match before any human reads them. The document about engineering has zero lines of code on it. A CV tells the employer what the candidate sat through, and none of it is the work itself.

*Cue: Slow on the zero-lines-of-code line. Let that one land.*

---

### Slide 5 — The take-home [1:50 → 2:15]

For a long time the take-home was the closest hiring came to watching the candidate do the actual work, because they had to sit with a problem for a few hours and ship something a hiring manager could read end to end. Then frontier models made it cheap to ship a clean PR overnight without weighing a single trade-off along the way. Authorship is gone, because a submitted PR looks identical whether the candidate sat with it for four hours or piped the brief into Cursor. Effort is invisible, because the path the candidate took to reach the artefact is lost. Comparison breaks down, because each candidate gets a slightly different brief with a different bar. Hiring managers know this, and they keep shipping the take-home because they have nothing better.

*Cue: "Nothing better" is the line that sets up the product. Read it without flinching.*

---

### Slide 6 — The portfolio [2:15 → 2:40]

A portfolio was once the proof a CV could not give, because shipping one took weeks and the result told the hiring manager something about how the candidate worked when nobody was watching. The bar for putting a clean, deployed site up dropped to a Cursor prompt and a Vercel deploy, and the polish on the page stopped being a signal about the person behind it. READMEs nobody reads, polished sites that look the same as the next polished site, and commit graphs that are shape without story: the portfolio became wallpaper that looks nice and tells the hiring manager nothing.

*Cue: Land "wallpaper." That is the word that closes the problem section.*

---

### Slide 7 — What they want [2:40 → 3:10]

What hiring managers want is to watch the candidate do the work. What they want, in detail, is the artefact the candidate would have built in their first month on the job, and the reasoning behind the moves that produced it. Three properties make that readable on a hiring manager's desk. It has to be real, in the sense that the task lives inside the job the candidate would do. It has to be comparable, with the same brief and the same rubric across applicants. It has to be time-bound, because the clock is what makes the artefact a signal again. A founder whiteboarding the three features their team needs this quarter already knows the shape of the test they would put a hire through, and no way to run it on a stranger.

*Cue: Slow on the founder line. That is the audience for the rest of the deck.*

---

### Slide 8 — The reframe [3:10 → 3:30]

So what if the application was the work. If a candidate shipped a piece of the actual job before they applied, you would see who was thinking with the model and who was just letting it ship, and decide whether to interview on the strength of what they had built. Both sides start the job before either side commits to it.

*Cue: This is the pivot. Read it slower than you want to. Let "Both sides start the job before either side commits to it" sit.*

---

### Slide 9 — The product [3:30 → 4:00]

Candela v8 is hiring rebuilt around the work itself. A founder pastes the role they are hiring for, and Candela writes the project a strong candidate would have to ship to prove they could do the job from week one. The candidate finds the role through the company's page on Candela, takes the project on a visible window, and builds it inside the existing workspace with the thinking partner beside them. The submission is scored against the rubric the role generated, and the hiring manager opens the work that cleared the bar and reads it before deciding whether to call. Three primitives carry it: the role becomes a project, the build runs live with the thinking partner in the room, and the submissions land on the hiring manager's desk ranked and ready to read.

*Cue: The three primitives are the spine of the rest of the deck. Say them in order; the next ten slides drill into each one.*

---

### Slide 10 — Paste a JD [4:00 → 4:20]

For the hiring manager: paste a job description, any job description. Whatever you have already written, whether the version sitting in your ATS, the LinkedIn post you copy-pasted yesterday, or the Google Doc the team argued over for two weeks, Candela reads on the way in. The platform reads the role on the left of the screen, and the project a strong candidate would ship is about to come out on the right.

*Cue: Point at the left pane. The right pane is intentionally still loading; the reveal comes next.*

---

### Slide 11 — The reveal [4:20 → 4:50]

Out comes the project a strong candidate would ship to prove they can do the job. From the founding engineer JD: ship a Postgres-backed ledger reconciler from a sample feed. The first milestone parses the sample CSV ingest and writes typed rows into Postgres. The second implements the reconciler against a second feed with deliberate mismatches and asks the candidate to log the trade-off they chose to live with. The third asks for the README the next engineer would need to take this on call without a meeting. The whole thing is scored against reasoning depth, scope discipline, code quality, communication, and iteration honesty. The artefact that comes back is the same thing the team would have asked a new hire to ship in their first month, ready for the candidate to fork, build, and submit inside the window the hiring manager set.

*Cue: This is the demo moment Nadal reacted to. Move slowly through the right pane and let the milestones land in sequence.*

---

### Slide 12 — The brief [4:50 → 5:15]

What Candela writes is the project itself. On paste, the role becomes a structured brief: three milestones in sequence, a repo skeleton and a sample input the candidate can clone from the next click, and a five-criterion rubric pulled from the role and weighted to it. The first milestone proves the candidate can stand the project up. The second exposes the trade-off the role will face on the job. The third tests how the candidate would ship it for the next hire. The hiring manager wrote a job description, and Candela shipped a comparable, time-bound, real project on top of it.

*Cue: Slow on the rubric. It is the part hiring managers ask about first.*

---

### Slide 13 — Your portal [5:15 → 5:35]

The role lives on your own page on Candela. Your logo at the top, your hiring brief underneath, the open roles and the projects a candidate would ship for them on a single page. The link is shareable to a careers office, an investor list, or a Slack DM, and the candidate who clicks finds the test in front of them. What used to be a LinkedIn job post is now a page that says something about how the work gets done here.

*Cue: Point at the role rows. Each one is a project the candidate would ship.*

---

### Slide 14 — For the candidate [5:35 → 5:55]

For the candidate. A recent graduate hears about Candela from their careers office, at Imperial first, then Oxbridge, then any technical university. They open the company's page on Candela and read the role, and the project they would build is laid out next to the salary and the build window, with a clock for it that has not started yet. The application is the project itself.

*Cue: Read the role title and the salary as you point. The clock has not started yet is the line that flips the page.*

---

### Slide 15 — The clock [5:55 → 6:15]

Twenty-four hours, headphones on, build. On click the clock starts and the candidate goes into the workspace, with the brief, the thinking partner, and the rubric sitting alongside the code, and the only other piece of chrome on the screen is the submission window counting down.

*Cue: This is the candidate's beat. Say it like the candidate would say it, then pause.*

---

### Slide 16 — The build [6:15 → 6:30]

The candidate builds inside Candela's workspace, with the thinking partner beside them, and the reasoning log capturing how they think. The IDE, the thinking partner, and the reasoning log already exist in Candela v1, and v8 puts them in the candidate's hands as the application surface, so a candidate applying for a role builds it the same way a Candela student builds anything else.

*Cue: Point at the coach pane. Read the coach question aloud. That is the magic the rest of the platform now extends to hiring.*

---

### Slide 17 — Submit [6:30 → 6:45]

On submit, the work locks and Claude scores it against the rubric the role generated. The candidate ships before the clock runs out, and the files and the reasoning log lock at the same moment, with the submission landing on the hiring manager's pipeline within seconds and ranked against the other submissions for the same role.

*Cue: One sentence per pillar. Move quickly here; the next slide is the payoff.*

---

### Slide 18 — The pipeline [6:45 → 7:00]

Sixteen applied, eleven are building, four have submitted, and two cleared the bar. The hiring manager opens the role and sees four columns: applied, building, submitted, cleared. Each card carries a face, a name, a score, and a pull-quote from the candidate's reasoning log, sitting in the place where the recruiter used to read a CV and a cover letter. The hiring manager reads the column that matters.

*Cue: Read the column counts in the title, then point at the flame-bordered column on the right.*

---

### Slide 19 — The filter [7:00 → 7:20]

Three submissions cleared the bar this morning, with the work behind each one a click away. The hiring manager opens Candela and sees the column that matters, with sixteen applicants reduced to three reads by the time the morning coffee landed, and each card lifts the strongest excerpt from the candidate's reasoning log next to a link to the frozen project behind it. From sixteen CVs to three reads, by the time the founder's coffee lands.

*Cue: Read one of the reasoning excerpts aloud. That is the texture the rest of the product is built to surface.*

---

### Slide 20 — The close [7:20 → 7:40]

When the application is the work, hiring is no longer theatre. The candidate already did Day 1, the hiring manager already read their reasoning, and the offer turns into paperwork. That is what Candela v8 is for. Paste a JD into candela-ed.com, watch it become a real project, and read the work it pulls back.

*Cue: Stop on "That is what Candela v8 is for." Do not add a thank-you on top. Let the silence do the work.*

---

## Part 2 — Top Questions and Answers

The Q&A picks up where the deck leaves off. Answer short, answer first, then stop.

---

### Q1. "How is this different from a take-home?"

A take-home is private, asymmetric, and uncomparable across candidates. A Candela project is public to the candidate, generated from the role, scored on the same rubric across applicants, and runs against a visible clock. Authorship is captured by the reasoning log as the candidate builds, so the hiring manager can read how they got there alongside what they shipped. The output is a ranked stack with reasoning excerpts attached, where the hiring manager used to be handed twenty take-homes in a folder.

---

### Q2. "What stops the candidate from prompting Claude for the whole thing?"

Two things. First, the reasoning log captures the path the candidate took alongside the artefact they landed on, the rubric scores iteration honesty alongside code quality, and a candidate who handed the build to a model without weighing the trade-off shows up in the log. Second, the thinking partner asks the question that makes the candidate weigh the trade-off before accepting whatever the model offered first. The platform is built around frontier models in the room with the candidate, and the signal is what the candidate did with that model.

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
| Problem · Recruiter scan time per CV | **6 seconds** | Eye-tracking research, major UK + US firms |
| Problem · CVs filtered by ATS before a human reads | **84%** | Jobscan ATS research, 2024 |
| Problem · Lines of code on a CV | **0** | The point |
| Product · Time from paste to generated project | **~15 seconds** | Claude Haiku for metadata, Sonnet for the brief |
| Product · Build window per role | **24 hours, configurable** | Set by the hiring manager |
| Product · Rubric criteria | **5, weighted from the JD** | Reasoning depth, scope discipline, code quality, communication, iteration honesty |
| Product · Candidate-side platform | **Existing Candela v1.0** | IDE, thinking partner, reasoning log, scorer |
| Product · Demo pipeline cohort | **3 companies, 10 candidates each** | Helia (energy), Ferrum (banking), Vexel (deeptech) |

---

## Part 4 — Before You Walk In

- **Rehearse the paste-the-JD beat hardest.** Slide 10 to 11 is the moment Nadal reacted to. The pause between the loading dots and the reveal is where the product lands.
- **Have the live URL ready to share.** Slide 20 closes on "paste a JD into candela-ed.com." Be ready to do it in the room if the meeting goes long.
- **The candidate beat is in the second half.** Slides 14 to 17 are the recent-graduate story. Tell it like a story.
- **End on the close.** "That is what Candela v8 is for" is the last sentence you say out loud. The CTA panel underneath is for them to take with them.
- **If you overrun,** the cuts are slide 4 (CV stats) or slide 6 (portfolio). The product half does not bend.
