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

### Key Interactions
- **With QA Lead**: Collaborate on test strategy, provide test environments, discuss defect triage
- **With UX Designer**: Implement UI/UX specifications, provide technical feasibility feedback
- **With DevOps Engineer**: Coordinate on deployment readiness, infrastructure requirements, CI/CD pipeline updates
- **With Product Manager**: Clarify acceptance criteria, estimate effort, discuss trade-offs
- **With Security Lead**: Incorporate security requirements, discuss implementation security concerns, participate in threat reviews

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

### Key Interactions
- **With UX Designer**: Validate user flows, define requirements, gather user feedback
- **With Business Analyst**: Clarify business requirements, refine backlog items
- **With QA Lead**: Define acceptance criteria and quality gates
- **With Stakeholders**: Communicate progress, validate direction, gather feedback
- **With Data Analyst**: Review metrics and insights to inform prioritization, validate success metrics
- **With Customer Support Liaison**: Gather customer feedback and pain points to inform roadmap decisions

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

### Key Interactions
- **With Product Manager**: Align on priorities, dependencies, and release timing
- **With DevOps Engineer**: Coordinate deployment windows, manage release schedules
- **With Stakeholders**: Provide status updates, escalate blockers, manage expectations
- **With Business Analyst**: Ensure scope clarity and requirement refinement
- **With Security Lead**: Manage security review timelines and incident escalations
- **With Data Analyst**: Track project metrics and success indicators

---

## QA Lead

### Role Summary
QA Leads oversee quality assurance strategy and execution. They coordinate manual and automated testing efforts, establish quality gates, and ensure acceptance criteria are met before release.

### Responsibilities
- Define and maintain test strategy and test plans
- Coordinate manual and automated testing efforts
- Establish quality gates and acceptance criteria thresholds
- Triage and track defects, communicate risk to the team
- Collaborate with developers on test environment setup
- Validate release readiness before deployment

### Goals
- Ensure high-quality releases that meet customer expectations
- Minimize production defects and customer-impacting issues
- Reduce time spent on rework and regression testing through effective test automation
- Provide clear, actionable feedback on quality risks

### Typical Communication
- Daily status on test coverage and defect tracking
- Test plans and quality gate reports
- Release readiness assessments
- Defect triage and root cause discussions

### Key Interactions
- **With Developers**: Collaborate on test strategy, provide feedback on testability, triage defects
- **With Product Manager**: Clarify acceptance criteria and quality expectations
- **With DevOps Engineer**: Coordinate test environment provisioning and automation infrastructure
- **With UX Designer**: Validate user-facing functionality, ensure UX compliance in testing
- **With Security Lead**: Incorporate security test cases, validate security compliance

---

## UX Designer

### Role Summary
UX Designers create user-centered designs and ensure the product is usable, accessible, and aligned with user needs. They provide design specifications and collaborate throughout implementation to maintain design integrity.

### Responsibilities
- Conduct user research and define user flows
- Create wireframes, prototypes, and detailed design specifications
- Ensure accessibility and usability standards are met
- Collaborate with developers on implementation feasibility
- Provide design assets and style guides
- Validate final implementation against design specifications

### Goals
- Deliver intuitive, accessible, and engaging user experiences
- Reduce user friction and support burden through good design
- Align product experience with user needs and business goals
- Support rapid iteration through collaborative prototyping

### Typical Communication
- Design specifications and style guides
- Prototype walkthroughs and feedback sessions
- Accessibility compliance reviews
- Design rationale and user research findings

### Key Interactions
- **With Product Manager**: Align on user requirements, validate problem statement, gather user feedback
- **With Developers**: Discuss technical feasibility, review implementation, iterate on designs
- **With QA Lead**: Define UX acceptance criteria, validate user flows in testing
- **With Stakeholders**: Present design concepts, gather feedback on direction
- **With Customer Support Liaison**: Gather user experience feedback and pain points from support interactions

---

## DevOps Engineer

### Role Summary
DevOps Engineers maintain and improve deployment infrastructure, CI/CD pipelines, and production environments. They enable reliable, repeatable releases and support the team's operational requirements.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage and monitor production, staging, and development environments
- Ensure infrastructure security and compliance
- Support deployment readiness and execute releases
- Plan and test rollback procedures
- Monitor application health and resolve operational issues
- Anticipate infrastructure risks and recommend mitigations

### Goals
- Enable fast, reliable, and repeatable deployments
- Minimize deployment failures and production incidents
- Reduce operational overhead through automation
- Ensure infrastructure supports team and business needs

### Typical Communication
- Environment and pipeline status updates
- Deployment runbooks and release procedures
- Infrastructure capacity and performance metrics
- Incident response and post-incident reviews

### Key Interactions
- **With Developers**: Support deployment readiness, provide infrastructure feedback, troubleshoot deployment issues
- **With Project Manager**: Coordinate deployment windows, manage release schedules
- **With QA Lead**: Provision test environments, support test automation infrastructure
- **With Release team**: Ensure rollback plans are tested and documented
- **With Security Lead**: Implement infrastructure security controls, respond to security incidents

---

## Business Analyst

### Role Summary
Business Analysts bridge business goals and technical execution. They clarify requirements, support backlog refinement, and ensure that proposed solutions are aligned with business needs and technically feasible.

### Responsibilities
- Gather and document business requirements
- Support backlog refinement and user story creation
- Ensure requirements are clear, testable, and actionable
- Analyze trade-offs between business needs and technical constraints
- Support scope management and change control
- Validate that delivered solutions meet business objectives

### Goals
- Ensure alignment between business needs and technical delivery
- Reduce rework and scope creep through clear requirements
- Enable the team to make informed trade-off decisions
- Support effective communication between business and technical teams

### Typical Communication
- Requirements documentation and user stories
- Scope analysis and impact assessments
- Backlog refinement notes and acceptance criteria
- Trade-off analysis and decision logs

### Key Interactions
- **With Product Manager**: Clarify and refine backlog items, validate business value
- **With Developers**: Ensure requirements are actionable and testable, discuss feasibility
- **With Stakeholders**: Gather requirements and validate solutions meet business needs
- **With Project Manager**: Support scope management and change control
- **With Data Analyst**: Incorporate data requirements and metrics into business requirements

---

## Stakeholder

### Role Summary
Stakeholders represent customer, user, or business interests in the project. They provide requirements, feedback, and validation throughout the project lifecycle and benefit from the delivered solutions.

### Responsibilities
- Communicate business needs and success criteria
- Provide feedback on prototypes, designs, and releases
- Participate in acceptance testing and sign-off
- Monitor project progress and escalate concerns
- Champion the project and support adoption

### Goals
- Ensure the delivered solution meets business and user needs
- Maintain transparency and alignment on project progress
- Reduce risk of delivering solutions that miss the mark
- Enable rapid feedback and iteration

### Typical Communication
- Requirements and success criteria inputs
- Feedback on designs, prototypes, and releases
- Progress and status review meetings
- Acceptance testing and sign-off communications

### Key Interactions
- **With Product Manager**: Define requirements and success metrics, provide user feedback
- **With Project Manager**: Receive status updates, escalate concerns, participate in reviews
- **With UX Designer**: Provide design feedback and validate user experience
- **With QA Lead**: Participate in acceptance testing and release validation
- **With Customer Support Liaison**: Share customer feedback and adoption concerns

---

## Security Lead

### Role Summary
Security Leads advise on security requirements, threat modeling, and incident coordination. They ensure that projects incorporate security best practices, compliance requirements, and risk mitigation strategies from the beginning of development through deployment and operation.

### Responsibilities
- Define security requirements and acceptance criteria for features
- Conduct threat modeling and security architecture reviews
- Advise on secure coding practices and vulnerability remediation
- Coordinate security testing and penetration testing efforts
- Lead incident response and post-incident analysis
- Monitor and report on security compliance and risk posture
- Provide security training and guidance to development teams

### Goals
- Minimize security vulnerabilities and breaches
- Ensure compliance with relevant security standards and regulations
- Build security awareness and practices across the team
- Enable rapid, secure incident response and recovery
- Balance security requirements with delivery timelines

### Typical Communication
- Security requirements and threat models
- Vulnerability reports and remediation guidance
- Compliance and audit documentation
- Incident alerts and post-mortem analysis
- Security training and awareness updates

### Key Interactions
- **With Developers**: Review code for security issues, advise on secure implementation, discuss vulnerability fixes
- **With Product Manager**: Define security success metrics, prioritize security features and fixes
- **With Project Manager**: Manage security review timelines, escalate critical vulnerabilities
- **With QA Lead**: Define security test cases, validate security compliance before release
- **With DevOps Engineer**: Implement infrastructure security controls, respond to security incidents
- **With Stakeholders**: Report on security posture, compliance status, and risk mitigation progress

---

## Customer Support Liaison

### Role Summary
Customer Support Liaisons bridge the gap between customer support teams and product development. They surface user pain points, relay customer feedback, and ensure that customer issues inform product decisions and improvements.

### Responsibilities
- Gather and synthesize customer feedback from support interactions
- Surface recurring issues, feature requests, and pain points to the product team
- Participate in customer calls and support ticket triage
- Help prioritize defects based on customer impact and frequency
- Provide customer context and real-world use cases to developers
- Track customer satisfaction and support metrics
- Validate solutions with customers before and after release

### Goals
- Reduce customer support volume through better product design
- Ensure product decisions are informed by real customer needs
- Improve customer satisfaction and retention
- Accelerate time-to-resolution for critical customer issues
- Build stronger customer relationships and advocacy

### Typical Communication
- Customer feedback summaries and trends
- Customer support metrics and dashboards
- Feature requests and defect priority recommendations
- Customer testimonials and case studies
- Post-release customer feedback and validation

### Key Interactions
- **With Product Manager**: Share customer feedback to inform roadmap and prioritization, discuss feature gaps
- **With Developers**: Provide customer context for bugs and features, help validate solutions
- **With UX Designer**: Share customer experience feedback and usability concerns
- **With QA Lead**: Advocate for customer-critical test scenarios, validate fixes with customers
- **With Stakeholders**: Report on customer satisfaction, adoption challenges, and business impact

---

## Data Analyst

### Role Summary
Data Analysts drive metrics definition, data collection, and insight generation to support decision-making. They work across the team to establish success metrics, analyze product performance, and inform strategic and tactical decisions with data-driven evidence.

### Responsibilities
- Define and instrument success metrics for projects and features
- Establish data collection and analytics infrastructure
- Analyze product usage, performance, and business metrics
- Generate insights and reports to inform prioritization and strategy
- Support A/B testing and experimentation efforts
- Track project health indicators and KPIs
- Document data definitions and analytical approaches for team alignment

### Goals
- Enable data-driven decision-making across the organization
- Provide clear visibility into product performance and customer behavior
- Accelerate learning from releases and experiments
- Support business case validation and ROI measurement
- Build data literacy and analytical capability across teams

### Typical Communication
- Metrics dashboards and KPI reports
- Data-driven insights and recommendations
- Experimental design and results analysis
- Data documentation and definitions
- Performance trend analysis and anomaly alerts

### Key Interactions
- **With Product Manager**: Define success metrics, analyze feature impact, support prioritization decisions
- **With Project Manager**: Track project health metrics and success indicators
- **With Developers**: Advise on data instrumentation and logging requirements, validate data quality
- **With Business Analyst**: Incorporate data metrics into business requirements and success criteria
- **With Stakeholders**: Report on business metrics, customer behavior, and impact evidence

---

## Community Manager

### Role Summary
Community Managers foster engagement and support for open source or public projects. They build and nurture communities of users and contributors, manage communication channels, and ensure that community feedback informs product decisions.

### Responsibilities
- Build and grow engaged community around the project
- Manage communication channels (forums, Discord, GitHub discussions, etc.)
- Moderate discussions and ensure welcoming, inclusive environment
- Coordinate community events, office hours, and workshops
- Gather and synthesize community feedback and feature requests
- Support community contributors and manage contribution workflows
- Represent the community in product planning discussions

### Goals
- Build a vibrant, engaged community of users and contributors
- Accelerate feature development through community contributions
- Improve product usability and adoption through community feedback
- Build brand advocacy and word-of-mouth growth
- Create welcoming environment that reflects project values
- Reduce friction for new users and contributors

### Typical Communication
- Community discussions and Q&A responses
- Contributor acknowledgment and recognition
- Community feedback summaries for product team
- Event announcements and coordination
- Community guidelines and code of conduct enforcement
- Contributor onboarding and documentation

### Key Interactions
- **With Product Manager**: Advocate for community feedback in prioritization, validate feature relevance
- **With Developers**: Help onboard contributors, clarify technical questions, celebrate contributions
- **With UX Designer**: Gather community feedback on usability and design
- **With Customer Support Liaison**: Share community-reported issues and pain points
- **With Stakeholders**: Report on community health, growth, and engagement metrics

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the "Key Interactions" section to understand cross-functional collaboration points and dependencies.
