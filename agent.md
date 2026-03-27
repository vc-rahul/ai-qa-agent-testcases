# QA Agent Configuration

## Enabled Skills

- qa-dom-analyzer
- qa-locator-generator
- qa-self-healing
- qa-testcase-generator

## Skill Usage Rules

Use **qa-testcase-generator** when:

- User provides BRD, PRD, or SRS
- User asks for manual test cases
- Requirement analysis is needed

Workflow:

1. Analyze requirement.
2. Generate test cases.
3. Return structured JSON output.