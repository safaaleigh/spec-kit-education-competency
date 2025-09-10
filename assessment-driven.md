# Competency-Driven Assessment (CDA)

## Adaptation from Spec-Driven Development

Competency-Driven Assessment (CDA) adapts the proven methodology of Spec-Driven Development for educational contexts. Just as SDD revolutionized software development by making specifications executable and the primary source of truth, CDA transforms educational assessment by making learning objectives executable and the foundation for comprehensive evaluation systems.

The same principles that enable AI to generate working code from precise specifications can be applied to generate authentic assessment frameworks from well-defined competencies. Where SDD uses `/specify`, `/plan`, and `/tasks` commands to create software systems, CDA uses `/assess`, `/validate`, and `/execute` commands to create evaluation systems that truly measure student learning and growth.

## The Assessment Inversion

For decades, standardized tests have been king. Learning objectives served testing—they were the scaffolding we built and then discarded once the "real work" of measuring began. We wrote standards to guide assessment, created rubrics to inform evaluation, drew learning progressions to visualize growth. But these were always subordinate to the test itself. Test scores were truth. Everything else was, at best, good intentions. Tests were the source of truth, as they moved forward, and learning objectives rarely kept pace. As the measure (test) and the evaluation are one, it's not easy to have parallel assessment methods without trying to build from the test.

Competency-Driven Assessment (CDA) inverts this power structure. Learning objectives don't serve tests—assessment serves learning objectives. The learning standards aren't a guide for evaluation; they're the source that generates comprehensive assessment systems. Assessment frameworks aren't documents that inform testing; they're precise definitions that produce authentic evaluation. This isn't an incremental improvement to how we assess learning. It's a fundamental rethinking of what drives educational evaluation.

The gap between learning objectives and assessment implementation has plagued educational evaluation since its inception. We've tried to bridge it with better rubrics, more detailed standards, stricter alignment processes. These approaches fail because they accept the gap as inevitable. They try to narrow it but never eliminate it. CDA eliminates the gap by making learning objectives and their concrete assessment frameworks executable. When learning objectives generate comprehensive evaluation systems, there is no gap—only transformation.

This transformation is now possible because AI can understand and implement complex learning objectives, and create detailed assessment frameworks. But raw AI generation without structure produces chaos. CDA provides that structure through learning objectives and subsequent assessment frameworks that are precise, complete, and unambiguous enough to generate working evaluation systems. The learning objectives become the primary artifact. Assessment activities become their expression in particular modalities and contexts.

In this new world, maintaining assessment means evolving learning objectives. The intent of the educational team is expressed in natural language ("**learning-driven evaluation**"), pedagogical principles, and educational guidelines. The **lingua franca** of assessment moves to a higher-level, and specific evaluation methods are the last-mile approach.

Debugging means fixing learning objectives and their assessment frameworks that generate inappropriate evaluation. Refining means restructuring for clarity and equity. The entire assessment workflow reorganizes around learning objectives as the central source of truth, with assessment frameworks and activities as the continuously regenerated output. Updating assessments with new competencies or creating parallel evaluation methods means revisiting the learning objectives and creating new assessment frameworks. This process is therefore a 0 -> 1, (1', ..), 2, 3, N.

The educational team focuses on their pedagogical creativity, experimentation, and critical thinking about authentic learning measurement.

## The CDA Workflow in Practice

The workflow begins with a learning goal—often vague and incomplete. Through iterative dialogue with AI, this goal becomes comprehensive learning objectives. The AI asks clarifying questions, identifies edge cases, and helps define precise competency criteria. What might take days of meetings and documentation in traditional assessment design happens in hours of focused objective work. This transforms the traditional assessment lifecycle—learning standards and evaluation design become continuous activities rather than discrete phases. This is supportive of a **team process**, where team-reviewed learning objectives are expressed and versioned, created in branches, and merged.

When an educator updates competency criteria, assessment frameworks automatically flag affected evaluation decisions. When a curriculum designer discovers a better approach, the learning objectives update to reflect new possibilities.

Throughout this objective-setting process, research agents gather critical context. They investigate pedagogical approaches, assessment validity, and equity implications. Institutional constraints are discovered and applied automatically—your school's standards alignment, accommodation requirements, and evaluation policies seamlessly integrate into every learning objective.

From the learning objectives, AI generates assessment frameworks that map competencies to evaluation decisions. Every assessment method has documented rationale. Every evaluation approach traces back to specific learning objectives. Throughout this process, consistency validation continuously improves quality. AI analyzes learning objectives for ambiguity, contradictions, and gaps—not as a one-time gate, but as an ongoing refinement.

Assessment activity generation begins as soon as learning objectives and their frameworks are stable enough, but they do not have to be "complete." Early generations might be exploratory—testing whether the learning objective makes sense in practice. Learning concepts become competency models. Student evidence becomes portfolio pieces. Demonstration scenarios become performance tasks. This merges evaluation and learning through objectives—assessment activities aren't designed after learning, they're part of the objectives that generate both instruction and evaluation.

The feedback loop extends beyond initial assessment. Student performance data and learning evidence don't just trigger grade adjustments—they update learning objectives for the next iteration. Learning gaps become new competency requirements. Bias indicators become constraints that affect all future assessments. This iterative dance between learning objectives, assessment implementation, and educational reality is where true understanding emerges and where the traditional assessment lifecycle transforms into continuous learning improvement.

## Why CDA Matters Now

Three trends make CDA not just possible but necessary:

First, AI capabilities have reached a threshold where natural language learning objectives can reliably generate comprehensive assessment systems. This isn't about replacing educators—it's about amplifying their effectiveness by automating the mechanical translation from learning objectives to evaluation frameworks. It can amplify pedagogical exploration and creativity, it can support "start-over" easily, it supports addition, subtraction and critical thinking about student learning.

Second, assessment complexity continues to grow exponentially. Modern education integrates diverse learning modalities, accommodation needs, and standards requirements. Keeping all these pieces aligned with original learning intent through manual processes becomes increasingly difficult. CDA provides systematic alignment through objective-driven generation. Assessment tools may evolve to provide AI-first support, not human-first support, or architect around reusable evaluation components.

Third, the pace of change accelerates. Requirements change far more rapidly today than ever before. Pivoting is no longer exceptional—it's expected. Modern product development demands rapid iteration based on user feedback, market conditions, and competitive pressures. Traditional development treats these changes as disruptions. Each pivot requires manually propagating changes through documentation, design, and code. The result is either slow, careful updates that limit velocity, or fast, reckless changes that accumulate technical debt.

SDD can support what-if/simulation experiments, "If we need to re-implement or change the application to promote a business need to sell more T-shirts, how would we implement and experiment for that?".

SDD transforms requirement changes from obstacles into normal workflow. When specifications drive implementation, pivots become systematic regenerations rather than manual rewrites. Change a core requirement in the PRD, and affected implementation plans update automatically. Modify a user story, and corresponding API endpoints regenerate. This isn't just about initial development—it's about maintaining engineering velocity through inevitable changes.

## Core Principles

**Specifications as the Lingua Franca**: The specification becomes the primary artifact. Code becomes its expression in a particular language and framework. Maintaining software means evolving specifications.

**Executable Specifications**: Specifications must be precise, complete, and unambiguous enough to generate working systems. This eliminates the gap between intent and implementation.

**Continuous Refinement**: Consistency validation happens continuously, not as a one-time gate. AI analyzes specifications for ambiguity, contradictions, and gaps as an ongoing process.

**Research-Driven Context**: Research agents gather critical context throughout the specification process, investigating technical options, performance implications, and organizational constraints.

**Bidirectional Feedback**: Production reality informs specification evolution. Metrics, incidents, and operational learnings become inputs for specification refinement.

**Branching for Exploration**: Generate multiple implementation approaches from the same specification to explore different optimization targets—performance, maintainability, user experience, cost.

## Implementation Approaches

Today, practicing SDD requires assembling existing tools and maintaining discipline throughout the process. The methodology can be practiced with:

- AI assistants for iterative specification development
- Research agents for gathering technical context
- Code generation tools for translating specifications to implementation
- Version control systems adapted for specification-first workflows
- Consistency checking through AI analysis of specification documents

The key is treating specifications as the source of truth, with code as the generated output that serves the specification rather than the other way around.

## Streamlining SDD with Claude Commands

The SDD methodology is significantly enhanced through two powerful Claude commands that automate the specification and planning workflow:

### The `new_feature` Command

This command transforms a simple feature description (the user-prompt) into a complete, structured specification with automatic repository management:

1. **Automatic Feature Numbering**: Scans existing specs to determine the next feature number (e.g., 001, 002, 003)
2. **Branch Creation**: Generates a semantic branch name from your description and creates it automatically
3. **Template-Based Generation**: Copies and customizes the feature specification template with your requirements
4. **Directory Structure**: Creates the proper `specs/[branch-name]/` structure for all related documents

### The `generate_plan` Command

Once a feature specification exists, this command creates a comprehensive implementation plan:

1. **Specification Analysis**: Reads and understands the feature requirements, user stories, and acceptance criteria
2. **Constitutional Compliance**: Ensures alignment with project constitution and architectural principles
3. **Technical Translation**: Converts business requirements into technical architecture and implementation details
4. **Detailed Documentation**: Generates supporting documents for data models, API contracts, and test scenarios
5. **Manual Testing Plans**: Creates step-by-step validation procedures for each user story

### Example: Building a Chat Feature

Here's how these commands transform the traditional development workflow:

**Traditional Approach:**
```
1. Write a PRD in a document (2-3 hours)
2. Create design documents (2-3 hours)
3. Set up project structure manually (30 minutes)
4. Write technical specifications (3-4 hours)
5. Create test plans (2 hours)
Total: ~12 hours of documentation work
```

**SDD with Commands Approach:**
```bash
# Step 1: Create the feature specification (5 minutes)
/new_feature Real-time chat system with message history and user presence

# This automatically:
# - Creates branch "003-chat-system"
# - Generates specs/003-chat-system/feature-spec.md
# - Populates it with structured requirements

# Step 2: Generate implementation plan (10 minutes)
/generate_plan WebSocket for real-time messaging, PostgreSQL for history, Redis for presence

# This automatically creates:
# - specs/003-chat-system/implementation-plan.md
# - specs/003-chat-system/implementation-details/
#   - 00-research.md (WebSocket library comparisons)
#   - 02-data-model.md (Message and User schemas)
#   - 03-api-contracts.md (WebSocket events, REST endpoints)
#   - 06-contract-tests.md (Message flow scenarios)
#   - 08-inter-library-tests.md (Database-WebSocket integration)
# - specs/003-chat-system/manual-testing.md
```

In 15 minutes, you have:
- A complete feature specification with user stories and acceptance criteria
- A detailed implementation plan with technology choices and rationale
- API contracts and data models ready for code generation
- Comprehensive test scenarios for both automated and manual testing
- All documents properly versioned in a feature branch

### The Power of Structured Automation

These commands don't just save time—they enforce consistency and completeness:

1. **No Forgotten Details**: Templates ensure every aspect is considered, from non-functional requirements to error handling
2. **Traceable Decisions**: Every technical choice links back to specific requirements
3. **Living Documentation**: Specifications stay in sync with code because they generate it
4. **Rapid Iteration**: Change requirements and regenerate plans in minutes, not days

The commands embody SDD principles by treating specifications as executable artifacts rather than static documents. They transform the specification process from a necessary evil into the driving force of development.

### Template-Driven Quality: How Structure Constrains LLMs for Better Outcomes

The true power of these commands lies not just in automation, but in how the templates guide LLM behavior toward higher-quality specifications. The templates act as sophisticated prompts that constrain the LLM's output in productive ways:

#### 1. **Preventing Premature Implementation Details**

The feature specification template explicitly instructs:
```
- ✅ Focus on WHAT users need and WHY
- ❌ Avoid HOW to implement (no tech stack, APIs, code structure)
```

This constraint forces the LLM to maintain proper abstraction levels. When an LLM might naturally jump to "implement using React with Redux," the template keeps it focused on "users need real-time updates of their data." This separation ensures specifications remain stable even as implementation technologies change.

#### 2. **Forcing Explicit Uncertainty Markers**

Both templates mandate the use of `[NEEDS CLARIFICATION]` markers:
```
When creating this spec from a user prompt:
1. **Mark all ambiguities**: Use [NEEDS CLARIFICATION: specific question] 
2. **Don't guess**: If the prompt doesn't specify something, mark it
```

This prevents the common LLM behavior of making plausible but potentially incorrect assumptions. Instead of guessing that a "login system" uses email/password authentication, the LLM must mark it as `[NEEDS CLARIFICATION: auth method not specified - email/password, SSO, OAuth?]`.

#### 3. **Structured Thinking Through Checklists**

The templates include comprehensive checklists that act as "unit tests" for the specification:
```
### Requirement Completeness
- [ ] No [NEEDS CLARIFICATION] markers remain
- [ ] Requirements are testable and unambiguous  
- [ ] Success criteria are measurable
```

These checklists force the LLM to self-review its output systematically, catching gaps that might otherwise slip through. It's like giving the LLM a quality assurance framework.

#### 4. **Constitutional Compliance Through Gates**

The implementation plan template enforces architectural principles through phase gates:
```
### Phase -1: Pre-Implementation Gates
#### Simplicity Gate (Article VII)
- [ ] Using ≤3 projects?
- [ ] No future-proofing?
#### Anti-Abstraction Gate (Article VIII)
- [ ] Using framework directly?
- [ ] Single model representation?
```

These gates prevent over-engineering by making the LLM explicitly justify any complexity. If a gate fails, the LLM must document why in the "Complexity Tracking" section, creating accountability for architectural decisions.

#### 5. **Hierarchical Detail Management**

The templates enforce proper information architecture:
```
**IMPORTANT**: This implementation plan should remain high-level and readable. 
Any code samples, detailed algorithms, or extensive technical specifications 
must be placed in the appropriate `implementation-details/` file
```

This prevents the common problem of specifications becoming unreadable code dumps. The LLM learns to maintain appropriate detail levels, extracting complexity to separate files while keeping the main document navigable.

#### 6. **Test-First Thinking**

The implementation template enforces test-first development:
```
### File Creation Order
1. Create `contracts/` with API specifications
2. Create test files in order: contract → integration → e2e → unit
3. Create source files to make tests pass
```

This ordering constraint ensures the LLM thinks about testability and contracts before implementation, leading to more robust and verifiable specifications.

#### 7. **Preventing Speculative Features**

Templates explicitly discourage speculation:
```
- [ ] No speculative or "might need" features
- [ ] All phases have clear prerequisites and deliverables
```

This stops the LLM from adding "nice to have" features that complicate implementation. Every feature must trace back to a concrete user story with clear acceptance criteria.

### The Compound Effect

These constraints work together to produce specifications that are:
- **Complete**: Checklists ensure nothing is forgotten
- **Unambiguous**: Forced clarification markers highlight uncertainties
- **Testable**: Test-first thinking baked into the process
- **Maintainable**: Proper abstraction levels and information hierarchy
- **Implementable**: Clear phases with concrete deliverables

The templates transform the LLM from a creative writer into a disciplined specification engineer, channeling its capabilities toward producing consistently high-quality, executable specifications that truly drive development.

## The Constitutional Foundation: Enforcing Architectural Discipline

At the heart of SDD lies a constitution—a set of immutable principles that govern how specifications become code. The constitution (`base/memory/constitution.md`) acts as the architectural DNA of the system, ensuring that every generated implementation maintains consistency, simplicity, and quality.

### The Nine Articles of Development

The constitution defines nine articles that shape every aspect of the development process:

#### Article I: Library-First Principle
Every feature must begin as a standalone library—no exceptions. This forces modular design from the start:
```
Every feature in Specify MUST begin its existence as a standalone library. 
No feature shall be implemented directly within application code without 
first being abstracted into a reusable library component.
```

This principle ensures that specifications generate modular, reusable code rather than monolithic applications. When the LLM generates an implementation plan, it must structure features as libraries with clear boundaries and minimal dependencies.

#### Article II: CLI Interface Mandate
Every library must expose its functionality through a command-line interface:
```
All CLI interfaces MUST:
- Accept text as input (via stdin, arguments, or files)
- Produce text as output (via stdout)
- Support JSON format for structured data exchange
```

This enforces observability and testability. The LLM cannot hide functionality inside opaque classes—everything must be accessible and verifiable through text-based interfaces.

#### Article III: Test-First Imperative
The most transformative article—no code before tests:
```
This is NON-NEGOTIABLE: All implementation MUST follow strict Test-Driven Development.
No implementation code shall be written before:
1. Unit tests are written
2. Tests are validated and approved by the user
3. Tests are confirmed to FAIL (Red phase)
```

This completely inverts traditional AI code generation. Instead of generating code and hoping it works, the LLM must first generate comprehensive tests that define behavior, get them approved, and only then generate implementation.

#### Articles VII & VIII: Simplicity and Anti-Abstraction
These paired articles combat over-engineering:
```
Section 7.3: Minimal Project Structure
- Maximum 3 projects for initial implementation
- Additional projects require documented justification

Section 8.1: Framework Trust
- Use framework features directly rather than wrapping them
```

When an LLM might naturally create elaborate abstractions, these articles force it to justify every layer of complexity. The implementation plan template's "Phase -1 Gates" directly enforce these principles.

#### Article IX: Integration-First Testing
Prioritizes real-world testing over isolated unit tests:
```
Tests MUST use realistic environments:
- Prefer real databases over mocks
- Use actual service instances over stubs
- Contract tests mandatory before implementation
```

This ensures generated code works in practice, not just in theory.

### Constitutional Enforcement Through Templates

The implementation plan template operationalizes these articles through concrete checkpoints:

```markdown
### Phase -1: Pre-Implementation Gates
#### Simplicity Gate (Article VII)
- [ ] Using ≤3 projects?
- [ ] No future-proofing?

#### Anti-Abstraction Gate (Article VIII)
- [ ] Using framework directly?
- [ ] Single model representation?

#### Integration-First Gate (Article IX)
- [ ] Contracts defined?
- [ ] Contract tests written?
```

These gates act as compile-time checks for architectural principles. The LLM cannot proceed without either passing the gates or documenting justified exceptions in the "Complexity Tracking" section.

### The Power of Immutable Principles

The constitution's power lies in its immutability. While implementation details can evolve, the core principles remain constant. This provides:

1. **Consistency Across Time**: Code generated today follows the same principles as code generated next year
2. **Consistency Across LLMs**: Different AI models produce architecturally compatible code
3. **Architectural Integrity**: Every feature reinforces rather than undermines the system design
4. **Quality Guarantees**: Test-first, library-first, and simplicity principles ensure maintainable code

### Constitutional Evolution

While principles are immutable, their application can evolve:
```
Section 4.2: Amendment Process
Modifications to this constitution require:
- Explicit documentation of the rationale for change
- Review and approval by project maintainers
- Backwards compatibility assessment
```

This allows the methodology to learn and improve while maintaining stability. The constitution shows its own evolution with dated amendments, demonstrating how principles can be refined based on real-world experience.

### Beyond Rules: A Development Philosophy

The constitution isn't just a rulebook—it's a philosophy that shapes how LLMs think about code generation:

- **Observability Over Opacity**: Everything must be inspectable through CLI interfaces
- **Simplicity Over Cleverness**: Start simple, add complexity only when proven necessary
- **Integration Over Isolation**: Test in real environments, not artificial ones
- **Modularity Over Monoliths**: Every feature is a library with clear boundaries

By embedding these principles into the specification and planning process, SDD ensures that generated code isn't just functional—it's maintainable, testable, and architecturally sound. The constitution transforms AI from a code generator into an architectural partner that respects and reinforces system design principles.

## The Transformation

This isn't about replacing developers or automating creativity. It's about amplifying human capability by automating mechanical translation. It's about creating a tight feedback loop where specifications, research, and code evolve together, each iteration bringing deeper understanding and better alignment between intent and implementation.

Software development needs better tools for maintaining alignment between intent and implementation. SDD provides the methodology for achieving this alignment through executable specifications that generate code rather than merely guiding it.