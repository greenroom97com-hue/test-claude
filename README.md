# GreenRoom97 Monorepo

**Owner:** Larry B. Hawkins Jr. (Hawk)  
**Focus:** AI-powered content + automations + client delivery

## Structure
- \pps/\ — websites/landing pages
- \utomations/\ — PowerShell, n8n, scripts
- \content/\ — captions, reels scripts, headers, calendar.json
- \snapshots/\ — HighLevel/ASSIST (flows, emails, sms)
- \docs/\ — setup/deploy/import guides
- \.github/\ — workflows, PR/issue templates, labels

## Using @claude
Create an Issue and add a comment like:

\\\
@claude
Goal: add hello.py that prints "Hello, GreenRoom97!"
Acceptance:
- file at repo root
- update README "How to run"
- open PR titled "feat: hello world"
\\\

Claude will branch → commit → open a PR → comment back.

## Requirements
- Actions enabled with "Read and write" workflow permissions
- Secret: \ANTHROPIC_API_KEY\ (Settings → Secrets → Actions)

