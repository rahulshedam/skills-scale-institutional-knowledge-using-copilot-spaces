# OctoAcme — Role Handoff Checklist

## Purpose
Ensure smooth transitions between roles and phases of work by providing clear handoff procedures, reducing ambiguity, and maintaining continuity across the project lifecycle.

## When to Use
- When transferring work between different roles or teams
- At key project milestones (design → development, development → QA, QA → release)
- When onboarding new team members mid-project
- During escalations or incident handoffs

---

## Product Manager → Developers

### Handoff Checklist
- [ ] Problem statement clearly documented in project one-pager
- [ ] User stories or features defined with acceptance criteria
- [ ] Success metrics and KPIs identified
- [ ] Priority and timeline communicated
- [ ] Dependencies and constraints documented
- [ ] Design mocks or wireframes linked (if applicable)
- [ ] Stakeholder expectations aligned

### Handoff Artifact
- Project one-pager or feature specification document
- Acceptance criteria in issue or backlog item
- Link to design files or user research findings

---

## UX/UI Designer → Developers

### Handoff Checklist
- [ ] Final designs approved by Product Manager
- [ ] Design specifications documented (spacing, colors, typography)
- [ ] Interactive prototype or mockups provided
- [ ] Accessibility requirements specified (WCAG compliance level)
- [ ] Edge cases and error states designed
- [ ] Responsive behavior documented for different screen sizes
- [ ] Design system components identified and documented
- [ ] Assets exported and organized (icons, images, etc.)

### Handoff Artifact
- Design specification document or Figma/Sketch file with developer handoff mode
- Component library references
- Accessibility checklist

---

## Developers → QA/Testing

### Handoff Checklist
- [ ] Feature implementation complete per acceptance criteria
- [ ] Unit tests written and passing
- [ ] Code reviewed and approved
- [ ] PR merged to test/staging branch
- [ ] Known limitations or edge cases documented
- [ ] Test environment deployed and accessible
- [ ] Test data or accounts provided (if needed)
- [ ] Rollback plan documented

### Handoff Artifact
- Link to deployed test environment
- Test account credentials (in secure vault)
- List of acceptance criteria to validate
- Known issues or workarounds document

---

## QA/Testing → Release/Deployment

### Handoff Checklist
- [ ] All acceptance criteria validated
- [ ] Regression testing completed
- [ ] Security and performance testing passed
- [ ] Critical bugs resolved or documented as known issues
- [ ] Test report or summary documented
- [ ] Smoke test plan prepared for production
- [ ] Sign-off obtained from Product Manager

### Handoff Artifact
- QA test report with pass/fail status
- List of known issues or limitations
- Smoke test checklist for production validation

---

## DevOps → Developers (Incident/Deployment Issues)

### Handoff Checklist
- [ ] Incident severity and impact assessed
- [ ] Timeline of events documented
- [ ] Error logs and metrics collected
- [ ] Affected systems and services identified
- [ ] Temporary mitigation applied (if any)
- [ ] Reproduction steps documented
- [ ] Hypothesis of root cause provided

### Handoff Artifact
- Incident report with logs and metrics
- Link to monitoring dashboard or alerts
- Reproduction steps or affected request IDs

---

## Developers → Technical Writer

### Handoff Checklist
- [ ] Feature complete and merged to main branch
- [ ] API changes or new endpoints documented in code
- [ ] User-facing changes identified
- [ ] Screenshots or demo video provided
- [ ] Target release version specified
- [ ] Migration steps documented (if applicable)

### Handoff Artifact
- Feature summary document
- API specification or OpenAPI/Swagger file
- Screenshots or demo of new functionality
- Migration or upgrade guide (if needed)

---

## Customer Success/Support → Product/Engineering

### Handoff Checklist
- [ ] Issue or feature request clearly described
- [ ] Customer impact and frequency documented
- [ ] Reproduction steps provided (for bugs)
- [ ] Workarounds documented (if any)
- [ ] Customer business context explained
- [ ] Priority or urgency assessed
- [ ] Related support tickets linked

### Handoff Artifact
- Customer feedback summary or escalation document
- Reproduction steps with screenshots or logs
- Frequency and impact analysis
- Link to support tickets or customer conversations

---

## General Handoff Best Practices

1. **Use a Single Source of Truth**: Document handoffs in the project board, README, or dedicated handoff document
2. **Schedule Handoff Meetings**: For complex work, schedule a 15-30 minute sync to walk through the checklist
3. **Verify Receipt**: Ensure the receiving role acknowledges and understands the handoff
4. **Document Decisions**: Capture any decisions or clarifications made during handoff
5. **Set Clear Timelines**: Establish expected completion dates for the next phase
6. **Maintain Context**: Link to relevant issues, PRs, designs, and discussions
7. **Iterate on Checklists**: Update handoff checklists based on retrospective feedback

---

## Escalation Handoff

When escalating issues beyond the team:

- [ ] Summarize the issue and business impact
- [ ] Document steps already taken to resolve
- [ ] Provide supporting evidence (logs, metrics, customer feedback)
- [ ] Specify what decision or action is needed
- [ ] Set clear timeline expectations
- [ ] Identify who needs to be involved

Use escalation path: Team Lead → Product Lead → Executive Sponsor
