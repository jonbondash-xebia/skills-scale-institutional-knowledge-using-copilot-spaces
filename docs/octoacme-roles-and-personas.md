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

## Engagement Lead

### Role Summary
Engagement Leads serve as primary liaisons for external stakeholders and cross-team programs (sales, customers, partner teams). They bridge organizational boundaries and ensure alignment between project outcomes and stakeholder expectations.

### Responsibilities
- Coordinate stakeholder expectations and gather requirements from external parties
- Manage communications for scope or timeline changes
- Own stakeholder sign-offs and facilitate demo scheduling
- Maintain stakeholder communication plans and update cadence
- Escalate business-impacting issues to sponsors and executive stakeholders
- Track and communicate on customer/partner commitments

### Goals
- Maximize stakeholder satisfaction and alignment
- Reduce scope creep through clear communication and expectation management
- Enable faster decision-making through clear escalation paths
- Strengthen relationships with key external partners and customers

### Interactions
- Works closely with Product Manager and Project Manager for prioritization and scheduling
- Collaborates with Developers and QA during demos and acceptance reviews
- Escalates sponsor-level issues to executive leadership when needed
- Coordinates with Support Lead for post-release customer communications

### Typical Communication
- Stakeholder kick-off meetings and regular syncs
- Status updates and change impact communications
- Demo facilitation and feedback synthesis
- Executive briefings and escalation reports

---

## Delivery Engineer

### Role Summary
Delivery Engineers specialize in deployment, CI/CD infrastructure, reliability, and operational excellence. They ensure projects move smoothly from development to production with minimal risk and maximum observability.

### Responsibilities
- Maintain and improve deployment pipelines and CI/CD infrastructure
- Own release automation and deployment runbooks
- Create and maintain rollback and incident recovery plans
- Assist teams with production troubleshooting and support runbooks
- Ensure deployments meet security and compliance standards
- Monitor deployment metrics and optimize release cycles

### Goals
- Reduce mean time to deployment and recovery
- Minimize production incidents and improve mean time to resolution
- Enable safe, repeatable releases with high confidence
- Maintain high observability and alerting for production systems

### Interactions
- Collaborates with Developers during sprint planning and release preparation
- Works with QA on test automation and staging environment management
- Coordinates with Project Manager on release scheduling and timelines
- Partners with Security Liaison for compliance checks and secure deployments
- Supports Support Lead with troubleshooting tools and runbooks

### Typical Communication
- Release planning meetings and deployment windows
- Runbook documentation and incident post-mortems
- CI/CD pipeline status and improvement proposals
- Cross-team incident response coordination

---

## UX Researcher

### Role Summary
UX Researchers ensure projects deliver user-centered solutions by validating assumptions through qualitative and quantitative research. They bridge the gap between user needs and product delivery.

### Responsibilities
- Conduct user research (interviews, testing, surveys) to validate assumptions
- Synthesize research findings into actionable insights
- Validate acceptance criteria from a usability and user experience perspective
- Provide design recommendations based on user feedback
- Participate in backlog refinement and acceptance criteria definition
- Track and report on usability metrics and user satisfaction

### Goals
- Ensure solutions meet user needs and usability standards
- Reduce rework through early validation of designs
- Increase product adoption and user satisfaction
- Make data-informed design decisions

### Interactions
- Partners with Product Manager on research planning and metrics definition
- Collaborates with Developers during design reviews and technical discussions
- Works with QA on acceptance criteria validation and edge cases
- Provides user insights to Engagement Lead for stakeholder communications
- Shares findings in sprint planning and retrospectives

### Typical Communication
- User research plans and findings reports
- Acceptance criteria validation feedback
- Design review sessions and usability test results
- Sprint planning insights and retrospective contributions

---

## Data Analyst / Observability Lead

### Role Summary
Data Analysts and Observability Leads define and implement the metrics, dashboards, and instrumentation needed to measure project success. They provide data-driven insights to support decision-making throughout the project lifecycle.

### Responsibilities
- Define success metrics aligned with project goals
- Ensure proper instrumentation and telemetry in code and systems
- Create dashboards and reports for key signals and health indicators
- Develop runbooks for data triage and issue diagnosis
- Assist in troubleshooting production issues using data and logs
- Provide reporting for project dashboards and stakeholder reviews

### Goals
- Enable data-driven decision-making and course correction
- Provide early warning of issues through proactive monitoring
- Increase observability and mean time to diagnosis
- Quantify project success and impact

### Interactions
- Works with Product Manager to define success metrics and measure impact
- Collaborates with Developers on instrumentation implementation
- Supports Project Manager with reporting and metrics dashboards
- Assists Support Lead with production issue diagnosis and root cause analysis
- Provides insights to Engagement Lead for stakeholder reporting

### Typical Communication
- Metrics definition sessions and success criteria alignment
- Dashboard reviews and data-driven insights
- Incident analysis and post-mortem findings
- Weekly reporting to Project Manager and stakeholder reviews

---

## Support Lead

### Role Summary
Support Leads own the post-release support experience and customer issue triage. They are the frontline for customer-facing problems and coordinate fixes with the delivery team.

### Responsibilities
- Own escalation path for customer-reported issues and bugs
- Maintain support runbooks and troubleshooting guides
- Coordinate bug fixes and feature requests with Developers
- Track and communicate issue status to stakeholders and customers
- Identify trends in customer issues and escalate systemic problems
- Provide feedback to Product Manager on customer pain points

### Goals
- Minimize customer impact and reduce mean time to resolution
- Proactively identify and escalate product gaps and issues
- Maintain high customer satisfaction and confidence
- Enable faster issue resolution through clear escalation and coordination

### Interactions
- Coordinates closely with Delivery Engineer for production issue diagnosis and fixes
- Works with Developers on bug prioritization and hotfix deployment
- Collaborates with Project Manager on issue tracking and reporting
- Communicates with Engagement Lead for customer-facing communications
- Provides insights to Product Manager for backlog prioritization

### Typical Communication
- Customer issue tracking and status updates
- Support runbooks and troubleshooting documentation
- Bug reports and fix coordination with Developers
- Trend analysis and retrospective findings
- Customer satisfaction and escalation communications

---

## Security Liaison

### Role Summary
Security Liaisons serve as the focal point for security and compliance concerns throughout the project lifecycle. They ensure projects meet security standards and compliance requirements.

### Responsibilities
- Perform security checklists and reviews at key project gates
- Coordinate security scans and penetration testing
- Ensure vulnerabilities are tracked, prioritized, and remediated
- Advise on compliance requirements and controls
- Review and validate secure coding practices
- Maintain security documentation and runbooks

### Goals
- Prevent security incidents and data breaches
- Ensure compliance with regulatory and organizational standards
- Reduce security-related rework and delays
- Build a security-first culture within the team

### Interactions
- Works with Delivery Engineer for secure deployment pipelines and infrastructure reviews
- Collaborates with Developers on secure coding practices and vulnerability remediation
- Notifies Project Manager and Product Manager of security risks and required mitigations
- Coordinates with QA on security testing and validation
- Provides guidance to Engagement Lead for customer security communications

### Typical Communication
- Security review findings and remediation plans
- Vulnerability assessments and patch coordination
- Secure deployment checklists and pre-release reviews
- Compliance documentation and audit support
- Security incident response and post-mortem participation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Extended personas (Engagement Lead, Delivery Engineer, UX Researcher, Data Analyst/Observability Lead, Support Lead, Security Liaison) clarify ownership for cross-cutting activities and reduce handoff friction.
