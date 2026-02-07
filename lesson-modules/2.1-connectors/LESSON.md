# Lesson 2.1: Connectors

Welcome to Module 2.

You made it. You crushed Module 1 - file exploration, working with documents, agents, creating Word and Excel and PowerPoint files, web research. You've got a real toolkit now.

But everything you did in Module 1 lived inside your computer. Local files. Local folders.

Now we open the door to the outside world.

Module 2 is about connecting Claude to the tools you already use every day - Slack, Notion, Google Calendar, Asana, and more. By the end of this module, Claude won't just be a smart assistant that reads your files. It'll be wired into your actual workflow.

This lesson is about **connectors** - the bridges between Claude and your favorite tools.

STOP: Ready to level up?

USER: Yes / let's go

---

## What Is a Connector?

Think of a connector like a bridge.

Right now, Claude lives on your computer. It can read your files, create documents, search the web. But it can't see your Slack messages. It can't check your calendar. It can't read your Notion pages.

A connector changes that. It links Claude to an outside tool so they can talk to each other.

Once connected, you can say things like:

- "What meetings do I have this week?"
- "Post a summary of this doc to the #marketing channel in Slack"
- "Pull my latest Notion notes into this conversation"

No copy-pasting. No switching tabs. Claude just... knows.

STOP: Make sense so far? A connector is just a link between Claude and another tool.

USER: Yes

---

## Two-Way Street

Here's the part that surprises people.

Connectors aren't just for reading. They go both ways.

**Claude can pull data IN:**
- Check your calendar for upcoming meetings
- Read a Notion page or database
- See recent messages in a Slack channel

**Claude can also push data OUT:**
- Create a new calendar event
- Update a Notion page
- Send a Slack message

So it's not just "tell me what's on my calendar." It's "block off Tuesday afternoon for deep work and let my team know in Slack."

That's the difference between a tool that informs you and a tool that works for you.

STOP: See the difference? Reading AND writing. Pull AND push. Cool, right?

USER: Yes

---

## What Connectors Are Available?

Here are the most common connectors people use with Claude:

| Connector | What It Does |
|-----------|--------------|
| **Slack** | Read channels, send messages, search conversations |
| **Notion** | Read and update pages, query databases |
| **Google Calendar** | Check schedule, create events, find free time |
| **Google Drive** | Access docs, sheets, slides stored in Drive |
| **Asana** | View and create tasks, check project status |
| **Linear** | Manage issues, track sprints |
| **Jira** | View tickets, update status, add comments |
| **HubSpot** | Pull CRM data, view contacts and deals |
| **Microsoft 365** | Access Outlook, Teams, OneDrive, SharePoint |
| **GitHub** | View repos, issues, pull requests |
| **Figma** | View and comment on designs |

You don't need all of these. You just need the ones YOU use.

STOP: Which of these tools do you use in your day-to-day work? Tell me what's in your toolkit.

USER: [Lists their tools - e.g., "Slack and Notion" or "Google Calendar and Asana"]

---

## Your Recommended Connectors

ACTION: Based on what the user said, acknowledge their tools and recommend which connectors to set up first. Prioritize whatever they actually use. If they listed tools that have connectors, suggest those. If they're unsure, use the scenario-based recommendations below.

**CLAUDE INSTRUCTIONS - SCENARIO-BASED CONNECTOR RECOMMENDATIONS:**

If the user isn't sure which tools to connect, or if you want to add scenario-relevant suggestions, use this table based on the scenario they chose in 1.1:

| Scenario | Recommended Connectors | Why |
|----------|----------------------|-----|
| **Event Planning** | Google Calendar, Slack, Asana | Scheduling vendors, coordinating with team, tracking tasks |
| **Bookstore Turnaround** | Notion, Google Calendar, Slack | Inventory tracking, event scheduling, team communication |
| **Product Launch** | Linear or Jira, Slack, Notion | Issue tracking, team updates, documentation |
| **Restaurant Rebrand** | Slack, Google Calendar, Notion | Staff coordination, scheduling, menu/brand planning |
| **Nonprofit Grant** | Google Drive, Notion, Google Calendar | Grant documents, research notes, deadline tracking |
| **Loyalty Program** | HubSpot, Slack, Notion | CRM data, team updates, program documentation |
| **Real Estate** | Google Calendar, HubSpot, Slack | Showings, client tracking, team communication |
| **Freelancer/Consultant** | Slack, Notion, Google Calendar | Client communication, project docs, scheduling |
| **HR/People Ops** | Slack, Notion, Google Calendar | Team communication, employee docs, interview scheduling |

**Say something like:**

"Based on what you told me, I'd start with **[TOP TOOL]** - that'll give you the most immediate value for [REASON]. After that, **[SECOND TOOL]** would be a great add.

For your [SCENARIO NAME] scenario specifically, having [TOOL] connected means Claude can [SPECIFIC BENEFIT]."

STOP: Want to try connecting your first tool right now?

USER: Yes

---

## Connecting Your First Tool

Here's how to set up a connector. It takes about 30 seconds.

**Step 1:** Look at the bottom of your chat window. You'll see a **+** button next to where you type messages. Click it.

**Step 2:** You'll see a list of available connectors. Find the one you want to connect.

**Step 3:** Click on it and follow the authorization steps. This usually means signing into the tool (like Slack or Google) and giving Claude permission to access it.

**Step 4:** That's it. Once authorized, Claude can talk to that tool.

No terminal. No code. No installation. Just click, authorize, done.

STOP: Go ahead and try it. Connect the tool we just talked about. I'll wait. Let me know when you're done, or if you hit a snag.

USER: [Done / connected / having trouble]

---

## Troubleshooting

ACTION: If the user says they connected successfully, celebrate and move to the next section. If they're having trouble, walk them through it step by step:

**CLAUDE INSTRUCTIONS - IF USER IS STUCK:**

Common issues and how to help:
- **Can't find the + button**: It's at the bottom of the chat window, near the text input area. On some versions it may be in Settings > Connectors.
- **Don't see the connector they want**: Not all connectors are available to all users yet. Suggest an alternative or have them check for updates.
- **Authorization failed**: Have them try again. Sometimes the popup gets blocked by the browser. Make sure they're signed into the tool first.
- **Not sure if it worked**: Ask Claude to test it. For example: "What's on my calendar today?" or "Show me my recent Slack messages."

**If they connected successfully, say something like:**

"Nice! You just gave Claude a new superpower. Let's test it out."

STOP: Ready to test your new connector?

USER: Yes

---

## Test Drive

Let's make sure it actually works.

ACTION: Based on which tool the user connected, suggest a simple test command. Examples:

- **Slack**: "Ask me what's happening in one of your Slack channels."
- **Notion**: "Ask me to read one of your Notion pages."
- **Google Calendar**: "Ask me what's on your calendar this week."
- **Asana/Linear/Jira**: "Ask me to show your current tasks."
- **HubSpot**: "Ask me to pull up a recent contact or deal."
- **Google Drive**: "Ask me to find a recent document in your Drive."

**Say something like:**

"Try asking me something about your [CONNECTED TOOL]. For example: '[EXAMPLE QUESTION]'"

STOP: Go ahead - ask me something using your new connector.

USER: [Asks a question using the connected tool]

ACTION: Actually use the connector to pull live data and respond to their question. Show them real results from their connected tool. This is the "wow" moment - make it land.

After responding with real data, point out what just happened:

"See what just happened? I pulled live data from [TOOL] directly into our conversation. No copy-pasting. No switching tabs. That's the power of connectors."

STOP: Pretty cool, right? Want to try one more thing?

USER: Yes

---

## Push Something Back

Now let's go the other direction. Instead of pulling data in, let's push something out.

ACTION: Based on which tool the user connected, suggest a simple write action:

- **Slack**: "Want me to send a message to a channel? Pick a channel and tell me what to say."
- **Notion**: "Want me to create a quick note in Notion? Tell me what page or database to add to."
- **Google Calendar**: "Want me to create an event? Give me a title, date, and time."
- **Asana/Linear/Jira**: "Want me to create a task? Tell me the title and any details."
- **HubSpot**: "Want me to add a note to a contact? Tell me who."
- **Google Drive**: "Want me to create a new doc in Drive?"

If the user doesn't want to write back to their tool (maybe it's a work account and they don't want to mess anything up), that's totally fine. Acknowledge it and explain the concept without forcing it:

"Totally get it. The important thing to know is that connectors go both ways. When you're ready, Claude can create events, send messages, update pages - whatever you need. You're in control of when that happens."

STOP: Try it out, or say "skip" if you'd rather not push anything right now.

USER: [Tries it / skips]

ACTION: If they tried it, confirm it worked and celebrate. If they skipped, acknowledge and move on warmly.

---

## Connecting More Tools (Optional)

You don't have to connect everything right now. But if you want to add another connector, go for it. Same process - click the **+**, find the tool, authorize.

The more tools you connect, the more Claude can do in a single conversation. Imagine this:

"Check my calendar for tomorrow, pull the agenda from the Notion doc, and send a reminder to the team in Slack."

One sentence. Three tools. That's where this is heading.

STOP: Want to connect another tool now, or move on to the wrap-up?

USER: [Connects another / move on]

ACTION: If they want to connect another tool, walk them through it the same way. If they want to move on, proceed to wrap-up.

---

## Wrap-up

You just unlocked something big.

In Module 1, Claude could read and create files on your computer. Now it can reach out to the tools you use every day. That's a fundamental shift.

**Meta skills you just learned:**

1. **Connecting external tools** - Linking Claude to apps like Slack, Notion, Google Calendar, and others
2. **Two-way communication** - Understanding that connectors let Claude both read from and write to your tools
3. **Testing integrations** - Verifying a connector works by pulling real data into the conversation

**Where else this applies:**
- Pull your week's calendar into a Monday morning planning session with Claude
- Read and update Notion docs or Jira tickets without leaving the conversation
- Send Slack messages or check channels for updates before a meeting
- Create tasks in Asana or Linear based on your conversation with Claude
- Pull CRM data from HubSpot to prep for a sales call
- Combine multiple tools in a single request - check calendar, draft a message, send it to Slack

**Next up:** In 2.2, you'll install a plugin that gives Claude deep expertise in your specific job function. Think of connectors as the wires and plugins as the brain. You've got the wires. Now let's add the smarts.

STOP: Ready for 2.2?

USER: Yes / let's go

---

## Important Notes for Claude

- **Remember their scenario**: The user chose a scenario in 1.1. Use the scenario-based connector recommendations table to suggest relevant tools. Reference their scenario by name.
- **Remember their name**: Use their name occasionally for a personal touch (they shared it in 1.1).
- **Actually use connectors**: When testing, actually attempt to use the connected tool. Pull real data. This is the "wow" moment.
- **Don't force writes**: If the user doesn't want to push data back to a work tool, respect that. The concept matters more than the exercise.
- **Troubleshoot patiently**: Non-technical users may struggle with authorization flows. Walk them through it step by step without making them feel bad.
- **Module 2 fresh start**: This is the first lesson of a new module. It should feel like a new chapter, not a continuation of the last lesson. Celebrate their Module 1 completion.
- **No jargon**: Never say "MCP", "Model Context Protocol", "API", "endpoint", or "OAuth". Use plain language only. "Connector" and "authorize" are the most technical it should get.
- **Pacing**: Let the user go at their speed. If they want to connect five tools, great. If they only connect one, that's also great.

## Success Criteria

- [ ] Student understands what a connector is (a bridge between Claude and an external tool)
- [ ] Student understands connectors are two-way (read and write)
- [ ] Student has connected at least one external tool
- [ ] Student has tested the connector by pulling live data into the conversation
- [ ] Student has either tested pushing data back or understands the concept
- [ ] Student received scenario-relevant connector recommendations
- [ ] Student is ready to proceed to 2.2
