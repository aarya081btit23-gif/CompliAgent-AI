# CompliAgent AI

**CompliAgent AI** is an AI-powered compliance workflow prototype designed for securities market intermediaries. It converts regulatory documents such as SEBI circulars and master circulars into structured compliance actions, helping compliance teams track obligations, assign tasks, manage evidence, identify gaps, and generate audit-ready insights.

## Team Details

**Team Name:** Hack2Future

**Team Members:**
- Aarya Soni
- Shalini Jha
- Shivam Singh

## Problem Statement

Securities market intermediaries operate under a continuously evolving regulatory framework. SEBI regularly issues circulars, master circulars, notifications, and guidelines that create obligations for entities such as stock brokers, investment advisers, depository participants, AMCs, and other market participants.

Most regulatory information is published as unstructured text, while operational compliance requires structured workflows, task ownership, deadlines, evidence tracking, and audit trails. This creates a gap between regulatory issuance and actual compliance implementation.

CompliAgent AI addresses this gap by transforming regulatory text into actionable and auditable compliance workflows.

## Proposed Solution

The platform acts as a compliance co-pilot that helps users move from regulatory interpretation to operational execution.

It is designed to:

- Extract obligations from regulatory documents
- Convert obligations into department-wise compliance tasks
- Assign risk levels to obligations
- Track task completion status
- Manage evidence required for compliance
- Detect missing or incomplete evidence
- Support audit-readiness through structured reporting
- Provide a clear dashboard for compliance monitoring

## Key Features

- Compliance dashboard with summary metrics
- Regulatory obligation extraction interface
- Department-wise task board
- Evidence vault for compliance proof
- Risk and status tracking
- Clean multi-page navigation
- Audit-focused compliance workflow

## Target Users

- Stock brokers
- Investment advisers
- Compliance officers
- Legal teams
- Operations teams
- Risk teams
- Internal audit teams
- Securities market intermediaries

## Technology Stack

- HTML
- CSS
- JavaScript

## Future Scope

The current version is a frontend prototype. Future implementation can include:

- Backend using FastAPI or Node.js
- PostgreSQL or MongoDB database
- PDF parsing for SEBI circulars
- LLM-based obligation extraction
- RAG-based compliance assistant
- Vector database such as FAISS or ChromaDB
- User authentication and role-based access
- Evidence file upload and verification
- Automated audit report generation

## Project Flow

```text
SEBI Circular / Master Circular
        ↓
Regulatory Text Processing
        ↓
Obligation Extraction
        ↓
Applicability Mapping
        ↓
Department-wise Task Creation
        ↓
Risk Scoring
        ↓
Evidence Tracking
        ↓
Gap Detection
        ↓
Audit-ready Compliance Dashboard
```

## Project Structure

```text
compliagent_ai_connected/
│
├── index.html
│
├── compliance_dashboard/
│   ├── index.html
│   ├── code.html
│   └── screen.png
│
├── obligation_extractor/
│   ├── index.html
│   ├── code.html
│   └── screen.png
│
├── task_board/
│   ├── index.html
│   ├── code.html
│   └── screen.png
│
├── evidence_vault/
│   ├── index.html
│   ├── code.html
│   └── screen.png
│
└── compliagent_ai_system/
    └── DESIGN.md
```

## How to Run

1. Download or clone the project folder.
2. Open the folder in any code editor.
3. Open `index.html` in a browser.

You can also run it using a local server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Use Case Example

A compliance officer of a stock broking firm needs to review a new SEBI circular. The platform helps extract the key obligations, convert them into tasks, assign them to the correct department, track required evidence, and highlight incomplete compliance items.

Example output:

```text
Obligation: Maintain required records and submit compliance reports.
Assigned Department: Compliance Team
Evidence Required: Internal report, approval note, submission receipt
Risk Level: High
Status: Pending
```

## Business Potential

CompliAgent AI can be developed into a B2B SaaS product for regulated financial market participants.

Potential customers include:

- Stock broking firms
- Investment advisory firms
- AMCs
- Depository participants
- Registrar and transfer agents
- Compliance consulting firms

Possible revenue models include:

- Monthly subscription plans
- Enterprise licensing
- Custom compliance workflow setup
- API access for financial institutions
- White-label deployment for compliance firms

## Impact

CompliAgent AI reduces manual compliance effort, improves consistency in regulatory interpretation, detects gaps early, and supports audit readiness. It is especially useful for small and mid-sized intermediaries that may not have large compliance teams.

## Tagline

**From SEBI circular to audit-ready compliance action in minutes.**
