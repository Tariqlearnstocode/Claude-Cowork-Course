# Emergency Standup - October 17, 2024

**Attendees:** Jerome (CTO), Pete (Lead Dev), Carmen (Support), Marcus (PM)
**Note-taker:** Pete Novak
**Duration:** 30 minutes
**Context:** Day 2 post-launch. Things are on fire.

---

## Current Crisis

**Carmen:** I have 89 support tickets from the last 24 hours. I cannot keep up. Major issues:

1. **Calendar sync failing** - About 15 users reporting Google Calendar isn't syncing. Appointments appearing in BookIt but not Google. This is bad.

2. **Mobile app crashes** - Android especially. At least 20 reports.

3. **Can't figure out setup** - The majority of tickets. People creating accounts and then getting stuck.

4. **SMS reminders not sending** - 5 reports. Might be Twilio issue?

5. **Password reset emails not arriving** - 3 reports.

**Jerome:** Calendar sync is priority one. Pete, can you look at it immediately?

**Pete:** Already on it. I think I know the bug—we're not handling Google's rate limiting properly. Fix should take a few hours.

**Jerome:** Do it. Drop everything else.

---

## Triage

**Marcus:** Let's prioritize. What's going to cause the most churn?

**Carmen:** Calendar sync. If people can't trust their appointments are syncing, they'll leave immediately.

**Pete:** I'll have a fix by end of day. Might need to push an emergency patch.

**Marcus:** Mobile crashes?

**Jerome:** That's a bigger fix. The app was rushed to launch. We need significant optimization work.

**Pete:** I've been saying this for months. We shipped before it was ready.

**Marcus:** I know. Let's focus on what we can do now. Can we at least fix the worst crashes?

**Pete:** I can patch the critical ones. But real performance improvement is weeks of work.

**Jerome:** Patch the crashes. Pete, how many hours in a day do you have?

**Pete:** Apparently not enough. I've been here until midnight every night since Friday.

---

## Support Overload

**Carmen:** I need help. I'm one person handling 90 tickets, answering the chat widget, managing social media DMs, and fielding phone calls.

**Marcus:** Dana said we'd hire a contractor.

**Carmen:** When? I'm drowning NOW.

**Jerome:** I'll talk to Dana today. In the meantime, can Aaliyah help with social DMs?

**Marcus:** She's handling the launch marketing. But I'll ask.

**Carmen:** Can we at least create some help docs? Half my tickets are "how do I set up my services" - if we had a guide, I could just link it.

**Marcus:** I'll work on that today. Quick start guide.

**Carmen:** Thank you. Anything helps.

---

## Decisions

1. **Pete:** Fix calendar sync bug TODAY - emergency patch
2. **Pete:** Patch critical Android crashes - next 48 hours
3. **Marcus:** Write quick start guide - today
4. **Jerome:** Talk to Dana about support help - today
5. **Carmen:** Triage tickets - calendar sync and crashes get priority responses

---

## Off-the-Record (Pete's addition)

I'm adding this because I'm frustrated and I want it documented.

This crisis was preventable. In September, I told leadership:
- The mobile app wasn't ready
- Calendar sync had edge cases that would fail
- We needed more QA time

I was told "we're launching October 15, make it work."

Now it's October 17 and everything I warned about is happening.

I've worked 70+ hours in the last week. I'm exhausted. My partner is angry that I'm never home. I have a headache that won't go away.

Jerome and Dana made the call to ship early. The engineering team is now paying the price.

If this continues, I'm going to burn out. And if I burn out, they'll really be in trouble—I'm the only one who understands the entire codebase.

I don't know how much longer I can do this.

—Pete

---

## Follow-Up (October 18)

**Calendar sync:** Fixed. Pushed patch at 11pm on Oct 17.
**Android crashes:** Critical ones patched. Still issues but not crashing constantly.
**Quick start guide:** Marcus finished it. Carmen says it's helping.
**Support help:** Dana approved a contractor but HR hasn't posted the job yet.

We're stabilizing but we're in firefighting mode. No time to actually improve anything—just keeping our heads above water.

—Pete
