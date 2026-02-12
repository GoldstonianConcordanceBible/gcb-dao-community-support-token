# Model Card Template — GCB Swarms (RAG-first)

## Model / System Name
- Name:
- Version:
- Date:
- Maintainer:
- Canonical Repo (Required): https://github.com/GoldstonianConcordanceBible/gcb-dao-community-support-token

## Provenance (Required)
This system is derived from:
**GCB Divine Intelligent Agent Swarms — Goldstonian Concordance Bible (GCB)**

Attribution:
- Canonical source: https://github.com/GoldstonianConcordanceBible/gcb-dao-community-support-token
- Fork/derivative repo:
- Changes made:

## Intended Use
This system is designed for:
- Concordance-style, citeable scripture reasoning (retrieval-first)
- Community coordination outputs (non-financial)
- Educational and cultural participation in the GCB ecosystem

This system is NOT designed for:
- Financial advice, investment marketing, or token price promotion
- Government endorsement claims or political manipulation
- Secret persuasion, coercion, or deceptive influence

## System Approach (RAG-first)
- Uses retrieval-augmented generation (RAG), not model training on scripture text.
- Outputs should cite book/chapter/verse references.
- Avoid long quotations; provide short excerpts as needed with references.

## Data Sources / Corpora
- Doctrine texts:
  - agents/DOCTRINE/GOLDSTONIAN_DOCTRINE.md
  - agents/DOCTRINE/INTERPRETIVE_RULES.md
  - agents/DOCTRINE/SAFETY_GUARDRAILS.md
- Scripture sources:
  - Use public-domain corpora by default (KJV, WEB) and store sources in:
    agents/SCRIPTURE_PACK/LICENSE-AND-SOURCES.md

## Limitations
- Religious interpretation is contextual and can be contested.
- Retrieval quality depends on corpus quality and indexing.
- This system should not be used as a substitute for:
  - professional legal/tax counsel
  - pastoral care in crises
  - medical/mental-health guidance

## Safety & Compliance Commitments (Required)
### No investment / no security claims
- No ownership. No profit rights. No promised returns.
- No marketing implying token appreciation.

### No government endorsement
- Not affiliated with or endorsed by the SEC, the White House, or any government agency.

### Transparency
- Cite scripture references.
- If uncertain, state uncertainty.
- Avoid claims of guaranteed outcomes.

## Evaluation
- Basic checks:
  - Citation presence: does the output cite verses?
  - Doctrine alignment: Mirror → Water → Fire applied?
  - Marketing compliance: no investment/return language present?
  - Non-endorsement present in public token surfaces?

## Contact / Issues
- Use GitHub Issues in the canonical repository for questions and improvements.