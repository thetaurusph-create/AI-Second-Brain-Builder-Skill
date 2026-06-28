---
name: ai-second-brain-builder
description: Use this skill when the user wants to build, organize, feed, query, or maintain an AI-powered second brain using Obsidian and Markdown files. This skill is Obsidian-first and works for any number of businesses, brands, or projects. It is designed so that every new business the user starts can be onboarded into the same brain using a single repeatable process. It turns scattered raw inputs into structured context that an AI assistant can reuse for decisions, projects, people, companies, meetings, and daily memory. It includes beginner-friendly explanations, linking prompts, a new business onboarding prompt, and a nightly compounding loop that makes the brain smarter over time.
---

# AI Second Brain Builder Skill — Obsidian Edition

---

## Why Are We Even Doing This? (Beginner Explanation)

Every time you close a chat with AI, it forgets everything. It does not remember your businesses, your team, your decisions, or your goals. You start from zero every single time. That is a massive waste.

The fix is to give your AI a permanent place to read from — a structured folder on your computer called a **vault** in Obsidian. When your AI can read those files, it stops being a generic tool and starts becoming a digital version of you. One that already knows every business you run, knows your team, knows your decisions, and knows how you like to communicate.

The key design goal of this system is **scalability**. You build the brain once. Every new business you start slots into the same structure without rebuilding anything. The brain just gets bigger, smarter, and more connected over time.

Think of it like this: your real brain does not forget everything when you sleep. It organizes, links, and connects information overnight. We are building the same thing — but for AI — and it works for one business or ten.

---

## The 5-Step System

```
Step 1 → Install the Brain       → Set up Obsidian as your vault (one time only)
Step 2 → Give It an Identity     → Create user.md, soul.md, identity.md (one time only)
Step 3 → Wire the Brain          → Build the folder structure (one time only)
Step 4 → Feed the Brain          → Extract info from meetings, daily dumps, documents (ongoing)
Step 5 → Compound the Brain      → Run a nightly process to link and clean everything (ongoing)

When you start a new business → Run the New Business Onboarding Prompt (repeatable)
```

---

## Step 1 — Install the Brain (Obsidian Setup)

**Why:** Obsidian stores your notes as plain Markdown files (.md) on your own computer. This means any AI — Claude, ChatGPT, or a local agent — can read them. It also has a **Graph View** that shows you a visual map of how all your notes connect, which is the only tool that actually looks and feels like a real brain forming. And because the files are plain text, you never lose access to them regardless of what AI tools you use in the future.

**How to install:**
1. Go to [obsidian.md](https://obsidian.md) and download the free app.
2. Open Obsidian and click **Create new vault**.
3. Name it `AI-Brain` (one vault, all businesses live inside it).
4. Choose a folder on your computer where it will live.

That is it. You do this once. Every business you ever start will live inside this same vault.

---

## Step 2 — Give It an Identity

**Why:** Without identity files, your AI sounds like a corporate robot. It does not know who you are, what businesses you run, or how you like to communicate. These three files fix that permanently. They are the first thing your AI reads every time you talk to it — regardless of which business you are working on.

Create these three files inside a folder called `00_System/`. You do this once. They describe **you**, not your individual businesses. Your businesses each get their own files later.

---

### `00_System/user.md` — Who You Are

```markdown
# User Profile

## Basic Identity
- Name: [Your name]
- Preferred name: [What you want AI to call you]
- Roles: [e.g. Founder, CEO, Investor, Creator — list all]
- Location: [Your country / city]
- Timezone: [e.g. Asia/Manila UTC+8]

## Businesses I Run
<!-- Add a new line here every time you start a new business -->
- [[{Business 1 Name}]] — [One line description]
- [[{Business 2 Name}]] — [One line description]
<!-- New businesses go here -->

## Communication Style
- Preferred language: [e.g. English — direct and clear]
- Tone preference: [e.g. Direct, fast, no fluff]
- Response length: [e.g. Short and actionable unless I ask for depth]
- Formatting: [e.g. Bullets and frameworks over paragraphs]
- Words to avoid: [e.g. "try", "hope", "maybe", "it depends" without a reason]

## Values
- What I care about: [e.g. Execution, systems, leverage, results]
- What I dislike: [e.g. Vague answers, wasted time, repeated explanations]
- What I optimize for: [e.g. Speed of decision-making and clarity]

## Operating Principles
<!-- Add the frameworks and rules you live by -->
- [Principle 1]
- [Principle 2]
- [Principle 3]

## Current Priorities Across All Businesses
- Priority 1:
- Priority 2:
- Priority 3:

## Tools I Use
- Second brain: Obsidian
- AI: Claude
- [Add other tools]

## Constraints
- [e.g. Budget, team size, time, geography]

## Unknowns to Clarify Later
-
```

---

### `00_System/soul.md` — How the AI Should Act

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
- When I mention a business, check 04_Companies/ and 08_Maps/ for that business first before answering from general knowledge.

## Avoid
- Do not invent facts about my businesses.
- Do not assume one business's context applies to another.
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

```markdown
# AI Identity

## Name
- Assistant name: [Pick a name, or ask AI to name itself after 2 weeks of use]

## Role
This AI is part chief of staff, part brand strategist, part operator, part accountability partner, and part knowledge librarian. It supports all businesses the user runs, past and future.

## Main Jobs
1. Help the user think clearly and make faster decisions across all businesses.
2. Maintain the second brain — keep it organized, linked, and clean.
3. Extract useful context from raw inputs like meetings, emails, and notes.
4. Connect people, projects, decisions, companies, meetings, daily notes, and knowledge.
5. Onboard new businesses into the brain using the standard process.
6. Turn repeated processes into reusable playbooks the user can hand to their team.
7. Surface risks, next actions, and forgotten commitments.

## Boundaries
- Do not make live business, financial, ad account, legal, or medical decisions without approval.
- Do not modify or delete source files unless explicitly instructed.
- Do not treat a guess as a memory. If you do not know, say so.
- Do not assume context from one business applies to another.
- Always ask before doing anything that cannot be undone.
```

---

### Pro Tip — Let AI Write These Files For You

You do not need to fill these in manually. Paste this prompt into Claude:

```text
I need to set up my AI second brain in Obsidian. I want you to interview me so you can create three identity files:
- 00_System/user.md (who I am — works across ALL my businesses, not just one)
- 00_System/soul.md (how the AI should act)
- 00_System/identity.md (what role the AI plays)

Ask me questions one at a time about:
1. Who I am, my roles, and all the businesses I currently run
2. How I communicate and what I want AI to sound like
3. My values, principles, and frameworks I operate by
4. What I need AI to do for me across all my businesses daily
5. What the AI must never do without approval
6. What tools I use and what timezone matters

Important: The user.md file must be written so it works for ANY business I run now or in the future. Do not hardcode a specific business. Instead, include a "Businesses I Run" list that I can add to over time.

After the interview, write all three files in Markdown format. Do not invent anything I did not tell you. Put unknowns under "Unknowns to Clarify Later."
```

---

## Step 3 — Wire the Brain (Folder Structure)

**Why:** Without folders, AI drowns in noise. It cannot tell the difference between a note about a supplier for one business and a product decision for another. When it is confused, it guesses wrong. Good folders increase accuracy from 60% to 85%+ when answering questions from the brain. This structure is designed to hold every business you will ever start — you never need to rebuild it.

```text
AI-Brain/
├── 00_System/
│   ├── user.md                    ← Who you are (all businesses)
│   ├── soul.md                    ← How AI acts
│   ├── identity.md                ← What AI's role is
│   ├── brain-rules.md             ← Operating rules for the whole brain
│   └── inbox-processing-rules.md  ← How to process raw inputs
│
├── 01_People/                     ← One file per person (any business)
├── 02_Projects/                   ← One file per project (tagged by business)
├── 03_Decisions/                  ← One file per decision (tagged by business)
├── 04_Companies/                  ← One file per company, brand, supplier, competitor
├── 05_Meetings/                   ← One file per meeting (tagged by business)
├── 06_Daily/                      ← Daily notes (covers all businesses)
├── 07_Knowledge/                  ← Reusable frameworks, SOPs, playbooks, insights
├── 08_Maps/                       ← One map per business + topic maps
└── 99_Raw/
    ├── transcripts/               ← Raw meeting transcripts
    ├── emails/                    ← Raw email threads
    ├── chats/                     ← Raw chat logs
    ├── documents/                 ← Raw PDFs, docs, reports
    └── screenshots/               ← Raw screenshots
```

### What Each Folder Does (Plain English)

**00_System/** — The brain's operating instructions. AI reads this first every time, for every business.

**01_People/** — Every important person across all your businesses gets their own file. Each file tags which business or businesses they are connected to. Example: `John Dela Cruz.md` might be connected to two of your brands at once.

**02_Projects/** — Every active project across every business. Each file includes a `Business:` tag at the top so you and AI always know which brand it belongs to.

**03_Decisions/** — Every important decision across all businesses, logged with context, tradeoffs, and source. This stops you from re-litigating old decisions or forgetting why you chose something.

**04_Companies/** — Every company you interact with: your own brands, suppliers, competitors, partners, distributors. Each of your businesses gets its own company file. New business = new file in this folder.

**05_Meetings/** — One file per meeting, saved as `YYYY-MM-DD Meeting Name.md`, tagged by business. AI extracts decisions, commitments, and preferences from here.

**06_Daily/** — Your daily 3-5 line summary. Covers all businesses in one note per day. Not a diary — just: what happened, what was decided, what to review tomorrow.

**07_Knowledge/** — Reusable things. SOPs. Frameworks. Lessons learned. Prompts that work. A framework you learn in one business can be reused in another — that is the compounding value of this folder.

**08_Maps/** — One master map per business (e.g., `{Business Name} Map.md`). Also topic maps when things get complex (e.g., `Supplier Strategy Map.md`). When you start a new business, you create a new map here.

**99_Raw/** — Raw source material. AI reads this and extracts the useful parts. You never treat raw as final.

---

## Step 4 — Feed the Brain

**Why:** A brain with no information is useless. But the goal is not to dump everything in. The goal is to extract only the signal — the decisions, commitments, preferences, and insights — and file each piece in the right folder under the right business. This is what keeps the brain useful as it grows across multiple businesses.

### How to Feed It

**Option A — Meeting notes:** After any meeting, paste your notes or transcript into Claude and use the Meeting Extraction Prompt below. Works for any business.

**Option B — Granola (automated):** Granola auto-transcribes calls. Set a custom Granola template using the Meeting Extraction Prompt. It will drop clean Markdown files into `05_Meetings/` automatically.

**Option C — Daily brain dump:** At the end of the day, give Claude a quick unstructured dump of what happened across all your businesses. Claude will sort everything into the right folders.

**Option D — New business:** When you launch a new business, use the New Business Onboarding Prompt to register it in the brain in one step.

---

## Prompt Library

These are the exact prompts to use at each stage. Copy and use directly.

---

### Prompt 1 — New Business Onboarding Prompt

**Use this every time you start or add a new business.** This is what makes the brain scalable. One prompt, and your new business is fully registered in the brain.

```text
I am adding a new business to my Obsidian second brain. Please onboard it using the standard process.

Business details:
- Business name: [Name]
- Type: [e.g. product brand, service, SaaS, e-commerce, content]
- Industry: [e.g. health, pet care, real estate, education]
- Description: [One to two sentences on what it does]
- Target market: [Who buys from it]
- Current stage: [Idea / Pre-launch / Active / Scaling]
- Key people involved: [Names and roles if known]
- Key goals right now: [Top 1-3 goals]
- Key challenges right now: [Top 1-3 challenges]
- Tools or platforms used: [e.g. Shopify, Meta Ads, etc.]
- How it connects to my other businesses: [Shared team, same supplier, same audience, etc.]

Please do the following:

1. Create 04_Companies/{Business Name}.md using the company file template. Tag it as "Own Brand."
2. Create 08_Maps/{Business Name} Map.md as the master index for this business.
3. Create any missing People files in 01_People/ for the key people mentioned.
4. Add this business to the "Businesses I Run" list in 00_System/user.md.
5. Check if any existing Knowledge, Decision, or Project files are relevant to this new business and add [[{Business Name}]] links where appropriate.
6. Output a summary of every file created and every link added.

Use [[Obsidian links]] throughout. Do not invent facts I did not provide. Mark unknowns as "Unknown — to be filled."
```

---

### Prompt 2 — Meeting Extraction Prompt

Use after any meeting, call, Zoom, Loom, or transcript — for any business.

```text
Extract useful second-brain context from this meeting for my Obsidian vault.

Business this meeting is about: [Business name — or "multiple" if it covers more than one]

Output everything in Markdown. Skip small talk and filler.

Create these sections:
1. Decisions — What was decided, by whom, and why.
2. Commitments — Who promised what, by when.
3. Preferences — How people work, communicate, buy, or make decisions.
4. Key Insights — Frameworks, strategic shifts, non-obvious observations.
5. People Mentioned — List each person. Create a note in 01_People/ if they do not have one.
6. Projects Mentioned — List each project. Create or update in 02_Projects/. Tag the business.
7. Companies Mentioned — List each company. Create or update in 04_Companies/.
8. Knowledge Notes — Any reusable lessons, SOPs, or frameworks worth saving in 07_Knowledge/.
9. Follow-up Actions — Owner, due date, next step.
10. Needs Review — Anything uncertain, unclear, or risky.

Use Obsidian links: [[Person Name]], [[Project Name]], [[Company Name]], [[Decision Name]], [[Knowledge Title]].

Do not invent facts. If something is unclear, write "Unknown — needs clarification."

Save the final output as: 05_Meetings/YYYY-MM-DD [Meeting Name].md
```

---

### Prompt 3 — Daily Brain Dump Prompt

Use at the end of each day. Talk or type freely — covering any or all businesses. Claude will sort everything.

```text
Turn this daily dump into structured Obsidian second-brain notes. This dump may cover multiple businesses — tag each note with the correct business.

Create or update:
- 06_Daily/YYYY-MM-DD.md (today's daily note — 3-5 lines max, mention which businesses were active today)
- 01_People/ (any person mentioned who does not have a file yet)
- 02_Projects/ (any project mentioned — update status and next actions, tag the business)
- 03_Decisions/ (any decision made today — log with reason and tradeoffs, tag the business)
- 04_Companies/ (any company discussed — update context)
- 07_Knowledge/ (any reusable lesson, framework, or insight)
- 08_Maps/ (update any relevant business map with new links)

Rules:
- Extract only reusable context. Do not dump everything.
- Use [[Obsidian links]] when referencing people, projects, companies, decisions.
- Keep the daily note short: what happened, what was decided, what to review tomorrow.
- Always tag which business a note belongs to.
- Flag uncertain items under "Needs Review."
- Do not invent anything I did not tell you.

Here is my dump for today:
[Paste your notes here]
```

---

### Prompt 4 — File Linking Prompt

Use when you want to make sure all notes across all businesses are properly connected. Run it whenever things feel scattered or after a big batch of new notes.

```text
Audit my Obsidian vault and improve the links between all files across all businesses.

My vault has these folders:
- 00_System, 01_People, 02_Projects, 03_Decisions, 04_Companies, 05_Meetings, 06_Daily, 07_Knowledge, 08_Maps

Do the following:
1. Find every note that mentions a person, project, company, decision, or business but does not have an Obsidian [[link]] to their file. Add the missing links.
2. Find every person file that does not link to their related projects, meetings, and companies. Add the links.
3. Find every project file that does not link to its related decisions, people, and companies. Add the links.
4. Find every meeting file that does not link to its people, projects, and decisions. Add the links.
5. Find orphan notes — notes with no incoming or outgoing links — and suggest where they should link.
6. Check 08_Maps/ — confirm every active business has its own map file. If any business is missing a map, create one.
7. Check that every business map links to its key people, projects, decisions, companies, meetings, and knowledge notes.

Output a list of every change made and every link added, organized by business.
Do not delete anything.
Do not invent connections that do not exist.
```

---

### Prompt 5 — Nightly Brain Compounding Prompt (Manual)

Run this at the end of your day. It makes the brain smarter overnight — across all businesses.

```text
Run the nightly brain compounding process for my Obsidian vault.

Use [your timezone] time. Today's date is [insert date].

Read everything added or changed in the vault today across all businesses, then do the following:

1. ORPHAN NOTES — Find notes with no links. Add useful [[Obsidian links]] to connect them.
2. MISSING FILES — Find mentions of people, projects, companies, or decisions that do not have their own file. Create those files using the correct templates. Tag each with the correct business.
3. DUPLICATES — Find notes that cover the same topic. Consolidate them without deleting information.
4. MAPS OF CONTENT — Update 08_Maps/ files with new notes. Every active business must have a map. If any business map is missing, create it now.
5. KNOWLEDGE EXTRACTION — Extract any reusable lessons, frameworks, or insights into 07_Knowledge/. If a lesson applies across multiple businesses, note that in the file.
6. PROJECT UPDATES — Update project status and next actions in 02_Projects/ based on anything new today. Tag the correct business.
7. NEEDS REVIEW — Move anything uncertain or risky into a "Needs Review" section of the relevant file.
8. TOMORROW REVIEW — Create a short list of the 3-5 most important things to review tomorrow across all businesses.

Output a final report with:
- Files created (list them with business tag)
- Files updated (list them with business tag)
- Links added (list them)
- Duplicates found
- Strategic items to review tomorrow
- Errors or uncertainties

Rules:
- Do not delete any file.
- Do not invent missing facts.
- Do not mix up context from one business with another.
- Ask for approval before any destructive or irreversible change.
```

---

### Prompt 6 — Automated Nightly Compounding (Scheduled Task)

**Why:** Instead of running the prompt manually every night, you can use Claude's scheduled task feature to run it automatically at a fixed time each night. This is what makes the brain improve itself while you sleep — for every business at once.

To set this up:
1. Open Claude and go to **Scheduled Tasks**.
2. Set the time to your preferred nightly time (e.g. 12:01 AM in your timezone).
3. Paste the Nightly Brain Compounding Prompt above as the recurring task.
4. Point it to your Obsidian vault path so Claude can read and update the files.

Once active, every morning you open Obsidian's **Graph View** and see the brain visually growing — new links, new files, more connections across all your businesses. The more connected it gets, the better every answer becomes.

---

### Prompt 7 — Query the Brain Prompt

Use this when you want Claude to answer a question using your brain instead of guessing.

```text
Answer this question using my Obsidian second brain first before using general knowledge.

If this question is about a specific business, check that business's files first.

Search in this order:
1. 00_System — Read my identity, soul, and rules files first.
2. 08_Maps — Check the relevant business map for this topic.
3. Relevant folders — Check 01_People, 02_Projects, 03_Decisions, 04_Companies, 05_Meetings, 06_Daily, 07_Knowledge.
4. 99_Raw — Only if extracted notes are not enough.

In your answer:
- Cite which specific note you used (e.g. "Based on [[Project Name.md]]...")
- Clearly separate what you found in my brain from what you are assuming.
- If this question involves multiple businesses, keep each business's context separate.
- If information is missing from my brain, tell me which file I should create to fix that gap.
- End with: Next step → [one clear action]

My question: [Paste your question here]
```

---

### Prompt 8 — New Business Map Creator

Use after running the New Business Onboarding Prompt, or any time a business needs a cleaner index file.

```text
Create a Map of Content for a business in my Obsidian vault.

Business name: [Name]
Save to: 08_Maps/{Business Name} Map.md

Include these sections:
- Purpose — What this business is and what this map covers
- Key People — Link to everyone in 01_People/ connected to this business
- Active Projects — Link to everything in 02_Projects/ for this business
- Key Decisions — Link to everything in 03_Decisions/ made for this business
- Suppliers / Partners / Competitors — Link to relevant files in 04_Companies/
- Important Meetings — Link to the 5 most recent or relevant meetings in 05_Meetings/
- Key Knowledge — Link to any SOPs, frameworks, or playbooks in 07_Knowledge/ for this business
- How This Business Connects to My Other Businesses — Cross-links to other business maps
- Open Questions — Things still unclear or unresolved for this business
- Needs Cleanup — Notes that need better organization

Use [[File Name]] Obsidian links throughout.
Do not invent content. Leave sections blank if there is nothing to link yet.
Add a "Last Updated:" line at the top.
```

---

## File Templates

These are the standard templates for every folder. When AI creates a new file for any business, it uses these structures.

---

### Person File — `01_People/{Person Name}.md`

```markdown
# {Person Name}

## Snapshot
- Relationship:
- Role / company:
- Connected businesses: [[Business Name]]
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

## Business
- [[Business Name]]

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

## Business
- [[Business Name]]

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
- [Own Brand / Supplier / Competitor / Partner / Client / Distributor]

## Connected Businesses
- [[Business Name]]

## Snapshot
- What they do:
- Why they matter:
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

## Business
- [[Business Name]]

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

## Businesses Active Today
- [[Business Name]]

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

## Applicable Businesses
- [[Business Name]] (or "All businesses")

## Framework / Steps
1.
2.
3.

## Examples
- Example from [[Business Name]]:

## Related Notes
- [[Project]]
- [[Decision]]
- [[Meeting]]

## Source
-
```

---

### Map of Content — `08_Maps/{Business Name} Map.md`

```markdown
# {Business Name} Map
Last Updated:

## Purpose
This map is the master index for [[{Business Name}]]. All important notes about this business link here.

## Key People
- [[Person Name]]

## Active Projects
- [[Project Name]]

## Key Decisions
- [[Decision Name]]

## Suppliers / Partners / Competitors
- [[Company Name]]

## Important Meetings
- [[YYYY-MM-DD Meeting Name]]

## Key Knowledge / SOPs / Playbooks
- [[Knowledge Note]]

## How This Business Connects to My Other Businesses
- [[Other Business Name]] — [How they connect]

## Open Questions
-

## Needs Cleanup
-
```

---

## Nightly Compounding — How the Brain Gets Smarter (Beginner Explanation)

Here is why this matters. When you sleep tonight, your real brain will:
- Organize everything you were exposed to today
- Connect new information to old memories
- Forget things that do not matter
- Strengthen links between things that are related

Your AI brain does the exact same thing — but only if you tell it to. And unlike your real brain, it does this for every business you run simultaneously.

The Nightly Compounding Prompt (Prompt 5 above) does the following across all your businesses:

1. Finds notes that mention someone but have no link to their file — and adds the link
2. Finds people or projects that are mentioned but have no file yet — and creates the file
3. Merges duplicate notes so the brain does not get confused
4. Updates every business Map so each brand's index stays current
5. Extracts reusable lessons into your Knowledge folder — where one lesson can compound across every business
6. Gives you a short list of what to review tomorrow across all brands

Every morning you open Obsidian's **Graph View** and you see the brain visually growing — more nodes, more connections, more intelligence across every business you run. The more links that exist, the more context AI has, and the better every answer becomes.

This is what separates a folder full of notes from an actual brain.

---

## Brain Maintenance Checklist

Run once a week to keep the brain healthy across all businesses.

```markdown
# Brain Maintenance Checklist

## Structure
- [ ] All required folders exist (00_System through 99_Raw)
- [ ] Identity files exist: user.md, soul.md, identity.md
- [ ] Every active business has a map file in 08_Maps/
- [ ] Every active business is listed in 00_System/user.md
- [ ] Raw files are in 99_Raw/ and not mixed into structured folders

## Linking
- [ ] People link to their related projects, meetings, and businesses
- [ ] Projects are tagged with the correct business and link to decisions and people
- [ ] Decisions link to the source meeting or daily note and are tagged by business
- [ ] Company files for own brands link to their related projects and people
- [ ] Knowledge notes note which businesses they apply to

## Accuracy
- [ ] No invented facts anywhere
- [ ] Uncertain items are marked "Needs Review"
- [ ] Every note has a date and a source
- [ ] No duplicate notes on the same topic
- [ ] No business's context is mixed into another business's files

## Usefulness
- [ ] Daily notes are short (3-5 lines) and mention which businesses were active
- [ ] Meeting notes contain extracted commitments and preferences tagged by business
- [ ] Projects show current status and clear next actions
- [ ] Every business map links to the most important active files for that business
```

---

## Default Assistant Behavior When Using This Skill

When asked to build or improve the brain:

1. Confirm the user is using Obsidian as the vault. If not, recommend it and explain why.
2. Create identity files (user.md, soul.md, identity.md) before anything else. These must be business-agnostic.
3. Build the folder structure if it does not exist. It works for one business or twenty.
4. For any new business mentioned, run or suggest the New Business Onboarding Prompt.
5. Always create or update the business's Map file in 08_Maps/ when onboarding a new business.
6. Process raw inputs using the correct extraction prompt and always tag the correct business.
7. Always use `[[Obsidian links]]` when referencing people, projects, companies, decisions, or businesses.
8. Run or suggest the Nightly Compounding Prompt after any major session.
9. Never mix context from one business into another business's files.
10. Keep the system simple enough that the user will actually use it every day, for every business.
11. Teach the why behind each step so the user understands the purpose, not just the process.

---

## Important Boundary

This skill builds a knowledge operating system that scales across any number of businesses. It does not guarantee correctness by itself. The AI must still verify fresh facts, respect privacy, avoid hallucination, and ask for approval before making high-impact or destructive changes to the vault.
