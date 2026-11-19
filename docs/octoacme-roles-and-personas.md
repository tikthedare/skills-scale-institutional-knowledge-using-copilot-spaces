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

## Engineering / Technical Lead

### Role Summary
The Engineering or Technical Lead provides technical direction and ensures that proposed solutions are feasible, maintainable, secure, and aligned with delivery constraints.

### Responsibilities
- Guide technical design and architecture decisions
- Estimate technical scope and identify engineering risks
- Coordinate work across Developers and review major technical changes
- Propose mitigations for dependencies, scalability, and operational concerns
- Confirm testability of implementation approaches

### Decision Ownership
The Technical Lead owns technical implementation recommendations and raises unresolved trade-offs to the Product Manager and Project Manager.

### Goals
- Deliver a coherent, maintainable technical approach
- Reduce delivery risk caused by unclear dependencies or technical decisions
- Maintain appropriate engineering standards and observability

### Typical Communication
- Architecture and design reviews
- Planning and estimation sessions
- Technical risk updates in team and PM syncs
- Cross-team implementation coordination

### Collaboration with Existing Roles
- Partners with the Product Manager to assess feasibility and balance scope, cost, and outcomes.
- Provides the Project Manager with technical dependencies, estimates, and delivery risks.
- Coordinates Developers and advises QA/Testing on testability and validation needs.
- Works with Security/Privacy and Operations roles to address risks and operational readiness.

---

## UX/UI Designer or User Researcher

### Role Summary
The UX/UI Designer or User Researcher represents customer needs in solution design and ensures that experiences are understandable, accessible, and usable.

### Responsibilities
- Conduct or synthesize user research
- Create and validate user flows, wireframes, and interaction designs
- Translate findings into design requirements and usability acceptance criteria
- Review implementation for fidelity to intended experience

### Decision Ownership
Owns user experience and research recommendations, while the Product Manager retains product prioritization and scope decisions.

### Goals
- Improve usability and accessibility
- Reduce uncertainty about customer needs
- Ensure implemented experiences match validated designs

### Typical Communication
- Research readouts and design critiques
- Backlog refinement and acceptance-criteria reviews
- Design handoffs and implementation reviews

### Collaboration with Existing Roles
- Partners with the Product Manager to turn user evidence into product priorities and acceptance criteria.
- Collaborates with Developers on feasible implementation and with QA/Testing on usability validation.
- Provides Stakeholders with customer insights and proposed experience decisions.
- Coordinates with the Project Manager on design dependencies and review milestones.

---

## Business Owner or Executive Sponsor

### Role Summary
The Business Owner or Executive Sponsor ensures alignment with organizational strategy and provides authority for resources, priority, and major decisions.

### Responsibilities
- Clarify strategic outcomes and business constraints
- Secure funding, resources, and stakeholder engagement
- Approve major scope, budget, or priority changes within delegated authority
- Resolve escalations that cannot be handled by delivery leadership

### Decision Ownership
Owns strategic scope and resource decisions, while implementation and delivery decisions remain with the Product and Project Managers and delivery team.

### Goals
- Ensure the project delivers measurable business value
- Keep the initiative aligned with organizational priorities
- Unblock decisions with material business impact

### Typical Communication
- Executive or sponsor updates
- Milestone and investment reviews
- Escalation discussions and decision records

### Collaboration with Existing Roles
- Aligns with the Product Manager on outcomes, priority, and success measures.
- Gives the Project Manager authority and context for scope, resource, and escalation decisions.
- Receives status and risk summaries from delivery leadership and provides direction to Stakeholders.
- Partners with Technical, Security, Operations, and Analytics roles when a business decision depends on their expertise.

---

## Security / Privacy Lead

### Role Summary
The Security/Privacy Lead advises the team on threats, privacy obligations, and required controls throughout the project lifecycle.

### Responsibilities
- Identify security and privacy requirements and risks
- Review threat models, data handling, and control gaps
- Recommend mitigations and evidence required for approval
- Support incident and vulnerability escalation

### Decision Ownership
Owns security and privacy recommendations and applicable approval decisions when delegated through policy.

### Goals
- Reduce exposure to security and privacy risks
- Ensure controls are designed and verified early
- Improve readiness for audits and releases

### Typical Communication
- Threat and control reviews
- Security risk and release-readiness updates
- Incident-response coordination

### Collaboration with Existing Roles
- Works with Developers and the Technical Lead to embed controls and mitigations.
- Coordinates with QA/Testing on security, privacy, and compliance validation.
- Advises the Project Manager of release readiness, incidents, and unresolved risks.
- Partners with the Product Manager and Business Owner on risk trade-offs and required scope.

---

## Operations / Site Reliability / Support Representative

### Role Summary
The Operations, Site Reliability, or Support Representative prepares the service for production and represents operational and customer-support needs.

### Responsibilities
- Define monitoring, alerting, support, and operational readiness requirements
- Plan deployment, observability, capacity, backup, and rollback needs
- Establish incident-response ownership and support procedures
- Share recurring customer issues and operational feedback

### Decision Ownership
Owns operational-readiness recommendations and may approve readiness when delegated, while the Project Manager coordinates release decisions.

### Goals
- Improve production reliability and supportability
- Reduce mean time to detect and recover from incidents
- Give customers a clear and effective support path

### Typical Communication
- Readiness reviews and runbooks
- Operational dashboards and incident updates
- Support handoff and post-release feedback

### Collaboration with Existing Roles
- Partners with Developers and the Technical Lead on monitoring, deployment, and recovery capabilities.
- Works with QA/Testing on reliability, smoke, and operational acceptance checks.
- Coordinates release readiness and support timing with the Project Manager.
- Shares production and customer-impact feedback with the Product Manager and Stakeholders.

---

## Data / Analytics Lead

### Role Summary
The Data/Analytics Lead ensures that outcomes are measurable and that instrumentation and reporting support evidence-based decisions.

### Responsibilities
- Define required events, metrics, and reporting needs
- Assess data quality and instrumentation coverage
- Establish baselines and support outcome analysis
- Communicate findings and measurement limitations

### Decision Ownership
Owns measurement methodology and reporting recommendations; the Product Manager owns how outcome findings influence product decisions.

### Goals
- Enable reliable measurement of success metrics
- Improve confidence in experimentation and outcome reporting
- Identify gaps in instrumentation and data quality early

### Typical Communication
- Metric and instrumentation reviews
- Experiment and dashboard updates
- Outcome analyses and learning summaries

### Collaboration with Existing Roles
- Partners with the Product Manager to align metrics with success criteria and prioritize measurement needs.
- Coordinates event implementation with Developers and Technical Leads.
- Works with QA/Testing to validate tracking and reporting behavior.
- Provides the Project Manager and Stakeholders with clear outcome and data-quality updates.

---

## Applying Personas to a Project

Roles may be combined or assigned to multiple people on smaller projects. They may also be omitted when a project does not require the associated responsibility. Regardless of team size or structure, each responsibility should have a named owner and documented handoff or escalation path.

When defining a project team, assign an accountable person for technical direction, customer experience, business sponsorship, security/privacy, operational readiness, and outcome measurement where applicable. Add the assignments to the project plan and confirm any decision or escalation boundaries during kickoff.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
