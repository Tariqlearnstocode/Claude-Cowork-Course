# Lesson 1.3: Working with Files

Now that you can see your files, let's actually work with them.

This lesson covers the main ways you'll use Claude Cowork with files. We're going to do 5 scenarios.

As we go through these files, you'll also be learning about the situation you've inherited. This information will be helpful in future lessons. We're unraveling the mystery.

STOP: Ready?

USER: Yes

---

## Scenario 1: Single File → Extract

First up: reading one file and extracting structured info from it.

The person before you left messy notes. Let's see what's useful.

STOP: Ask me to read the handoff notes file and extract the action items and key insights.

USER: Types request about reading the notes file

**CLAUDE INSTRUCTIONS - HANDOFF NOTES FILE MAPPING:**

Read the correct handoff notes file based on the student's chosen scenario:

| Scenario | File to Read |
|---|---|
| bookstore-turnaround | `inherited-chaos/previous-owner-notes.md` |
| event-planning | `inherited-chaos/previous-coordinator-notes.md` |
| freelancer-consultant | `inherited-chaos/jordans-handoff-notes.md` |
| hr-people-ops | `inherited-chaos/kelly-handoff-notes.md` |
| loyalty-program | `inherited-chaos/previous-manager-notes.md` |
| nonprofit-grant | `inherited-chaos/director-notes.md` |
| product-launch | `inherited-chaos/pm-handoff-notes.md` |
| real-estate | `inherited-chaos/daves-notes.md` |
| restaurant-rebrand | `inherited-chaos/manager-rebrand-notes.md` |

ACTION: Read the appropriate handoff notes file, extract action items and key insights, create organized/action-items.md with the structured output.

**CLAUDE INSTRUCTIONS - DISCOVERY (SEED IDEA):**

Each scenario's handoff notes contain a buried seed of a promising idea - something the previous person mentioned offhand but never followed through on. When presenting the extracted insights, highlight this seed idea as a "Discovery." Examples:
- loyalty-program: "food personality quiz" concept
- bookstore-turnaround: children's programming expansion / rare books collector network
- product-launch: a niche vertical focus that keeps getting dismissed
- nonprofit-grant: an unconventional partnership or storytelling approach
- event-planning: a community-driven element that got deprioritized
- freelancer-consultant: a strategic insight about a client that was never acted on
- hr-people-ops: a people-first initiative that got shelved during the chaos
- real-estate: a relationship-building approach or market niche that was overlooked
- restaurant-rebrand: an identity/brand direction that was floated but abandoned

Find the most interesting or promising buried idea in the notes and highlight it. Say something like: "Interesting... there's a note here about [IDEA]. Let's keep that in mind for later."

I've created organized/action-items.md with the extracted insights.

STOP: See how we pulled structure from chaos? You could do the same thing with meeting notes, research documents, or any messy file. Ready for the next one?

USER: Yes

---

## Scenario 2: Folder → Synthesize

Next: pointing at a WHOLE folder and finding patterns across multiple files.

There's a collection of feedback and communications from different people over time. What are they telling us?

STOP: Ask me to look at all the feedback/communication files and synthesize the themes.

USER: Types request about feedback or communications

**CLAUDE INSTRUCTIONS - FEEDBACK FOLDER MAPPING:**

Read ALL files in the correct feedback/communications folder based on the student's scenario:

| Scenario | Folder to Read | Description |
|---|---|---|
| bookstore-turnaround | `inherited-chaos/customer-feedback/` (5 files) | Customer reviews, comment cards, surveys |
| event-planning | `inherited-chaos/sponsor-communications/` (5 files) | Sponsor email threads |
| freelancer-consultant | `inherited-chaos/client-communications/` (4 files) | Client email threads |
| hr-people-ops | Multiple individual files in `inherited-chaos/` | Read these communication/feedback files: `priya-frustrations-slack.md`, `aaliyah-conversation-notes.md`, `benefits-enrollment-issues.md`, `time-tracking-issues.md` |
| loyalty-program | `inherited-chaos/customer-feedback/` (4 files) | Monthly feedback summaries |
| nonprofit-grant | `inherited-chaos/beneficiary-stories/` (4 files) | Beneficiary testimonials and stories |
| product-launch | `inherited-chaos/customer-complaints/` (5 files) | Support tickets, reviews, complaints |
| real-estate | `inherited-chaos/client-communications/` (8 files) | Client email threads |
| restaurant-rebrand | `inherited-chaos/social-media-analysis/` (4 files) | Social media and review analysis |

ACTION: Read all files in the appropriate folder, synthesize patterns across them, create organized/feedback-synthesis.md with the themes.

**CLAUDE INSTRUCTIONS - DISCOVERY (RECURRING THEME):**

Find the dominant recurring theme across the files. Every scenario has one - a pattern that emerges when you read them together that you would miss looking at any single file alone. Present it as a "Discovery." For example:
- loyalty-program: "fine but forgettable" - people sign up and lose interest
- bookstore-turnaround: customers love the store's soul but feel it's stuck in the past
- product-launch: the product tries to do everything and does nothing well
- nonprofit-grant: powerful individual stories but inconsistent data and messaging
- event-planning: sponsors feel unheard and undervalued
- freelancer-consultant: scope creep and unclear deliverables across all clients
- hr-people-ops: employees feel unsupported and systems are breaking down
- real-estate: clients feel neglected and communication has been inconsistent
- restaurant-rebrand: there's a disconnect between what the restaurant thinks it is and what customers experience

Find the actual recurring theme in the files and highlight it. This theme will be important for the rest of the course.

I've created organized/feedback-synthesis.md with the synthesized themes.

STOP: Imagine doing that manually - opening multiple files, reading each one, taking notes, finding patterns. This took seconds. You could do this with hundreds of customer emails, support tickets, survey responses - anything where patterns are hiding in volume. Ready for the next one?

USER: Yes

---

## Scenario 3: Apply Template

So far I've been doing things my own way. But you might have a particular format, template, or instructions you want me to follow.

Instead of explaining the format every time, you can just point me to a template file.

Leadership needs an update. We have a template we use for these.

STOP: Ask me to create a leadership update using the feedback synthesis we just created, following the format in templates/leadership-update-template.md

USER: Types request about creating leadership update

ACTION: Read both files (the feedback synthesis from organized/feedback-synthesis.md and the template from templates/leadership-update-template.md), create organized/leadership-update.md following the template format with content from the feedback synthesis.

**CLAUDE INSTRUCTIONS:**
- The template is at the ROOT level of the course folder: `templates/leadership-update-template.md`
- It is generic and works for all scenarios - no mapping needed
- Fill it in using the feedback synthesis content from Scenario 2
- Output goes to `organized/leadership-update.md`

Done! I created the leadership update following your template.

Key learning: You can use files as format guides, not just content sources. This is your first peek into building out your own workflows and systems.

STOP: Think about all the templates you use - meeting notes, weekly reports, proposals. Save them as files, and I'll always follow that format. No more copy-pasting into ChatGPT and hoping it gets the structure right. Make sense?

USER: Yes

---

## Scenario 4: Image → Analyze

I can also analyze images!

**CLAUDE INSTRUCTIONS - IMAGE ANALYSIS ROUTING:**

This exercise teaches that Claude can analyze images. Route based on the student's scenario:

**If the student's scenario is loyalty-program:**
- Analyze `attachments/loyalty-flyer.jpg`
- Say: "There's a loyalty program flyer in the attachments folder. Let's see if I can find any improvements."
- Note that it's generic, lacks personality and brand identity, could be any chain's flyer
- Discovery: "Generic offer. Nothing that says [company name]. Could be any chain. This is part of the problem - even the marketing materials have no personality."

**For ALL other scenarios:**
- There are no image files in the attachments folder for this scenario
- Pivot the exercise: explain that Claude can analyze any image, and ask the student to provide one
- Say something like: "I can analyze any image you share with me. Since we don't have a visual asset in our scenario files, let's try this with something from your actual work. Do you have a screenshot, a design, a flyer, a chart, or any image you'd like me to analyze? You can also paste a URL to an image from the web - like a competitor's website, a marketing piece, or an infographic."
- If they provide an image or URL, analyze it and give useful feedback
- If they prefer to skip, that's fine - acknowledge the capability and move on
- Either way, make sure the teaching point lands: Claude can see and analyze images

STOP: Ask me to analyze an image.

USER: Types request about analyzing an image

ACTION: Follow the routing above. Analyze the image (whether it's the loyalty flyer, a student-provided image, or a web URL) and provide substantive feedback.

STOP: This is useful for all kinds of things - analyzing designs, reviewing screenshots, looking at competitor materials, understanding charts. And you can share multiple images at once. Make sense?

USER: Yes

---

## Scenario 5: Web → Research

Last one: pulling in external information from the web.

What are the best practices in our space? What are others doing that we're not?

STOP: Ask me to search the web for best practices relevant to our situation.

USER: Types request for web research

**CLAUDE INSTRUCTIONS - WEB SEARCH MAPPING:**

Search for the correct topic based on the student's scenario:

| Scenario | Search Query |
|---|---|
| bookstore-turnaround | "independent bookstore success strategies" |
| event-planning | "community festival best practices" |
| freelancer-consultant | "creative agency client management best practices" |
| hr-people-ops | "HR compliance and people ops best practices for startups" |
| loyalty-program | "restaurant loyalty program best practices" |
| nonprofit-grant | "successful grant writing strategies for arts nonprofits" |
| product-launch | "SaaS product relaunch strategies" |
| real-estate | "real estate agent pipeline management best practices" |
| restaurant-rebrand | "restaurant modernization and rebrand strategies" |

ACTION: Search the web using the appropriate query, find relevant information, synthesize key findings.

**CLAUDE INSTRUCTIONS - DISCOVERY:**

After presenting the web research findings, connect them back to what the student has already learned from the handoff notes (Scenario 1) and feedback synthesis (Scenario 2). The best practices from the web should illuminate what's missing in their inherited situation. Highlight how the external research validates or challenges what they've been seeing in the files.

STOP: Web search is incredibly powerful for research tasks. Need to understand a new industry? Research competitors? Find best practices for anything? Just ask. I'll search, read, and synthesize - no more 97 browser tabs. Cool, right?

USER: Yes

---

## End of Lesson Reflection

Patterns are starting to emerge from the chaos. We've seen symptoms across the notes, the feedback, and the research - and they're pointing in a consistent direction.

But we need to go deeper to find the real problem and the real solution.

That's what we'll do in the next lessons - we'll use agents to process everything at once and get perspectives from different angles.

STOP: See how we've started to piece together a picture?

USER: Yes

---

## Wrap-up

**Meta skills you just learned:**

1. **Single file → Extract:** Pull structured information from messy documents
2. **Folder → Synthesize:** Find patterns across multiple files
3. **Apply template:** Use one file to control the format of output
4. **Image → Analyze:** Get insights from visual content
5. **Web → Research:** Pull in external information on demand

**Where else this applies:**
- Meeting notes from the last quarter - extract every action item assigned to you
- 50 customer support tickets - synthesize into themes for your product team
- Your company has a specific format for proposals - use it as a template for any new proposal
- Screenshot a competitor's pricing page - get instant analysis of their positioning
- Research best practices for anything: hiring, onboarding, presentation design, whatever you're working on

**Next up:** In 1.4, you'll learn about Cowork's built-in features - the todo list, conversation tips, and how to get the most out of your sessions.

STOP: Ready for 1.4?

USER: Yes / let's go

---

## Important Notes for Claude

- **File creation**: Actually create the output files (action-items.md, feedback-synthesis.md, leadership-update.md) in the organized/ folder
- **Scenario awareness**: Always reference files from the student's chosen scenario folder in `scenarios/[scenario-name]/inherited-chaos/`
- **Seed idea**: Make sure to highlight the buried promising idea when extracting from the handoff notes - this seeds the solution that will be revealed in lesson 1.5
- **Recurring theme**: Identify and emphasize the recurring theme across the feedback/communication files - this is a key discovery for the narrative arc
- **Web search**: Use real web search capabilities to find actual best practices
- **Image analysis**: For loyalty-program, analyze the actual flyer image. For all other scenarios, pivot to having the student provide an image or use a web image
- **Template**: The leadership update template is at the ROOT level (`templates/leadership-update-template.md`), NOT inside any scenario folder
- **Narrative continuity**: The discoveries across all 5 scenarios should build on each other, creating a mounting sense that something fundamental needs to change. This sets up lesson 1.5 where agents will reveal the core discovery.

## Success Criteria

- [ ] Student extracted action items from messy handoff notes into structured file
- [ ] Student synthesized multiple feedback/communication files into themes
- [ ] Student created a leadership update using a template
- [ ] Student experienced image analysis (via scenario flyer, their own image, or web image)
- [ ] Student saw web research in action
- [ ] Student noticed the recurring theme across the feedback files
- [ ] Student heard about the buried seed idea from the handoff notes (seed for later)
- [ ] Student is ready for 1.4
