# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own the quality strategy and ensure features meet acceptance criteria before release. They work closely with developers and product managers to define testability requirements and validate product quality.

### Responsibilities
- Define and execute test plans aligned with project scope
- Create and maintain test cases and acceptance criteria checklists
- Coordinate manual QA and automation testing efforts
- Triage and document bugs; track quality metrics
- Participate in sprint planning to ensure testability is considered
- Validate releases against success metrics before production deployment

### Goals
- Ensure high-quality releases with minimal post-production issues
- Reduce cycle time by catching issues early
- Provide clear visibility into test coverage and quality risks

### Typical Communication
- Participate in daily standups and sprint planning
- Report test status and quality metrics in weekly syncs
- Collaborate with developers on bug triage and acceptance criteria clarity

### Interaction with Other Roles
- **Developers**: Works with developers to understand implementation and design test cases; provides feedback on testability
- **Product Manager**: Validates features align with acceptance criteria and user expectations
- **Project Manager**: Reports quality blockers and escalates release-blocking issues; contributes to risk register

---

## Technical Lead/Architect

### Role Summary
Technical Leads provide architectural guidance, design decisions, and technical direction. They ensure solutions are scalable, maintainable, and aligned with system design principles.

### Responsibilities
- Review technical designs and architecture for projects
- Provide guidance on technology choices and trade-offs
- Mentor developers on best practices and code quality
- Identify technical risks and propose mitigation strategies
- Participate in design reviews and code reviews for critical changes
- Guide team on performance, scalability, and security considerations

### Goals
- Ensure technical excellence and long-term maintainability
- Reduce technical debt and rework
- Enable developers to make sound design decisions independently

### Typical Communication
- Technical design documents and architecture reviews
- Code review feedback on complex changes
- Technical risk register entries and mitigation planning

### Interaction with Other Roles
- **Developers**: Provides guidance and review on design and implementation; mentors on technical best practices
- **Project Manager**: Flags technical risks and estimates technical complexity; informs timeline and resource planning
- **Product Manager**: Advises on feasibility and trade-offs between features and quality; helps inform scope decisions

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors are business owners who provide strategic direction, funding, and approval authority for projects. They represent customer, business, or organizational interests.

### Responsibilities
- Define business needs and strategic alignment
- Provide project funding and resource approval
- Make go/no-go decisions at key gates
- Review and approve major milestone deliverables
- Escalate blockers and resolve cross-organizational dependencies
- Communicate project status to executive leadership

### Goals
- Ensure projects deliver measurable business value
- Maximize return on investment
- Maintain alignment with organizational strategy

### Typical Communication
- Kick-off meetings and project reviews
- Milestone approvals and decision gates
- Monthly stakeholder status updates
- Escalation and issue resolution

### Interaction with Other Roles
- **Project Manager**: Receives status updates and escalations; approves timeline and scope changes
- **Product Manager**: Collaborates on prioritization and success metrics; provides business context
- **Developers/Technical Lead**: Reviews technical feasibility and risks at key checkpoints

---

## Scrum Master/Iteration Coach

### Role Summary
Scrum Masters and Iteration Coaches facilitate Agile ceremonies, remove blockers, and coach the team on process improvement. They focus on enabling the team to work effectively and iteratively.

### Responsibilities
- Facilitate daily standups, sprint planning, and retrospectives
- Identify and escalate team blockers
- Coach team members on Agile practices and continuous improvement
- Maintain sprint board and track velocity metrics
- Support removal of impediments to team progress
- Foster psychological safety and team collaboration

### Goals
- Maximize team velocity and predictability
- Enable continuous process improvement
- Maintain team morale and psychological safety

### Typical Communication
- Daily standups and sprint ceremonies
- One-on-ones with team members to address concerns
- Retrospective facilitation and action item tracking

### Interaction with Other Roles
- **Project Manager**: Coordinates on timeline and resource planning; escalates blockers
- **Developers**: Removes impediments and coaches on process adherence
- **All Roles**: Facilitates ceremonies and fosters collaborative team environment

---

## Security/Compliance Officer

### Role Summary
Security and Compliance Officers ensure that projects meet security standards, regulatory requirements, and risk mitigation policies. They provide guidance on secure design and compliance validation.

### Responsibilities
- Review security requirements and threat modeling
- Conduct or coordinate security reviews and assessments
- Ensure compliance with regulatory and organizational standards
- Identify and escalate security and compliance risks
- Provide guidance on secure development practices
- Participate in incident response and post-incident reviews

### Goals
- Prevent security breaches and compliance violations
- Enable secure, compliant product delivery
- Build security and compliance awareness across teams

### Typical Communication
- Security design reviews and threat assessments
- Compliance checklists and risk register entries
- Incident response and post-incident communications

### Interaction with Other Roles
- **Technical Lead/Architect**: Collaborates on secure design and architectural decisions
- **Developers**: Provides guidance on secure coding and security best practices
- **Project Manager**: Flags security and compliance risks; participates in risk management
- **All Roles**: Educates on security and compliance requirements

---

## Release Manager

### Role Summary
Release Managers coordinate deployment activities, manage release checklists, and oversee production deployments. They ensure releases are executed smoothly and risks are minimized.

### Responsibilities
- Coordinate release planning and scheduling
- Manage release checklists and pre-deployment verifications
- Oversee deployment to staging and production environments
- Execute or coordinate rollback procedures if needed
- Manage release notes and communication to stakeholders
- Track post-deployment verification and incident response

### Goals
- Execute zero-defect releases with minimal production impact
- Ensure clear communication and transparency during releases
- Enable rapid recovery if issues arise post-deployment

### Typical Communication
- Release planning meetings and deployment windows
- Release notes and stakeholder communications
- Incident response and rollback coordination

### Interaction with Other Roles
- **Developers**: Ensures code is release-ready and coordinates final validation
- **QA/Testing Lead**: Validates all acceptance criteria met; coordinates smoke testing
- **Project Manager**: Informs stakeholders of release status and timelines
- **Technical Lead/Architect**: Addresses technical issues during deployment if needed

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Personas should be considered in cross-functional project planning to ensure clear accountability and communication paths.
