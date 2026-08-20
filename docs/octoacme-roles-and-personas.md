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

## Quality Assurance / QA Lead

### Role Summary
QA Leads own the quality strategy, test planning, and acceptance validation for projects. They collaborate with developers and product managers to ensure features meet acceptance criteria and quality standards before release.

### Responsibilities
- Develop and maintain test plans aligned with feature scope
- Define acceptance criteria and quality gates
- Coordinate manual and automated testing efforts
- Validate features against acceptance criteria before sign-off
- Identify quality risks and propose mitigations
- Coordinate smoke tests and pre-release validation

### Goals
- Ensure features meet defined acceptance criteria
- Reduce defects reaching production
- Enable confidence in release readiness

### Interaction with Other Roles
- **Developers**: Collaborate on test strategy and acceptance criteria definition; review test coverage and automated test implementation
- **Product Managers**: Align on quality expectations and acceptance criteria; validate feature completeness before handoff
- **Project Managers**: Report on quality status and blockers in delivery syncs; escalate quality risks that impact timelines
- **Technical Leads**: Coordinate on test infrastructure and technical quality gates

### Typical Communication
- Quality gate reviews in sprint planning
- Test status in weekly delivery syncs
- Pre-release quality sign-off
- Test case reviews and acceptance criteria validation

---

## Product Lead

### Role Summary
Product Leads set strategic direction for product initiatives and align cross-functional teams around customer outcomes. They own the decision-making authority for prioritization, scope, and success metrics across multiple Product Managers.

### Responsibilities
- Define strategic product direction and customer outcomes
- Approve high-level roadmap and release priorities
- Align stakeholders and executive sponsors around product vision
- Review and validate success metrics
- Escalate and resolve cross-product dependencies
- Mentor and align individual Product Managers

### Goals
- Maximize customer value across product initiatives
- Ensure alignment between business strategy and execution
- Enable consistent decision-making across the product organization

### Interaction with Other Roles
- **Product Managers**: Provide strategic guidance and mentoring; approve roadmap and prioritization decisions
- **Project Managers**: Set high-level timelines and milestones; escalate business-impacting risks
- **Stakeholders/Sponsors**: Communicate product strategy and trade-offs; align on organizational priorities
- **Developers & Technical Leads**: Balance technical feasibility with business goals in architectural decisions

### Typical Communication
- Monthly roadmap and strategy alignment
- Weekly PM syncs and mentoring
- Quarterly stakeholder reviews
- Executive sponsor briefings

---

## Technical Lead / Architect

### Role Summary
Technical Leads guide the technical direction of projects, identify architectural risks, and mentor developers on design and implementation best practices. They collaborate with Product Managers and Project Managers to balance technical feasibility with business goals.

### Responsibilities
- Define technical architecture and design patterns
- Review technical proposals and architectural trade-offs
- Identify technical risks and propose mitigations
- Mentor developers on code quality and design
- Coordinate technical integration points and dependencies
- Support estimation and capacity planning

### Goals
- Deliver scalable, maintainable technical solutions
- Reduce technical debt and rework
- Enable team learning and skill growth

### Interaction with Other Roles
- **Developers**: Provide architectural guidance, mentor on design patterns, review technical designs
- **Product Managers**: Advise on technical feasibility of features; identify dependencies and constraints
- **QA Leads**: Define technical quality gates and testing infrastructure requirements
- **Project Managers**: Contribute to risk identification and capacity planning; escalate technical blockers

### Typical Communication
- Technical design reviews and architecture discussions
- Risk assessments in planning and execution
- Code reviews and mentoring
- Technical spike investigations and recommendations

---

## Stakeholder / Sponsor

### Role Summary
Sponsors provide business context, approve resource allocations, and escalate business-impacting issues. They ensure projects align with organizational priorities and have adequate support.

### Responsibilities
- Provide business context and strategic alignment
- Approve project charter and resource allocation
- Participate in initiation and go/no-go decisions
- Escalate business-impacting risks and blockers
- Approve major scope or timeline changes
- Support team by removing organizational barriers

### Goals
- Ensure projects deliver business value
- Maintain strategic alignment with organizational priorities
- Enable team success by providing executive support

### Interaction with Other Roles
- **Project Managers**: Approve timelines and budgets; escalate blockers; provide organizational context
- **Product Leads**: Align on product strategy and priorities; approve roadmap changes
- **Product Managers**: Provide business requirements and success criteria; approve scope changes
- **Development Team**: Remove organizational barriers; advocate for team needs at executive level

### Typical Communication
- Project initiation and approval
- Monthly stakeholder updates
- Ad-hoc escalation and decision-making
- Executive steering committee meetings (if applicable)

---

## Security & Compliance Officer

### Role Summary
Security Officers ensure projects meet security, privacy, and compliance requirements. They collaborate with developers and product teams to build security into products from the start and respond to security incidents.

### Responsibilities
- Define security and compliance requirements for projects
- Review and approve security-related design decisions
- Coordinate security scanning and penetration testing
- Triage and escalate security incidents
- Ensure post-incident follow-up and remediation
- Maintain security runbooks and incident response procedures

### Goals
- Ensure products meet security and compliance standards
- Reduce security risk and incident impact
- Enable secure-by-default development practices

### Interaction with Other Roles
- **Developers**: Define security requirements and best practices; review security-related code changes
- **Technical Leads**: Collaborate on security architecture and threat modeling; advise on security trade-offs
- **Project Managers**: Escalate security incidents; track remediation; communicate security timelines to stakeholders
- **QA Leads**: Coordinate security testing and vulnerability scanning; validate security fixes

### Typical Communication
- Security requirements in project planning
- Security scanning in CI/CD
- Incident response and triage
- Post-incident retrospectives
- Security training and awareness activities

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Cross-role interactions help teams understand how these personas collaborate and depend on each other in project execution.
