# ABX Play Recommender

An internal tool for Amplitude's Account-Based Experience (ABX) team to quickly generate personalized play recommendations for global enterprise accounts.

## What it does

Enter details about a target account and the tool surfaces 3 recommended ABX plays ranked by fit score, each with:

- Recommended channels
- Effort level and budget range
- A description of what to do and why it works
- A personalized copy starter (email/message) you can adapt and send

## How to use it

Open `abx-play-recommender.html` in any browser — no installation or server needed.

Fill in the account details:

| Field | Options |
|---|---|
| Account name | Free text |
| Industry | Financial Services, Retail & eCommerce, Media & Entertainment, Travel & Hospitality, Technology & SaaS, QSR & Food Service, Logistics & Supply Chain, Healthcare |
| Geo | AMER, EMEA, APJ |
| Account type | Prospect, Customer |
| Deal stage | No Open Opps, S1–S6 |
| Persona to target | All, Product, Marketing, Data, Engineering, AI Builder |
| ABX goal | Generate pipeline, Accelerate deal, Multithread personas, Prevent churn, Drive expansion |
| Key challenge or context | Optional free text (e.g. "Champion went dark", "Evaluating Mixpanel") |

If no ABX goal is selected, the tool infers one from the deal stage and account type.

## Play types included

The play library includes 27 plays across 5 goals, covering:

- Executive air cover campaigns
- Curated gifting sequences (Sendoso)
- 1:1 LinkedIn matched audience ad tracks
- Onsite executive briefings and working sessions
- VIP dinners and persona roundtables
- Proof of value sprints
- Competitive displacement bundles
- Champion re-engagement sequences
- Usage health workshops
- Land-and-expand motions
- Platform upsell webinars
- Executive cross-sell briefings

## Notes

- All account data shown is mock/demo data — no real Amplitude customer data is used
- Play selection rotates based on account name and persona to surface different combinations
- Copy starters are personalized to industry, persona, and context using built-in hooks
- Suggested contacts are placeholder names for demo purposes — intended to be replaced with live CRM/6sense data in a future integration

## Built by

Amplitude ABX Team · June 2026
