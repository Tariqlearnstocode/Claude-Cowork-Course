# Gusto PTO Policy Configuration

*Screenshot notes from Kelly's laptop - how PTO is currently set up in Gusto*

---

## Policy Name: "Standard PTO"

**Accrual Method:** Accrual-based
**Accrual Frequency:** Per pay period (bi-weekly)
**Annual Accrual:** 120 hours (15 days)
**Accrual Rate:** 4.62 hours per pay period

**Maximum Balance:** 240 hours (can bank up to 30 days)
**Carryover:** Unlimited (no use-it-or-lose-it)

**Waiting Period:** None (starts accruing day 1)

**Applied To:** All full-time employees by default

---

## Policy Name: "Legacy PTO - 10 Days"

**Status:** INACTIVE (no longer applying to new hires)

**Accrual Method:** Accrual-based
**Accrual Frequency:** Per pay period
**Annual Accrual:** 80 hours (10 days)
**Accrual Rate:** 3.08 hours per pay period

**Maximum Balance:** 160 hours
**Carryover:** Unlimited

**Waiting Period:** None

**Applied To:** (Should be early employees but not properly configured)

---

## Policy Name: "Executive PTO"

**Accrual Method:** Accrual-based
**Accrual Frequency:** Per pay period
**Annual Accrual:** 160 hours (20 days)
**Accrual Rate:** 6.15 hours per pay period

**Maximum Balance:** 320 hours
**Carryover:** Unlimited

**Waiting Period:** None

**Applied To:** David Kowalski only

---

## Problems I Found

### 1. Wrong Employees on Wrong Policies

When I configured the 15-day "Standard PTO" policy, I didn't go back and move early employees from the 10-day policy to the new one. Some of them are still accruing at 10 days, some were manually moved, and I don't have good records of who is where.

**Employees who SHOULD be on 10 days (if we're honoring original terms):**
- E001-E009 (hired before informal change)

**Employees who ARE on 15 days in Gusto:**
- Most people, but I'm not 100% sure

**Employees who need 20 days:**
- David Kowalski (correctly configured)
- Marcus and Priya (founders - I set them to "unlimited" by just not tracking)

### 2. Carryover Doesn't Match Handbook

The handbook says "use it or lose it" at year end. Gusto is configured for unlimited carryover. We've never enforced the use-it-or-lose-it because:
- I forgot to configure it
- No one complained
- It would have been a mess to implement mid-year

### 3. Part-Time Employee

Tiffany Morgan (part-time, 25 hrs/week) should get prorated PTO. I configured her at 60 hours (7.5 days) per year, which is roughly proportional. But the handbook doesn't have a part-time policy, so this was my best guess.

### 4. Sick Time vs. PTO

Michigan's Earned Sick Time Act (ESTA) requires employers to provide sick time. Our PTO policy is supposed to cover this, but I'm not sure it's properly compliant. The law has specific requirements about:
- Accrual rates
- Eligible uses
- Carryover
- Payout at termination

I meant to research this more carefully but never did.

### 5. Negative Balances

Gusto is configured to allow negative balances (employees can take PTO they haven't accrued yet). We've done this a few times for employees with personal emergencies. But:
- There's no policy about this
- If someone goes negative and then quits, can we deduct from final pay? (Maybe not in Michigan?)
- I've approved negative requests case-by-case with no consistency

---

## What Needs to Happen

1. **Audit who is on which policy** - Match Gusto settings to what each employee was actually promised
2. **Decide on carryover** - Either update handbook to match Gusto or change Gusto to match handbook
3. **ESTA compliance** - Verify our PTO structure meets Michigan sick leave requirements
4. **Document exceptions** - David's 20 days, any other negotiated amounts
5. **Decide on part-time policy** - Formalize what Tiffany has
6. **Decide on negative balance policy** - Write it down and apply consistently

---

## Gusto Login

PTO policies can be edited in: Settings > Time Off > Time Off Policies

Admin login required. Current admins:
- Kelly Ostrowski (kelly.o@) - TRANSFER TO NEW HR PERSON
- Marcus Chen (marcus@)
- Natasha Collins (natasha.c@) - Finance, limited access

---

*PTO sounds simple but it's one of the messiest things at this company. Three different policies, nothing matching the handbook, no one knows what they actually have. Good luck.*
