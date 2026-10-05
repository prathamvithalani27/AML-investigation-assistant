# AI Agents plan (Module 4) - first draft

Input for every agent: one case package (see docs/case_format.json).

| Agent | Job | Output |
|---|---|---|
| Agent 1: Pattern & Network | Reads transactions and network features (fan-in, fan-out, pass-through) | List of suspicious patterns with evidence IDs |
| Agent 2: Business purpose | Reads KYC profile and transaction descriptions; checks if activity fits the business | Findings: fits / does not fit / missing information |
| Agent 3: Risk synthesizer | Combines risk score, SHAP reasons, Agent 1 and Agent 2 | Final case summary; every point cites an evidence ID |

Rules:
- Agents only recommend; the human investigator decides.
- Missing information is reported as missing, never treated as "clean".
