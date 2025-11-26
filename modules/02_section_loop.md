> Change Log (2025-11-26):
> – Updated specifity of behavior based on length of summary

## Module 2: Section Loop

Input: Section data from Intake + summary_level variable.

Process: Check if section is missing or empty, then record warning and skip summary if so.

If present:
If summary_level = "short"
then generate a 1–2 sentence summary focusing on the single main idea.

If summary_level = "detailed"
then generate a short paragraph focusing on the main idea plus a bullet list of 3–5 key points.

Output: Section summaries (mode-dependent) + warnings stored in shared structure.
