# Activities: [ASSESSMENT NAME]

**Input**: Assessment documents from `/assessments/[###-assessment-name]/`
**Prerequisites**: framework.md (required), research.md, competency-model.md, rubrics/

## Execution Flow (main)
```
1. Load framework.md from assessment directory
   → If not found: ERROR "No assessment framework found"
   → Extract: assessment methods, evaluation criteria, structure
2. Load optional assessment documents:
   → competency-model.md: Extract competencies → demonstration activities
   → rubrics/: Each file → evaluation activity
   → research.md: Extract pedagogical decisions → setup activities
3. Generate activities by category:
   → Setup: assessment preparation, materials, instructions
   → Diagnostic: pre-assessment, baseline measurement
   → Core: demonstration tasks, portfolio pieces, performance activities
   → Reflection: self-assessment, peer evaluation, metacognitive activities
   → Evaluation: rubric application, feedback generation, progress tracking
4. Apply activity rules:
   → Different competencies = mark [P] for parallel
   → Same skill area = sequential (no [P])
   → Diagnostic before demonstration (Assessment-First)
5. Number activities sequentially (A001, A002...)
6. Generate dependency graph
7. Create parallel execution examples
8. Validate activity completeness:
   → All competencies have demonstration activities?
   → All rubrics have evaluation activities?
   → All learning objectives covered?
9. Return: SUCCESS (activities ready for implementation)
```

## Format: `[ID] [P?] Description`
- **[P]**: Can run in parallel (different competencies, no dependencies)
- Include exact competency alignments and materials needed

## Assessment Structure Conventions
- **Individual assessment**: Student portfolios, self-reflection journals
- **Collaborative assessment**: Group projects, peer evaluations
- **Performance-based**: Demonstrations, presentations, authentic tasks
- Structure shown below assumes individual focus - adjust based on framework.md

## Phase 3.1: Assessment Setup
- [ ] A001 Prepare assessment materials per framework plan
- [ ] A002 Set up assessment environment and resources
- [ ] A003 [P] Configure rubrics and evaluation criteria

## Phase 3.2: Diagnostic Assessment ⚠️ MUST COMPLETE BEFORE 3.3
**CRITICAL: These diagnostic activities MUST establish baseline before ANY demonstration activities**
- [ ] A004 [P] Pre-assessment survey on prior knowledge
- [ ] A005 [P] Diagnostic task for [competency 1] baseline
- [ ] A006 [P] Self-assessment of current confidence levels
- [ ] A007 [P] Learning preferences inventory

## Phase 3.3: Core Demonstration Activities (ONLY after baseline established)
- [ ] A008 [P] Portfolio piece #1: [competency demonstration]
- [ ] A009 [P] Performance task for [skill area]
- [ ] A010 [P] Collaborative project component
- [ ] A011 Individual presentation or demonstration
- [ ] A012 Problem-solving application task
- [ ] A013 Creative expression of understanding
- [ ] A014 Real-world application scenario

## Phase 3.4: Reflection & Peer Assessment
- [ ] A015 Self-reflection journal entry on learning process
- [ ] A016 Peer evaluation using structured protocol
- [ ] A017 Metacognitive analysis of strengths/growth areas
- [ ] A018 Goal-setting for continued learning

## Phase 3.5: Evaluation & Feedback
- [ ] A019 [P] Apply rubrics to portfolio pieces
- [ ] A020 Generate formative feedback for students
- [ ] A021 [P] Track competency progression over time
- [ ] A022 Document evidence of transfer/application
- [ ] A023 Complete comprehensive evaluation summary

## Dependencies
- Diagnostic (A004-A007) before demonstration (A008-A014)
- A008 supports A015, A019
- A016 requires A010 completion
- Demonstration before evaluation (A019-A023)

## Parallel Example
```
# Launch A004-A007 together:
Assessment: "Pre-assessment survey on prior knowledge"
Assessment: "Diagnostic task for [competency 1] baseline" 
Assessment: "Self-assessment of current confidence levels"
Assessment: "Learning preferences inventory"
```

## Notes
- [P] activities = different competencies, no dependencies
- Verify baseline established before demonstrations
- Document evidence after each activity
- Avoid: vague activities, assessment bias

## Activity Generation Rules
*Applied during main() execution*

1. **From Rubrics**:
   - Each rubric file → evaluation activity [P]
   - Each criterion → demonstration opportunity
   
2. **From Competency Model**:
   - Each competency → demonstration activity [P]
   - Learning progressions → scaffolded activities
   
3. **From Learning Objectives**:
   - Each objective → assessment task [P]
   - Evidence requirements → collection activities

4. **Ordering**:
   - Setup → Diagnostic → Demonstration → Reflection → Evaluation
   - Dependencies block parallel execution

## Validation Checklist
*GATE: Checked by main() before returning*

- [ ] All competencies have demonstration activities
- [ ] All rubrics have evaluation activities
- [ ] All diagnostic activities come before demonstration
- [ ] Parallel activities truly independent
- [ ] Each activity specifies exact competency alignment
- [ ] No activity assesses same competency area as another [P] activity