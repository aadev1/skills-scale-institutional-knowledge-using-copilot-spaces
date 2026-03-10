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

## QA Engineer

### Role Summary
QA Engineers own quality validation across the project lifecycle. They define test strategies, execute test plans, identify defects, and ensure that features meet acceptance criteria before release.

### Responsibilities
- Define and maintain test plans, test cases, and acceptance criteria
- Execute manual and automated testing across unit, integration, and end-to-end levels
- Document, triage, and prioritize defects with severity and reproduction steps
- Validate bug fixes and regression coverage
- Champion testability in design discussions and code reviews
- Ensure security and performance testing are included where applicable

### Goals
- Prevent defects from reaching production
- Maintain high test coverage and reliable CI test suites
- Provide clear quality gates before each release

### Typical Communication
- Sprint planning: clarify acceptance criteria and testability requirements
- Daily standups: flag blocking defects or test environment issues
- PR reviews: verify test coverage and flag missing test cases
- Pre-release sign-off: confirm readiness with PM and Product Manager

### Interactions with Existing Roles
- **Project Manager (PM):** Reports quality status and gate readiness; escalates blocking defects that impact schedule.
- **Product Manager (PdM):** Clarifies acceptance criteria; validates that delivered features meet user expectations.
- **Developers:** Reviews PRs for test coverage; pairs on tricky test scenarios; confirms defect reproduction steps.

---

## UX Designer

### Role Summary
UX Designers create user-centered experiences by translating product goals into intuitive interfaces and interaction flows. They advocate for usability and accessibility throughout the design and development process.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Create wireframes, prototypes, and high-fidelity design specs
- Define and maintain design system components and patterns
- Ensure accessibility standards (e.g., WCAG) are met
- Participate in sprint planning to align design timelines with development
- Review implemented features for design fidelity

### Goals
- Deliver clear, accessible, and delightful user experiences
- Reduce rework by aligning design specs with engineering constraints early
- Ensure usability issues are surfaced and resolved before release

### Typical Communication
- Discovery and planning: share research findings and early wireframes
- Sprint kick-off: hand off finalized specs and answer developer questions
- Design reviews: gather feedback from PM, PdM, and stakeholders
- Post-release: review analytics and user feedback to inform iterations

### Interactions with Existing Roles
- **Project Manager (PM):** Aligns design milestones with project timeline; flags design-related risks or dependencies.
- **Product Manager (PdM):** Translates product goals and user problems into experience requirements; validates designs against success metrics.
- **Developers:** Collaborates closely during implementation to clarify specs and review design fidelity in delivered features.

---

## Security Specialist

### Role Summary
Security Specialists identify, assess, and mitigate security risks across the software lifecycle. They ensure that the team follows secure development practices and that the product meets compliance and security requirements.

### Responsibilities
- Perform threat modeling and security risk assessments
- Integrate security scanning (SAST, DAST, dependency scanning) into CI/CD
- Review code and architecture for security vulnerabilities
- Document security findings, mitigation plans, and remediation status
- Lead security incident response and post-incident reviews
- Educate the team on secure coding practices and emerging threats

### Goals
- Prevent security vulnerabilities from reaching production
- Maintain compliance with relevant security standards and policies
- Ensure rapid, coordinated response to security incidents

### Typical Communication
- Planning: identify security requirements and threat model for new features
- Code reviews: flag vulnerabilities and advise on secure patterns
- Incident response: lead triage, communicate impact, and coordinate remediation
- Regular reports to PM and stakeholders on security posture

### Interactions with Existing Roles
- **Project Manager (PM):** Escalates security incidents and compliance risks that affect scope or timeline; provides input to the risk register.
- **Product Manager (PdM):** Advises on security trade-offs in prioritization decisions; ensures security requirements are captured as acceptance criteria.
- **Developers:** Reviews PRs for security issues; pairs on secure implementations; validates security fixes before closing vulnerabilities.

---

## Customer Success Manager

### Role Summary
Customer Success Managers (CSMs) are the bridge between customers and the product team. They ensure customers achieve value from the product, surface feedback and pain points, and support post-release adoption.

### Responsibilities
- Build and maintain relationships with key customers and stakeholders
- Document and triage common customer issues and feature requests
- Track product adoption trends and report on customer health metrics
- Coordinate with engineering and PM to address critical customer pain points
- Support onboarding and training for new customers
- Represent the customer perspective in backlog refinement and planning

### Goals
- Drive customer satisfaction, retention, and adoption
- Ensure customer feedback is reflected in product priorities
- Reduce time-to-value for new customers

### Typical Communication
- Regular check-ins with key customers to gather feedback and surface issues
- Weekly or bi-weekly syncs with Product Manager and PM on customer health
- Escalation to engineering for urgent customer-impacting defects
- Release notes and customer-facing announcements coordinated with PdM

### Interactions with Existing Roles
- **Project Manager (PM):** Escalates customer-impacting issues that require schedule or scope adjustments; provides input on customer-facing risks.
- **Product Manager (PdM):** Shares customer feedback, usage trends, and pain points to inform roadmap decisions; validates that releases address customer needs.
- **Developers:** Coordinates on reproducing and prioritizing customer-reported defects; communicates fix status back to affected customers.

---

## Engineering Manager / Tech Lead

### Role Summary
Engineering Managers and Tech Leads provide technical leadership and people management. They guide architectural decisions, unblock the team, support developer growth, and act as the primary escalation point for technical issues.

### Responsibilities
- Own architectural decisions and technical standards for the team
- Review and approve significant design changes and technical trade-offs
- Unblock developers on complex technical issues
- Manage team capacity, hiring, and individual developer growth
- Coordinate with PM on technical risks, estimates, and delivery commitments
- Represent engineering in cross-functional planning

### Goals
- Maintain a healthy, productive engineering team
- Deliver technically sound solutions that are maintainable and scalable
- Ensure technical risks are surfaced and addressed early

### Typical Communication
- Regular 1:1s with developers for coaching and unblocking
- Sprint planning and estimation with PM and PdM
- Architecture reviews and technical design sessions
- Escalation bridge between engineering and PM/stakeholders

### Interactions with Existing Roles
- **Project Manager (PM):** Aligns on resource capacity, technical risks, and delivery commitments; escalates technical blockers.
- **Product Manager (PdM):** Advises on technical feasibility and trade-offs during roadmap planning.
- **Developers:** Provides technical mentorship, unblocks complex issues, and owns team standards and practices.

---

## Site Reliability Engineer / DevOps

### Role Summary
Site Reliability Engineers (SREs) and DevOps Engineers maintain the reliability, performance, and operability of production systems. They own CI/CD pipelines, infrastructure, observability, and incident response.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and deployment infrastructure
- Define and monitor SLOs, SLAs, and key reliability metrics
- Respond to production incidents and lead post-incident reviews
- Automate operational tasks to reduce toil and improve scalability
- Collaborate with developers on observability instrumentation (logging, metrics, tracing)
- Manage infrastructure as code and environment provisioning

### Goals
- Maximize system reliability, availability, and performance
- Reduce mean time to detection (MTTD) and mean time to recovery (MTTR)
- Enable fast, safe, and repeatable deployments

### Typical Communication
- On-call rotations and incident response channels
- Release planning: coordinate deployment readiness and rollback plans
- Post-incident reviews with PM, engineering, and stakeholders
- Dashboards and alerts for proactive monitoring

### Interactions with Existing Roles
- **Project Manager (PM):** Provides input on deployment readiness, production risks, and incident impact; escalates infrastructure blockers.
- **Product Manager (PdM):** Advises on observability and reliability requirements; surfaces operational issues affecting the customer experience.
- **Developers:** Partners on observability instrumentation, CI/CD configuration, and production debugging.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

