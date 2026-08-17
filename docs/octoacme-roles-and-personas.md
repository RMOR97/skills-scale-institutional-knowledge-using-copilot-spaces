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

## Design/UX Lead

### Role Summary
Design/UX Leads ensure user-centered design principles guide product decisions and that all interfaces meet usability and accessibility standards. They champion the user experience throughout the product lifecycle.

### Responsibilities
- Conduct user research and validate design concepts with target users
- Create and maintain design systems and component libraries
- Review and approve UI/UX for features entering development
- Ensure accessibility compliance (WCAG standards) across all interfaces
- Collaborate with developers on implementation details and design fidelity
- Participate in design reviews and provide feedback on technical feasibility

### Goals
- Deliver intuitive, accessible user experiences that drive adoption
- Maintain design consistency across the product and all touchpoints
- Reduce rework due to usability issues and accessibility gaps
- Enable faster time-to-market through design best practices

### Interaction with Other Roles
- Works with Product Managers to translate customer needs and business goals into design requirements
- Collaborates with Developers during design review, prototyping, and QA
- Partners with QA/Testing Lead on usability testing and accessibility validation
- Engages with Stakeholders/Sponsors on design direction and major UX decisions

### Typical Communication
- Design review meetings with development and product teams
- Accessibility and usability testing reports
- Design system documentation and component guidelines
- User research findings and design rationale documentation

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads define and execute quality strategies, ensuring features meet acceptance criteria and quality standards before release. They are the primary advocate for quality throughout the project lifecycle.

### Responsibilities
- Define test strategies and comprehensive acceptance criteria
- Build and maintain test automation frameworks and infrastructure
- Conduct manual testing and exploratory testing for complex scenarios
- Track, triage, and manage defects through resolution
- Validate release readiness and coordinate smoke testing
- Partner with developers on test coverage and quality metrics

### Goals
- Minimize bugs and regressions in production environments
- Enable fast, confident releases with measurable quality metrics
- Continuously improve test coverage, automation, and efficiency
- Shift testing left by embedding quality early in the development process

### Interaction with Other Roles
- Works with Product Managers and Developers to clarify and refine acceptance criteria
- Collaborates with Technical Architects on test strategy for complex integrations and systems
- Supports DevOps/Infrastructure Engineers on smoke and deployment testing procedures
- Partners with Design/UX Lead on usability and accessibility testing
- Reports quality metrics and test coverage to Project Managers for risk assessment

### Typical Communication
- Test plan and test case documentation
- Defect reports with reproduction steps and severity assessments
- Quality dashboards and test coverage reports
- Release readiness assessments and validation sign-offs

---

## Technical Architect

### Role Summary
Technical Architects provide strategic technical direction and design oversight to ensure systems are scalable, maintainable, and aligned with organizational standards. They bridge business requirements with technical implementation.

### Responsibilities
- Design system architecture and technical solutions for complex features
- Review and approve technical design decisions and implementations
- Provide guidance on system integration, scalability, and performance
- Identify and mitigate technical risks and architectural debt
- Ensure compliance with technology standards and best practices
- Mentor developers and support technical problem-solving

### Goals
- Deliver scalable, maintainable systems that support future growth
- Reduce technical debt and architectural risks
- Enable consistent technical standards across projects
- Accelerate time-to-market through proven architectural patterns

### Interaction with Other Roles
- Partners with Product Managers on feasibility and trade-off analysis
- Guides Developers on architectural decisions and design patterns
- Collaborates with QA/Testing Lead on test strategy for complex integrations
- Works with DevOps/Infrastructure Engineers on deployment architecture and infrastructure requirements
- Reports technical risks and architectural decisions to Project Managers

### Typical Communication
- Architecture design documents and technical specifications
- Design reviews and technical feasibility assessments
- Architecture decision records (ADRs) documenting key technical choices
- Technical risk assessments and mitigation plans

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors are executive or business owners who approve scope, budget, and high-level decisions. They represent business interests and provide strategic direction and support for projects.

### Responsibilities
- Approve project charter, scope, and key milestones
- Allocate budget and resources for project execution
- Provide business context and strategic alignment
- Escalate and resolve business-level blockers and conflicts
- Validate that delivered solutions meet business objectives
- Support change management and stakeholder engagement

### Goals
- Ensure projects deliver measurable business value and ROI
- Maintain strategic alignment across organizational initiatives
- Enable faster decision-making by removing business-level obstacles
- Maximize stakeholder satisfaction and adoption

### Interaction with Other Roles
- Partners with Project Managers on scheduling, scope changes, and escalations
- Engages with Product Managers on business objectives and success metrics
- Reviews and approves major technical and design decisions through Project Managers
- Provides executive visibility and support to unblock dependencies

### Typical Communication
- Project charter and business case reviews
- Monthly or milestone-based status reports
- Scope change and decision approval communications
- Stakeholder briefings and announcement of major milestones

---

## DevOps/Infrastructure Engineer

### Role Summary
DevOps/Infrastructure Engineers manage deployment pipelines, infrastructure as code, and production operations. They ensure systems are reliable, scalable, and maintainable in production environments.

### Responsibilities
- Design and maintain deployment pipelines and CI/CD infrastructure
- Implement infrastructure as code (IaC) for reproducible environments
- Monitor system performance, availability, and security in production
- Manage production incidents and coordinate incident response
- Document runbooks and operational procedures for on-call support
- Collaborate with developers on deployment strategies and infrastructure requirements

### Goals
- Enable fast, reliable deployments to production
- Maintain high system availability and performance
- Reduce operational overhead through automation and self-service tools
- Support scalability and resilience of systems

### Interaction with Other Roles
- Works with Developers on deployment strategies and infrastructure requirements
- Supports QA/Testing Lead on smoke testing and deployment validation
- Partners with Technical Architects on infrastructure design and scalability planning
- Coordinates with Project Managers on deployment scheduling and release windows
- Collaborates with Security/Compliance Officer on security controls and compliance

### Typical Communication
- Deployment and runbook documentation
- Infrastructure design and capacity planning documents
- Production monitoring dashboards and alerts
- Post-incident reports and operational metrics

---

## Security/Compliance Officer

### Role Summary
Security/Compliance Officers ensure security requirements, compliance standards, and risk mitigation are embedded throughout the project lifecycle. They protect organizational assets and ensure adherence to regulatory and policy requirements.

### Responsibilities
- Define security requirements and threat modeling for features
- Review code and designs for security vulnerabilities
- Ensure compliance with regulatory requirements and policies
- Conduct security assessments and penetration testing
- Manage security incidents and coordinate remediation
- Maintain security documentation and audit trails

### Goals
- Prevent security breaches and data loss
- Ensure compliance with regulations (GDPR, HIPAA, SOC 2, etc.)
- Minimize organizational risk and liability
- Enable secure, trustworthy product delivery

### Interaction with Other Roles
- Engages with Product Managers on security and compliance requirements early in planning
- Reviews Developers' code and architecture with security lens
- Works with Technical Architects on security-by-design principles
- Partners with DevOps/Infrastructure Engineers on security controls and monitoring
- Advises Project Managers and Stakeholders/Sponsors on security risks and compliance implications

### Typical Communication
- Security requirements and threat models
- Security assessment and code review findings
- Compliance audit reports and remediation plans
- Security incident response and post-mortems

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference interaction patterns to understand cross-functional collaboration and dependencies.
