---
name: validate
description: "Create assessment framework for the learning objectives. This is the second step in the Competency-Driven Assessment lifecycle."
---

Create assessment framework for the learning objectives.

This is the second step in the Competency-Driven Assessment lifecycle.

Given the assessment methods provided as an argument, do this:

1. Run `scripts/setup-framework.sh --json` from the repo root and parse JSON for ASSESSMENT_SPEC, FRAMEWORK_PLAN, ASSESSMENTS_DIR, BRANCH. All future file paths must be absolute.
2. Read and analyze the learning objectives to understand:
   - The competency requirements and learning evidence
   - Assessment criteria and evaluation methods
   - Success criteria and demonstration standards
   - Any accommodation needs or constraints mentioned

3. Read the constitution at `/memory/constitution.md` to understand assessment principles.

4. Execute the assessment framework template:
   - Load `/templates/framework-template.md` (already copied to FRAMEWORK_PLAN path)
   - Set Input path to ASSESSMENT_SPEC
   - Run the Execution Flow (main) function steps 1-10
   - The template is self-contained and executable
   - Follow error handling and gate checks as specified
   - Let the template guide artifact generation in $ASSESSMENTS_DIR:
     * Phase 0 generates research.md
     * Phase 1 generates competency-model.md, rubrics/, activities.md
     * Phase 2 generates execution.md
   - Incorporate user-provided details from arguments into Assessment Context: {ARGS}
   - Update Progress Tracking as you complete each phase

5. Verify execution completed:
   - Check Progress Tracking shows all phases complete
   - Ensure all required artifacts were generated
   - Confirm no ERROR states in execution

6. Report results with branch name, file paths, and generated artifacts.

Use absolute paths with the repository root for all file operations to avoid path issues.
