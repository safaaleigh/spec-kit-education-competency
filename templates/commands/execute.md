---
name: execute
description: "Break down the framework into executable assessment activities. This is the third step in the Competency-Driven Assessment lifecycle."
---

Break down the framework into executable assessment activities.

This is the third step in the Competency-Driven Assessment lifecycle.

Given the context provided as an argument, do this:

1. Run `scripts/check-activity-prerequisites.sh --json` from repo root and parse ASSESSMENT_DIR and AVAILABLE_DOCS list. All paths must be absolute.
2. Load and analyze available assessment documents:
   - Always read framework.md for assessment methods and criteria
   - IF EXISTS: Read competency-model.md for learning objectives
   - IF EXISTS: Read rubrics/ for evaluation standards
   - IF EXISTS: Read research.md for pedagogical decisions
   - IF EXISTS: Read activities.md for assessment scenarios

   Note: Not all assessments have all documents. For example:
   - Simple skill assessments might not have rubrics/
   - Portfolio assessments might not need competency-model.md
   - Generate activities based on what's available

3. Generate activities following the template:
   - Use `/templates/activities-template.md` as the base
   - Replace example activities with actual activities based on:
     * **Setup activities**: Assessment preparation, materials, instructions
     * **Diagnostic activities [P]**: One per competency, one per learning objective
     * **Core activities**: One per skill demonstration, performance task, portfolio piece
     * **Reflection activities**: Self-assessment, peer evaluation, metacognitive tasks
     * **Evaluation activities [P]**: Rubric application, feedback generation, progress tracking

4. Activity generation rules:
   - Each rubric file → evaluation activity marked [P]
   - Each competency in model → demonstration activity marked [P]
   - Each learning objective → assessment task (not parallel if shared criteria)
   - Each evidence type → collection activity marked [P]
   - Different competencies = can be parallel [P]
   - Same skill area = sequential (no [P])

5. Order activities by dependencies:
   - Setup before everything
   - Diagnostic before demonstration (Assessment-First)
   - Skills before application
   - Individual before collaborative
   - Core before reflection
   - Everything before evaluation

6. Include parallel execution examples:
   - Group [P] activities that can run together
   - Show actual assessment agent commands

7. Create ASSESSMENT_DIR/activities.md with:
   - Correct assessment name from framework
   - Numbered activities (A001, A002, etc.)
   - Clear competency alignments for each activity
   - Dependency notes
   - Parallel execution guidance

Context for activity generation: {ARGS}

The activities.md should be immediately executable - each activity must be specific enough that an educator can implement it without additional context.
