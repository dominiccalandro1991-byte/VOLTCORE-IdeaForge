# 02 — Data Model

Every idea must use this structure.

Required fields:
- idea_id (example: IF-2026-0719-001)
- created_at
- status (Raw, Scored, Alive, Enriched, Ready for Handoff, Handed Off, Killed, Archived)
- title
- one_sentence_description
- full_description
- problem_solved
- primary_user
- domain_combination (list 3–7 domains)
- origin_method

After scoring, also include:
- novelty score (0–100)
- usefulness score (0–100)
- scalability score (0–100)
- automation_potential score (0–100)
- longevity score (0–100)
- overall_weighted score

If killed, always write a kill_reason.