---
name: assess
description: "Start a new assessment by creating learning objectives and assessment branch. This is the first step in the Competency-Driven Assessment lifecycle."
---

Start a new assessment by creating learning objectives and assessment branch.

This is the first step in the Competency-Driven Assessment lifecycle.

Given the learning objectives description provided as an argument, do this:

1. Run the script `scripts/create-new-assessment.sh --json "{ARGS}"` from repo root and parse its JSON output for BRANCH_NAME and ASSESSMENT_FILE. All file paths must be absolute.
2. Load `templates/assessment-template.md` to understand required sections.
3. Write the learning objectives to ASSESSMENT_FILE using the template structure, replacing placeholders with concrete details derived from the learning objectives description (arguments) while preserving section order and headings.
4. Report completion with branch name, assessment file path, and readiness for the next phase.

Note: The script creates and checks out the new branch and initializes the assessment file before writing.
