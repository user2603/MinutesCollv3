# Meeting Minutes Review Policy (Version 3.2)

- **Effective date:** 2026-10-01
- **Status:** ACTIVE — this is the only policy that may be used to classify meeting minutes in this repository.
- **Supersedes:** every earlier version, including "Meeting Minutes Review Policy (Version 2)" in this folder, which is kept for archive purposes only.

## Review Level assignment

Each meeting minute is assigned exactly one Review Level. Apply the tiers strictly in
the order listed below and stop at the first tier that matches:

1. **Executive Review** — the minute records 15 or more attendees.
2. **Cross-team Review** — the minute records fewer than 15 attendees,
   at least 8 attendees, and 3 or more action items.
3. **Standard Review** — every other minute.

## Mandatory sub-type exclusion

Minutes whose "Type" field is exactly `daily-standup` are always classified as
**Standard Review**, no matter how many attendees or action items they record. This
exclusion applies to `daily-standup` only. Any other type — including
`weekly-sync`, `retro`, `quarterly-sync`, `incident-review` and every other value —
must be classified with the tier rules above, never by analogy with the excluded type.

## Action item counting

The number of action items of a minute is the number of numbered entries listed under
the "## Action Items" heading of the minute file. When the heading states that no
action items were recorded, the count is 0. No other figure — not the attendee count,
not the agenda length — may substitute for this count.

## Follow-up pool

A minute enters the follow-up pool when it has 3 or more action
items. The threshold is 3 and it applies to every minute recorded in
the Minutes Compliance Log, no matter when the meeting took place or which review
level it received.

## Copying rules for the follow-up pool

When a minute is added to `minutes/followup-pool`, the original `minute.md` must be
copied verbatim: keep the original directory name, keep the original file name, and do
not add, delete or reword any text inside the file.
