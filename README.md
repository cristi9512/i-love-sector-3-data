# Sesizări Sector 3 · date

The archive behind [sesizari-sector3.vercel.app](https://sesizari-sector3.vercel.app): every public report sent through
the Sector 3 City Hall's CityCare service ("I Love Sector 3"), checked every 15 minutes, with the history of each report.

Code and documentation: [cristi9512/i-love-sector-3-public](https://github.com/cristi9512/i-love-sector-3-public).

| Path | What it holds |
|---|---|
| `data/incidents/YYYY-MM.json` | Every report created in that month, one per line, with its `history` of status changes, replies, edits and deletions |
| `data/changes/YYYY-MM.jsonl` | Log of every change the archive noticed |
| `data/meta.json` | Last run, totals, archive coverage, reports open for over 30 days |
| `data/recurrence.json` | Places where the same problem was reported again after being closed as resolved |
| `data/feeds/*.xml` | RSS feeds for the whole sector and each neighbourhood |
| `data/suppressed.json` | Report numbers removed on request; never stored again |

The data comes from a public service of the City Hall and may contain personal details that residents or the City Hall
wrote. To ask for a report to be removed, use the form on the site's repository (label `eliminare`). This repository's
history may be squashed from time to time to keep it small.
