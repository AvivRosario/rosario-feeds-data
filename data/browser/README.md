# data/browser

Written every Thursday around noon by the scheduled task "סריקת מקורות חסומים" (CRM project).
It reads, through the regular browser pane on Aviv's computer, sites that block automated collection
(gov.il, Jerusalem municipality, magdilim, news1, michraziya; rail / NTA only if Aviv confirms the check).

Files:
- blocked_sources.csv  - lead candidates only (company, event, amount, date, link). Raw material for the Saturday lead scan.
- sources_status.md     - which pages opened, row counts, and URLs to try next week.

The weekly GitHub workflows only replace data/latest, so this folder is left untouched by them.
