# kb-4471-date-reports

S01E03 work: ticket #4471 (412 date reports) holds two bugs.

- Issues: one per problem, each with its report count.
- `src/routes/kb/incidents/4471-split/+page.svx`: the kb page.
- `rendered/4471-split.html`: the page as the desk sees it.

## Fix

Decision 0002 (`src/routes/kb/decisions/0002-dedupe-by-cause/`) replaces the subject-line merge rule
with a cause rule, so the parser bug (379) and the booking-v3 hint bug (33) are triaged apart.
