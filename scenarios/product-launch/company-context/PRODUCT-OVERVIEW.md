# BookIt Product Overview

*Version 1.2 | Last updated: September 2024*

---

## What Is BookIt?

BookIt is a scheduling and appointment management application for small businesses. Customers can book appointments online, businesses can manage their calendar, and everyone gets reminders.

**Current version:** 1.2.4
**Platforms:** Web app, iOS, Android
**Launch date:** October 15, 2024

---

## Core Features

### Booking Management
- Online booking page (customizable with business branding)
- Calendar view (day/week/month)
- Manual appointment creation
- Recurring appointments
- Multi-staff scheduling
- Service catalog with durations and pricing

### Customer Communication
- Email confirmations
- SMS reminders (optional add-on)
- Rescheduling/cancellation links
- Custom reminder timing

### Integrations
- Google Calendar sync
- Outlook Calendar sync
- Stripe for payments
- Square for payments
- Zoom for virtual appointments
- Zapier (beta)

### Business Tools
- Basic reporting (appointments per day/week/month)
- Customer database
- No-show tracking
- Revenue tracking
- Export to CSV

### Team Features
- Multi-user accounts
- Staff schedules and availability
- Permission levels (admin, staff, view-only)
- Team calendar view

### Enterprise Features *(added Q3 2024)*
- API access
- Custom branding removal
- SSO integration (SAML)
- Dedicated support
- Custom contract terms

---

## Pricing Tiers

| Plan | Price | Target |
|------|-------|--------|
| **Free** | $0/mo | Testing, very small use |
| **Solo** | $12/mo | Individual service providers |
| **Team** | $29/mo | Small businesses, 2-5 staff |
| **Business** | $79/mo | Growing businesses, 6-15 staff |
| **Enterprise** | Custom | Large organizations, 15+ staff |

*Note: Enterprise tier was added in September 2024 at Dana's direction. Pricing and feature set were not fully finalized before launch.*

---

## Tech Stack

**Frontend:**
- React 18
- TypeScript
- Tailwind CSS
- React Query

**Backend:**
- Node.js / Express
- PostgreSQL
- Redis for caching
- AWS infrastructure

**Mobile:**
- React Native (shared codebase)

**Third-party services:**
- Twilio (SMS)
- SendGrid (email)
- Stripe / Square (payments)

---

## Target Market

### Original Target (Q1-Q2 2024)
- Solopreneurs and freelancers
- Local service businesses (5 or fewer employees)
- Industries: salons, fitness, wellness, consulting, home services

### Revised Target (Q3 2024)
- Small-to-medium businesses
- Professional services firms
- "Anyone who books appointments"
- Enterprise clients (new focus)

### Actual User Base (as of January 2025)
- ~340 active accounts
- Mostly individual consultants and freelancers
- Very few multi-staff businesses
- Zero enterprise clients

---

## Known Issues (as of last update)

1. **Mobile app performance** - Slow load times, occasional crashes on Android
2. **Calendar sync reliability** - Google Calendar sync fails ~5% of the time
3. **Onboarding confusion** - Users don't complete setup; many abandon at payment integration step
4. **Feature discoverability** - Users don't find features they're paying for
5. **SMS delivery** - Delays reported, especially international numbers

---

## Competitive Positioning

**Intended positioning:** "The scheduling app that's powerful enough for growing businesses but simple enough for anyone."

**Actual perception (based on reviews):** "Confusing interface, tries to do too much, not as polished as Calendly."

---

## Development Roadmap (Pre-Launch)

*This was the plan as of August 2024:*

**Phase 1 (MVP):** Basic booking, calendar, reminders ✓
**Phase 2:** Integrations (Google, Stripe, Zoom) ✓
**Phase 3:** Team features ✓
**Phase 4:** Mobile apps ✓
**Phase 5:** Enterprise features ← *rushed to include in launch*
**Phase 6:** Advanced analytics ← *not started*
**Phase 7:** Marketplace/ecosystem ← *not started*

---

## Key Metrics (Current)

| Metric | Target (Jan 2025) | Actual |
|--------|-------------------|--------|
| Active Users | 5,000 | 340 |
| MRR | $15,000 | $2,100 |
| Churn Rate | <5%/mo | 23%/mo |
| NPS Score | 40+ | 12 |
| App Store Rating | 4.5+ | 3.1 |

---

## Open Questions

- Should Enterprise tier be removed or repositioned?
- What features do actual users value most?
- Is the product too complex or not complex enough?
- Who is our actual customer?

---

*This document needs significant revision based on post-launch learnings. Consider this a snapshot, not current strategy. —Marcus, 11/2024*
