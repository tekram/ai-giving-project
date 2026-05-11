# OBAT Helpers Marketing Deck — Insights & Ideas

## Context

OBAT Helpers is a 20+ year old nonprofit (founded 2004) serving camps in Bangladesh across education, clean water, health, and economic empowerment. They raised $1.59M in 2024 (down from a $2.18M peak in 2023) and are targeting $3M+ in 2026. This deck reveals strong mission clarity but significant structural fundraising challenges — particularly around donor retention and first-time donor conversion — that givestack is well-positioned to address.

---

## Key Insights from the Slides

### 1. Revenue Dropped 27% in 2024 — The Biggest Red Flag
- $1.93M (2022) → $2.18M (2023) → **$1.59M (2024)**
- The deck frames 2026 targets optimistically but doesn't explain what caused the 2024 drop
- The 2023 peak likely coincides with a strong Ramadan/Qurbani campaign or a major donor push
- **Insight:** Recovering to $2M+ requires understanding the 2023 driver, not just setting higher targets

### 2. First-Time Donor Churn is the #1 Financial Lever
- **58% of first-time donors never give again** (target: 40%)
- Reducing overall churn 14% → $450K+ in additional annual revenue (their own estimate)
- 58% of their donor base are small donors (≤$100) — the volume is there, the stickiness is not
- **Insight:** The acquisition funnel is working; the post-donation experience is failing

### 3. Zakat & Islamic Giving Are Underbuilt as Retention Tools
- Zakat calculator mentioned as a conversion tool
- Zakat reminders listed under retention
- Ramadan/Qurbani campaigns are their largest (Q2) engagement spike
- Yet only 10% of budget goes to Marketing & Awareness
- **Insight:** Islamic giving is not a campaign — it's a calendar. It should drive year-round engagement architecture, not just a Q2 spike

### 4. Monthly Recurring Donors Are at 32% — Industry Average is Often 20-30%, So Ceiling is Higher Than Acknowledged
- Target is 50%, which is aggressive but achievable for cause-aligned donors
- The jump from 32% to 50% requires identity shift: donors from "givers" to "partners"
- **Insight:** The deck lists monthly giving under "Retention" but it should be treated as an onboarding outcome, not a retention tactic

### 5. TikTok Has 120K Monthly Reach But No Follower Momentum
- Instagram: 8.2K followers; TikTok: 120K reach/month but follower count not shown at scale
- TikTok reach suggests content is being algorithmically distributed but not converting to owned audience
- **Insight:** TikTok is top-of-funnel reach they don't own — they need a bridge from TikTok → email/SMS list

### 6. Donor Breakdown Is Extremely Top-Heavy in Volume, Bottom-Heavy in Revenue
- 58% small (≤$100), 10% mosque/community, 4% corporate/Zakat partners, 2% $1K+ individuals
- Revenue per segment not shown — likely the 4% corporate/major donors drive disproportionate revenue
- **Insight:** There's a missing "mid-tier" donor segment ($250–$999) that could be cultivated from the 58% small donor pool

### 7. Budget Allocation Is Unusual — 70% Unlabeled
- Pie chart shows: 70% (unlabeled, possibly unrestricted/pass-through), 15% Programs & Direct Aid, 10% Marketing, 5% Fundraising
- If 70% is program delivery, the overhead ratio is excellent for donor trust
- **Insight:** This story (70 cents of every dollar to programs) is a major trust signal that isn't being marketed prominently enough

---

## Ideas for givestack

### Idea 1: Islamic Giving Calendar Mode for NGO Profiles
OBAT's entire donor journey is structured around the Islamic calendar (Ramadan, Qurbani/Eid al-Adha, Zakat due dates). givestack could offer NGOs with Muslim donor bases a calendar-aware mode:
- Automated campaign launch tied to Islamic calendar dates
- Pre-Ramadan donor outreach sequence (30/14/7 day pre-campaign warming)
- Zakat eligibility calculator embedded in the donation flow (donor enters nisab, gets recommended amount)
- Post-Eid giving reminders for Qurbani

### Idea 2: First-Time Donor Onboarding Journey
OBAT's 58% first-time churn is almost certainly a post-donation experience failure. givestack could build:
- A "Day 1, Day 7, Day 30" automated impact update sequence for new donors
- Specific impact attribution: "Your $50 enrolled 1 student for a month"
- A soft monthly upgrade prompt at Day 30 ("Join 32% of our supporters as a monthly partner")
- This is distinct from generic thank-you emails — it's impact-linked with real numbers from the NGO's data

### Idea 3: Churn Prediction & Win-Back Dashboard for NGOs
With $450K in identified revenue at stake from churn reduction, an NGO would pay for tools that:
- Flag donors who haven't given in 11 months (before the 1-year lapse threshold)
- Segment: lapsed small donors vs. lapsed repeat donors (different messaging needed)
- Surface a "win-back campaign" builder with pre-written re-engagement templates
- Track win-back rate over time

### Idea 4: Donor Tier Upgrade Engine
58% of donors are ≤$100. The upgrade path to $250/year (mid-tier) is underserved. Ideas:
- "Impact unlock" messaging: "At $250/year, you sponsor a student for a full semester"
- Milestone-triggered upgrade prompts: after 3 consecutive donations, offer a loyalty recognition + upgrade ask
- Corporate matching awareness at the $100–$500 tier (many employers match but donors don't know)

### Idea 5: Corporate Partnership Pipeline for NGOs
Only 4% of OBAT's donor base is corporate — a massive untapped segment. givestack could:
- Add a "Corporate Partners" section to NGO profiles with partnership tier cards
- Build a simple lead capture form for corporate inquiries tied to the NGO's CRM
- Surface corporate matching programs that align with the NGO's cause categories
- This connects directly to the SFDC research already in the repo

### Idea 6: TikTok → Email Bridge (Social-to-Owned Conversion)
OBAT has 120K monthly TikTok reach with no clear capture mechanism. givestack could:
- Provide NGOs a "link in bio" landing page optimized for social-to-email conversion
- Offer a lead magnet template ("Get OBAT's 2024 Impact Report") gated by email
- Track social referral traffic through the embeddable widget

### Idea 7: Impact Transparency as a Retention Tool
The 2024 annual report data (11.7K students, 165K clean water access) is compelling but buried in a deck. Ideas:
- An auto-generated "Impact Card" for donors after each major campaign closes
- A live impact counter widget on the NGO's site (updated from Firestore)
- Donor-specific impact statements ("In 2024, your giving helped provide clean water to 8 people")

### Idea 8: Revenue Recovery Analysis Mode
The 2022→2023→2024 revenue dip is a signal that requires explanation before setting 2026 targets. givestack could offer:
- A revenue trend visualization in the NGO dashboard showing year-over-year donation patterns
- Campaign attribution: which campaign drove the 2023 peak?
- Cohort analysis: did a specific donor segment churn heavily in 2024?

---

## Prioritization (Highest Impact First)

| Idea | Impact | Effort | Why |
|------|--------|--------|-----|
| First-time donor onboarding journey | Very High | Medium | Directly addresses the $450K churn gap |
| Islamic giving calendar mode | High | Medium | Differentiates platform for Muslim-focused NGOs |
| Churn prediction dashboard | High | High | Requires Firestore analytics build |
| Donor tier upgrade engine | Medium | Low | Can be messaging-only initially |
| TikTok → email bridge | Medium | Low | Link-in-bio landing page is fast to build |
| Corporate partnership pipeline | Medium | High | Connects to SFDC research already underway |
| Impact transparency cards | Medium | Medium | Requires NGO data pipeline |
| Revenue recovery analysis | Low | High | Analytics infrastructure needed |

---

## Connection to givestack

OBAT Helpers is an ideal pilot NGO for the platform. They have:
- Real data (Form 990 public financials)
- Clear donor segments (Islamic community, corporate, small)
- An active campaign calendar
- A churn problem quantified in dollar terms
- An existing embeddable widget use case (their donation QR code / site)

The ideas above map directly to features already in development (CampaignDiscovery, DonorIntelligence, DonorLifecyclePipeline, FilterBuilder) and could be validated against OBAT's real marketing needs.
