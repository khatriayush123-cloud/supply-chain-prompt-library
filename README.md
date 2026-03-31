📚 Prompt Library — Supply Chain
Assessment 1 | Generative AI for Business
Student: Ayush Sanjivkumar Khatri | Business Field: Supply Chain Operations
Model tested on: Gemini Pro
Last updated: 31-03-2026

What This Library Does
This prompt library supports workflow automation in [your chosen business field]. It contains 10 documented, tested, and iterated prompts organised by the business function they support.

Each prompt entry follows the same structure: - The exact prompt text (with placeholders) - The workflow task it supports - The problem it solves - Its automation potential - Known risks and mitigations - Version history and test results

📂 Folder Structure
prompt-library/
│
├── README.md                        ← You are here (library index)
│
├── 01-onboarding/
│   ├── README.md                    ← Section overview
│   ├── P01-welcome-email.md
│   ├── P02-induction-schedule.md
│   └── P03-role-briefing.md
│
├── 02-operations/
│   ├── README.md
│   ├── P04-incident-report.md
│   └── P05-shift-handover.md
│
├── 03-customer-service/
│   ├── README.md
│   ├── P06-complaint-triage.md
│   ├── P07-response-draft.md
│   └── P08-escalation-summary.md
│
└── 04-your-prompts/
    ├── README.md
    ├── P09-[your-prompt].md
    └── P10-[your-prompt].md
💡 Rename folders and files to match your chosen business field.
The structure above is an example for HR/Retail operations.

📊 Library Summary Table
ID	Prompt Name	Workflow	Automation Level	Risk Level	Status
P01	Welcome email	Onboarding	High	Low	✅ Tested
P02	Induction schedule	Onboarding	Medium	Low	✅ Tested
P03	Role briefing	Onboarding	High	Medium	✅ Tested
P04	Incident report	Operations	Medium	High	✅ Tested
P05	Shift handover	Operations	High	Low	✅ Tested
P06	Complaint triage	Customer service	Very High	Medium	✅ Tested
P07	Response draft	Customer service	High	Medium	✅ Tested
P08	Escalation summary	Customer service	Medium	High	✅ Tested
P09	[Your prompt]	[Workflow]	[Level]	[Level]	🔄 In progress
P10	[Your prompt]	[Workflow]	[Level]	[Level]	🔄 In progress
Automation levels: Very High / High / Medium / Low
Risk levels: High (always needs human review) / Medium (spot-check recommended) / Low (can automate with audit)

🔗 Prompt Chaining Map
Some prompts in this library are designed to work in sequence. The chains below show how outputs from one prompt feed the next.

ONBOARDING CHAIN
P01 (Welcome email) → P02 (Induction schedule) → P03 (Role briefing)

INCIDENT MANAGEMENT CHAIN  
P04 (Incident report draft) → P08 (Escalation summary)

CUSTOMER SERVICE CHAIN
P06 (Complaint triage) → P07 (Response draft) → P08 (Escalation summary)
⚙️ Prompting Strategies Used
Strategy	Prompts	Why chosen
RACE framework (Role–Action–Context–Evaluation)	P01, P03, P07	Consistent structure; comparable outputs for A/B testing
Grounding constraint ("using only...")	P04, P08	Prevents hallucination in factual/legal contexts
JSON output format	P06	Machine-readable for CRM/API integration
Word/format limits	All	Ensures output is production-ready without heavy editing
Self-critique step	P04	Model reviews its own output for unsupported inferences
📝 Iteration Evidence
All prompt versions are saved in this repository. See individual prompt files for version histories.
Commit history = version log — each commit message describes what changed and why.

Prompt	Versions	Key improvement
P01	v1.0 → v1.2	Added RACE role + word limit; edit time 14 min → 2 min
P04	v1.0 → v1.1	Grounding constraint added after v1.0 hallucinated causes
P06	v1.0 → v1.2	Constrained category list added; JSON output enforced
📖 References
Anthropic (2025). Prompt Engineering Overview. docs.claude.ai
Kartaca (2026). Standardizing Enterprise Intelligence with a Corporate Prompt Library.
MIT Sloan (2025). Prompt Engineering is So 2024 — Try These Prompt Templates Instead.
Microsoft (2025). Get Started with Prompt Library — Copilot Studio.
VE3 Global (2025). 10 Key Elements of a Prompt Library for Enterprise Tasks.
