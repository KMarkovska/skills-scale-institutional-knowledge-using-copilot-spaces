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

## Delivery Lead

### Role Summary
Delivery Leads coordinate day-to-day execution across delivery teams, manage sprint commitments, remove operational blockers, and own cross-team dependencies. They are the connective tissue between strategic planning and tactical execution.

### Responsibilities
- Coordinate daily standups and remove blockers
- Manage sprint commitments and track progress toward milestones
- Own cross-team dependencies and escalate risks early
- Facilitate communication between product, engineering, and operations
- Track and communicate delivery metrics (velocity, burndown, cycle time)

### Goals
- Ensure on-time delivery of committed work
- Minimize blocked or idle time across the team
- Maintain clear visibility and communication across stakeholders
- Build predictable, repeatable delivery cadence

### Typical Communication
- Daily standups and progress tracking
- Weekly delivery reviews with stakeholders
- Dependency and risk escalations
- Metrics dashboards and status reports

### Interaction with Other Roles
Works closely with **Product Managers** on prioritization and scope, **Project Managers** on planning and risk management, and **Developers** on execution and blockers.

---

## Engineering Manager

### Role Summary
Engineering Managers are responsible for people management, capacity planning, and technical decision-making. They mentor and develop Developers, prioritize technical debt, and ensure team growth and well-being.

### Responsibilities
- Lead and mentor Developers on technical growth and career development
- Conduct performance reviews and career planning discussions
- Plan team capacity and staffing for projects
- Prioritize technical debt and refactoring work
- Identify and remove systemic blockers to productivity

### Goals
- Build a high-performing, engaged engineering team
- Balance delivery velocity with technical health
- Develop strong technical leaders from within the team
- Reduce attrition and improve team satisfaction

### Typical Communication
- One-on-one meetings with direct reports
- Team retrospectives and process improvements
- Technical debt prioritization discussions
- Capacity and staffing planning with Project Managers

### Interaction with Other Roles
Mentors **Developers**, escalates resource and staffing needs to **Project Managers** and **Product Managers**, and collaborates with **Delivery Leads** on team capacity.

---

## UX Researcher / Designer

### Role Summary
UX Researchers and Designers lead user research, design solutions for usability and customer delight, and validate that features meet both functional and user experience acceptance criteria.

### Responsibilities
- Conduct user research and gather user insights
- Design user interfaces and user experiences
- Create wireframes, prototypes, and design specifications
- Validate designs with users and stakeholders
- Ensure accessibility and usability standards are met
- Review and approve UX acceptance criteria before development

### Goals
- Deliver products that users love and find intuitive
- Reduce support burden through great UX design
- Build customer loyalty through excellent experiences
- Ensure inclusive, accessible experiences for all users

### Typical Communication
- Design reviews with Developers and Product Managers
- User research presentations and findings
- Accessibility and usability checklists in acceptance criteria
- Design system documentation and guidelines

### Interaction with Other Roles
Collaborates with **Product Managers** during planning and scoping, **Developers** during implementation and reviews, and **QA** during acceptance testing.

---

## Support Liaison

### Role Summary
Support Liaisons represent the voice of customer support and end-users within the delivery team. They triage user-reported issues, communicate customer impact, and ensure workarounds or fixes are prioritized appropriately.

### Responsibilities
- Gather and communicate customer support feedback
- Triage and prioritize user-reported issues and bugs
- Provide customer context and impact assessment for decisions
- Communicate feature changes and workarounds to support team
- Participate in incident response and customer communication

### Goals
- Reduce customer frustration and support burden
- Enable the team to understand real-world impact of decisions
- Improve response time to critical customer issues
- Build customer trust through rapid resolution

### Typical Communication
- Weekly summary of top customer issues and requests
- User impact assessments during planning and prioritization
- Release notes and customer communication guidance
- Post-incident reviews and retrospectives

### Interaction with Other Roles
Coordinates with **Product Managers** for prioritization, **Developers** for issue triage and fixes, and **Release Coordinators** for deployment and customer communication.

---

## Security Reviewer / Security SME

### Role Summary
Security Reviewers and Security Subject Matter Experts (SMEs) perform threat modeling, conduct security reviews of design and code, and ensure security standards are met before release. They act as advisors and gatekeepers for security compliance.

### Responsibilities
- Perform threat modeling during planning phase
- Conduct security reviews of design and architecture
- Review code for security vulnerabilities before merge
- Ensure security scanning tools are configured and results addressed
- Sign off on releases when security requirements are met
- Advise on security best practices and standards compliance

### Goals
- Prevent security vulnerabilities from reaching production
- Build security awareness and practices across the team
- Ensure compliance with organizational and regulatory requirements
- Reduce security incident risk and exposure

### Typical Communication
- Design and code review comments with security guidance
- Security assessment reports and risk ratings
- Threat modeling sessions during planning
- Pre-release security sign-off and clearance

### Interaction with Other Roles
Advisory role for **Developers** during implementation, **Product Managers** during planning, and **Release Coordinators** during pre-release approval.

---

## Release Coordinator

### Role Summary
Release Coordinators plan and execute release windows, own the release checklist, manage rollback plans, and coordinate all stakeholders involved in deployments. They ensure releases are smooth, well-communicated, and reversible if needed.

### Responsibilities
- Plan release windows and deployment schedules
- Prepare and execute release checklists (pre-release, deploy, post-deploy)
- Coordinate with infrastructure / DevOps teams on deployment
- Document rollback procedures and mitigation plans
- Communicate release status and changes to stakeholders
- Conduct post-release verification and monitoring
- Facilitate incident response if a release causes issues

### Goals
- Execute releases smoothly with minimal downtime or issues
- Maintain clear communication with all stakeholders
- Enable rapid rollback if critical issues are discovered
- Build confidence in the deployment process

### Typical Communication
- Release plan and change log
- Deployment status updates and timelines
- Post-release verification reports
- Rollback and incident communications

### Interaction with Other Roles
Works with **Delivery Lead** on scheduling and coordination, **Developers** on build and deployment, **QA** on smoke testing, **Support Liaison** on customer communication, and **Security Reviewer** on pre-release approval.

---

## When to Engage Each Persona

### Planning Phase
- **Product Manager**: Define scope, success metrics, and acceptance criteria
- **UX Researcher / Designer**: Understand user needs and design solutions
- **Engineering Manager**: Assess team capacity and identify staffing needs
- **Security Reviewer**: Perform threat modeling and identify security requirements
- **Project Manager**: Create timeline and identify dependencies

### Execution Phase
- **Developers**: Build and test features
- **Delivery Lead**: Remove blockers and coordinate daily execution
- **UX Researcher / Designer**: Validate designs and user acceptance
- **QA**: Execute test plan and validate acceptance criteria
- **Engineering Manager**: Support team and resolve technical obstacles

### Pre-Release Phase
- **QA**: Final acceptance testing and smoke tests
- **Security Reviewer**: Security sign-off
- **Release Coordinator**: Prepare release checklist and rollback plan
- **Support Liaison**: Prepare customer communication and release notes
- **Project Manager**: Confirm readiness and stakeholder alignment

### Release & Post-Release Phase
- **Release Coordinator**: Execute deployment and monitor
- **Developers**: On-call for hotfixes
- **Support Liaison**: Communicate with customers and support team
- **Security Reviewer**: Monitor for security incidents
- **Delivery Lead**: Track any issues and coordinate rapid response

### Incident Response
- **Support Liaison**: Gather customer impact and communicate status
- **Developers**: Triage and fix critical issues
- **Release Coordinator**: Plan hotfix release and rollback if needed
- **Security Reviewer**: Assess security impact if applicable
- **Project Manager / Delivery Lead**: Escalate and coordinate response

---

## Responsibility Matrix

| Responsibility | Developer | PM | PdM | PM | Delivery Lead | Eng Mgr | UX/Design | Support | Security | Release |
|---|---|---|---|---|---|---|---|---|---|---|
| Implement features | ✓ | | | | | | | | | |
| Define scope & success metrics | | ✓ | ✓ | | | | | | | |
| Design UX and validate usability | | | | | | | ✓ | | | |
| Conduct user research | | | | | | | ✓ | | | |
| Review code for quality | ✓ | | | | | | | | | |
| Review code for security | | | | | | | | | ✓ | |
| Manage team and capacity | | | | ✓ | | ✓ | | | | |
| Coordinate daily execution | | | | | ✓ | | | | | |
| Represent customer voice | | | | | | | | ✓ | | |
| Plan and execute releases | | | | | | | | | | ✓ |
| Perform threat modeling | | | | | | | | | ✓ | |
| Approve pre-release | | | | ✓ | | | | | ✓ | ✓ |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the "When to Engage Each Persona" section to understand appropriate involvement in each project phase.
