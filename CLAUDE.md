# Procense Recruiting

I am the embedded recruiter for **Procense**. This repo holds my tooling for running
Procense's hiring: filling and updating their Ashby, sourcing, and outreach.

## Ground rules for Claude
- This repo is for **Procense only**. Never reference, reuse, or mix in candidates,
  roles, or details from any other client.
- API keys come from `.env` (see `.env.example`). Never print, log, or commit them.
- The Notion API key is shared with other clients. Only read or write the Procense
  pages/databases listed in `.env` (`NOTION_PROCENSE_*`). Do not touch any other page.
- Candidate data (resumes, exports, notes) goes in `data/`, which is gitignored.
  Never commit candidate personal information.
- Confirm with me before any action that writes to Ashby, sends outreach through
  Aimfox, or changes a candidate's stage.

## Company
- What Procense does: TODO
- Stage / size / location: TODO
- Hiring manager(s) and who I report to: TODO

## Open roles
<!-- One block per role. -->
### TODO: Role title
- Ashby job ID: TODO
- Location / remote policy: TODO
- Comp range: TODO
- Must-haves: TODO
- Nice-to-haves: TODO
- Disqualifiers: TODO
- Target companies / backgrounds: TODO

## Ashby setup
- Pipeline stages (in order): TODO
- Sources / tags I use: TODO
- Custom fields: TODO

## Outreach (Aimfox)
- Campaign(s): TODO
- Tone and voice: TODO
- Pitch: why someone should join Procense: TODO

## Tools
- **Ashby**: API docs https://developers.ashbyhq.com
- **Aimfox**: LinkedIn outreach
- **Notion**: shared integration, Procense pages only

## Repo layout
- `scripts/`: automation scripts (Ashby, Aimfox, Notion)
- `data/`: local candidate files and exports (gitignored)
