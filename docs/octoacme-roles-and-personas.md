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
QA/Testing Leads own quality assurance strategy, test planning, and acceptance validation. They collaborate with product and development teams to define quality standards and ensure features meet acceptance criteria before release. QA/Testing Leads work closely with Developers to establish testability requirements and with Product Managers to validate acceptance criteria alignment.

### Responsibilities
- Define test strategy and QA approach for projects aligned with project scope
- Create and maintain test plans aligned with acceptance criteria
- Coordinate manual and automated testing efforts across the team
- Identify and report quality issues with clear reproduction steps
- Approve features for release based on acceptance criteria fulfillment
- Collaborate with Developers on test automation and test coverage
- Partner with Product Managers to validate feature completeness

### Goals
- Ensure high quality and reliability of delivered features
- Reduce defects reaching production and minimize post-release issues
- Enable team confidence in release decisions
- Improve test automation and reduce manual testing effort

### Typical Communication
- QA planning sessions during project kickoff and sprint planning
- Test reports and quality dashboards shared with stakeholders
- Release sign-off communications with Project Managers and Product Managers
- Defect tracking and triage in daily standups

### Interactions with Other Roles
- **With Developers**: Reviews technical designs for testability, collaborates on test automation strategies, provides clear bug reports
- **With Product Managers**: Validates acceptance criteria clarity, flags missing test scenarios, confirms feature completeness
- **With Project Managers**: Reports quality metrics, escalates release blockers, participates in release planning

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove team blockers, and coach teams on agile practices. They help the team maintain velocity and psychological safety while ensuring adherence to agile principles. Scrum Masters work across all team members to enable consistent, efficient delivery.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Identify and help remove blockers affecting team velocity
- Coach team members on agile principles and practices
- Track sprint metrics and team health indicators
- Escalate impediments beyond team control to Project Managers
- Protect the team from external distractions and scope creep
- Foster psychological safety and continuous improvement culture

### Goals
- Enable consistent sprint delivery and predictable velocity
- Foster psychological safety and encourage team feedback
- Reduce cycle time and improve team velocity over time
- Identify and address systemic process improvements

### Typical Communication
- Agile ceremonies facilitation and timeboxing
- Blocker resolution and team coaching during standups
- Metrics and velocity tracking in retrospectives
- Coaching conversations with individual team members
- Escalation of blockers to Project Managers

### Interactions with Other Roles
- **With Project Managers**: Escalates impediments, provides velocity metrics, coordinates sprint planning alignment with project timelines
- **With All Team Members**: Facilitates ceremonies, removes blockers, coaches on agile practices
- **With Product Managers**: Ensures backlog clarity and story readiness for sprint planning

---

## Technical Lead/Architect

### Role Summary
Technical Leads define technical direction, review architectural decisions, and ensure technical excellence. They work across developers and product leadership to balance innovation with maintainability, scalability, and security. Technical Leads serve as technical mentors and decision authorities for architectural choices.

### Responsibilities
- Define technical architecture and design patterns for projects
- Review technical designs and code for architectural alignment and best practices
- Identify technical risks and propose mitigation strategies
- Guide technology selections and tool evaluations
- Mentor Developers on technical best practices and code quality
- Collaborate with Project Managers on technical timeline estimates
- Advise Product Managers on technical feasibility of requirements

### Goals
- Ensure scalable, maintainable technical solutions that reduce future rework
- Reduce technical debt and maintain system quality over time
- Enable team to make sound technical trade-offs aligned with business goals
- Foster knowledge sharing and technical excellence culture

### Typical Communication
- Technical design reviews and architecture discussions with Developers
- Risk assessments and mitigation planning with Project Managers
- Code review guidance and technical mentoring with Developers
- Technical feasibility assessments with Product Managers
- Architecture documentation and design rationale

### Interactions with Other Roles
- **With Developers**: Provides design guidance, reviews technical proposals, mentors on best practices
- **With Project Managers**: Advises on technical complexity and timeline estimates, escalates technical risks
- **With Product Managers**: Assesses technical feasibility, advises on architectural trade-offs
- **With QA/Testing Leads**: Collaborates on test strategy and automation architecture

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors represent business priorities, provide funding and authority, and ensure projects align with organizational strategy. They are the decision authority for project approval, prioritization, and major trade-offs. Stakeholders ensure projects deliver business value and maintain organizational alignment.

### Responsibilities
- Define business requirements and success metrics with Product Managers
- Approve project charters and release decisions
- Provide prioritization guidance and trade-off decisions when needed
- Remove organizational blockers and secure resources for project delivery
- Receive regular status updates and escalations from Project Managers
- Validate that solutions meet business objectives
- Approve budget and resource allocation for projects

### Goals
- Ensure projects deliver measurable business value
- Align project work with organizational strategy and priorities
- Enable timely decision-making and remove organizational barriers
- Maximize return on investment and resource efficiency

### Typical Communication
- Project approval and kickoff sign-off with Project Managers
- Monthly stakeholder status updates and business reviews
- Escalation and decision requests from Project Managers
- Quarterly strategy alignment and roadmap reviews
- Post-release business impact reviews

### Interactions with Other Roles
- **With Project Managers**: Approves projects, receives status updates, makes escalation decisions
- **With Product Managers**: Aligns on business objectives, approves roadmap prioritization
- **With Developers/Technical Leads**: Reviews technical feasibility trade-offs when necessary
- **With All Team Members**: Occasional engagement at kickoff, review, and release gates

---

## Operations/DevOps Engineer

### Role Summary
Operations and DevOps Engineers manage deployment infrastructure, monitor production systems, and provide operational support. They ensure reliable, secure, and performant systems in production. DevOps Engineers bridge development and operations, enabling fast and safe deployments through automation and monitoring.

### Responsibilities
- Manage CI/CD pipelines and deployment automation
- Monitor production systems and respond to incidents promptly
- Maintain infrastructure, security controls, and system compliance
- Document operational runbooks and incident procedures
- Collaborate on performance and scalability requirements during planning
- Support rollback procedures and disaster recovery planning
- Optimize infrastructure costs and resource utilization

### Goals
- Ensure reliable and secure production systems with high availability
- Enable fast, safe deployments with minimal risk and downtime
- Provide observability and incident response capabilities
- Reduce mean time to recovery (MTTR) and incident impact

### Typical Communication
- Deployment planning and coordination with Project Managers
- Infrastructure and scalability requirements discussions with Developers and Technical Leads
- Incident response and escalations during production issues
- Post-incident reviews and operational metrics reporting
- Infrastructure and monitoring updates in weekly syncs

### Interactions with Other Roles
- **With Project Managers**: Coordinates deployment schedules, provides infrastructure readiness status
- **With Developers/Technical Leads**: Collaborates on scalability, performance requirements, deployment strategies
- **With All Team Members**: Provides operational support, incident response, production monitoring
- **With QA/Testing Leads**: Supports staging environment setup and smoke testing coordination

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the "Interactions with Other Roles" sections to understand cross-functional dependencies and collaboration patterns.
