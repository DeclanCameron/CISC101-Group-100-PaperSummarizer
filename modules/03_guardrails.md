> Change Log (2025-11-26):
>  – Strengthened evidence and hallucination guardrails

## Module 3: Guardrails

Input: Section summaries + raw text + evidence_mode flag.

Process: Enforce non-invention rules: prevent creation of claims, citations, equations, or sections that do not appear in the source text.

While evidence_mode = "strict":
Only use claims, results, and equations explicitly found in the provided text.

#### Handle missing or very short sections:
If section is missing or empty
Then record warning: "Section skipped: no usable text"

If section is under 50 words
Then record warning: “Section very short: summary may be incomplete.”

If paper is long
Then chunk and recombine text

Output: Verified summaries + standardized warnings.
