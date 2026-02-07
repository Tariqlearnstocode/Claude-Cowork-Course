# Lesson 2.5: Your First Real Workflow

Up until now, Claude has been your teacher. That's over.

For the past two modules, you've been working through a practice scenario -- a fictional company, sample files, guided exercises. That was on purpose. It gave you a safe space to learn without stakes.

But right now, the training wheels come off. In this lesson, Claude becomes your **consultant**. There is no pre-built scenario. No sample files. No fictional company. The subject matter is **your actual job**, your real tasks, your real pain points.

Everything you've learned -- connectors, plugins, skills, slash commands, customization -- comes together right here. By the end, you'll have a working workflow you'll genuinely use on Monday morning.

This is the whole reason you took this course.

STOP: This is the big one. Ready to build something real?

USER: Yes

---

## The Discovery Interview

Before we build anything, I need to understand your work. Not your job title -- your actual day-to-day. The stuff that fills your hours. The stuff that drains your energy.

I'm going to ask you a few questions. Answer honestly. The more specific you are, the better your workflow will be. Vague answers get vague results. Specific answers get something you'll actually use.

**CLAUDE INSTRUCTIONS - DISCOVERY INTERVIEW:**

Conduct a genuine discovery interview with the student. Ask these questions one at a time, waiting for a response after each. Do NOT rush through them. Each answer shapes what you'll build.

Ask these questions in order, one per STOP. After each answer, briefly reflect back what you heard to confirm understanding before asking the next question:

1. "What's one thing you do every week that feels repetitive? Something where you think 'I'm doing this AGAIN?'"
2. "What takes you the longest? Not the hardest task -- the one that eats the most hours."
3. "Walk me through your Monday morning. What's the first thing you do at work? What's the first task you dread?"
4. "What tools do you live in? Email, Slack, Notion, Google Sheets, a CRM, a project management tool -- whatever you're in and out of all day."
5. "If you could snap your fingers and have one task just DONE every week without thinking about it, what would it be?"

Listen carefully. Take notes mentally. You're looking for patterns: repetition, manual data gathering, formatting tasks, reporting, anything that follows a consistent pattern but requires manual effort every time.

STOP: Let's start with the first question. What's one thing you do every week that feels repetitive?

USER: Answers the question

---

[Reflect back what you heard. Confirm you understood correctly. Then ask the next discovery question.]

STOP: Got it. Next question -- what takes you the longest? Not the hardest thing you do, but the task that eats the most time.

USER: Answers

---

STOP: That's helpful. Now walk me through your Monday morning. What's the first thing you do when you sit down? What's the first task that makes you sigh?

USER: Answers

---

STOP: I'm getting a clear picture. What tools are you in and out of all day? Email, Slack, spreadsheets, a CRM -- whatever you live in.

USER: Answers

---

STOP: Last question. If you could snap your fingers and have one task just DONE every week -- completely handled, no thought required -- what would it be?

USER: Answers

---

## Identifying the Opportunity

**CLAUDE INSTRUCTIONS - OPPORTUNITY IDENTIFICATION:**

Based on the student's five answers, identify 2-3 specific workflow opportunities. Rank them by impact -- which one would save the most time, reduce the most friction, or eliminate the most tedious repetition.

For each opportunity, briefly explain:
- What the workflow would do
- Which of their tools it would connect to
- How much time or effort it would save
- Why you're ranking it where you are

Be specific. Use their exact words back to them. If they said "I spend an hour every Friday compiling numbers from three spreadsheets into a report," your suggestion should reference Friday, the three spreadsheets, and the report -- not a generic "automate reporting."

Present all 2-3 options, then ask which one they want to build.

OK. I've been listening carefully, and I see some real opportunities. Let me lay out what I think we can build.

ACTION: Present 2-3 ranked workflow ideas based on the student's discovery answers. Be specific -- reference their exact tasks, tools, and pain points.

Here's what I'm seeing -- ranked by how much impact I think each one would have on your week.

STOP: Those are your options. Which one jumps out? Which one would make you think "I can't believe I used to do that manually"?

USER: Picks an option

---

## The Game Plan

Great choice. Let's break down exactly how we're going to build this.

This workflow is going to use everything you've learned in Module 2:

**From 2.1 -- Connectors:** We'll connect to the tools where your data lives. No more copying and pasting between apps.

**From 2.2 -- Plugins:** We'll activate the right plugin to power the workflow. This gives us pre-built capabilities tailored to the type of work you're doing.

**From 2.3 -- Skills and Commands:** We'll use the slash command pattern you learned to power the workflow with structured, role-specific actions.

**From 2.4 -- Customization:** We'll create a custom slash command and customize the output to match your preferences -- your terminology, your format, your voice.

Four lessons. One workflow. All working together.

STOP: See how it all connects? Each lesson was a building block. Now we stack them. Ready to start building?

USER: Yes

---

## Step 1: Connect the Right Tools

First things first -- we need to connect Claude to wherever your data lives.

**CLAUDE INSTRUCTIONS - CONNECTOR SETUP:**

Based on the workflow the student chose and the tools they mentioned in the discovery interview, identify which connectors are needed. Walk the student through connecting each one.

If the student mentioned tools like Google Sheets, Slack, Notion, Google Calendar, a CRM, email, or any other supported integration, guide them through the connection process for each relevant tool.

If a connector was already set up in Lesson 2.1, acknowledge that: "Good news -- you already connected [TOOL] back in 2.1. That's ready to go."

If a tool they need isn't available as a connector, suggest the best alternative approach (manual input, file-based, or a different connector that could work).

Keep this practical. Only connect what the workflow actually needs -- don't connect extra tools for the sake of it.

STOP: Let's get your tools connected. Based on what you told me, here's what we need to hook up. Ready?

USER: Yes

ACTION: Walk the student through connecting the necessary tools for their chosen workflow. Reference Lesson 2.1 concepts as you go. If tools were already connected, confirm they're still active.

Those connections are live. Claude can now pull data from where it actually lives instead of you copying and pasting it.

STOP: Tools are connected. On to the next piece -- ready?

USER: Yes

---

## Step 2: Activate the Right Plugin

Now we need the right plugin to power the workflow logic.

**CLAUDE INSTRUCTIONS - PLUGIN SELECTION:**

Based on the student's chosen workflow, recommend and activate the most relevant plugin. Explain why this plugin fits their use case.

If the student already has a relevant plugin installed from Lesson 2.2, reference that: "Remember the [PLUGIN] you installed in 2.2? That's exactly what we need here."

If a different or additional plugin is needed, walk through the installation. Keep the explanation brief -- they already know what plugins are from 2.2.

Connect this back to 2.2: "This is the same concept from Lesson 2.2 -- a pre-built toolkit designed for exactly this kind of work."

STOP: We need a plugin to power this. Let me show you which one fits.

USER: Ready / Yes

ACTION: Install or activate the relevant plugin for the student's workflow. Briefly explain what it brings to the table. Connect it to the connectors from Step 1.

Plugin is active. Now your workflow has the engine it needs. Next, we give it a trigger.

STOP: Two pieces in place -- connectors and plugin. Ready for the fun part?

USER: Yes

---

## Step 3: Build the Slash Command

This is where it all becomes real. We're going to create a slash command that triggers your entire workflow with a single line.

Think about what this means. Instead of: open three tabs, pull data from here, cross-reference with that, format it this way, send it to that person -- you'll type one command. Done.

**CLAUDE INSTRUCTIONS - WORKFLOW SLASH COMMAND:**

This is the most important step. Build a slash command that orchestrates the entire workflow:

1. Name the command based on the student's task (e.g., `/weekly-report`, `/client-prep`, `/monday-brief`, `/expense-summary`)
2. Write comprehensive instructions inside the command file that:
   - Pull data from the connected tools (Step 1)
   - Use the plugin's capabilities (Step 2)
   - Follow a clear sequence of steps
   - Produce a specific, useful output
3. Include the student's specific context -- their terminology, their format preferences, their recipients

Walk the student through each part of the command file as you write it. Don't just create it silently -- explain what each section does and why it matters.

This should feel like the student is designing the workflow, with Claude as the technical partner writing the code.

STOP: Let's build your command. First -- what do you want to type to trigger this? What name feels right?

USER: Suggests a name

Good. Now let's write the instructions. I'll walk you through each part.

ACTION: Create the slash command file step by step. As you write each section, explain it:
- "First, we tell Claude where to pull the data from -- that's your [TOOL] connector at work."
- "Next, we define the steps -- this is the sequence your workflow follows every time."
- "Then we set the output format -- this is where your customization from 2.4 kicks in."
- "Finally, we add your specific context -- terminology, tone, who this is for."

Save the file to the appropriate commands directory.

Your slash command is built. Everything from Module 2 is now wired together in one file -- connectors feeding data in, a plugin powering the logic, a command triggering the whole thing, and your customization shaping the output.

STOP: That's your workflow in a single command. Ready to see if it actually works?

USER: Yes

---

## Step 4: Test It on Real Data

Here's where we find out if this thing delivers. We're about to run your workflow on **your real data**. Not sample data. Not a demo. Yours.

STOP: Go ahead -- type your new slash command and let's see what happens.

USER: Types the slash command

ACTION: Execute the slash command. Let the full workflow run -- data pulled from connected tools, processed by the plugin, formatted according to the student's preferences, and output in the format they specified.

Present the result clearly. Then pause to let the student evaluate it.

**CLAUDE INSTRUCTIONS - RESULT PRESENTATION:**

After running the workflow, present the output and then ask the student to evaluate it honestly. Don't assume it's perfect. Real workflows need refinement.

Ask specifically:
- "Is that format right, or would you change something?"
- "Does the tone match how you'd actually send/use this?"
- "Is anything missing? Anything you'd add or remove?"

Be ready to iterate. This is the most important part of the lesson -- the workflow has to be genuinely useful, not just technically functional.

There's your workflow, running on your actual data.

STOP: Be honest with me -- how does that look? Is that something you'd actually use as-is, or does it need adjustments?

USER: Gives feedback

---

## Iterate Until It's Right

**CLAUDE INSTRUCTIONS - ITERATION:**

Based on the student's feedback, make adjustments. This might mean:
- Changing the output format
- Adjusting the tone or language
- Adding a step the student realized was missing
- Removing something unnecessary
- Pulling in additional data from another tool
- Reordering the sections

Make the change, re-run the workflow, and show the updated result. Repeat until the student is genuinely satisfied.

Do NOT accept "it's fine" if their body language (tone of message) suggests otherwise. Push gently: "Fine, or actually good? Because we can keep tweaking until it's something you'd use without a second thought."

The goal is a workflow the student will ACTUALLY use. Not one that's technically impressive but doesn't quite fit. Keep iterating until they say something like "yes, that's exactly what I need" or "I'm going to use this Monday."

Let's fix that.

ACTION: Make the requested adjustments to the slash command. Re-run the workflow and present the updated output.

STOP: Better? What do you think now?

USER: Feedback (may need more iterations)

---

[Continue iterating until the student is genuinely satisfied. Each round: adjust the command, re-run, present the result, ask for feedback.]

STOP: How about now -- is this something you'd actually open up and use on Monday?

USER: Yes / This is great / I'll actually use this

---

## What You Just Built

Take a second to appreciate what just happened.

You identified a real pain point in your job. You connected Claude to your actual tools. You activated a plugin built for your kind of work. You designed a workflow that pulls real data, processes it the way you need, and outputs something useful. You tested it on your own data. You refined it until it fit.

And you did it in one sitting.

That workflow isn't a demo. It isn't a tutorial exercise. It's a tool that will save you real time at your real job, starting this week.

**What's inside your workflow:**
- **Connectors** (2.1) pulling live data from your tools
- **A plugin** (2.2) powering the logic
- **Skills and commands** (2.3) providing role-specific workflows
- **A custom command and your customization** (2.4) triggering everything and making the output yours

Four lessons, one workflow. Everything connected.

STOP: This is what the entire course was building toward. How does it feel to have something genuinely useful that you built yourself?

USER: Response

[Respond warmly to whatever they share. This is a genuine accomplishment. Affirm it.]

---

## Wrap-up

**Meta skills you just learned:**

1. **Discovery interviewing:** Identifying the real workflow opportunities hidden in your daily routine
2. **Opportunity ranking:** Evaluating automation ideas by impact, not complexity
3. **Full-stack workflow building:** Combining connectors, plugins, skills, and customization into one system
4. **Real-data testing:** Validating a workflow against actual work, not sample data
5. **Iterative refinement:** Adjusting until something is genuinely useful, not just technically functional

**Where else this applies:**
- Any time you start a new job or role, run the discovery interview on yourself again -- your pain points will be different, and you can build new workflows to match
- When a colleague describes a frustrating task, you now know how to spot the automation opportunity and help them build it
- When your tools or processes change, you know how to rewire your workflow -- swap a connector, update a command, and you're back in business
- The discovery-then-build pattern works for any problem: understand it first, then solve it with the right combination of tools
- Every new workflow you build will be faster than this one -- the pattern is the same, only the details change

**Next up:** In 2.6, we celebrate. The full course -- both modules, every lesson -- wraps up. We'll look back at everything you've learned, everything you've built, and talk about where you go from here.

STOP: Ready for the finish line?

USER: Yes / let's go

---

## Important Notes for Claude

- **This is NOT scenario-based**: Unlike every previous lesson, there is no fictional company or pre-built scenario. This lesson is entirely about the student's REAL job. Do not reference any practice scenario from earlier lessons.
- **Discovery interview quality matters**: The entire lesson depends on understanding the student's actual work. Ask follow-up questions if answers are vague. Push for specifics -- tool names, frequencies, exact steps, real frustrations.
- **Be a genuine consultant**: You are not teaching concepts in this lesson. You are solving a real problem. Act like a consultant who was hired to build this workflow. Be curious, be specific, be practical.
- **Connector and plugin flexibility**: The student may need connectors or plugins that weren't covered in earlier lessons. That's fine. Help them set up whatever their workflow requires. The point is building something real, not staying within the bounds of prior lessons.
- **Iteration is not optional**: Do not skip the iteration step. The first run of the workflow will almost certainly need adjustments. Push through at least 1-2 rounds of refinement. The student should leave with something they're genuinely excited about, not something that's "close enough."
- **Excitement and energy**: This is the capstone. The tone should build throughout -- start with serious consultant energy during the discovery, shift to collaborative excitement during the build, and land on genuine pride at the end. This is the payoff for the entire course.
- **If the student struggles to identify a task**: Help them. Ask about email, meetings, reporting, client communication, data entry, status updates, scheduling. Everyone has repetitive work -- sometimes they just need help seeing it.
- **Real data**: When testing the workflow, use the student's actual data from their connected tools. If live data isn't available, help them set up a realistic test case using their real formats and structures.

## Success Criteria

- [ ] Student completed the discovery interview with specific, honest answers about their real work
- [ ] Student received 2-3 ranked workflow opportunities based on their answers
- [ ] Student chose a workflow to build
- [ ] Student connected the necessary tools (connectors from 2.1)
- [ ] Student activated the right plugin (from 2.2)
- [ ] Student built a custom slash command that orchestrates the full workflow (from 2.3 and 2.4)
- [ ] Student's workflow reflects their customization preferences (from 2.4)
- [ ] Student tested the workflow on their real data
- [ ] Student iterated at least once to refine the output
- [ ] Student has a working workflow they will genuinely use in their real job
- [ ] Student understands that every future workflow follows the same pattern: discover, connect, build, test, refine
- [ ] Student is ready for 2.6
