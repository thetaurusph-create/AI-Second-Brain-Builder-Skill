---
name: ai-second-brain-builder
description: Use this skill when the user wants to build, organize, feed, query, or maintain an AI-powered second brain using Obsidian and Markdown files. This skill is Obsidian-first and designed for business owners running multiple brands like SeaVital and PetVitalith. It turns scattered raw inputs into structured context that an AI assistant can reuse for decisions, projects, people, companies, meetings, and daily memory. It includes beginner-friendly explanations, linking prompts, and a nightly compounding loop.
---

# AI Second Brain Builder Skill — Obsidian Edition

---

## Why Are We Even Doing This? (Beginner Explanation)

Every time you close a chat with AI, it forgets everything. It does not remember your businesses, your team, your decisions, or your goals. You start from zero every single time. That is a massive waste.

The fix is to give your AI a permanent place to read from — a structured folder on your computer called a **vault** in Obsidian. When your AI can read those files, it stops being a generic tool and starts becoming a digital version of you — one that already knows you run SeaVital and PetVitalith, knows your team, knows your decisions, and knows how you like to communicate.

Think of it like this: your real brain does not forget everything when you sleep. It organizes, links, and connects information overnight. We are building the same thing — but for AI.

---

## The 5-Step System (From the Transcript)

```
Step 1 → Install the Brain     → Set up Obsidian as your vault
Step 2 → Give It an Identity   → Create user.md, soul.md, identity.md
Step 3 → Wire the Brain        → Build the folder structure
Step 4 → Feed the Brain        → Extract info from meetings, daily dumps, documents
Step 5 → Compound the Brain    → Run a nightly process to link and clean everything
```

---

## Step 1 — Install the Brain (Obsidian Setup)

**Why:** Obsidian stores your notes as plain Markdown files (.md) on your own computer. This means any AI — Claude, ChatGPT, or a local agent — can read them. It also has a **Graph View** that shows you a visual map of how all your notes connect, which is the only tool that actually looks and feels like a real brain forming.

**How to install:**
1. Go to [obsidian.md](https://obsidian.md) and download the free app.
2. Open Obsidian and click **Create new vault**.
3. Name it something like `AI-Brain` or `SeaVital-Brain`.
4. Choose a folder on your computer where it will live.

That is it. You now have the container. Now we fill it.

---

## Step 2 — Give It an Identity

**Why:** Without identity files, your AI sounds like a corporate robot. It does not know you run SeaVital, that you prefer direct answers, or that PetVitalith is a separate brand. These three files fix that. They are the first thing your AI reads every time you talk to it.

Create these three files inside a folder called `00_System/`:

---

### `00_System/user.md` — Who You Are

This file tells the AI about you. Copy this into Obsidian and fill in your details.

```markdown
# User Profile

## Basic Identity
- Name: [Your name]
- Preferred name: [What you want AI to call you]
- Roles: Founder, CEO, Brand Owner
- Businesses: SeaVital (marine health supplements), PetVitalith (pet health products)
- Location: Philippines
- Timezone: Asia/Manila (UTC+8)

## Communication Style
- Preferred language: English (direct and clear)
- Tone preference: Direct, fast, no fluff
- Response length: Short and actionable unless I ask for depth
- Formatting: Bullets and frameworks over paragraphs
- Words to avoid: "try", "hope", "maybe", "it depends" (without a reason)

## Values
- What I care about: Execution, systems, leverage, results
- What I dislike: Vague answers, wasted time, repeated explanations
- What I optimize for: Speed of decision-making and clarity

## Operating Principles
- Minimum effective dose — do the least to get the most
- Frameworks over opinions — give me a structure I can reuse
- Direct before diplomatic — tell me the truth first

## Current Priorities
- Priority 1: Grow SeaVital product reach
- Priority 2: Build PetVitalith brand presence
- Priority 3: Build AI systems so the business runs without me explaining everything twice

## Business Context
- SeaVital: [Add your current product lineup, target market, key issues]
- PetVitalith: [Add your current product lineup, target market, key issues]
- Tools used: Obsidian, Claude, [add others]
- Constraints: [Budget, team size, timeline constraints]

## Unknowns to Clarify Later
- 
```

---

### `00_System/soul.md` — How the AI Should Act

This file tells the AI how to behave when talking to you. Think of it as the personality settings.

```markdown
# AI Soul

## Voice
- Talk like a sharp, direct founder to founder.
- No hedging. No "it depends" without a reason.
- Give the answer first. Explain after if needed.
- Use frameworks. I think in systems.

## Behavior
- Solve before asking. If you can make a good first attempt, do it.
- Ask one question at a time if you must ask.
- Challenge weak assumptions with respect. Point out what I might be missing.
- Always surface the risk or hidden cost of a decision.
- End with one clear next action when relevant.

## Context to Always Remember
- I run SeaVital (marine health supplements) and PetVitalith (pet health products).
- Both are Philippine-based brands.
- My time is limited. Every answer should save me time, not cost me more.

## Avoid
- Do not invent facts about my business.
- Do not over-explain obvious things.
- Do not give generic advice when specific steps are possible.
- Do not expose sensitive business info unless I ask you to include it.

## Default Output Style
- Start with the answer or the action.
- Use bullets for comparisons and plans.
- Use tables only when comparing multiple options.
- End with: Next step → [one clear action]
```

---

### `00_System/identity.md` — Who the AI Is

This file defines the role your AI plays in your life and business.

```markdown
# AI Identity

## Name
- Assistant name: [Pick a name, or let the AI name itself after 2 weeks of use]

## Role
This AI is part chief of staff, part brand strategist, part operator, part accountability partner, and part knowledge librarian for SeaVital and PetVitalith.

## Main Jobs
1. Help me think clearly and make faster decisions.
2. Maintain the second brain — keep it organized, linked, and clean.
3. Extract useful context from raw inputs like meetings, emails, and notes.
4. Connect people, projects, decisions, companies, meetings, daily notes, and knowledge.
5. Turn repeated processes into reusable playbooks I can hand to my team.
6. Surface risks, next actions, and forgotten commitments.

## Boundaries
- Do not make live business, financial, ad account, legal, or medical decisions without my approval.
- Do not modify or delete source files unless I explicitly say so.
- Do not treat a guess as a memory. If you don't know, say so.
- Always ask before doing anything that cannot be undone.
```

---

### Pro Tip — Let AI Write These Files For You

You do not need to fill these in manually. Paste this prompt into Claude:

```text
I need to set up my AI second brain. I want you to interview me so you can create three identity files:
- 00_System/user.md (who I am)
- 00_System/soul.md (how the AI should act)
- 00_System/identity.md (what role the AI plays)

Ask me questions one at a time about:
1. Who I am, my roles, and my businesses (I run SeaVital and PetVitalith in the Philippines)
2. How I communicate and what I want AI to sound like
3. My values, principles, and frameworks
4. What I need AI to do for me daily
5. What the AI must never do without approval
6. What tools I use and what timezone matters

After the interview, write all three files in Markdown format. Do not invent anything I did not tell you. Put unknowns under "Unknowns to Clarify Later."
```

---

## Step 3 — Wire the Brain (Folder Structure)

**Why:** Without folders, AI drowns in noise. It cannot tell the difference between a note about your SeaVital supplier and a random idea you wrote down. When it is confused, it guesses — and guesses wrong. Good folders increase accuracy from 60% to 85%+ when answering questions from the brain.

Create these folders inside your Obsidian vault:

```text
AI-Brain/
├── 00_System/
│   ├── user.md                  ← Who you are
│   ├── soul.md                  ← How AI acts
│   ├── identity.md              ← What AI's role is
│   ├── brain-rules.md           ← Operating rules for the whole brain
│   └── inbox-processing-rules.md ← How to process raw inputs
├── 01_People/                   ← One file per important person
├── 02_Projects/                 ← One file per active project
├── 03_Decisions/                ← One file per important decision
├── 04_Companies/                ← SeaVital, PetVitalith, suppliers, competitors
├── 05_Meetings/                 ← One file per meeting or call
├── 06_Daily/                    ← Daily notes (3-5 line summaries)
├── 07_Knowledge/                ← Frameworks, SOPs, playbooks, insights
├── 08_Maps/                     ← Index files connecting scattered notes
└── 99_Raw/
    ├── transcripts/             ← Raw meeting recordings or transcripts
    ├── emails/                  ← Raw email threads
    ├── chats/                   ← Raw chat logs
    ├── documents/               ← Raw PDFs, docs, reports
    └── screenshots/             ← Raw screenshots
```

### What Each Folder Does (Plain English)

**00_System/** — The brain's instructions. AI reads this first every time.

**01_People/** — Every important person gets their own file. For example: `Maria Santos.md` (your SeaVital operations lead) would have her contact, her communication style, her commitments, and what projects she is on.

**02_Projects/** — Every active project gets a file. For example: `SeaVital Q3 Launch.md` would have the goal, current strategy, key decisions, next actions, and risks.

**03_Decisions/** — Every important decision you make gets recorded here. Why did you choose supplier A over B? What were the tradeoffs? This stops you from re-litigating the same decisions later.

**04_Companies/** — Every company you deal with: SeaVital (your own), PetVitalith (your own), suppliers, competitors, partners, distributors. Store research, pricing, key contacts, and positioning.

**05_Meetings/** — One file per meeting. Saved as `YYYY-MM-DD Meeting Name.md`. AI extracts decisions, commitments, and preferences from here.

**06_Daily/** — Your daily 3-5 line summary. Not a diary. Just: what happened, what was decided, what to review tomorrow.

**07_Knowledge/** — Reusable things. SOPs. Frameworks. Lessons learned. Prompts that work. For example: `How to Brief a Supplier.md` or `SeaVital Positioning Framework.md`.

**08_Maps/** — Index files that connect scattered notes on one topic. For example: `SeaVital Map.md` would link to every person, project, company, and decision related to SeaVital. This is your shortcut when things get complex.

**99_Raw/** — Raw stuff goes here. AI reads it and extracts the useful parts into the structured folders above. You never treat raw as final.

---

## Step 4 — Feed the Brain

**Why:** A brain with no information is useless. But the goal is not to dump everything in. The goal is to extract only the signal — the decisions, the commitments, the preferences, the insights — and put each piece in the right folder.

Think of it like your real brain. Right now thousands of signals are hitting you — temperature, sounds, light. Your brain filters all of that and only keeps what matters. This system does the same thing.

### How to Feed It

**Option A — Meeting notes (manual):** After every meeting, paste your notes or transcript into Claude and use the Meeting Extraction Prompt below.

**Option B — Granola (automated):** Granola auto-transcribes your calls and applies a custom template. Set your Granola template to the Meeting Extraction Prompt below and it will drop clean Markdown files directly into `05_Meetings/`.

**Option C — Daily brain dump:** At the end of the day, give Claude a quick unstructured dump of what happened. Claude will sort it into the right folders using the Daily Brain Dump Prompt below.

---

## Prompt Library

These are the exact prompts to use at each stage. Copy them directly.

---

### Prompt 1 — Meeting Extraction Prompt

Use after any meeting, call, Zoom, Loom, or transcript.

```text
Extract useful second-brain context from this meeting for my Obsidian vault.

I run SeaVital (marine health supplements) and PetVitalith (pet health products) in the Philippines.

Output everything in Markdown. Skip small talk and filler.

Create these sections:
1. Decisions — What was decided, by whom, and why.
2. Commitments — Who promised what, by when.
3. Preferences — How people work, communicate, buy, or make decisions.
4. Key Insights — Frameworks, strategic shifts, non-obvious observations.
5. People Mentioned — List each person. Create a note if they do not have one.
6. Projects Mentioned — List each project. Create or update a note.
7. Companies Mentioned — List each company. Create or update a note.
8. Knowledge Notes — Any reusable lessons, SOPs, or frameworks worth saving.
9. Follow-up Actions — Owner, due date, and next step.
10. Needs Review — Anything uncertain, unclear, or risky.

Use Obsidian internal links like [[Person Name]], [[Project Name]], [[Company Name]], [[Decision Name]], and [[Knowledge Title]].

Do not invent facts. If something is unclear, write "Unknown — needs clarification."

Save the final output as: 05_Meetings/YYYY-MM-DD [Meeting Name].md
```

---

### Prompt 2 — Daily Brain Dump Prompt

Use at the end of each day. Just talk or type freely. Claude will organize it.

```text
Turn this daily dump into structured Obsidian second-brain notes.

I run SeaVital and PetVitalith in the Philippines. Use Asia/Manila time for dates.

Create or update these files:
- 06_Daily/YYYY-MM-DD.md (today's daily note — keep it to 3-5 lines)
- 01_People/ (any person mentioned who does not have a file yet)
- 02_Projects/ (any project mentioned — update status and next actions)
- 03_Decisions/ (any decision made today — log it with reason and tradeoffs)
- 04_Companies/ (any company discussed — update context)
- 07_Knowledge/ (any reusable lesson, framework, or insight)
- 08_Maps/ (update any relevant map with new links)

Rules:
- Extract only reusable context. Do not dump everything.
- Use Obsidian links like [[Person]], [[Project]], [[Company]], [[Decision]].
- Keep the daily note short: what happened, what was decided, what to review tomorrow.
- Flag uncertain items under "Needs Review."
- Do not invent anything I did not tell you.

Here is my dump for today:
[Paste your notes here]
```

---

### Prompt 3 — File Linking Prompt

Use this when you want to make sure all your notes are properly connected to each other. Run it anytime things feel scattered.

```text
I need you to audit my Obsidian vault and improve the links between files.

My vault has these folders:
- 00_System (identity files)
- 01_People
- 02_Projects
- 03_Decisions
- 04_Companies
- 05_Meetings
- 06_Daily
- 07_Knowledge
- 08_Maps

Do the following:
1. Find every note that mentions a person, project, company, or decision but does not have an Obsidian link to their file. Add the missing links using [[File Name]] format.
2. Find every person file that does not link to their related projects and meetings. Add the links.
3. Find every project file that does not link to its related decisions, people, and companies. Add the links.
4. Find every meeting file that does not link to its people, projects, and decisions. Add the links.
5. Find any orphan notes — notes with no incoming or outgoing links — and suggest where they should link.
6. Check if SeaVital and PetVitalith each have a Map file in 08_Maps. If not, create one.

Output a list of every change made and every link added.
Do not delete anything.
Do not invent connections that do not exist.
```

---

### Prompt 4 — Nightly Brain Compounding Prompt (Manual Version)

Run this at the end of your day or before sleep. It makes the brain smarter overnight.

```text
Run the nightly brain compounding process for my Obsidian vault.

Use Asia/Manila time. Today's date is [insert date].

Read everything added or changed in the vault today, then do the following:

1. ORPHAN NOTES — Find notes with no links. Add useful Obsidian links to connect them.
2. MISSING FILES — Find mentions of people, projects, companies, or decisions that do not have their own file. Create those files using the correct templates.
3. DUPLICATES — Find notes that cover the same topic. Consolidate them without deleting any information.
4. MAPS OF CONTENT — Update 08_Maps/ files with any new notes that should appear there. If SeaVital or PetVitalith do not have a map, create one now.
5. KNOWLEDGE EXTRACTION — Extract any reusable lessons, frameworks, or insights into 07_Knowledge/.
6. PROJECT UPDATES — Update project status and next actions in 02_Projects/ based on anything new learned today.
7. NEEDS REVIEW — Move anything uncertain, incomplete, or risky into a "Needs Review" section of the relevant file.
8. TOMORROW REVIEW — Create a short list of the 3-5 most important things to review tomorrow.

Output a final report with:
- Files created (list them)
- Files updated (list them)
- Links added (list them)
- Duplicates found (list them)
- Strategic items to review tomorrow
- Errors or uncertainties

Rules:
- Do not delete any file.
- Do not invent missing facts.
- Ask for my approval before any destructive or irreversible change.
```

---

### Prompt 5 — Automated Nightly Compounding (Claude Scheduled Task)

**Why:** Instead of running the prompt manually every night, you can use Claude's scheduled task feature to run it automatically at 12:01 AM Manila time. This is what the transcript calls "automating the brain so it improves itself while you sleep."

To set this up in Claude:
1. Open Claude and go to **Scheduled Tasks** (or use Claude's Projects feature with a recurring prompt).
2. Set the time to **12:01 AM Asia/Manila**.
3. Paste the Nightly Brain Compounding Prompt above as the recurring task.
4. Point it to your Obsidian vault path so Claude can access the files.

Once this runs, every morning you open Obsidian's **Graph View** and you will see new links forming, new files appearing, and the brain visually growing and organizing itself overnight.

---

### Prompt 6 — Query the Brain Prompt

Use this when you want Claude to answer a question using your brain instead of guessing.

```text
Answer this question using my Obsidian second brain first before using general knowledge.

Search in this order:
1. 00_System — Read my identity, soul, and rules files first.
2. 08_Maps — Check if there is a relevant map for this topic.
3. Relevant folders — Check 01_People, 02_Projects, 03_Decisions, 04_Companies, 05_Meetings, 06_Daily, 07_Knowledge.
4. 99_Raw — Only check raw files if extracted notes are not enough.

In your answer:
- Cite which specific note you used (e.g., "Based on [[SeaVital Q3 Launch.md]]...")
- Clearly separate what you found in my brain from what you are assuming.
- If information is missing from my brain, tell me what file I should create to fix that gap.
- End with: Next step → [one clear action]

My question: [Paste your question here]
```

---

### Prompt 7 — SeaVital and PetVitalith Map Creator

Run this once to create the two most important index files for your businesses.

```text
Create two Maps of Content for my Obsidian vault in the 08_Maps/ folder.

Map 1: SeaVital Map.md
Map 2: PetVitalith Map.md

For each map, create sections for:
- Purpose (what this brand is and what this map covers)
- Key People (link to anyone in 01_People/ connected to this brand)
- Active Projects (link to anything in 02_Projects/ for this brand)
- Key Decisions (link to anything in 03_Decisions/ made for this brand)
- Suppliers / Partners (link to anything in 04_Companies/ related to this brand)
- Important Meetings (link to the 5 most recent or relevant meetings in 05_Meetings/)
- Key Knowledge (link to any SOPs, frameworks, or playbooks in 07_Knowledge/ for this brand)
- Open Questions (things still unclear or unresolved)
- Needs Cleanup (notes that need better organization)

Use [[File Name]] Obsidian links throughout.
Do not invent content. Leave sections blank if there is nothing to link yet.
```

---

## File Templates

These are the ready-to-use templates for each folder. When AI creates a new file, it uses these structures.

### Person File — `01_People/{Person Name}.md`

```markdown
# {Person Name}

## Snapshot
- Relationship:
- Role / company:
- Contact info:
- First mentioned:
- Last updated:

## Communication Preferences
- Style:
- Likes:
- Dislikes:
- Best channel:

## Relevant Projects
- [[Project Name]]

## Commitments
- [ ] Commitment — owner — due date — source meeting

## Important Context
- 

## Related Meetings
- [[YYYY-MM-DD Meeting Name]]

## Related Companies
- [[Company Name]]

## Needs Review
- 
```

---

### Project File — `02_Projects/{Project Name}.md`

```markdown
# {Project Name}

## Status
- Stage: [Planning / Active / On Hold / Done]
- Owner:
- Priority: [High / Medium / Low]
- Last updated:

## Goal
- 

## Current Strategy
- 

## Key Decisions
- [[Decision Name]]

## People Involved
- [[Person Name]]

## Companies / Tools
- [[Company Name]]

## Next Actions
- [ ] Action — owner — due date

## Risks / Constraints
- 

## Related Meetings
- [[YYYY-MM-DD Meeting Name]]

## Needs Review
- 
```

---

### Decision File — `03_Decisions/{Decision Name}.md`

```markdown
# {Decision Name}

## What Was Decided
- 

## Why
- 

## Alternatives Considered
- Option A:
- Option B:

## Tradeoffs
- 

## Date Decided:
## Owner:
## Review Date:

## Source
- [[YYYY-MM-DD Meeting Name]] or [[YYYY-MM-DD Daily Note]]

## Needs Review
- 
```

---

### Company File — `04_Companies/{Company Name}.md`

```markdown
# {Company Name}

## Type
- [Supplier / Competitor / Partner / Client / Own Brand]

## Snapshot
- What they do:
- Why they matter to SeaVital or PetVitalith:
- Key contact: [[Person Name]]
- Last updated:

## Research / Notes
- 

## Pricing / Terms
- 

## Related Projects
- [[Project Name]]

## Related Meetings
- [[YYYY-MM-DD Meeting Name]]

## Needs Review
- 
```

---

### Meeting File — `05_Meetings/YYYY-MM-DD {Meeting Name}.md`

```markdown
# YYYY-MM-DD {Meeting Name}

## Attendees
- [[Person Name]]

## Decisions
- What was decided — by whom — why

## Commitments
- [ ] Who promised what — due date

## Preferences
- Person — preference — evidence

## Key Insights
- Frameworks:
- Strategic shifts:
- Non-obvious observations:

## Follow-ups
- [ ] Action — owner — due date

## Links Created
- People: [[Name]]
- Projects: [[Name]]
- Companies: [[Name]]
- Decisions: [[Name]]
- Knowledge: [[Name]]

## Needs Review
- 
```

---

### Daily File — `06_Daily/YYYY-MM-DD.md`

```markdown
# YYYY-MM-DD

## Day Summary (3-5 lines max)
- 

## Important Decisions
- 

## Commitments Made
- 

## People / Projects / Companies Mentioned
- 

## Lessons / Insights
- 

## Tomorrow Review
- 
```

---

### Knowledge File — `07_Knowledge/{Knowledge Title}.md`

```markdown
# {Knowledge Title}

## Core Idea
- 

## When to Use
- 

## Framework / Steps
1. 
2. 
3. 

## Examples
- SeaVital example:
- PetVitalith example:

## Related Notes
- [[Project]]
- [[Decision]]
- [[Meeting]]

## Source
- 
```

---

### Map of Content — `08_Maps/{Topic} Map.md`

```markdown
# {Topic} Map

## Purpose
This map connects the most important notes about {Topic}.

## Core Notes
- [[Important Note 1]]
- [[Important Note 2]]

## People
- [[Person Name]]

## Projects
- [[Project Name]]

## Decisions
- [[Decision Name]]

## Companies
- [[Company Name]]

## Knowledge / Frameworks
- [[Knowledge Note]]

## Open Questions
- 

## Needs Cleanup
- 
```

---

## Nightly Compounding — How the Brain Gets Smarter (Beginner Explanation)

Here is why this matters. When you sleep tonight, your real brain will:
- Organize what you learned today
- Connect new information to old memories
- Forget things that do not matter
- Strengthen links between things that are related

Your AI brain does the exact same thing — but only if you tell it to. The Nightly Compounding Prompt (Prompt 4 above) runs this process on your Obsidian vault. It:

1. Finds notes that mention someone but have no link to their file — and adds the link
2. Finds people or projects that are mentioned but have no file yet — and creates the file
3. Merges duplicate notes so the brain does not get confused
4. Updates your Maps of Content so SeaVital and PetVitalith stay organized
5. Extracts reusable lessons into your Knowledge folder
6. Gives you a short list of what to review tomorrow

Every morning you open Obsidian's **Graph View** and you see the brain visually growing — more nodes, more connections, more intelligence. The more links that exist, the more context AI has when you ask it a question, and the better its answers get.

---

## Brain Maintenance Checklist

Run this once a week to make sure the brain stays healthy.

```markdown
# Brain Maintenance Checklist

## Structure
- [ ] All required folders exist (00_System through 99_Raw)
- [ ] Identity files exist: user.md, soul.md, identity.md
- [ ] SeaVital Map and PetVitalith Map exist in 08_Maps/
- [ ] Raw files are in 99_Raw/ and not mixed into structured folders

## Linking
- [ ] People link to their related projects and meetings
- [ ] Projects link to their decisions, people, and companies
- [ ] Decisions link to the source meeting or daily note
- [ ] Companies (SeaVital, PetVitalith, suppliers) link to relevant projects
- [ ] Knowledge notes link to real examples from SeaVital or PetVitalith

## Accuracy
- [ ] No invented facts anywhere
- [ ] Uncertain items are marked "Needs Review"
- [ ] Every note has a date and a source
- [ ] No duplicate notes on the same topic

## Usefulness
- [ ] Daily notes are short (3-5 lines) and decision-focused
- [ ] Meeting notes contain extracted commitments and preferences
- [ ] Projects show current status and clear next actions
- [ ] Maps connect scattered topics into one reference file
```

---

## Default Assistant Behavior When Using This Skill

When asked to build or improve the brain:

1. Confirm the user is using Obsidian as the vault. If not, recommend it.
2. Create identity files (user.md, soul.md, identity.md) before anything else.
3. Build the folder structure if it does not exist.
4. Create SeaVital and PetVitalith map files in 08_Maps/ early.
5. Process raw inputs using the correct extraction prompt.
6. Always use `[[Obsidian links]]` when referencing people, projects, companies, decisions, or meetings.
7. Run or suggest the Nightly Compounding Prompt after any major session.
8. Keep the system simple enough that the user will actually use it every day.
9. Teach the why behind each step so the user understands the purpose, not just the process.

---

## Important Boundary

This skill builds a knowledge operating system. It does not guarantee correctness by itself. The AI must still verify fresh facts, respect privacy, avoid hallucination, and ask for approval before making high-impact or destructive changes to the vault.
