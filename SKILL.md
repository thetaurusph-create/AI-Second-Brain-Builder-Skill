---
name: ai-second-brain-builder
description: Use this skill when the user wants to build, organize, feed, query, or maintain an AI-powered second brain using Obsidian, Markdown files, Notion, Google Drive, or another persistent knowledge vault. This skill turns scattered raw inputs into structured context that an AI assistant can reuse for decisions, projects, people, companies, meetings, and daily memory.
---

# AI Second Brain Builder Skill

## Purpose

This skill helps create and maintain an AI-readable second brain. The goal is not to store everything. The goal is to extract only the context that helps future AI agents make better decisions, remember important relationships, understand the user's operating style, and reuse knowledge without re-explaining it every time.

Default storage recommendation: **Obsidian / Markdown vault** because the files are local, readable, portable, linkable, and easy for AI agents to inspect. Notion or Google Drive may be used when the user prefers them, but Markdown is the default.

## When to Use This Skill

Use this skill when the user asks to:

- Build an AI brain, second brain, personal OS, or company OS.
- Create an Obsidian vault structure for AI use.
- Create `user.md`, `soul.md`, or `identity.md` agent files.
- Convert meeting notes, transcripts, emails, chats, documents, or business data into reusable context.
- Create a daily processing or nightly compounding prompt.
- Organize people, projects, decisions, companies, meetings, daily notes, or knowledge.
- Make an AI assistant act more like the user.
- Reduce repeated context-giving across AI conversations.

## Core Philosophy

1. **Context beats memory.** AI becomes more useful when it has structured files to read from.
2. **Extract signal, not noise.** Do not dump raw data everywhere. Extract decisions, commitments, preferences, insights, and reusable context.
3. **Identity first.** Before feeding information, define who the user is, how the AI should act, and what role the AI plays.
4. **Folders create accuracy.** Without a clear structure, the AI drowns in noise and may hallucinate.
5. **The brain must compound.** A second brain should be cleaned, linked, deduplicated, and summarized regularly.
6. **Every note should become more useful over time.** Link related people, projects, companies, decisions, meetings, and knowledge.
7. **Do not invent context.** If information is missing, mark it as unknown or ask the user only when needed.

## Operating Rules

- Prefer Markdown files and clear headings.
- Use internal links with double brackets when using Obsidian, for example `[[Russ]]` or `[[SeaVital]]`.
- Do not store private, sensitive, or speculative information unless the user explicitly wants it saved.
- Separate raw sources from extracted knowledge.
- Always preserve source traceability when possible: include date, source type, source file/link, and extraction date.
- Do not delete or overwrite important user information without explicit approval.
- When uncertain, create a `Needs Review` section instead of guessing.
- For scheduled maintenance, use **Asia/Manila time** by default when the user is Russ or working in the Philippines. Do not rely only on the computer OS timezone if the user specifically wants Philippine time.

## Default Vault Structure

Create this structure inside the user's vault:

```text
AI-Brain/
├── 00_System/
│   ├── user.md
│   ├── soul.md
│   ├── identity.md
│   ├── brain-rules.md
│   └── inbox-processing-rules.md
├── 01_People/
├── 02_Projects/
├── 03_Decisions/
├── 04_Companies/
├── 05_Meetings/
├── 06_Daily/
├── 07_Knowledge/
├── 08_Maps/
└── 99_Raw/
    ├── transcripts/
    ├── emails/
    ├── chats/
    ├── documents/
    └── screenshots/
```

### Folder Purpose

#### `00_System/`
Contains the identity and operating instructions for the AI brain.

#### `01_People/`
One file per important person. Store relationship context, communication preferences, commitments, relevant projects, and known contact details only if provided.

#### `02_Projects/`
One file per active or archived project. Store goals, status, decisions, next actions, risks, resources, and linked people/companies.

#### `03_Decisions/`
One file per important decision. Store what was decided, why, alternatives considered, tradeoffs, date, owner, and review date.

#### `04_Companies/`
One file per company, brand, vendor, competitor, client, or partner. Store research, offers, pricing, claims, positioning, contacts, and links to related projects.

#### `05_Meetings/`
One file per meeting or call. Extract decisions, commitments, preferences, insights, follow-ups, and linked entities.

#### `06_Daily/`
Daily notes. Keep them short. Capture important events, decisions, energy, constraints, lessons, and anything that should update other files.

#### `07_Knowledge/`
Reusable frameworks, lessons, principles, playbooks, quotes, prompts, SOPs, and insights.

#### `08_Maps/`
Maps of Content. These are index files that connect scattered notes around a topic, such as `Marketing Map.md`, `SeaVital Map.md`, `Cycling Performance Map.md`, or `AI Business OS Map.md`.

#### `99_Raw/`
Raw source material. Store transcripts, documents, chats, screenshots, and original dumps here. The AI should extract from this folder into the structured folders, not treat the raw folder as the final brain.

## Identity Files

Create these three files before feeding the brain.

### `00_System/user.md`

Use this to define who the user is.

```markdown
# User Profile

## Basic Identity
- Name:
- Preferred name:
- Roles:
- Businesses / projects:
- Location / timezone:

## Communication Style
- Preferred language:
- Tone preference:
- Response length preference:
- Formatting preference:
- Words or styles to avoid:

## Values
- What the user cares about:
- What the user dislikes:
- What the user optimizes for:

## Operating Principles
- Key frameworks:
- Decision-making style:
- Risk tolerance:
- Speed vs accuracy preference:

## Current Priorities
- Priority 1:
- Priority 2:
- Priority 3:

## Important Context
- Business context:
- Fitness / personal context:
- Tools used:
- Constraints:

## Unknowns to Clarify Later
- 
```

### `00_System/soul.md`

Use this to define how the AI should behave.

```markdown
# AI Soul

## Voice
- Speak in the user's preferred style.
- Be direct, useful, and practical.
- Prefer frameworks over fluff.
- Use simple language unless the user asks for technical depth.

## Behavior
- Solve before asking.
- Ask questions only when missing information blocks progress.
- If the task is complex, make the best useful version first.
- Challenge weak assumptions respectfully.
- Point out risks, hidden costs, and tradeoffs.
- Make the next action clear.

## Avoid
- Do not use fake certainty.
- Do not invent facts.
- Do not over-explain obvious points.
- Do not use vague advice when a concrete step is possible.
- Do not expose private or sensitive information unnecessarily.

## Default Output Style
- Start with the practical answer.
- Use bullet points when comparing or planning.
- Use tables only when they improve clarity.
- End with one clear next step when useful.
```

### `00_System/identity.md`

Use this to define the AI assistant's role.

```markdown
# AI Identity

## Name
- Assistant name:

## Role
This AI is part chief of staff, part strategist, part operator, part accountability partner, and part knowledge librarian.

## Main Jobs
1. Help the user think clearly.
2. Maintain the second brain.
3. Extract useful context from raw inputs.
4. Connect people, projects, decisions, companies, meetings, daily notes, and knowledge.
5. Turn repeated processes into reusable playbooks.
6. Surface risks, next actions, and forgotten commitments.

## Boundaries
- Do not make live business, financial, ad account, legal, medical, or personal decisions without approval.
- Do not modify or delete source files unless explicitly instructed.
- Do not treat guesses as memory.
```

## File Templates

### Person File Template

Path: `01_People/{Person Name}.md`

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
- [ ] Commitment — owner — due date — source

## Important Context
- 

## Related Meetings
- [[YYYY-MM-DD Meeting Name]]

## Needs Review
- 
```

### Project File Template

Path: `02_Projects/{Project Name}.md`

```markdown
# {Project Name}

## Status
- Stage:
- Owner:
- Priority:
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

## Useful Knowledge
- [[Knowledge Note]]

## Source Notes
- [[Meeting Note]]
- [[Daily Note]]
```

### Decision File Template

Path: `03_Decisions/YYYY-MM-DD - {Decision}.md`

```markdown
# YYYY-MM-DD - {Decision}

## Decision
- 

## Decided By
- 

## Why This Was Chosen
- 

## Alternatives Considered
1. 
2. 
3. 

## Tradeoffs
- Upside:
- Downside:
- Risk:

## Related People
- [[Person Name]]

## Related Projects
- [[Project Name]]

## Review Date
- 

## Source
- 
```

### Company File Template

Path: `04_Companies/{Company Name}.md`

```markdown
# {Company Name}

## Snapshot
- Type: competitor / vendor / client / partner / platform / brand
- Website:
- Market:
- Last updated:

## What They Do
- 

## Offer / Pricing
- 

## Positioning
- 

## Claims / Proof
- 

## People
- [[Person Name]]

## Related Projects
- [[Project Name]]

## Notes
- 

## Sources
- 
```

### Meeting File Template

Path: `05_Meetings/YYYY-MM-DD - {Meeting Name}.md`

```markdown
# YYYY-MM-DD - {Meeting Name}

## Metadata
- Date:
- Participants:
- Source:
- Related project:

## Decisions
- Decision — by whom — why — link to decision file

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
- People:
- Projects:
- Companies:
- Decisions:
- Knowledge:

## Needs Review
- 
```

### Daily File Template

Path: `06_Daily/YYYY-MM-DD.md`

```markdown
# YYYY-MM-DD

## 3-5 Line Day Summary
- 

## Important Decisions
- 

## Commitments Made
- 

## People / Projects Mentioned
- 

## Lessons / Insights
- 

## Tomorrow Review
- 
```

### Knowledge File Template

Path: `07_Knowledge/{Knowledge Title}.md`

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
- 

## Related Notes
- [[Project]]
- [[Decision]]
- [[Meeting]]

## Source
- 
```

### Map of Content Template

Path: `08_Maps/{Topic} Map.md`

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

## First-Run Interview Prompt

When setting up the brain for the first time, interview the user before creating identity files.

```text
I need to create your AI second brain identity files: user.md, soul.md, and identity.md.

Interview me about:
1. Who I am, my roles, businesses, projects, and priorities.
2. How I communicate and how I want AI to communicate with me.
3. What values, principles, and frameworks I use.
4. What I want the AI assistant to do for me.
5. What the AI must never do without approval.
6. What tools and folders I use.
7. What timezone and schedule rules matter.

After the interview, draft:
- 00_System/user.md
- 00_System/soul.md
- 00_System/identity.md
- 00_System/brain-rules.md

Use Markdown. Be practical. Do not invent missing details. Put unknowns under “Unknowns to Clarify Later.”
```

## Meeting Extraction Prompt

Use this prompt for meeting transcripts, Zoom calls, Loom videos, Granola notes, or raw meeting notes.

```text
Extract useful second-brain context from this meeting.

Output in Markdown and skip small talk.

Create these sections:
1. Decisions — what was decided, by whom, and why.
2. Commitments — who promised what, by when.
3. Preferences — how people work, communicate, buy, decide, or react.
4. Key insights — frameworks, strategic shifts, non-obvious observations.
5. People mentioned — create or update person notes if needed.
6. Projects mentioned — create or update project notes if needed.
7. Companies mentioned — create or update company notes if needed.
8. Knowledge notes — reusable lessons, SOPs, principles, or frameworks.
9. Follow-up actions — owner, due date, and next step.
10. Needs review — anything uncertain or risky.

Use links like [[Person]], [[Project]], [[Company]], [[Decision]], and [[Knowledge Note]].
Do not invent facts. If unclear, write “Unknown.”
```

## Daily Brain Dump Prompt

Use this when the user gives scattered daily updates.

```text
Turn this daily dump into structured second-brain notes.

Create or update:
- Today's daily note in 06_Daily/YYYY-MM-DD.md
- Any person notes in 01_People/
- Any project notes in 02_Projects/
- Any decision notes in 03_Decisions/
- Any company notes in 04_Companies/
- Any knowledge notes in 07_Knowledge/
- Any relevant map files in 08_Maps/

Keep the daily summary to 3-5 lines.
Extract only reusable context.
Flag uncertain items under Needs Review.
```

## Nightly Brain Compounding Prompt

Run this manually or on a schedule. For Russ / Philippines workflows, default to **12:01 AM Asia/Manila** unless the user changes it.

```text
Run the nightly brain compounding process using Asia/Manila date and time.

Read everything added or changed in the vault today.

Do the following:
1. Find orphan notes that have no links and add useful links.
2. Find mentions of people, projects, companies, or decisions that do not have files yet.
3. Create missing files using the correct templates.
4. Consolidate duplicate notes without deleting information.
5. Update relevant Maps of Content with new links.
6. Extract reusable lessons into 07_Knowledge/.
7. Update project status and next actions where new information exists.
8. Move uncertain or risky items into Needs Review.
9. Create a short Tomorrow Review list.
10. Produce a final report with:
   - Files created
   - Files updated
   - Links added
   - Duplicates found
   - Strategic items to review tomorrow
   - Errors or uncertainties

Do not delete files.
Do not invent missing facts.
Ask for approval before destructive changes.
```

## Query-the-Brain Prompt

Use this when the user asks the AI to answer using the brain.

```text
Answer using the second brain first.

Search these areas in order:
1. 00_System for identity and rules.
2. 08_Maps for topic-level context.
3. Relevant project, person, company, decision, meeting, daily, and knowledge files.
4. Raw files only if extracted notes are insufficient.

In the answer:
- Cite the specific notes used when possible.
- Separate facts from assumptions.
- Mention missing context if important.
- Give the most practical next action.
```

## Brain Maintenance Checklist

Use this checklist when auditing the second brain.

```markdown
# Brain Maintenance Checklist

## Structure
- [ ] Required folders exist.
- [ ] Identity files exist.
- [ ] Raw files are separate from extracted notes.
- [ ] Maps of Content exist for messy topics.

## Linking
- [ ] People link to projects and meetings.
- [ ] Projects link to decisions and next actions.
- [ ] Decisions link to source meetings or daily notes.
- [ ] Companies link to relevant projects and research.
- [ ] Knowledge notes link to examples.

## Accuracy
- [ ] No invented facts.
- [ ] Uncertain items are marked Needs Review.
- [ ] Dates and sources are included.
- [ ] Duplicate notes are flagged or consolidated.

## Usefulness
- [ ] Daily notes are short and decision-focused.
- [ ] Meeting notes extract commitments and preferences.
- [ ] Projects show current status and next actions.
- [ ] Maps make scattered topics easier to navigate.
```

## Default Assistant Behavior When Using This Skill

When asked to build or improve the brain:

1. Identify the user's current storage tool.
2. If unknown, recommend Obsidian Markdown as the default.
3. Create identity files before creating large amounts of content.
4. Build the folder structure.
5. Create templates.
6. Process raw inputs into structured notes.
7. Link related notes.
8. Create a nightly compounding prompt.
9. Add a review process for strategic items.
10. Keep the system simple enough that the user will actually use it.

## Important Boundary

This skill creates a knowledge operating system. It does not guarantee correctness by itself. The AI must still verify fresh facts, respect privacy, avoid hallucination, and ask for approval before making high-impact or destructive changes.
