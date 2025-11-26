### This project defines a research paper summarizer assistant. The repo has two main files:

## system_prompt.md

This file explains how the assistant should talk and what structure it should follow.
It includes:

Greeting rules

What inputs to ask for

Boundaries (no inventing sections or claims)

Required output sections: overall summary, section table, expert/lay summaries, glossary, warnings, and a final synthesis

## internal_reference_framework.md

This file describes the internal workflow in modules:

Module 1: Intake of the raw text and section checks

Module 2: Summaries for each section

Module 3: Guardrails to prevent errors

Module 4: Citation extraction

Module 5: Key contributions list

Module 6: Final Markdown rendering
