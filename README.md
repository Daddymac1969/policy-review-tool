# TASIS Policy Review Tool

Upload a policy document → Select policy type → AI scans for errors and omissions → Export PDF report in TASIS style.

## Features

- **Upload** — PDF, DOCX, or TXT files
- **Preset prompts** — 10 policy types with built-in requirements (Safeguarding, Boarding, Behaviour, H&S, HR, Admissions, SEND, Curriculum, Complaints, Data Protection)
- **Custom requirements** — Add specific checks for each document
- **AI analysis** — Checks template compliance + content issues
- **PDF export** — Professional report in TASIS branding

## Setup

1. Create GitHub repo, upload files
2. Connect to Netlify
3. Get Anthropic API key from console.anthropic.com
4. Enter key in ⚙️ Settings when you first open the tool

## Deployment

Same as other TASIS tools:
- GitHub → Netlify → auto-deploy

## Policy Types

| Type | Key Requirements |
|------|------------------|
| Safeguarding | KCSIE 2025, Working Together, DSL details, RESPOND |
| Boarding | NMS 2022, welfare, supervision, missing boarder |
| Behaviour | Equality Act, sanctions, exclusions, bullying |
| Health & Safety | H&S Act, risk assessment, first aid, fire |
| HR | Safer recruitment, DBS, code of conduct, SCR |
| Admissions | Non-discrimination, SEND, EAL |
| SEND | Code of Practice, graduated approach, EHCP |
| Curriculum | ISS Part 1, PSHE/RSE, British values |
| Complaints | Stages, timeframes, panel, ISI |
| Data Protection | UK GDPR, DPA 2018, rights, breaches |

## Template Checks

Every policy is checked for:
- Safeguarding commitment statement
- Whole-school scope statement
- Current version statement
- Metadata table (7 fields)
- Signatory block
- Numbered sections
- Review date
- Responsible area
- Legislation currency
- RESPOND framework (where relevant)

## Contact

Darren Singh-MacPherson  
TASIS England
