# Constitution Update Checklist

When amending the constitution (`/memory/constitution.md`), ensure all dependent documents are updated to maintain consistency.

## Templates to Update

### When adding/modifying ANY principle:
- [ ] `/templates/framework-template.md` - Update Constitution Check section
- [ ] `/templates/assessment-template.md` - Update if requirements/scope affected
- [ ] `/templates/activities-template.md` - Update if new activity types needed
- [ ] `/.claude/commands/validate.md` - Update if framework process changes
- [ ] `/.claude/commands/execute.md` - Update if activity generation affected
- [ ] `/CLAUDE.md` - Update runtime assessment guidelines

### Principle-specific updates:

#### Principle I (Multiple Assessment Modalities):
- [ ] Ensure templates emphasize diverse assessment methods
- [ ] Update activity examples for different learning styles
- [ ] Add accommodation requirement reminders

#### Principle II (Authentic Assessment Focus):
- [ ] Update real-world connection requirements in templates
- [ ] Add transfer and application emphasis
- [ ] Include relevance criteria reminders

#### Principle III (Student Agency and Voice):
- [ ] Update self-assessment requirements in all templates
- [ ] Emphasize student choice opportunities
- [ ] Add metacognitive reflection requirements

#### Principle IV (Bias Prevention and Equity):
- [ ] List equity check triggers
- [ ] Update cultural responsiveness priorities
- [ ] Add accommodation design requirements

#### Principle V (Growth-Oriented Evaluation):
- [ ] Add progress tracking requirements to templates
- [ ] Include formative feedback emphasis
- [ ] Update improvement documentation sections

## Validation Steps

1. **Before committing constitution changes:**
   - [ ] All templates reference new requirements
   - [ ] Examples updated to match new rules
   - [ ] No contradictions between documents

2. **After updating templates:**
   - [ ] Run through a sample implementation plan
   - [ ] Verify all constitution requirements addressed
   - [ ] Check that templates are self-contained (readable without constitution)

3. **Version tracking:**
   - [ ] Update constitution version number
   - [ ] Note version in template footers
   - [ ] Add amendment to constitution history

## Common Misses

Watch for these often-forgotten updates:
- Command documentation (`/commands/*.md`)
- Checklist items in templates
- Example code/commands
- Domain-specific variations (web vs mobile vs CLI)
- Cross-references between documents

## Template Sync Status

Last sync check: 2025-07-16
- Constitution version: 2.1.1
- Templates aligned: ❌ (missing versioning, observability details)

---

*This checklist ensures the constitution's principles are consistently applied across all project documentation.*