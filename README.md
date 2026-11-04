# Tidewell Physio (Handover Desk demo target)

A fictional physiotherapy clinic's site, used as the live target for
[Handover Desk](https://github.com/) demos. It is static HTML/CSS/JS with no build step.

**It ships with problems on purpose.** Handover Desk's `auditor` agent should find them
before the "client" sees the site, and the `fixer` agent should fix them in pull requests.
The answer key is in the Handover Desk repo, not here, so the auditor works only from the live URL.

Run it locally:

```bash
python3 -m http.server 8080
```
