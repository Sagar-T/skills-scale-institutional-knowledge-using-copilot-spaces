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

### Interactions with Other Roles
- Work with **Technical Lead** on architectural guidance and code quality standards
- Collaborate with **QA/Testing Lead** on acceptance criteria and test plans
- Coordinate with **DevOps/Release Engineer** on CI/CD pipeline and deployment processes
- Receive feature specifications and acceptance criteria from **Product Manager**

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

### Interactions with Other Roles
- Align with **Stakeholder/Sponsor** on business requirements and priority
- Work with **Project Manager** on roadmap and release planning
- Define acceptance criteria for **Developers** and **QA/Testing Lead**
- Report success metrics and outcomes to **Stakeholder/Sponsor**

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

### Interactions with Other Roles
- Partner with **Product Manager** on planning, scheduling, and roadmap execution
- Coordinate with **Technical Lead** on technical risks and architectural decisions
- Work with **QA/Testing Lead** on test planning and release readiness
- Escalate blockers and risks to **Stakeholder/Sponsor**
- Facilitate communication across all roles during sprints and releases

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality assurance strategy, test planning, and validation of acceptance criteria. They collaborate with developers and product teams to ensure features meet quality standards before release.

### Responsibilities
- Define and execute test plans aligned with project requirements
- Validate acceptance criteria and definition of done
- Identify quality risks and propose mitigations
- Coordinate manual and automated testing efforts
- Report quality metrics and test coverage
- Participate in release readiness reviews
- Work with **DevOps/Release Engineer** to define smoke tests and deployment verification procedures

### Goals
- Prevent defects from reaching production
- Enable fast, reliable releases with confidence
- Maintain high test coverage and quality standards

### Typical Communication
- Sprint planning and definition of done discussions
- Test plan reviews with Developers and Product Manager
- Quality metrics and test coverage reports
- Release readiness assessments

### Interactions with Other Roles
- Partner with **Developers** on test strategy, automation, and acceptance criteria
- Align with **Product Manager** on feature acceptance criteria and success metrics
- Support **Project Manager** with quality risks and release readiness status
- Collaborate with **DevOps/Release Engineer** on automated testing integration
- Report quality findings to **Stakeholder/Sponsor** as needed

---

## Technical Lead/Architect

### Role Summary
Technical Leads own technical design decisions, code quality standards, and architectural guidance. They mentor developers and ensure solutions align with long-term technical strategy.

### Responsibilities
- Design technical solutions and architecture for features
- Review technical designs and code quality
- Identify technical risks and propose mitigations
- Mentor developers on best practices
- Guide technology choices and platform decisions
- Participate in planning and estimation
- Define code review standards and technical excellence criteria

### Goals
- Ensure scalable, maintainable technical solutions
- Reduce technical debt and rework
- Enable sustainable delivery pace

### Typical Communication
- Technical design reviews and architecture discussions
- Code review feedback and mentoring
- Technical risk discussions in planning and retrospectives
- Technology strategy alignment

### Interactions with Other Roles
- Guide **Developers** on architectural decisions and code quality standards
- Support **Project Manager** with technical risk identification and mitigation planning
- Collaborate with **DevOps/Release Engineer** on infrastructure and deployment architecture
- Provide input to **Product Manager** on technical feasibility and timeline implications
- Mentor all technical team members on best practices and continuous improvement

---

## Stakeholder/Sponsor

### Role Summary
Sponsors provide business context, funding, and executive support for projects. They approve scope and timeline trade-offs and escalate blockers that require organizational intervention.

### Responsibilities
- Define business requirements and success criteria
- Approve project charter and resource allocation
- Provide funding and executive support
- Resolve escalated blockers and conflicts
- Receive and act on project status reports
- Communicate project value to broader organization
- Approve major scope changes and trade-offs

### Goals
- Ensure projects deliver measurable business value
- Remove organizational barriers to delivery
- Maintain strategic alignment

### Typical Communication
- Monthly stakeholder updates and business reviews
- Decision-making on scope and priority trade-offs
- Escalation resolution meetings
- Executive status and outcome reporting

### Interactions with Other Roles
- Set business direction and success criteria with **Product Manager**
- Receive project status and risk updates from **Project Manager**
- Approve resource and timeline trade-offs recommended by **Project Manager**
- Review outcome metrics and success validation from **Product Manager** and **QA/Testing Lead**
- Support team by removing organizational blockers identified by **Project Manager**

---

## DevOps/Release Engineer

### Role Summary
DevOps Engineers own deployment pipelines, infrastructure, and release automation. They enable safe, repeatable releases to production and maintain system reliability.

### Responsibilities
- Build and maintain CI/CD pipelines
- Manage infrastructure and environments (staging, production)
- Automate testing, security scanning, and deployment
- Plan and execute releases
- Monitor deployment health and support rollbacks
- Document runbooks and incident procedures
- Define deployment checklists and pre-release requirements

### Goals
- Enable fast, safe, automated releases
- Minimize deployment risk and downtime
- Maintain high availability and observability

### Typical Communication
- Release planning and deployment coordination meetings
- CI/CD pipeline status and automation improvements
- Incident response and post-mortem discussions
- Infrastructure and deployment runbooks

### Interactions with Other Roles
- Work with **Developers** on CI/CD integration and testing automation
- Support **QA/Testing Lead** with automated testing infrastructure and smoke test definition
- Coordinate with **Project Manager** on release planning and deployment windows
- Support **Technical Lead** on infrastructure architecture and deployment strategy
- Report deployment health and incident status to **Project Manager** and **Stakeholder/Sponsor**

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Understanding cross-functional interactions helps teams identify communication gaps and dependency management opportunities.
