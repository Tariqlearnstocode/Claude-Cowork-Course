# Lesson 2.4: Customizing Plugins

You've seen what your plugin can do out of the box. Now let's make it yours.

Here's the thing about plugins: they ship with sensible defaults, but they don't know your company. Think of a plugin like a new hire on day one -- talented, eager, capable -- but they need onboarding. They don't know your terminology, your tools, your processes, or how your team likes things done.

Customization is how you onboard Claude to do things **your** way.

And here's the best part: remember all that file editing you learned in Module 1? That's exactly what we're doing here. Plugins are just text files. You already know how to work with text files.

STOP: Ready to make a plugin feel like it was built for your job?

USER: Yes

---

## It's Just Text Files

Let's demystify this. Everything you'll customize in a plugin lives in **plain text** -- markdown files, config files, skill files. No code. No special tools. Just the same file reading and editing you've been doing since Lesson 1.3.

A typical plugin has a structure like this:

- **Config files** -- settings like which tools to connect to
- **Skill files** -- instructions that tell Claude how to do specific tasks
- **Slash command files** -- shortcuts for things you do repeatedly

Every single one of those is a text file you can read and edit. Claude will walk you through each change step by step.

STOP: Make sense? Same skills, new context. Let's start with the most common customization -- swapping connectors.

USER: Yes

---

## Swapping Connectors

Plugins often ship connected to a specific tool. But your team might use something different. For example, a CRM plugin might default to HubSpot, but your team uses Salesforce. A project management plugin might assume Asana, but you're on Monday.com.

Swapping is straightforward. You just tell Claude what you need:

> "This plugin uses HubSpot but we use Salesforce. Can you help me switch it?"

That's it. Claude will find the connector config, show you what's changing, and make the edit. The plugin now talks to your stack.

**CLAUDE INSTRUCTIONS - CONNECTOR SWAP DEMO:**

Based on the student's scenario, demonstrate a connector swap that makes sense for their context:

| Scenario | Suggest swapping... |
|---|---|
| Event Planning | "The vendor management plugin uses Google Sheets but let's point it at your Airtable" |
| Bookstore Turnaround | "The inventory plugin defaults to a generic POS -- let's configure it for Square" |
| Product Launch | "The feedback tracker uses Zendesk but your team uses Intercom" |
| Restaurant Rebrand | "The scheduling plugin assumes 7shifts but your team uses HotSchedules" |
| Nonprofit Grant | "The donor management plugin uses Bloomerang but let's switch to DonorPerfect" |
| Loyalty Program | "The CRM connector uses HubSpot but your team runs on Salesforce" |
| Real Estate | "The lead tracker defaults to kvCORE but your brokerage uses Follow Up Boss" |
| Freelancer/Consultant | "The time tracking connector uses Harvest but your agency uses Toggl" |
| HR/People Ops | "The payroll connector defaults to ADP but Woodward Ventures uses Gusto" |

Walk the student through viewing the connector config file, identifying the line to change, and making the swap. Emphasize that this is just editing a text file -- the same skill from Module 1.

STOP: Ask me to help you swap a connector in your plugin to match your actual tool stack.

USER: Types request to swap a connector

ACTION: Open the relevant plugin config file, show the student the connector setting, explain what it does, and edit it to point at their tool. Keep it conversational -- "See this line here? That's telling the plugin to talk to [OLD TOOL]. We're just going to change it to [NEW TOOL]."

That's done. Your plugin now talks to the right tool. One line changed, and the whole integration shifts.

STOP: See how simple that was? Same file editing, real impact. Now let's do something even more powerful -- teaching your plugin about your company.

USER: Yes

---

## Adding Company Context to Skill Files

This is where customization gets really interesting.

Skill files are instructions that tell Claude **how** to do a task. Out of the box, they're generic -- good enough for anyone, perfect for no one. But when you add your company's context, they become incredibly specific and useful.

There are four types of context you can add:

**Your terminology** -- what your team actually calls things. Maybe you say "client" instead of "customer," or "sprint" instead of "cycle," or "the deck" instead of "the presentation."

**Your org structure** -- who approves what, who owns which process, who needs to be CC'd on what.

**Your brand voice** -- formal? Casual? Technical? Friendly? A mix depending on the audience?

**Your processes** -- the actual steps your team follows, not generic best practices. Your specific approval workflow, your naming conventions, your review cycle.

STOP: Think about your own work for a second. What's something your team does differently from the "standard" way? Something where generic advice would miss the mark?

USER: Shares an example or says they're ready to try

---

## Exercise 1: Add Company Context to a Skill File

Let's do this for real. We're going to pick a skill file in your plugin and add your company's specific context to it.

**CLAUDE INSTRUCTIONS - CONTEXT EXERCISE:**

Based on the student's scenario, suggest a specific skill file to customize and guide them through adding relevant context:

| Scenario | Skill file to customize | Context to add |
|---|---|---|
| Event Planning | Event communication skill | Brightmoor Community Hub's tone (community-first, warm), key stakeholders (board members, city council), and the standard email sign-off |
| Bookstore Turnaround | Customer outreach skill | Inkwell Books' brand voice (literary, warm, personal), their loyalty tiers (Bookmark, Chapter, First Edition), and how they talk about recommendations |
| Product Launch | Status update skill | MotorCity Apps' reporting format, their JIRA workflow stages, and the stakeholder list for different update types |
| Restaurant Rebrand | Menu and marketing skill | State Fair Cafe's brand identity (nostalgic but modern), their menu categories, and the tone they use across channels |
| Nonprofit Grant | Grant writing skill | Detroit Youth Arts' mission statement, their program names, key impact metrics they always cite, and funder-specific language |
| Loyalty Program | Campaign drafting skill | State Fair Rewards terminology, their tier structure, the tone for member communications, and their seasonal promotion calendar |
| Real Estate | Client communication skill | Lakefront Realty Group's brand positioning (luxury lakefront specialists), their standard response templates, and the brokerage's compliance requirements |
| Freelancer/Consultant | Client deliverable skill | Corktown Creative's deliverable naming convention, their review/approval process, and the agency's standard quality bar |
| HR/People Ops | Policy documentation skill | Woodward Ventures' company values, their department structure, Michigan-specific compliance language, and the CEO's preferred communication style |

Guide the student through:
1. Reading the current skill file together
2. Identifying what's generic
3. Adding 3-4 pieces of company-specific context
4. Saving the updated file

STOP: Let's customize a skill file together. I'll show you the current version, and then we'll add your company's context to it. Ready?

USER: Yes / Ready

ACTION: Open the relevant skill file, walk through it with the student, point out the generic parts ("See how this says 'the customer'? Let's make it say what your team actually says"), and edit in 3-4 pieces of company-specific context. After each edit, briefly explain why it matters.

Save the updated skill file.

There it is. That skill file just went from "generic template" to "built for your team." Every time the plugin uses this skill now, it'll sound like it actually knows your company.

STOP: Notice how we just did the same thing we did in Module 1 -- read a file, understood it, edited it. The only difference is **what** we're editing and **why**. Make sense?

USER: Yes

---

## Creating Custom Slash Commands

Now let's talk about something you'll use every single day after this course: **custom slash commands**.

You know how you do certain tasks repeatedly? The weekly status email. The standup update. The client check-in. The end-of-day summary. Whatever it is, you probably do it the same way every time, with small variations.

A slash command turns that into a one-liner. You type `/weekly-update` and Claude knows exactly what to do -- where to pull data from, what format to use, who it's for, and what tone to strike.

A slash command is just a small text file. It contains:
- A name (what you type to trigger it)
- Instructions (what Claude should do when you type it)

That's it. No code, no configuration wizards. Just a text file describing a task.

STOP: Think about a task you do at least once a week that follows a pretty consistent pattern. What comes to mind?

USER: Shares a repeated task

---

## Exercise 2: Create a Custom Slash Command

Let's build a slash command for that task right now.

**CLAUDE INSTRUCTIONS - SLASH COMMAND CREATION:**

Based on what the student shared AND their scenario, help them create a meaningful slash command. If they didn't share something specific, suggest one based on their scenario:

| Scenario | Suggested slash command |
|---|---|
| Event Planning | `/vendor-status` -- checks all vendor contracts and flags anything overdue or unsigned |
| Bookstore Turnaround | `/daily-sales` -- pulls today's sales data and compares to last week and last month |
| Product Launch | `/standup` -- drafts the daily standup update from recent JIRA activity and Slack threads |
| Restaurant Rebrand | `/shift-prep` -- creates a shift prep checklist with today's specials, reservations, and staff notes |
| Nonprofit Grant | `/grant-tracker` -- checks all active grant deadlines and summarizes what's due this week |
| Loyalty Program | `/campaign-check` -- reviews active campaigns, engagement metrics, and flags anything underperforming |
| Real Estate | `/morning-brief` -- summarizes new leads, upcoming showings, and any client follow-ups due today |
| Freelancer/Consultant | `/client-pulse` -- checks all active client projects, upcoming deadlines, and flags anything at risk |
| HR/People Ops | `/compliance-check` -- reviews pending HR tasks, upcoming deadlines, and flags any audit items |

Guide the student through:
1. Naming their command
2. Writing clear instructions for what it should do
3. Adding any scenario-specific details (tools to check, format to follow, who it's for)
4. Saving the slash command file

STOP: Let's build it. Tell me the task you want to turn into a command, and I'll help you write the slash command file.

USER: Describes their task (or agrees to the suggested one)

ACTION: Create the slash command file step by step:
1. Name the file based on the command (e.g., `weekly-update.md`)
2. Write clear, specific instructions inside it
3. Include the student's company context (terminology, format preferences, data sources)
4. Save it to the appropriate plugin commands directory

Walk through each part as you write it: "First, we name it. Then we tell Claude what to do when someone types this. Then we add your specifics -- where to pull data from, what format your manager likes, what tone to use."

Your slash command is ready. Next time you type `/[COMMAND-NAME]`, Claude will know exactly what to do -- no re-explaining, no copy-pasting prompts. Just the result.

STOP: Try it out! Type your new slash command and see what happens.

USER: Types the slash command

ACTION: Execute the slash command. Show the student the result. Point out how the company context and specific instructions made the output much better than a generic request would have produced.

See the difference? That's not a generic response. That's **your** process, **your** format, **your** context -- every time, with one command.

STOP: Imagine having 5 or 10 of these for your most common tasks. That's where we're headed. Ready to learn one more trick?

USER: Yes

---

## The Plugin Management Plugin

Here's something useful: you can use the **plugin management plugin** to help manage and customize other plugins. Instead of finding and editing files manually every time, you can just ask:

> "Use the plugin manager to add our company's style guide to the marketing plugin"

> "Use the plugin manager to create a new slash command for weekly reporting"

> "Use the plugin manager to show me what's customizable in this plugin"

It's a plugin that edits plugins. Think of it as your customization assistant -- it knows where everything lives and how to make changes safely.

This is especially handy when you want to make quick changes without remembering exact file paths.

STOP: Want to try it? Ask me to use the plugin manager to make a change to one of your plugins.

USER: Types a request using the plugin manager

ACTION: Use the plugin management plugin to make the requested change. Show the student what happened behind the scenes -- which files were modified and why. Reinforce that it's still just editing text files, but with an easier interface.

Same result, different path. Whether you edit files directly or use the plugin manager, the end result is the same -- customized text files that make your plugins smarter.

STOP: Now you have two ways to customize: hands-on file editing and the plugin manager. Use whichever feels right for the situation. Ready to wrap up?

USER: Yes

---

## Wrap-up

**Meta skills you just learned:**

1. **Connector swapping:** Point a plugin at the tools your team actually uses
2. **Company context:** Add terminology, org structure, brand voice, and processes to skill files
3. **Custom slash commands:** Turn repeated tasks into one-liners
4. **Plugin management:** Use the plugin manager for quick customization

**Where else this applies:**
- Install any new plugin in the future and immediately customize it for your company
- When your team switches tools (CRM, project management, communication), update the connector in seconds
- Onboard a new team member to Claude Cowork by sharing your customized plugins -- they get your processes built in from day one
- Build a library of slash commands that mirrors your daily workflow -- morning routine, end of day, weekly reporting, client check-ins
- When your company's processes change (new approval workflow, new brand guidelines), update the skill files once and every future interaction reflects the change

**Next up:** In 2.5, you'll take everything you've learned -- connectors, plugins, skills, slash commands -- and build your first real workflow from scratch. No more training wheels.

STOP: Ready for 2.5?

USER: Yes / let's go

---

## Important Notes for Claude

- **Module 1 connection**: Emphasize throughout that customization is just file editing -- the same skill from Module 1, applied to plugin files. This should feel like a natural extension, not something new.
- **Scenario awareness**: Every exercise should use the student's chosen scenario. Reference their company name, their tools, their terminology. This lesson should feel personal.
- **No coding**: Nothing in this lesson requires code. If a student seems intimidated, remind them it's just reading and editing text.
- **Slash command persistence**: Make sure slash command files are actually saved to the right location so the student can use them in future lessons.
- **Plugin manager**: If the plugin management plugin isn't available, walk the student through the manual file editing approach instead and note that the plugin manager is available for future use.
- **Pacing**: This lesson has two hands-on exercises. Don't rush them. Let the student think about what context to add and what slash command to create. The more personal it is, the more valuable it feels.
- **Connector swap**: The connector swap is a demonstration. The student doesn't need a live integration -- just show them the file, make the edit, and explain what it would do.

## Success Criteria

- [ ] Student swapped a connector in a plugin config file
- [ ] Student understands that plugins are just text files they can edit
- [ ] Student added company-specific context to a skill file (terminology, voice, processes, or org structure)
- [ ] Student created a custom slash command for a task they repeat regularly
- [ ] Student tested their slash command and saw the result
- [ ] Student used or learned about the plugin management plugin
- [ ] Student sees the connection between Module 1 file skills and plugin customization
- [ ] Student's customizations reflect their specific scenario (company name, tools, context)
- [ ] Student is ready for 2.5
