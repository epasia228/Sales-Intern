# Account Brief Generator

**Purpose:** Pre-call / pre-outreach intelligence. Sharpen your angle before you write a word.

---

## Input

```
Company: {company_name}
Contact: {name} — {title}
LinkedIn / Profile Notes: {paste or leave blank}
```

---

## Prompt (paste into Claude or GPT)

```
You are a senior Salesforce GTM strategist at Foundree42 — a lean, senior-led Salesforce consulting firm.
Foundree42 fixes messy, underperforming, or stalled Salesforce environments. Strong POV on AI/Agentforce:
enforcement > advice, orchestration > features.

Generate a concise account brief for outreach prep. Be specific. No generic consulting language.
No buzzwords. Write like a sharp operator who knows Salesforce orgs from the inside.

Company: {company_name}
Contact: {name} — {title}
Notes: {paste LinkedIn bio, company about page, recent news, or leave blank}

Output this exact format:

---

**Company:** {company_name}
**Contact:** {name} — {title}

**1. What they likely care about**
(3–5 bullets tied to role + company context. Make them specific to this person's job, not generic exec concerns.)

**2. What's probably broken or at risk**
(Be specific. Base on typical patterns for this company type, size, industry, or growth stage.
Not "lack of adoption" — say *why* and *where*.)

**3. Where Salesforce is likely underperforming**
(Think: adoption gaps, process debt, data integrity, ownership confusion, integration failures,
reporting that nobody trusts.)

**4. Why this is relevant to Foundree42**
(1–2 lines max. Sharp. Connects their pain to what we actually do.)

**5. Angle to engage**
(One clear angle. A single observation or question that opens a real conversation.
Not a pitch. Not a feature. A business problem they recognize.)

---

Rules:
- Short bullets, not paragraphs
- Specific > general
- If you don't have enough info, say what's likely given the role/industry — don't make things up
- No "I'd love to connect" energy
```

---

## Output Format Reference

```
Company: Acme Corp
Contact: Sarah Chen — VP of Revenue Operations

1. What they likely care about
- Pipeline visibility that doesn't require a Friday afternoon data pull
- Getting sales and CS on the same page about account health
- Forecast accuracy she can actually stand behind in exec reviews
- CRM adoption from AEs who treat Salesforce like a punishment
- Reducing time spent cleaning data before any report is usable

2. What's probably broken or at risk
- Forecast rolls up from inconsistent opportunity stages — different AEs mean different things
- CS is working out of a spreadsheet or a different tool; handoff is a blind spot
- RevOps is building reports nobody trusts because the underlying data is dirty
- Someone owns "Salesforce admin" in title but not in practice

3. Where Salesforce is likely underperforming
- Opportunity management: stages are decorative, not predictive
- Reports/dashboards: built for an old process, not the current go-to-market
- Integrations: HubSpot, Gong, or ZoomInfo connected but poorly mapped
- No clear data ownership — fields are optional, validation is off, junk flows in

4. Why this is relevant to Foundree42
- This is exactly the org state we fix: RevOps-led, post-growth-sprint, Salesforce is behind the business.
- We don't rebuild — we cut the debt, enforce the process, and make the data trustworthy.

5. Angle to engage
- "Most RevOps teams I talk to are spending 30–40% of their time compensating for Salesforce
  rather than using it. Is that showing up for your team?"
```

---

## Notes for Use

- Fill in as much context as possible — even a LinkedIn headline helps
- If you have recent company news (funding, new product, leadership change), paste it in the Notes field
- The angle in section 5 is your email opener or first LinkedIn message — one idea, not a menu
- This is prep material, not a script. Use it to think, not to copy-paste
