# GitHub Profile Audit

Audit date: 2026-06-08  
Scope: profile README, pinned project links, live deployment links, contribution links, and knowledge graph consistency.

## Pinned Repositories

Verified against the public GitHub profile and GitHub repository API.

| Repo | Status | Notes |
|---|---|---|
| [OneAlert](https://github.com/mangod12/OneAlert) | Live repo | Public, Python primary, 30 stars, 3 forks, homepage configured. |
| [redline-AI](https://github.com/mangod12/redline-AI) | Live repo | Public, Python primary, emergency IVR / first responder system. |
| [industryERP](https://github.com/mangod12/industryERP) | Live repo | Public, Python primary, MIT license, manufacturing ERP. |
| [TaskForge](https://github.com/mangod12/TaskForge) | Live repo | Public, Python primary, MIT license, multi-agent crisis logistics. |
| [skydash](https://github.com/mangod12/skydash) | Live repo | Public, JavaScript primary, MIT license, spatial intelligence dashboard. |

## Link Check Results

Checked with Playwright from the local workspace.

| Link | Result | README action |
|---|---:|---|
| https://github.com/mangod12/OneAlert | 200 | Keep. |
| https://github.com/mangod12/redline-AI | 200 | Keep. |
| https://github.com/mangod12/industryERP | 200 | Keep. |
| https://github.com/mangod12/TaskForge | 200 | Keep. |
| https://github.com/mangod12/skydash | 200 | Keep. |
| https://kbsteel-backend-498310931350.asia-south1.run.app | 200 | Keep as IndustryERP live link. |
| https://cybersec-saas-498310931350.us-central1.run.app | 200 | Keep as OneAlert live link. |
| https://cybersec-saas-ebqzvaqu6a-uc.a.run.app/app/ | 503 | Remove from profile surface. |
| https://taskforge-ebqzvaqu6a-el.a.run.app | 503 | Use repo link until deployment is stable. |
| https://redline-ai-359883234654.us-central1.run.app/demo | 503 | Use repo link until demo is stable. |
| https://cwistudio.in | 200 | Keep. |
| https://anshajwebsite.vercel.app | 200 | Keep. |
| https://www.linkedin.com/in/anshajk/ | 999/authwall | Keep as a normal LinkedIn public-profile link; automated checks hit LinkedIn authwall. |
| https://github.com/biomejs/biome/pull/10543 | 200 | Keep. |
| https://github.com/Significant-Gravitas/AutoGPT/pull/13151 | 200 | Keep. |
| https://github.com/beenuar/AiSOC/issues/159 | 200 | Keep. |
| https://github.com/beenuar/AiSOC/pull/223 | 200 | Keep. |

## README Changes Made

- Replaced mojibake/corrupted characters with clean ASCII.
- Updated OneAlert proof from stale local copy to current public metadata.
- Removed unreliable live demo links for TaskForge and Redline AI from the primary project table.
- Added a compact Mermaid knowledge graph to the profile README.
- Added a full pinned-project knowledge graph in `KNOWLEDGE_GRAPH.md`.
- Added this audit file so future profile changes can be checked against explicit evidence.

## Remaining Manual Follow-Up

- If TaskForge and Redline AI demos are restored to stable 2xx responses, add live links back to the README.
- If LinkedIn authwall behavior changes, re-check the public profile link manually in a normal browser.
