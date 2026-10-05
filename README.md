# AML Investigation Assistant using LLM Agents

IPD project (S.Y. B.Tech IT, DJSCE). Team: Pratham Vithalani, Sanchit Sawant.

An assistant that prepares the investigation of a flagged bank customer:
ML risk score (XGBoost + SHAP) + 3 AI agents + a case report with evidence.
The final decision always stays with the human investigator.

## Dataset
AMLBench (public synthetic banking data, CC-BY-4.0). We start with one bank (Yellow Bank).
The dataset is NOT stored in this repo (about 9 GB); it is downloaded in Colab.

## Modules (Jira epics)
| Module | Owner |
|---|---|
| Module 1: Data Setup | Pratham |
| Module 2: Features & Alerts | Pratham |
| Module 3: Risk Model | Pratham |
| Module 4: AI Agents | Sanchit |
| Module 5: Evaluation & UI | Sanchit |

## Folder structure
- `notebooks/` Colab notebooks
- `docs/` formats, rules and notes

## Working rules
Every branch, commit and pull request starts with the Jira card ID (e.g. `AML-5`).
The other member reviews every pull request before it is merged.
