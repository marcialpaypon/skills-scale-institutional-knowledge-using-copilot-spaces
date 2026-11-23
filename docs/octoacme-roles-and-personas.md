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

## UX/UI Designers and User Researchers

### Role Summary
UX/UI Designers and User Researchers make sure solutions address real user needs and are understandable, accessible, and usable. Depending on team size, one person may cover research and design or the work may be split across specialists.

### Responsibilities
- Plan and conduct user research, and synthesize findings into user needs
- Create user flows, interaction designs, prototypes, and visual specifications
- Validate designs through usability testing and incorporate feedback
- Identify accessibility and usability considerations early
- Document design decisions and open questions for implementation

### Goals
- Deliver intuitive, inclusive experiences that solve validated user problems
- Reduce usability risk before implementation and release

### Typical Communication
- Research readouts, journey maps, prototypes, and design reviews
- Ongoing design handoffs and clarification with Developers

### Collaboration and Decision Boundaries
- Partner with Product Managers to refine user problems, requirements, and success measures; share evidence to inform prioritization. Product Managers remain accountable for product scope and priority.
- Work with Developers to assess feasibility, resolve implementation questions, and preserve design intent and accessibility. Developers own technical implementation decisions.
- Share research and usability risks with Project Managers so plans account for validation and design dependencies; Project Managers coordinate timing and cross-team handoffs.
- Own research and design recommendations, while product and delivery decisions remain with their accountable owners.

---

## QA Engineers and Test Leads

### Role Summary
QA Engineers and Test Leads help the team prevent defects and establish confidence that software meets functional, quality, and acceptance expectations. They may contribute directly to testing or coordinate quality practices across the team.

### Responsibilities
- Define test strategy, coverage, and appropriate test levels
- Translate requirements and acceptance criteria into test scenarios
- Coordinate exploratory, integration, and regression testing
- Report defects and quality risks with clear impact and reproduction details
- Track test results and outstanding issues for release readiness

### Goals
- Detect important defects early and provide transparent quality evidence
- Ensure critical user journeys and acceptance expectations are covered

### Typical Communication
- Test plans, defect reports, and quality summaries
- Test reviews and release-readiness discussions

### Collaboration and Decision Boundaries
- Partner with Product Managers to clarify acceptance criteria and discuss the impact of quality gaps on customer outcomes; Product Managers decide product scope and acceptance priorities.
- Work with Developers to improve testability, automate suitable checks, and reproduce and resolve defects. Developers own fixes and technical implementation.
- Coordinate testing timelines and communicate quality risks to Project Managers, who incorporate dependencies into delivery plans and escalate schedule or scope impacts.
- Provide evidence-based quality recommendations; release and risk acceptance decisions remain with the designated product and delivery decision-makers.

---

## DevOps and Site Reliability Engineers

### Role Summary
DevOps and Site Reliability Engineers help teams deliver and operate services safely and reliably. They focus on deployment, infrastructure, observability, and operational preparedness.

### Responsibilities
- Build and maintain delivery pipelines and deployment practices
- Provide reliable infrastructure and appropriate capacity planning
- Establish monitoring, alerting, and service health indicators
- Prepare rollback and recovery procedures and validate operational readiness
- Identify reliability risks and coordinate incident learning

### Goals
- Make releases repeatable, observable, and recoverable
- Maintain service reliability while enabling timely delivery

### Typical Communication
- Pipeline and infrastructure documentation, service dashboards, and runbooks
- Operational readiness reviews and incident or release updates

### Collaboration and Decision Boundaries
- Partner with Developers on build and deployment pipelines, infrastructure needs, and application observability; Developers remain responsible for application behavior and code changes.
- Align with Product Managers on service expectations and customer-impact priorities, and explain reliability trade-offs that may affect scope or timing.
- Work with Project Managers to plan release dependencies, readiness checks, and rollback contingencies; Project Managers coordinate schedules and stakeholder communications.
- Own operational recommendations and platform practices within their remit; product scope and project commitments remain with their respective accountable roles.

---

## Security and Privacy Leads

### Role Summary
Security and Privacy Leads advise teams on protecting systems and personal or sensitive data. They help identify risks and verify that appropriate safeguards and compliance requirements are addressed.

### Responsibilities
- Identify security, privacy, and compliance requirements and risks
- Advise on threat modeling, data handling, access controls, and safeguards
- Review proposed designs and changes for relevant risks
- Validate that agreed controls and mitigations are tracked and tested
- Escalate unresolved risks through the appropriate governance process

### Goals
- Reduce security and privacy exposure throughout the project lifecycle
- Make risks, controls, and residual decisions visible to accountable owners

### Typical Communication
- Risk assessments, review findings, and mitigation tracking
- Design consultations and readiness or compliance reviews

### Collaboration and Decision Boundaries
- Work with Product Managers to clarify data use, customer expectations, and applicable policy requirements; Product Managers own product requirements and prioritization.
- Advise Developers on implementing safeguards and reviewing technical designs; Developers implement the changes and provide evidence of controls.
- Help Project Managers track security and privacy risks, mitigation owners, and decision dates, and escalate unresolved issues. Project Managers coordinate delivery tracking, not risk acceptance.
- Provide specialist assessment and recommendations; exceptions or acceptance of residual risk must be decided by the authorized accountable owner, not assumed by the advisor.

---

## Customer Support and Operations Representatives

### Role Summary
Customer Support and Operations Representatives bring customer-impact and frontline service knowledge into planning and delivery. They help prepare teams to support changes and route feedback after release.

### Responsibilities
- Share recurring customer questions, pain points, and support trends
- Identify support, training, and service-readiness needs for planned changes
- Prepare or review customer-facing guidance and internal support materials
- Coordinate feedback and issue triage after launch
- Surface customer-impacting operational problems to the appropriate owners

### Goals
- Ensure customers and support teams are prepared for changes
- Turn post-release feedback into actionable product and delivery insights

### Typical Communication
- Support guides, FAQs, launch notes, and customer feedback summaries
- Readiness check-ins and post-release issue-triage updates

### Collaboration and Decision Boundaries
- Partner with Product Managers to represent customer needs and feedback; Product Managers decide product priorities and roadmap changes.
- Coordinate with Developers to route actionable defect reports and explain customer impact; Developers investigate and implement technical fixes.
- Work with Project Managers on support readiness, launch communications, and triage coordination; Project Managers manage delivery coordination and stakeholder updates.
- Own support preparation and customer-feedback routing, while product, technical, and release decisions remain with their designated owners.

---

## Applying roles across projects
Role assignments can be combined or tailored to the project's size and needs. Combining roles does not remove any responsibility: teams should name an accountable owner for each decision, deliverable, and risk, and involve specialist roles at the relevant planning, execution, and release points.

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
