# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.
Specialist responsibilities may be combined or shared rather than assigned to separate people, depending on project size and context.

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

## UX/UI Designer or Researcher

### Role Summary
Design and research specialists help the team understand users and shape accessible, usable experiences. One person may cover both research and design, or the responsibilities may be shared.

### Responsibilities
- Plan and conduct user research; synthesize findings into user needs and journey insights
- Create and validate interaction flows, prototypes, and visual designs
- Consider accessibility and usability throughout design
- Share design intent, research evidence, and usability risks with the team

### Decision Boundaries
- Recommend experience approaches based on user evidence and design principles
- Partner with the Product Manager on user needs and priorities; the Product Manager owns product outcomes and backlog priority
- Work within project scope and delivery decisions coordinated by the Project Manager

### Collaboration and Handoffs
- Align research questions and user outcomes with the Product Manager; communicate findings and priority implications
- Give Developers design specifications and clarify trade-offs; collaborate on feasible implementation
- Partner with QA/Testing to identify usability and accessibility checks for acceptance and validation
- Share research insights and design decisions with the Project Manager and relevant stakeholders; raise material scope or schedule impacts early

---

## Engineering/Technical Lead or Architect

### Role Summary
The technical lead or architect guides the technical direction and helps the team make sound engineering decisions. This responsibility may be held by a senior Developer or shared across the engineering team.

### Responsibilities
- Guide technical design, architecture, and engineering quality practices
- Identify technical risks, dependencies, and constraints; propose mitigations
- Support Developers with design decisions, reviews, and technical problem-solving
- Advise on maintainability, scalability, reliability, and implementation trade-offs

### Decision Boundaries
- Guide technical design and engineering standards within agreed product goals and project constraints
- Consult the Product Manager when technical trade-offs affect product scope or outcomes
- Surface technical dependencies, risks, and delivery impacts to the Project Manager, who coordinates plans and escalations

### Collaboration and Handoffs
- Coordinate implementation approach and technical reviews with Developers
- Work with QA/Testing to define testability, quality expectations, and technical validation needs
- Explain feasibility and trade-offs to the Product Manager and Project Manager to inform prioritization and delivery planning
- Communicate material technical decisions, risks, and dependencies to stakeholders through the Project Manager

---

## Delivery/Operations or Site Reliability Engineer

### Role Summary
Operations and reliability specialists help ensure services can be deployed, monitored, supported, and recovered in production. These responsibilities may be shared with Developers.

### Responsibilities
- Advise on deployment readiness, operational support, and service reliability
- Define or improve monitoring, alerting, and operational procedures
- Identify availability, capacity, and operational risks and recommend mitigations
- Support release validation, incident response, and operational handoff

### Decision Boundaries
- Recommend operational readiness criteria and reliability controls
- Coordinate release and incident work with Developers and QA/Testing; raise readiness concerns before deployment
- Provide operational risk and schedule implications to the Project Manager; deployment timing and scope are coordinated with project and product owners

### Collaboration and Handoffs
- Partner with Developers on deployment configuration, observability, and support documentation
- Work with QA/Testing on release validation and operational checks
- Provide the Project Manager with readiness status, risks, and handoff requirements for release coordination
- Advise the Product Manager and stakeholders about user or service impact, recovery expectations, and operational constraints

---

## Security/Privacy Lead

### Role Summary
Security and privacy specialists help the team identify and address security, privacy, and compliance needs throughout delivery. The role may be shared with an existing security or privacy function.

### Responsibilities
- Identify applicable security and privacy requirements, risks, and controls
- Advise on secure design, data handling, and privacy considerations
- Review relevant designs or changes and coordinate follow-up on findings
- Help define security and privacy validation needs for delivery

### Decision Boundaries
- Provide domain guidance on security, privacy, and compliance risks and required controls
- Explain findings and potential impact to the Product Manager and Project Manager; product scope and project coordination remain with those roles
- Escalate unresolved or unacceptable risks through established organizational channels before affected work or releases proceed

### Collaboration and Handoffs
- Work with Developers to integrate controls and address findings in implementation
- Partner with QA/Testing to include relevant security and privacy checks in validation
- Advise the Product Manager on implications for product choices, data use, and user commitments
- Inform the Project Manager of risks, dependencies, owners, and release concerns so they can be tracked and escalated
- Communicate material requirements and risks to stakeholders with the Product Manager and Project Manager

---

## Data/Analytics Lead

### Role Summary
Data and analytics specialists help define how the team will measure product outcomes and validate whether delivery achieves them.

### Responsibilities
- Translate success metrics into measurement and instrumentation requirements
- Advise on event definitions, data quality, and analytics approaches
- Validate that collected data supports reliable outcome measurement
- Communicate findings and measurement limitations to the team

### Decision Boundaries
- Recommend measurement methods and explain data limitations
- Align metric definitions and outcome interpretation with the Product Manager, who owns product success measures
- Coordinate instrumentation dependencies and delivery impacts with the Project Manager and Developers

### Collaboration and Handoffs
- Partner with the Product Manager to define success metrics and interpret results against product goals
- Work with Developers to implement instrumentation and document event behavior
- Collaborate with QA/Testing to validate event capture, data quality, and analytics acceptance criteria
- Tell the Project Manager about instrumentation dependencies or risks that affect plans and milestones
- Share relevant outcome insights and caveats with stakeholders through the agreed communication cadence

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
