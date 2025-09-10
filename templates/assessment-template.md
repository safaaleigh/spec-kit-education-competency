# Learning Objectives: [ASSESSMENT NAME]

**Assessment Branch**: `[###-assessment-name]`  
**Created**: [DATE]  
**Status**: Draft  
**Input**: Learning objectives description: "$ARGUMENTS"

## Execution Flow (main)
```
1. Parse learning objectives from Input
   → If empty: ERROR "No learning objectives provided"
2. Extract key competencies from description
   → Identify: skills, knowledge, performance criteria, contexts
3. For each unclear aspect:
   → Mark with [NEEDS CLARIFICATION: specific question]
4. Fill Learning Evidence & Assessment section
   → If no clear evidence pathway: ERROR "Cannot determine how competency will be demonstrated"
5. Generate Competency Requirements
   → Each requirement must be observable and measurable
   → Mark ambiguous requirements
6. Identify Key Skills (if procedural learning involved)
7. Run Review Checklist
   → If any [NEEDS CLARIFICATION]: WARN "Assessment has uncertainties"
   → If assessment method details found: ERROR "Remove specific tools/methods"
8. Return: SUCCESS (assessment ready for framework design)
```

---

## ⚡ Quick Guidelines
- ✅ Focus on WHAT students should demonstrate and WHY it matters
- ❌ Avoid HOW to assess (no specific tools, rubrics, or implementation methods)
- 👥 Written for educational stakeholders, not assessment technicians

### Section Requirements
- **Mandatory sections**: Must be completed for every assessment
- **Optional sections**: Include only when relevant to the learning context
- When a section doesn't apply, remove it entirely (don't leave as "N/A")

### For AI Generation
When creating learning objectives from an educator prompt:
1. **Mark all ambiguities**: Use [NEEDS CLARIFICATION: specific question] for any assumption you'd need to make
2. **Don't guess**: If the prompt doesn't specify something (e.g., "writing skills" without genre or context), mark it
3. **Think like an assessor**: Every vague objective should fail the "observable and measurable" checklist item
4. **Common underspecified areas**:
   - Student population and grade level
   - Prior knowledge assumptions
   - Performance criteria and standards
   - Context and application settings
   - Accommodation requirements
   - Transfer and generalization expectations

---

## Learning Evidence & Assessment *(mandatory)*

### Primary Learning Journey
[Describe the main pathway students will take to demonstrate competency in plain language]

### Evidence Collection Scenarios
1. **Given** [learning context], **When** [student demonstrates], **Then** [expected evidence]
2. **Given** [assessment context], **When** [student performs], **Then** [observable outcome]

### Edge Cases
- What happens when [student struggles with prerequisite skills]?
- How does assessment handle [different learning styles or needs]?

## Competency Requirements *(mandatory)*

### Learning Objectives
- **LO-001**: Students MUST demonstrate [specific competency, e.g., "ability to analyze cause-effect relationships"]
- **LO-002**: Students MUST show [specific skill, e.g., "effective peer collaboration"]  
- **LO-003**: Students MUST be able to [key performance, e.g., "transfer learning to new contexts"]
- **LO-004**: Students MUST exhibit [behavioral outcome, e.g., "metacognitive reflection on learning process"]
- **LO-005**: Students MUST display [content mastery, e.g., "understanding of core scientific principles"]

*Example of marking unclear objectives:*
- **LO-006**: Students MUST demonstrate writing proficiency at [NEEDS CLARIFICATION: grade level standard not specified - what genre, length, audience?]
- **LO-007**: Students MUST show mathematical reasoning in [NEEDS CLARIFICATION: context not specified - what type of problems?]

### Key Competencies *(include if assessment involves skill demonstration)*
- **[Competency 1]**: [What it involves, observable behaviors without specific assessment methods]
- **[Competency 2]**: [What it represents, relationships to other learning areas]

---

## Review & Acceptance Checklist
*GATE: Automated checks run during main() execution*

### Content Quality
- [ ] No assessment method details (specific tools, rubrics, platforms)
- [ ] Focused on student learning and competency demonstration
- [ ] Written for educational stakeholders  
- [ ] All mandatory sections completed

### Learning Objective Completeness
- [ ] No [NEEDS CLARIFICATION] markers remain
- [ ] Objectives are observable and measurable
- [ ] Success criteria are clearly defined
- [ ] Scope is appropriate for grade level/context
- [ ] Prerequisites and assumptions identified

---

## Execution Status
*Updated by main() during processing*

- [ ] Learning objectives parsed
- [ ] Key competencies extracted
- [ ] Ambiguities marked
- [ ] Evidence scenarios defined
- [ ] Requirements generated
- [ ] Competencies identified
- [ ] Review checklist passed

---
