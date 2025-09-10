# Quick Start Guide

This guide will help you get started with Competency-Driven Assessment using Assessment Kit.

## The 4-Step Process

### 1. Install Assessment Kit

Initialize your project depending on the AI agent you're using:

```bash
uvx --from git+https://github.com/github/spec-kit.git specify init <PROJECT_NAME>
```

### 2. Create Learning Objectives

Use the `/assess` command to describe what competencies you want to evaluate. Focus on the **what** students should demonstrate and **why** it matters.

```bash
/assess Create an assessment for 9th grade students demonstrating understanding of ecosystem relationships through a biodiversity project. Students should show they can identify interdependent relationships, analyze human impact on ecosystems, and propose evidence-based conservation solutions for their local environment.
```

### 3. Create Assessment Framework

Use the `/validate` command to specify assessment methods and evaluation criteria.

```bash
/validate Use project-based assessment with portfolio documentation, peer evaluation, self-reflection journals, and presentation to community stakeholders. Include rubrics for scientific reasoning, evidence analysis, and communication skills.
```

### 4. Break Down and Implement

Use `/execute` to create actionable assessment activities, then ask your agent to develop the complete evaluation system.

## Detailed Example: Creating Science Competency Assessment

Here's a complete example of creating a comprehensive science assessment:

### Step 1: Define Learning Objectives with `/assess`

```text
Create a comprehensive assessment for 10th grade biology students demonstrating mastery of cellular respiration and photosynthesis. Students should show they can explain the relationship between these processes, analyze data from experiments measuring gas exchange, create visual models showing energy flow, and apply this knowledge to solve real-world problems about plant growth and human metabolism. The assessment should reveal student understanding of molecular processes, energy transformation, and systems thinking while allowing multiple ways to demonstrate competency.
```

### Step 2: Refine the Learning Objectives

After the initial objectives are created, clarify any missing requirements:

```text
Include accommodations for English language learners and students with different learning preferences. 
Ensure the assessment can capture both conceptual understanding and procedural skills. Add opportunities 
for collaborative work and individual reflection.
```

Also validate the assessment checklist:

```text
Read the review and acceptance checklist, and check off each item if the assessment objectives meet the criteria. Leave it empty if it does not.
```

### Step 3: Generate Assessment Framework with `/validate`

Be specific about your assessment methods and evaluation criteria:

```text
Use portfolio-based assessment with laboratory investigation reports, concept mapping activities, 
peer teaching sessions, and self-reflection essays. Include rubrics for scientific reasoning, 
data analysis skills, and conceptual connections. Provide choice in final demonstration format: 
infographic, video explanation, or research proposal.
```

### Step 4: Validate and Execute

Have your AI agent audit the assessment framework:

```text
Review the assessment framework and activities to ensure they align with learning objectives 
and provide multiple pathways for students to demonstrate competency. Check that bias prevention 
measures are included and that the assessment reveals student strengths.
```

Finally, implement the assessment system:

```text
execute assessments/001-cellular-processes/framework.md
```

## Key Principles

- **Be explicit** about what competencies students should demonstrate and why
- **Don't focus on assessment tools** during objective-setting phase  
- **Iterate and refine** your learning objectives before creating frameworks
- **Validate** the framework before developing activities
- **Let the AI agent handle** the assessment implementation details

## Next Steps

- Read the complete methodology for in-depth guidance
- Check out more examples in the repository
- Explore the source code on GitHub
