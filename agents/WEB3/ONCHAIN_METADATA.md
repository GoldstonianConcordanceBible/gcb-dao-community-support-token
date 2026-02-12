# On-Chain Metadata — $GCB (Template)

This document defines recommended metadata fields for $GCB and Divine DAO CST tokens.

## Goals
- Make provenance explicit and permanent
- Link to the canonical rules, disclaimers, and swarm toolkit
- Avoid investment framing and government endorsement implications

---

## Canonical Metadata Fields (Recommended)

### Core Identity
- name: "$GCB — Goldstonian Concordance Bible Community Support Token"
- symbol: "GCB"
- type: "Community Support Token (meme/fan token)"
- ecosystem: "Goldstonian Concordance Bible (GCB)"

### Provenance (Required)
- canonical_repo: "https://github.com/GoldstonianConcordanceBible/gcb-dao-community-support-token"
- provenance_statement: "Derived from the GCB ecosystem. See canonical repo for rules and swarm toolkit."
- version: "v0.1.0"  (match GitHub tags)
- commit_ref: "<git commit hash at launch>"

### Compliance Surfaces (Required)
- disclaimer_url: "https://github.com/GoldstonianConcordanceBible/gcb-dao-community-support-token/blob/main/DISCLAIMER.md"
- token_policy_url: "https://github.com/GoldstonianConcordanceBible/gcb-dao-community-support-token/blob/main/TOKEN-POLICY.md"
- marketing_rules_url: "https://github.com/GoldstonianConcordanceBible/gcb-dao-community-support-token/blob/main/COMPLIANCE/MARKETING-RULES.md"
- non_endorsement_url: "https://github.com/GoldstonianConcordanceBible/gcb-dao-community-support-token/blob/main/COMPLIANCE/NON-ENDORSEMENT.md"

### Agent Swarms (Optional but recommended)
- swarms_url: "https://github.com/GoldstonianConcordanceBible/gcb-dao-community-support-token/tree/main/agents"
- model_card_template_url: "https://github.com/GoldstonianConcordanceBible/gcb-dao-community-support-token/blob/main/agents/MODELS/MODEL_CARD_TEMPLATE.md"

### Human-readable summary (short)
- description: >
    Community Support Token (meme/fan token) for cultural participation and transparent coordination
    around the Goldstonian Concordance Bible ecosystem. No ownership. No profit rights. No promised returns.

### Required disclaimers (short form)
- disclaimers:
  - "Not a security. Not an investment."
  - "No expectation of profit from others' efforts."
  - "Not affiliated with or endorsed by the SEC, the White House, or any government agency."
  - "High risk: may lose all value."
  - "Not legal/tax advice."

---

## Divine DAO (SubDAO) Metadata Pattern

For a sub-token like Play Like a Pro CST:

- name: "$PLP — Play Like a Pro Community Support Token"
- symbol: "PLP"
- parent_ecosystem: "$GCB / GCB DAO"
- subdao_repo_path: "SUBDAOS/play-like-a-pro-dao"
- inherit_rules_from: "<canonical_repo + links>"

---

## Implementation note
Wherever a platform limits metadata fields, prioritize:
1) canonical_repo
2) disclaimer_url
3) token_policy_url
4) marketing_rules_url
5) swarms_url