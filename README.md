# kb-4471-date-reports

S01E03 work: ticket #4471 (412 date reports) holds two problems.

| issue | problem | reports | outcome |
| --- | --- | --- | --- |
| #1 | parser reads dates month first for day-first tenants | 379 | fixed (`fix(dates): parse dd/mm for eu locales`) |
| #2 | booking-v3 form hint says MM/DD/YYYY to day-first tenants | 33 | won't fix (booking-v3 form retired) |

- `src/routes/kb/incidents/4471-split/+page.svx`: the kb page (signed).
- `rendered/4471-split.html`: the page as the desk sees it.
