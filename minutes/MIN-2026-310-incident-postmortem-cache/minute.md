# MIN-2026-310 — Incident Postmortem Cache

- **Meeting ID:** MIN-2026-310
- **Date:** 2026-10-12
- **Type:** incident-review
- **Facilitator:** Priya Raman
- **Attendees:** 13
- **Duration (minutes):** 25

## Agenda

- Timeline of the cache outage on 2026-10-10
- Action items to prevent a repeat

## Discussion

The postmortem covered the ninety-minute cache outage triggered by a bad eviction-policy rollout. Thirteen responders and stakeholders attended; the contributing factors were documented in the shared doc.

## Action Items

1. Add a canary stage for cache configuration rollouts — Priya Raman (due 2026-10-16)
2. Extend the eviction-policy alerting to all shards — Marcus Feld (due 2026-10-15)
3. Publish the postmortem to the engineering-wide channel — Elena Sokolova (due 2026-10-14)
