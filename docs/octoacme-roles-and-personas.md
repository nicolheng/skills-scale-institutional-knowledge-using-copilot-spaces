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
- Collaborate with **Technical Leads** on architecture and design decisions
- Work with **QA/Test Leads** to define testability requirements and acceptance criteria
- Receive prioritized work and acceptance criteria from **Product Managers**
- Coordinate dependencies and blockers with **Project Managers**
- Receive design specifications and UX feedback from **Designers/UX Leads**

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
- Partner with **Project Managers** on timelines and scope trade-offs
- Engage **Technical Leads** on technical feasibility and architecture trade-offs
- Collaborate with **Designers/UX Leads** on user experience and feature design
- Work with **QA/Test Leads** on quality bar and acceptance criteria
- Report progress and priorities to **Sponsors/Executive Stakeholders**

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
- Coordinate with **Technical Leads** on technical risks and timeline estimates
- Track quality metrics and blockers with **QA/Test Leads**
- Manage dependencies and escalations with **Developers**
- Partner with **Product Managers** on scope, priority, and trade-offs
- Escalate risks and status to **Sponsors/Executive Stakeholders**
- Coordinate with **Release Managers** on deployment schedules and milestones

---

## Technical Leads / Architects

### Role Summary
Technical Leads provide architectural direction, mentor developers, and ensure technical quality. They bridge the gap between product strategy and implementation, making key design decisions and identifying technical risks early.

### Responsibilities
- Define system architecture and technical approach
- Mentor and guide developers on technical best practices
- Conduct architecture and code reviews
- Identify and mitigate technical risks and debt
- Estimate technical effort and feasibility
- Collaborate on technology selection and trade-offs
- Document technical design decisions and rationale

### Goals
- Ensure scalable, maintainable, and performant systems
- Reduce technical debt and risk
- Enable fast, confident delivery
- Build a strong engineering culture

### Typical Communication
- Technical design reviews and architecture discussions
- Code review feedback and mentoring
- Risk assessments and feasibility studies
- Collaboration on sprint planning and estimation

### Interactions with Other Roles
- Guide **Developers** on architecture, design patterns, and technical standards
- Partner with **Product Managers** on technical feasibility and trade-offs
- Work with **QA/Test Leads** on testability, performance, and quality standards
- Coordinate with **Project Managers** on technical timelines and risks
- Support **Release Managers** with deployment planning and technical validation
- Report technical risks and architecture decisions to **Sponsors/Executive Stakeholders** when needed

---

## QA / Test Leads

### Role Summary
QA and Test Leads define quality standards, create test strategies, and ensure features meet acceptance criteria. They partner with developers to build quality into the process rather than testing it in at the end.

### Responsibilities
- Define test strategy and quality standards
- Create and maintain test plans and acceptance criteria
- Lead test design and execution (manual and automated)
- Identify and document defects and quality gaps
- Collaborate on testability requirements during design
- Report quality metrics and trends
- Advocate for quality and regression prevention

### Goals
- Ensure features meet acceptance criteria before release
- Reduce defect escape rate to production
- Build automation and efficiency in testing
- Enable fast, confident deployment

### Typical Communication
- Test plans and acceptance criteria
- Quality reports and defect documentation
- Collaboration on test case design and test automation
- Pre-release quality gates and sign-off

### Interactions with Other Roles
- Partner with **Developers** on testability, test design, and automated testing
- Collaborate with **Product Managers** on acceptance criteria and quality bar
- Support **Technical Leads** on performance and security testing strategies
- Coordinate with **Project Managers** on QA timelines and resource planning
- Work with **Release Managers** on pre-release smoke tests and quality verification
- Report quality metrics to **Sponsors/Executive Stakeholders** for release decisions

---

## Designers / UX Leads

### Role Summary
Designers and UX Leads ensure that solutions are intuitive, accessible, and meet user needs. They own the user experience vision and collaborate closely with product and engineering to deliver usable solutions.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Define interaction patterns and design systems
- Ensure accessibility and usability standards
- Provide design feedback and review
- Collaborate on user flows and information architecture
- Advocate for user needs and usability best practices

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support burden
- Build consistent, delightful interactions
- Enable users to achieve their goals efficiently

### Typical Communication
- Design reviews and feedback sessions
- User research insights and findings
- Design specifications and component documentation
- Usability testing reports and recommendations

### Interactions with Other Roles
- Collaborate with **Product Managers** on user needs, features, and prioritization
- Provide design specifications to **Developers** and support implementation
- Work with **QA/Test Leads** on usability testing and acceptance criteria
- Partner with **Technical Leads** on feasibility and performance trade-offs
- Coordinate with **Project Managers** on design milestones and timelines
- Present user research and design decisions to **Sponsors/Executive Stakeholders**

---

## Release Managers

### Role Summary
Release Managers orchestrate the release process, coordinate deployments, and ensure smooth transitions from development to production. They own the release checklist, deployment coordination, and post-release validation.

### Responsibilities
- Create and maintain release plans and schedules
- Coordinate deployment activities across teams
- Prepare and review release notes and documentation
- Execute deployment procedures and rollback plans
- Verify post-deployment functionality and performance
- Communicate release status and blockers to stakeholders
- Manage release configuration and environment setup
- Track and report on release metrics

### Goals
- Deliver releases on schedule with minimal risk
- Reduce deployment lead time and defect rate
- Maintain production stability and uptime
- Enable rapid, confident deployments

### Typical Communication
- Release notes and deployment plans
- Pre-release checklists and readiness reviews
- Deployment coordination and status updates
- Post-release verification and incident reports

### Interactions with Other Roles
- Coordinate with **Developers** on deployment procedures and rollback plans
- Partner with **QA/Test Leads** on pre-release smoke tests and quality sign-off
- Work with **Project Managers** on release timelines and milestone coordination
- Support **Technical Leads** with deployment validation and performance verification
- Consult with **Product Managers** on feature readiness and release timing
- Notify **Sponsors/Executive Stakeholders** of release status, risks, and go/no-go decisions

---

## Sponsors / Executive Stakeholders

### Role Summary
Sponsors and Executive Stakeholders provide business context, strategic alignment, and approval authority. They champion the project, remove organizational blockers, and ensure alignment with business objectives.

### Responsibilities
- Define business objectives and success criteria
- Provide strategic context and priority alignment
- Approve project scope, budget, and timeline
- Remove organizational and cross-team blockers
- Make escalated decisions on trade-offs and risks
- Communicate project status to broader leadership
- Ensure resource availability and support

### Goals
- Deliver business value aligned with strategy
- Enable teams to succeed through organizational support
- Reduce impediments and accelerate delivery
- Maintain executive visibility and confidence

### Typical Communication
- Monthly stakeholder updates and status reviews
- Executive dashboards and risk escalations
- Approval gates and decision forums
- Cross-team alignment and dependency coordination

### Interactions with Other Roles
- Receive regular updates from **Project Managers** on status, risks, and decisions needed
- Collaborate with **Product Managers** on strategic alignment and prioritization
- Engage **Technical Leads** on architectural decisions and technical debt trade-offs
- Support escalations from **QA/Test Leads** on quality gates and release decisions
- Provide organizational context and priority guidance to the entire project team
- Champion the project to remove cross-functional and organizational blockers

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the "Interactions with Other Roles" sections to understand cross-functional dependencies and communication patterns.
