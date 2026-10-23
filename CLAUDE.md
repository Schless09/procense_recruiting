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
- **What Procense does:** AI-powered software plus industrial-grade IoT for process
  manufacturers (personal care, chemicals, food, pharma). Replaces paper-based, legacy
  systems for production and quality operations: in-process data collection, batch
  records, quality, compliance. Customer example: Dr. Squatch (case study on site).
- **Users:** operators, quality leads, and plant managers on the plant floor.
- **Positioning:** "the operating layer for real-world manufacturing" and "the next
  leader in industrial automation, starting with process manufacturers."
- **Stage / size:** early-stage, small team, high customer demand. TODO: funding, headcount
- **Location:** San Francisco, CA (hybrid, 3 days/week, near public transit)
- **Stack:** React, TypeScript, Postgres, Terraform, AWS managed services. Integrates
  with ERPs, QMS systems, and industrial IoT devices.
- **Regulated environment:** builds for 21 CFR Part 11 and GMP.
- **Hiring manager(s) and who I report to:** TODO
- **Website / careers:** https://www.procense.ai/careers

### Culture (from the careers page, use in pitches)
- **Plant floor first:** features start from problems watched on the floor, not a whiteboard.
- **Real ownership:** everyone owns whole problems end to end, talks to customers, ships
  to production the same week.
- **Regulated by default:** rigor and trustworthiness over flash.
- **In the field:** site visits, real batch records, feedback from the floor within days.

## Open roles

### Sr. Full Stack Software Engineer
- Ashby job ID: TODO
- Location: Hybrid, 3 days/week in San Francisco
- Comp range: TODO
- Scope: full stack. Shop-floor operator interfaces, AI-integrated tools for admins and
  engineers, backend services, and infrastructure. Integrations with ERPs, QMS, and IoT.
  Guides architecture and mentors other engineers.
- **Must-haves:**
  - 5 to 7 years of full-stack development
  - Strong JavaScript / TypeScript
  - Modern frontend framework (React, Vue, or Angular)
  - Backend services in Node.js, Python, Go, or similar
  - Relational databases
  - Some cloud exposure (AWS, GCP, or Azure)
  - Strong problem solving and clear communication
  - Experience or demonstrated interest in AI-native development (LLMs, workflow automation)
- **Ideal:**
  - Shipped AI features in production (LLM products, agentic workflows, customer-facing AI)
  - Uses AI-augmented dev workflows (Claude Code, Cursor, etc.) to move faster
- **Nice-to-haves:**
  - IoT or hardware-connected software
  - Docker, Kubernetes, CI/CD
  - Regulated environments, especially GMP or 21 CFR Part 11
  - Startup experience or a real pull toward early stage
- **Disqualifiers:** TODO (e.g. no SF hybrid, maintenance-only background?)
- **Target companies / backgrounds:** TODO
- **Selling points:** real-world stakes (pharma, food, chemicals), build not maintain,
  own problem spaces end to end, AI meets industrial automation, close to customers.

### Business Development Representative
- Ashby job ID: TODO
- Location: TODO
- Comp range (base / OTE): TODO
- Must-haves: TODO (job description not captured yet)
- Nice-to-haves: TODO
- Disqualifiers: TODO
- Target companies / backgrounds: TODO

### Founding Account Executive
- Ashby job ID: TODO
- Location: TODO
- Comp range (base / OTE / equity): TODO
- Must-haves: TODO (job description not captured yet)
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
- Pitch: why someone should join Procense: see Culture and each role's selling points above

## Tools
- **Ashby**: API docs https://developers.ashbyhq.com
- **Aimfox**: LinkedIn outreach
- **Notion**: shared integration, Procense pages only

## Repo layout
- `scripts/`: automation scripts (Ashby, Aimfox, Notion)
- `data/`: local candidate files and exports (gitignored)
