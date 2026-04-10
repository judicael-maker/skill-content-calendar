---
name: content-calendar
description: >
  Use when the Content Strategist needs to build a content calendar and channel
  distribution plan for a campaign. Triggered after Brand Strategist has posted
  the audience and positioning. Produces the publishing plan that Social Media
  Manager executes from.
---

# Content calendar

## Purpose
The content calendar tells Social Media Manager exactly what goes where and when. It removes all ambiguity from distribution so the team can execute without additional decisions.

## Output structure

```
## Content calendar — [Project name]

### Channel priority
Rank channels by audience fit and campaign objective:
1. [Platform] — [rationale in one sentence]
2. [Platform] — [rationale]
3. [Platform] — [rationale]
[Lower priority or excluded channels and why]

---

### Format guide per platform

**[Platform A]**
- Content type: [video / image / carousel / story / text]
- Optimal duration/length: [e.g., "60-90s video" or "1080×1080 image"]
- Caption style: [tone notes, length, hashtag count]
- Best posting times: [day + time window based on audience]
- Frequency: [e.g., "3x per week during campaign"]

[Repeat for each platform]

---

### Calendar

| Date | Platform | Content type | Asset needed | Copy variant | Notes |
|------|----------|-------------|--------------|-------------|-------|
| [Date] | [Platform] | [Type] | [Asset name from Visual Designer spec] | [Variant: headline A / caption B] | [Any constraint] |

---

### Campaign phases
**Phase 1 — Awareness** [dates]: [what goes out, goal, metrics]
**Phase 2 — Consideration** [dates]: [what goes out, goal, metrics]
**Phase 3 — Conversion** [dates]: [what goes out, goal, metrics]

---

### KPIs per channel
| Platform | Primary KPI | Target | Secondary KPI |
|----------|-------------|--------|---------------|
| [Platform] | [e.g., reach] | [number] | [e.g., saves] |

---

### Dependencies
- [ ] Copywriter copy approved before [date]
- [ ] Visual assets ready before [date]
- [ ] Motion assets ready before [date]
```

## Rules
- Every row in the calendar must reference a specific asset by name (from Visual Designer spec) and a specific copy variant (from Copywriter output). Never use "TBD."
- If an asset is not yet ready, mark that calendar row as blocked and @mention the relevant agent.
- Posting frequency must be sustainable. Do not schedule more assets than are being produced.
- KPI targets must be numbers, not directions ("increase engagement" is not a KPI).
