# Project Development Guidelines

A comprehensive framework to maintain project focus and consistency from ideation to deployment.

## Project Foundation

### Core Project Statement
**Project Name:** [Your Project Name]

**One-Line Description:** [What does this project do in one sentence?]

**Problem Statement:** [What specific problem are you solving?]

**Success Criteria:** [How will you know when this project is successful?]

### Decision Log / Project Progress
| Date | Decision | Reasoning | Impact | Status |
|------|----------|-----------|--------|--------|
| YYYY-MM-DD | [Decision made] | [Why this was chosen] | [How it affects the project] | [In Progress/Complete] |

### Progress Tracking
- **Current Phase:** [Planning/Development/Testing/Deployment]
- **Week of:** [Date]
- **Key Accomplishments:** [What was completed this week]
- **Blockers:** [What's preventing progress]
- **Next Steps:** [What's planned for next week]

## PRD Development

### 1. Problem Statement & Vision
Ask AI to help you explore:

**Problem Definition:**
- What specific problem or pain point are you trying to solve?
- How do people currently handle this problem (existing solutions/workarounds)?
- Why is this problem worth solving now?

**Problem Scope:**
- Who experiences this problem most acutely?
- How widespread is this problem?
- What happens if this problem remains unsolved?

**Vision:**
- What's your high-level vision for how this solution will work?
- What would success look like for someone using your solution?
- How will the world be different once your solution exists?

### 2. Target Users & Use Cases
Next, define your users:

**Primary Users:**
- Who are your primary users (demographics, roles, characteristics)?
- What's their current workflow/process?
- What are their biggest frustrations with current solutions?

**User Goals & Motivations:**
- What are they trying to accomplish?
- What would motivate them to use your solution?
- What would prevent them from using it?

**Key User Journeys:**
- What are the main paths users will take through your solution?
- What are the critical moments in their experience?
- Where might they get stuck or confused?

### 3. Core Features & Requirements
Define your solution scope:

**Must-Have Features (MVP):**
- What features are absolutely essential for launch?
- What's the minimum viable experience?
- What features would make users switch from alternatives?

**Nice-to-Have Features:**
- What features would enhance the experience but aren't critical?
- What could be added in future iterations?
- What features might cause scope creep?

**Technical Constraints:**
- Any platform or technology limitations?
- Performance requirements?
- Integration needs with existing systems?

### 4. Success Metrics & Goals
Establish measurable outcomes:

**Success Metrics:**
- How will you measure if the solution is working?
- What are your key performance indicators (KPIs)?
- What user behaviors indicate success?

**Timeline & Milestones:**
- What are the key milestones along the way?
- What are the dependencies and risks?

### 5. Technical Considerations
Plan your implementation:

**Platform Requirements:**
- Web, mobile, desktop, or multiple platforms?
- Browser/device compatibility needs?
- Accessibility requirements?

**Scalability & Performance:**
- Expected number of users?
- Data storage and processing needs?
- Performance benchmarks?

**Integration & Dependencies:**
- What external services or APIs are needed?
- What internal systems need to connect?
- What are the security requirements?
  
  ## Project Scope & Boundaries

### In Scope
- [ ] [Core feature 1]
- [ ] [Core feature 2]
- [ ] [Core feature 3]

### Out of Scope
- [ ] [Feature that might cause scope creep]
- [ ] [Nice-to-have that can wait]
- [ ] [Complexity that doesn't align with core goals]

## Architecture & Design Principles

### Core Design Principles
1. **Simplicity First** - Choose the simplest solution that works
2. **Progressive Enhancement** - Build core functionality first, add features incrementally
3. **Separation of Concerns** - Keep different aspects of the system independent
4. **DRY (Don't Repeat Yourself)** - Avoid code duplication
5. **YAGNI (You Aren't Gonna Need It)** - Don't build features until you need them

### Technology Decisions
- **Language/Framework:** [Your choice and why]
- **Database:** [Your choice and why]
- **Hosting/Deployment:** [Your choice and why]
- **Key Dependencies:** [List with justification]

### Architecture Overview
```
[Create a simple diagram or description of your system architecture]
```

## Scope Management

### Before Adding New Features
Ask yourself:
1. Does this align with the core problem statement?
2. Is this in the original scope?
3. What is the opportunity cost?
4. Can this wait until after MVP?

### Scope Change Process
1. **Document the request** - What and why?
2. **Assess impact** - Time, complexity, dependencies
3. **Update decision log** - Record choice and reasoning
4. **Adjust timeline** - Be realistic about delays
5. **Communicate changes** - Update stakeholders

## Development Resources

### Essential References
- [Cursor AI Prompts Collection](https://github.com/chrisdunlopnz/cursor-starter) - Curated prompts for development phases
- [The Twelve-Factor App](https://12factor.net/) - Best practices for SaaS development
- [Clean Code Principles](https://github.com/ryanmcdermott/clean-code-javascript) - Code quality guidelines

### Technology-Specific Resources
- [Documentation for your main framework]
- [Best practices guide for your language]
- [Deployment platform documentation]

## Deployment Checklist

### Pre-Launch
- [ ] All core features implemented and tested
- [ ] Performance benchmarks met
- [ ] Security review completed
- [ ] Documentation updated
- [ ] Backup and recovery procedures in place

### Launch
- [ ] Production environment configured
- [ ] Monitoring and logging active
- [ ] Rollback plan prepared
- [ ] Stakeholders notified

### Post-Launch
- [ ] Monitor system performance
- [ ] Gather user feedback
- [ ] Plan next iteration
- [ ] Update project documentation

## Best Practices

### Effective AI Prompt Strategies
1. **Provide Context** - Always share relevant files and project constraints
2. **Be Specific** - Ask for exact implementations rather than general advice
3. **Request Alternatives** - Ask for multiple approaches to compare
4. **Validate Suggestions** - Always review AI output against your principles
5. **Iterate Incrementally** - Break complex features into smaller, manageable pieces

### Recommended AI Workflows
1. **Feature Planning**: Use AI to break down features into tasks
2. **Code Generation**: Generate boilerplate with your specific patterns
3. **Code Review**: Get AI feedback on implementation quality
4. **Debugging**: Systematic problem-solving assistance
5. **Refactoring**: Improve code while maintaining functionality


**Last Updated:** [DATE]
**Project Phase:** [CURRENT PHASE]
**Next Milestone:** [UPCOMING MILESTONE] 