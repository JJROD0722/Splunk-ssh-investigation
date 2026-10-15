# Splunk SSH Login Investigation

Investigated sample SSH authentication logs using Splunk Cloud, SPL searches, and a dashboard.

## Findings
- Found 132 failed-login events matching 194.8.74.23 across four hosts.
- Identified targeted usernames, including local, system, and root.
- Found no matching successful password or public-key SSH logins.
- Observed a pattern consistent with automated login guessing; compromise was not confirmed.

## Report
[Read the investigation](Splunk-SSH-Investigation.pdf)

## Skills demonstrated
- Log ingestion and analysis
- SPL searches and field extraction
- Dashboard creation
- Evidence-based reporting

## Scope
Used Splunk's official tutorialdata.zip practice dataset with All time selected. Repeated timestamps limit conclusions about attempt speed. No live incident or response actions were involved.
