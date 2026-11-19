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

## Release Manager

### Role Summary
Release Managers own release readiness and coordinate the activities required to move a validated change into production safely.

### Responsibilities
- Confirm that acceptance criteria, CI, security checks, release notes, smoke tests, and rollback plans are complete
- Schedule deployment windows and coordinate with Engineering, QA, Support, and Stakeholders
- Lead deployment communications and post-deployment verification
- Coordinate incident and rollback response with on-call teams

### Goals
- Reduce production risk and deployment uncertainty
- Make release decisions and readiness status visible
- Improve the consistency and reliability of releases

### Interactions with Existing Roles
- Works with the Project Manager to align the release with milestones, dependencies, and communications
- Works with Developers and QA/Testing to confirm that code and validation are complete
- Works with the Product Manager on release scope and Stakeholder messaging
- Coordinates with Support or Operations before and after deployment

### Typical Communication
- Release readiness reviews and deployment checklists
- Deployment announcements and status updates
- Rollback and incident notifications

---

## Security Lead

### Role Summary
Security Leads define and oversee security requirements, reviews, and response expectations throughout the project lifecycle.

### Responsibilities
- Identify applicable security and compliance requirements
- Review designs and implementations for security risks
- Define security acceptance criteria and validation activities
- Guide incident response and coordinate the security on-call process

### Goals
- Prevent and reduce security vulnerabilities
- Ensure security risks are understood and mitigated
- Improve secure delivery practices across teams

### Interactions with Existing Roles
- Partners with Developers on secure design, implementation, and remediation
- Works with QA/Testing to define security tests and verification
- Advises the Project Manager and Risk or Compliance Owner on security risks, mitigations, and escalation
- Helps the Product Manager evaluate trade-offs for security-sensitive features

### Typical Communication
- Threat and risk reviews
- Security findings and remediation plans
- Security incident updates and runbooks

---

## UX/Design Lead

### Role Summary
UX/Design Leads translate customer and stakeholder needs into usable flows, interfaces, and acceptance criteria.

### Responsibilities
- Research users and communicate needs and usability risks
- Create and validate interaction and visual designs
- Define design acceptance criteria and usability tests
- Incorporate feedback from validation and production usage

### Goals
- Improve usability and customer satisfaction
- Resolve design ambiguity before implementation
- Deliver consistent, accessible experiences

### Interactions with Existing Roles
- Partners with the Product Manager to translate customer outcomes into design requirements
- Collaborates with Developers during design and implementation reviews
- Works with QA/Testing to establish and validate usability and accessibility criteria
- Shares validated designs and insights with Stakeholders and the Project Manager

### Typical Communication
- Discovery findings and design proposals
- Design reviews and usability test summaries
- Acceptance criteria and implementation guidance

---

## Data Analyst

### Role Summary
Data Analysts establish how project outcomes and delivery health will be measured and turn evidence into actionable findings.

### Responsibilities
- Define measurement plans and success metrics
- Analyze product, delivery, quality, and operational data
- Identify trends, anomalies, and opportunities for improvement
- Support experiment design and post-release evaluation

### Goals
- Enable clear, evidence-based decisions
- Validate whether delivered work achieves intended outcomes
- Improve the quality and observability of project metrics

### Interactions with Existing Roles
- Works with the Product Manager to define success metrics and evaluate outcomes
- Helps the Project Manager monitor delivery signals and interpret risks
- Partners with Developers to ensure required instrumentation is implemented
- Shares findings with QA/Testing and Stakeholders to support decisions and follow-up

### Typical Communication
- Metric definitions and dashboards
- Experiment and outcome reports
- Decision summaries and follow-up recommendations

---

## Support or Operations Representative

### Role Summary
Support or Operations Representatives represent operational readiness and the needs of customers and internal support teams.

### Responsibilities
- Prepare support documentation, FAQs, escalation paths, and runbooks
- Identify operational capacity and support requirements
- Participate in readiness reviews and release planning
- Provide production feedback, customer themes, and incident observations

### Goals
- Improve customer support readiness
- Reduce operational surprises and recovery time
- Ensure production feedback informs the backlog

### Interactions with Existing Roles
- Works with the Release Manager and Project Manager on deployment and communication readiness
- Partners with Developers and Security on troubleshooting guidance and operational fixes
- Supplies customer and production insights to the Product Manager
- Works with QA/Testing to validate support workflows and known issues

### Typical Communication
- Readiness reviews and support plans
- Release FAQs and runbooks
- Production feedback and support escalations

---

## Risk or Compliance Owner

### Role Summary
Risk or Compliance Owners identify applicable business, regulatory, and governance constraints and maintain accountability for required mitigations.

### Responsibilities
- Identify regulatory, contractual, audit, and policy obligations
- Confirm required controls and evidence
- Maintain material risks and mitigation status
- Coordinate compliance findings and escalation with accountable leaders

### Goals
- Prevent non-compliance and avoidable business risk
- Keep obligations visible and tied to owned actions
- Support informed, documented decisions

### Interactions with Existing Roles
- Works with the Project Manager to capture risks, dependencies, owners, and deadlines
- Partners with the Security Lead on security and privacy controls
- Advises the Product Manager and Stakeholders on constraints affecting scope or prioritization
- Coordinates evidence and readiness checks with Developers and QA/Testing

### Typical Communication
- Compliance and risk assessments
- Risk register updates and escalation summaries
- Audit evidence and control validation

---

## Cross-role Collaboration

Accountability should remain explicit: assign one owner for each outcome or decision, consult the relevant roles, and distinguish accountable owners from contributors. Roles may be combined for smaller projects, but the responsibilities and handoffs should remain clear.

- **Planning:** The Product Manager prioritizes outcomes; the Project Manager coordinates timelines and dependencies; the UX/Design Lead, Data Analyst, Security Lead, and Risk or Compliance Owner contribute requirements and constraints.
- **Execution:** Developers implement work with QA/Testing and the UX/Design Lead; the Project Manager tracks progress and risks; the Data Analyst defines and monitors success measures.
- **Release readiness:** The Release Manager coordinates deployment; the Security Lead confirms security readiness; and the Support or Operations Representative verifies operational support.
- **Retrospectives:** Each relevant persona contributes lessons and improvement actions, with owners and due dates tracked in the project backlog or issue tracker.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
