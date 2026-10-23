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
- **Stage / size:** early-stage, small team, "well-funded, high-traction," high customer demand.
  TODO: funding amount, headcount
- **Leadership:** CEO; co-founder/head of GTM. TODO: names
- **Product (sales framing):** AI agents plus industrial-grade smart hardware. Outcomes: better
  batch performance, fewer deviations, stronger compliance, higher yields. Pitch line: most AI
  startups sell to tech companies; Procense serves front-line operators still working on paper.
- **Target customers (ICP):** mid-market and enterprise process manufacturers across personal
  care, specialty chemicals, nutraceuticals, food, and pharma, nationwide.
- **GTM tools:** HubSpot (CRM), Amplemarket and Clay (prospecting, enrichment, sequencing),
  LinkedIn Sales Navigator, Make/Zapier, Claude/ChatGPT.
- **Location:** San Francisco Bay Area. Engineering and AE in office 3 days/week; BDR 5 days/week
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

### Founding Account Executive
- Ashby job ID: TODO
- Location: SF Bay Area, in office 3+ days/week. Travel about 25% (on-site with customers monthly)
- Reports to: CEO. Builds the playbook with the CEO and the co-founder/head of GTM
- Comp: OTE $240K to $300K, uncapped commission with accelerators, early-stage equity, full benefits
- Scope: full cycle on net-new logos, nationwide. Deals mostly $75K to $150K ARR, some $200K+.
  Buying committee of Ops, Quality, Plant Leadership, IT, Finance. Technical discovery,
  tailored demos, plant visits, pilots/POCs, layered pricing, procurement. Sells to plant
  leaders, VPs, C-level. Forecasts in HubSpot. Helps hire and ramp the sales team after them.
- **Must-haves:**
  - 4+ years full-cycle, quota-carrying closing role in B2B SaaS, IoT, or enterprise software
  - Consistent quota over-achievement on complex $75K+ ARR deals, some above $150K ARR
  - Track record winning net-new logos (not only renewals or expansions)
  - Multi-stakeholder buying committees and owning C-level relationships
  - Strategic outbound, builds own pipeline
  - Negotiation: multi-year contracts, layered pricing, procurement
  - Thrives in fast-paced, ambiguous environments
  - Hands-on daily AI use (Claude, ChatGPT, Clay, or similar)
  - Willing to travel monthly (about 25%)
  - Bay Area based, in office 3+ days/week
- **Nice-to-haves:**
  - Sold into legacy or regulated industries: manufacturing, industrials, F&B, pharma, chemicals
  - Sold industrial IoT, MES, QMS, ERP, or other operations software
  - Early sales hire at a startup who helped build the playbook
  - MEDDPICC, Command of the Message, or similar methodology
- **Disqualifiers (from the JD's "may not be the right job if"):**
  - Needs a fully built playbook
  - Inbound only, or no meaningful self-sourced pipeline
  - Has not sold to a buying committee
  - Won't travel monthly
  - Wants fully remote, or not in the Bay Area
  - Also screen out: mostly renewals/expansion/account management, SMB or transactional deal sizes
- **Target companies / backgrounds:** TODO
- **Selling points:** first AE at a well-funded, high-traction startup, defines how the company
  sells, works directly with the CEO, path to sales leadership, huge underserved market, real
  and painful problem, big uncapped OTE.

### Business Development Representative
- Ashby job ID: TODO
- Location: SF Bay Area, in office **5 days/week** (no hybrid or remote)
- Reports to: TODO (works directly with the CEO)
- Comp: OTE $80K to $100K+ (base + commission), accelerated commissions above target,
  early-stage equity, full benefits
- Scope: volume-first outbound. 80+ calls/day plus email and LinkedIn. Targets ops, quality,
  and manufacturing leaders, plant managers, supply chain execs in process manufacturing
  (chemicals, personal care). Builds account lists in Amplemarket and Sales Navigator, builds
  AI workflows for research/enrichment/follow-up, logs everything in HubSpot. Measured on
  qualified meetings set for the CEO and sales team.
- Career path: top performers can promote to closing AE within one year
- **Must-haves:**
  - Genuine excitement about a career in enterprise tech sales
  - Previous cold calling experience, comfortable in a high-volume, quota-carrying environment
  - Resilience and growth mindset
  - Strong phone and written communication
  - Hands-on daily AI use (Claude, ChatGPT, Clay, or similar), not just familiarity
  - Comfortable with ambiguity and building the playbook as they go
  - Bay Area based, in office 5 days/week
- **Nice-to-haves:**
  - 1 to 3 years BDR/SDR/ADR experience in B2B SaaS or enterprise software
  - Sold into manufacturing, industrials, F&B, pharma, or supply chain
  - Familiar with ERP, MES, QMS, or IoT platforms
  - Prior startup experience
- **Disqualifiers (from the JD's "may not be the right job if"):**
  - Not OK with rejection, or no real cold calling reps
  - Needs rigid scripts or a built playbook
  - Treats AI as a nice-to-have
  - Wants remote or hybrid, or not in the Bay Area
  - Not a team player
- **Target companies / backgrounds:** TODO
- **Selling points:** one of the first GTM hires, clear path to AE in a year, works directly with
  the CEO, visible impact, accelerated commissions, early equity.

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
