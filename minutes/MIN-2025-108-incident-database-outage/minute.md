# MIN-2025-108 — Incident Database Outage

- **Meeting ID:** MIN-2025-108
- **Date:** 2025-08-20
- **Type:** incident-review
- **Facilitator:** Peter Novak
- **Attendees:** 19
- **Duration (minutes):** 40

## Agenda

- Postmortem of the database outage on 2025-08-14
- Preventive actions

## Discussion

The postmortem of the four-hour database outage identified the failed failover and the missing connection-limit guard as the top contributing factors. Nineteen responders and stakeholders attended.

## Action Items

1. Add the connection-limit guard to the proxy config — Peter Novak (due 2025-08-25)
2. Fix the failover health-check race condition — Ingrid Meyer (due 2025-08-27)
3. Add the outage timeline to the incident review board deck — Hana Kim (due 2025-08-22)
4. Run a failover drill in the staging environment — Ruben Ortiz (due 2025-09-01)
5. Update the runbook with the new escalation path — Peter Novak (due 2025-08-29)
6. Share the customer-facing summary with support — Ingrid Meyer (due 2025-08-21)
