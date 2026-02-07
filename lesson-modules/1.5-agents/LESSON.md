# Lesson 1.5: Agents

Remember those competitor files, past work folders, and the CSV data we saw but didn't touch? They're all in `inherited-chaos/` - take a look if you need a refresher.

Now we handle them.

This is where things get crazy.

STOP: Ready to process EVERYTHING at once?

USER: Yes

---

## The Big Reveal - Parallel Processing

**The Big Reveal:** We have a whole folder of past work files to analyze - previous initiatives, old plans, past attempts at solving this problem.

Normally you'd read them one by one. That would take forever. It would even take me a while.

Instead, I can spin up multiple agents - independent instances of myself - and process them simultaneously.

Think of it like cloning myself. I give each clone their own task. All clones work at the same time.

Then I combine their findings.

STOP: This is one of the most powerful features in Claude Cowork. Tasks that would take hours manually happen in seconds. Ready to see it in action?

USER: Yes

---

## Decision Quiz

STOP: Quick quiz - when should you use agents? A) One complex task, or B) Many similar tasks?

USER: B / Many similar tasks

Exactly! Agents are for parallelizable work - many similar things that can be done independently.

STOP: Ready to see it in action?

USER: Yes

---

## Initiative Analysis - Multiple Agents

Let's start with the past work files from `inherited-chaos/`.

STOP: Ask me to use agents to analyze all the past initiative files in inherited-chaos/ and figure out which ideas are worth salvaging.

USER: Types request about analyzing past work files with agents

CLAUDE INSTRUCTIONS: Identify the largest folder (or set of related folders) of past work files in the student's `inherited-chaos/` directory. These are the "many similar files" that make agents shine. The specific folder varies by scenario:
- bookstore: inherited-chaos/marketing-ideas/ (6 files)
- event-planning: inherited-chaos/old-festivals/ (4 files)
- freelancer: inherited-chaos/client-projects/ (3 subfolders with ~18 files total)
- hr-people-ops: the many scattered policy/compliance docs across inherited-chaos/
- loyalty-program: inherited-chaos/old-campaigns/ (10 files)
- nonprofit-grant: inherited-chaos/previous-applications/ (3 files) + budget-drafts/ (3 files) + impact-data/ (5 files)
- product-launch: inherited-chaos/launch-materials/ (5 files) + meeting-notes/ (4 files)
- real-estate: inherited-chaos/deal-files/ (5 files) + showing-notes/ (2 files)
- restaurant-rebrand: inherited-chaos/menu-experiments/ (5 files)

Launch agents to process these files in parallel. Each agent should analyze one file (or a small group) and report on:
- What was attempted
- What worked (if anything)
- What failed or was abandoned
- Any patterns or recurring themes

Synthesize results into analysis/initiative-salvage-report.md. The report should identify: which ideas are worth salvaging, what patterns emerge across all the past work, and what was tried repeatedly without success.

Do NOT hardcode findings. Read the actual files and report what they contain. The key discovery should emerge from the data itself.

I've created analysis/initiative-salvage-report.md with the findings.

STOP: That just happened in parallel. All those files, analyzed simultaneously, synthesized into one report. Imagine doing this with 100 customer interviews, or a year's worth of meeting notes. This is where Cowork starts feeling like a superpower. Ready for more?

USER: Yes

---

## Advanced: Cross-Source Analysis

Now let's do something more advanced. We've analyzed past initiatives and competitors separately. Let's connect the dots.

I'll use multiple agents, each doing something DIFFERENT:

- **Agent 1:** Analyze the data file(s) - what do the numbers tell us?
- **Agent 2:** Cross-reference competitor research vs past initiatives - what are competitors doing that we tried and failed at?
- **Agent 3:** Connect feedback and communications themes to competitor insights - what are stakeholders asking for that competitors already offer?
- **Agent 4:** Identify gaps - what works elsewhere that hasn't been tried here?

Then synthesize into one comprehensive picture.

STOP: Ask me to use multiple agents to: analyze the data files, cross-reference competitors vs our past initiatives, connect feedback to competitor strengths, and identify gaps. Then synthesize it all.

USER: Types request for multi-agent analysis

CLAUDE INSTRUCTIONS: Launch 4 specialized agents for cross-source analysis. The specific files vary by scenario:

**Agent 1 - Data/CSV Analysis.** Find and analyze the CSV or data files:
- bookstore: sales-data.csv
- event-planning: budget-draft.csv + vendor-status.csv
- freelancer: master-client-tracker.csv + time-tracking-export-jan.csv
- hr-people-ops: employee-master-list.csv + pto-tracking-chaos.csv + terminated-employees.csv
- loyalty-program: member-data-summary.csv
- nonprofit-grant: attendance-actuals.csv (in impact-data/)
- product-launch: feature-requests.csv
- real-estate: crm-export-partial.csv + lead-database.csv
- restaurant-rebrand: customer-surveys.csv

Look for trends, anomalies, and what the numbers reveal that the narrative files might miss.

**Agent 2 - Competitor vs Past Initiatives.** Cross-reference the competitor-research/ (or competitor-analysis/) folder against the initiative-salvage-report.md. What are competitors succeeding at that the predecessor tried and failed at? What does that gap tell us?

**Agent 3 - Feedback/Communications Analysis.** Analyze the feedback or communications files:
- bookstore: customer-feedback/ (5 files)
- event-planning: sponsor-communications/ (5 files)
- freelancer: client-communications/ (4 files)
- hr-people-ops: scattered individual feedback/complaint files in inherited-chaos/
- loyalty-program: customer-feedback/ (4 files)
- nonprofit-grant: beneficiary-stories/ (4 files)
- product-launch: customer-complaints/ (5 files)
- real-estate: client-communications/ (8 files)
- restaurant-rebrand: social-media-analysis/ (4 files)

Connect these themes to competitor insights. What are stakeholders asking for?

**Agent 4 - Gap Analysis.** Based on what the other agents are finding, identify: what approaches work elsewhere in this industry that have never been tried here? What's the unexplored territory?

Synthesize everything into analysis/comprehensive-research-synthesis.md. The synthesis should connect findings across all four agents into a coherent picture. Let the actual data drive the conclusions - do NOT invent or hardcode findings.

I've created analysis/comprehensive-research-synthesis.md with everything combined.

STOP: See how connecting different sources reveals things you'd miss looking at them separately?

USER: Yes

---

## The Core Discovery

CLAUDE INSTRUCTIONS: Based on all the analysis completed so far (initiative-salvage-report.md and comprehensive-research-synthesis.md), synthesize the findings and identify THE CORE PROBLEM.

This should be a specific, actionable insight - not a generic observation. It should feel like a revelation that reframes everything. The kind of insight where the student thinks "oh, THAT'S what's really going on."

Every scenario has its own core discovery that emerges naturally from the files. Read your synthesis reports and identify the single biggest problem - the root cause that explains why past initiatives failed, why the numbers look the way they do, and what stakeholders are really asking for even if they can't articulate it.

Present it as a clear, quotable statement. Format it as:

**THE CORE DISCOVERY:** "[The specific insight for this scenario]"

This should be a genuine finding from the data, not a platitude. Bad example: "They need better communication." Good example: a specific structural or strategic problem that, once you see it, makes everything else click.

Connecting this to the overall story:

**THE CORE DISCOVERY:** The insight that changes everything about how we see this situation.

STOP: Are you seeing it? This is the thread that ties everything together.

USER: Yes

---

## The Solution Seed

CLAUDE INSTRUCTIONS: Connect back to the promising idea that was discovered in the handoff notes during lesson 1.3. Every scenario has a "seed" buried in the predecessor's notes - a half-baked idea or abandoned direction that, in light of the core discovery, now looks like a real opportunity.

Show the student how the core problem VALIDATES that earlier idea. The predecessor stumbled onto something but didn't see the full picture. Now, with the comprehensive analysis complete, that throwaway idea looks like the beginning of a real solution.

Present this as a callback moment: "Remember that idea from the handoff notes? It's starting to make a lot more sense now."

Explain specifically how the core discovery and the idea seed connect - why the idea addresses the root cause, not just the symptoms.

This connects back to the seed from earlier... that half-baked idea is starting to make sense.

STOP: We're going to develop this further in the next lessons. For now, let it sit. The best ideas need time to take shape.

USER: Yes

---

## Agent Decision Framework

So when should you use agents?

**Use agents when:**
- You have many similar files to process
- Tasks can run in parallel (don't depend on each other)
- You need to research across multiple sources
- You want different perspectives on the same thing

**Don't use agents when:**
- You have one complex task that needs deep focus
- Work is sequential (each step depends on the previous)
- You need to iterate on a single document

STOP: The mental model: if you could hand the same instructions to 10 interns and have them each work independently, agents are perfect. If the work requires back-and-forth or builds on itself, stick with regular conversation. Clear?

USER: Yes

---

## Wrap-up

**Meta skill:** Parallel processing - handling many similar tasks simultaneously instead of one at a time.

**When to use agents:** You have multiple similar things that need the same type of analysis. The work is parallelizable - each piece can be done independently.

**Where else this applies:**
- 10 job postings for roles you're considering - analyze all of them at once, compare requirements
- 5 vendors you're evaluating - research each one in parallel, synthesize into a comparison
- 20 articles you've saved to read - have agents summarize each, then synthesize the key insights
- Apartment hunting - 8 listings to analyze for pros/cons/red flags simultaneously
- Competitive analysis - research 6 competitors at once instead of one by one
- Planning a trip - agents researching flights, hotels, activities, restaurants all at once

**Next up:** In 1.6, you'll learn about document creation - creating professional Word documents, Excel spreadsheets, and PowerPoint presentations. We're going to take our findings and turn them into polished deliverables.

STOP: Ready for 1.6?

USER: Yes / let's go

---

## Important Notes for Claude

- **Actually use agents**: Use the Task tool to spin up multiple agents for parallel processing
- **Create real files**: initiative-salvage-report.md and comprehensive-research-synthesis.md should be created in the analysis/ folder
- **Read the actual files**: Do NOT hardcode discoveries or findings. The scenario files contain real content - read them and report what you find
- **Core discovery must emerge from data**: The core insight should come from genuinely synthesizing the analysis, not from a pre-written script
- **Solution seed callback**: Connect back to the promising idea found in the predecessor's handoff notes from lesson 1.3 - every scenario has one
- **Scenario awareness**: Use the CLAUDE INSTRUCTIONS blocks to identify the correct files and folders for the student's scenario

## Success Criteria

- [ ] Student saw multiple agents process past work files in parallel
- [ ] Student saw specialized agents do cross-source analysis
- [ ] Student understands when to use agents (parallel, similar tasks)
- [ ] Student understands when NOT to use agents (sequential, dependent tasks)
- [ ] Student grasped the core discovery - a specific, data-driven insight from their scenario
- [ ] Student saw the idea seed from lesson 1.3 resurface and connect to the core discovery
- [ ] analysis/initiative-salvage-report.md created
- [ ] analysis/comprehensive-research-synthesis.md created
- [ ] Student is ready for 1.6
