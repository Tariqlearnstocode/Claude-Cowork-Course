# TriNet HRIS Implementation - STALLED

**Started:** June 2024
**Current Status:** Partially implemented, mostly abandoned
**Monthly Cost:** $850/month (YES, WE'RE STILL PAYING FOR THIS)

---

## Background

In June 2024, Marcus decided we needed a "real HRIS" to scale. Gusto was handling payroll fine but we wanted:
- Better employee self-service
- Document management
- Time off tracking
- Performance management
- Onboarding workflows
- Reporting

We looked at several options:
- Rippling (too expensive at the time)
- BambooHR (didn't integrate well with Gusto)
- Paylocity (overkill for our size)
- TriNet (seemed like a good middle ground)

Marcus signed a 1-year contract with TriNet in June 2024.

---

## What Was Implemented

**Employee Directory:** ✓
- All employees are in TriNet
- Basic info (name, title, department, manager)
- Last synced with Gusto: August 2024

**Document Storage:** Partial
- Some employee documents uploaded
- Inconsistent - newer hires are in TriNet, older employees mostly in Google Drive
- No one actually uses it

**PTO Tracking:** ✓ (sort of)
- Configured for 15 days PTO + 10 holidays
- Problem: Doesn't match everyone's actual allocation (early employees have 10 days, David has 20)
- Problem: Historical PTO not imported, so balances are wrong
- Problem: Most employees don't use it, they still email me directly

**Onboarding Workflows:** Partial
- Templates created but never actually used
- New hires are still onboarded manually

**Performance Management:** Never set up
- Intended to do performance reviews through TriNet
- Never configured
- We still don't have a performance review process

**Reporting:** Never used
- Reports are available but I never learned how to use them
- Still doing reporting manually via Excel exports from Gusto

---

## What Was NOT Implemented

- Benefits administration (still using Gusto + direct enrollment)
- Time tracking (still using Gusto for hourly employees)
- Org chart (use Lucidchart occasionally)
- Payroll (stayed with Gusto)
- Recruiting/ATS (don't have one, use email and spreadsheets)

---

## Why Implementation Stalled

1. **Time:** I was the only HR person for 45+ employees. I didn't have time to learn a new system AND do my actual job.

2. **Dual Systems:** Running Gusto for payroll and TriNet for everything else meant constant syncing and reconciliation. It was more work, not less.

3. **Employee Adoption:** I tried to get employees to use TriNet self-service for PTO requests. About 30% adopted it. The rest kept emailing me.

4. **Support Issues:** TriNet's implementation support was... okay. After the initial setup period, I was on my own and couldn't figure things out.

5. **Leadership Attention:** Marcus signed the contract and then never checked in. No one was holding me accountable to finish implementation.

---

## Current State

We're paying $850/month ($10,200/year) for a system we barely use.

**What we use TriNet for:**
- Employee directory (sometimes)
- Document storage (inconsistently)
- PTO tracking (maybe 30% of employees)

**What we don't use it for:**
- Everything else

---

## Options Going Forward

### Option 1: Fully Implement TriNet
- Would require dedicated time (40+ hours) to configure properly
- Need to migrate all historical data
- Need to train all employees and managers
- Need to deprecate parallel systems

**Pros:** We're already paying for it
**Cons:** Significant time investment, still doesn't include payroll

### Option 2: Abandon TriNet, Use Gusto Only
- Gusto can do more than we're using it for
- PTO tracking, basic document storage, onboarding workflows
- Simpler for employees (one system)

**Pros:** Cheaper, simpler
**Cons:** Gusto is weaker on document management and doesn't have performance management

### Option 3: Switch to All-in-One Platform
- Rippling, Gusto (expanded), Justworks, Deel, etc.
- One system for payroll, HR, benefits, time tracking, etc.
- More expensive but less complexity

**Pros:** Modern, integrated, handles multi-state compliance
**Cons:** Migration project, cost, contract buyout

### Option 4: Keep Status Quo
- Continue paying for both Gusto and TriNet
- Continue using both half-heartedly
- Continue with manual processes filling the gaps

**Pros:** No effort required
**Cons:** Expensive, inefficient, data scattered everywhere

---

## TriNet Account Info

**Account Number:** WV-287456
**Admin Login:** kelly.o@woodwardventures.io (need to transfer to someone else)
**Password:** In my 1Password, need to give IT access
**Implementation Contact:** Gave up on us, no current contact
**Account Rep:** Sarah at (800) 555-0147 ext 4521 (she was helpful early on)
**Contract End:** June 2025 (RENEWAL DECISION NEEDED)

---

## Recommendation

Honestly? I'd recommend Option 3 - move to an all-in-one platform that includes payroll.

If we're going to Series A next year, investors will want to see clean HR operations. Having employee data scattered across Gusto, TriNet, Google Drive, and spreadsheets is not a good look.

Rippling is what I would have recommended but Marcus thought it was too expensive. It's worth revisiting. Or look at Deel (good for multi-state), Justworks (PEO option), or even just fully leaning into Gusto's expanded features.

Whatever you do, cancel TriNet before the contract auto-renews in June.

---

## Key Files/Locations

- TriNet employee import template: HR Shared > TriNet > employee-import-template.xlsx
- Training materials from implementation: HR Shared > TriNet > Training
- Original contract: HR Shared > Contracts > TriNet Contract 2024.pdf (should be - I might not have saved it)

---

*This is one of my regrets. We spent money and time on something that didn't work out. Hopefully the next person can either fix it or cut our losses.*
