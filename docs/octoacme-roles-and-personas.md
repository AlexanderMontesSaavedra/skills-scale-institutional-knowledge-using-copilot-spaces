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
The Release Manager owns release readiness, deployment timing, and rollback coordination so that delivery teams can ship with confidence and minimal disruption.

### Responsibilities
- Define release windows and sequencing across services or teams
- Confirm that deployment prerequisites are met, including validation, sign-off, and rollback readiness
- Coordinate communication with stakeholders, support teams, and leadership before and after launch
- Manage release checklists, issue triage, and post-release follow-up
- Partner with engineering and project leadership to resolve release blockers

### Goals
- Reduce deployment risk and production incidents
- Improve predictability and transparency around launches
- Ensure a clear path for recovery if a release does not behave as expected

### Typical Communication
- Release readiness review meetings
- Deployment check-ins and launch updates
- Post-release summaries and incident coordination when needed

### Interaction with Existing Roles
- Works closely with Developers to confirm code, test, and rollback readiness before deployment
- Aligns with Product Managers and Project Managers on timing, stakeholder communication, and release scope
- Coordinates with Support / Operations to prepare monitoring, customer impact communication, and operational handoff
- Escalates risks to leadership when release scope, timing, or business impact require decision-making

---

## QA Lead

### Role Summary
The QA Lead defines quality gates, test strategy, and defect triage so the team can release reliably and validate that outcomes meet customer and business expectations.

### Responsibilities
- Define test strategy for unit, integration, regression, and release validation
- Review acceptance criteria and validate that requirements are testable and complete
- Own defect triage, prioritization, and escalation for quality issues
- Partner with Developers on test automation, bug fixes, and release readiness
- Ensure manual and automated validation are completed for critical flows before launch

### Goals
- Improve product quality and reduce defects in production
- Improve confidence in release readiness through consistent validation
- Align testing with customer experience and business impact

### Typical Communication
- Quality gate reviews and bug triage sessions
- Test strategy planning with engineering and product stakeholders
- Release validation reports and sign-off communications

### Interaction with Existing Roles
- Collaborates with Developers on test coverage, automation, and defect resolution
- Works with Product Managers to validate whether acceptance criteria are being met
- Keeps Project Managers informed of risks, blockers, and release confidence concerns
- Coordinates with the Release Manager to confirm deployment readiness and post-release validation

---

## Security / Compliance Owner

### Role Summary
The Security / Compliance Owner identifies and reviews security, privacy, and regulatory risks so the project can meet required controls and reduce exposure before release.

### Responsibilities
- Assess security and compliance risks during planning, implementation, and release
- Review security requirements, data handling, access controls, and third-party dependencies
- Partner with engineering teams to validate remediation and control coverage
- Support incident response and escalation when a vulnerability or compliance issue is identified
- Maintain awareness of policy and regulatory obligations that affect the project

### Goals
- Reduce risk to users, the business, and the platform
- Ensure compliance with relevant rules and internal policies
- Build security into the delivery lifecycle instead of treating it as a final gate

### Typical Communication
- Security review meetings and risk assessments
- Compliance checkpoints during planning and release readiness
- Incident notification and remediation updates

### Interaction with Existing Roles
- Advises Product Managers and Project Managers on risk trade-offs and delivery decisions
- Works with Developers to review implementation choices and evidence of secure practices
- Coordinates with Release Managers to confirm security checks are complete before launch
- Escalates critical findings to leadership and the appropriate response teams when necessary

---

## Support / Operations Liaison

### Role Summary
The Support / Operations Liaison ensures that products and services are operationally ready for release, can be monitored effectively, and have a clear path for support and incident response.

### Responsibilities
- Coordinate service readiness checks, monitoring, and alerting prior to launch
- Help define runbooks, escalation paths, and support documentation for operational issues
- Participate in handoff from delivery teams to support or operations teams
- Support incident response and triage when issues occur in production
- Share operational feedback back to project and product teams to improve reliability

### Goals
- Improve service stability and customer support readiness
- Reduce operational surprises after launch
- Ensure clear ownership during incidents and routine support workflows

### Typical Communication
- Readiness reviews and operational handoff meetings
- Incident calls and support escalation updates
- Post-release feedback loops with product and engineering teams

### Interaction with Existing Roles
- Works with Developers on observability, monitoring, and production readiness
- Aligns with Product Managers and PMs on customer impact and communication needs
- Partners with the Release Manager to confirm support coverage and monitoring before go-live
- Supports the Security / Compliance Owner during incident response if operational controls or data exposure are involved

---

## Customer / Stakeholder Advocate

### Role Summary
The Customer / Stakeholder Advocate represents user needs, business impact, and decision quality so product work remains aligned with outcomes and adoption goals.

### Responsibilities
- Represent user feedback, business priorities, and stakeholder concerns in planning and delivery
- Help clarify customer pain points, desired outcomes, and adoption criteria
- Validate that product decisions remain aligned with business value and user experience
- Support stakeholder communication and expectation-setting across project phases
- Help surface trade-offs that affect customer outcomes, usability, and trust

### Goals
- Keep delivery focused on customer and business value
- Improve stakeholder confidence and alignment
- Ensure product decisions reflect real user needs and operational realities

### Typical Communication
- Stakeholder briefings and requirement reviews
- User feedback synthesis and product decision discussions
- Milestone updates and adoption-related reporting

### Interaction with Existing Roles
- Works with Product Managers to shape roadmaps and priorities based on customer outcomes
- Shares feedback with Developers and QA to improve usability and acceptance criteria
- Keeps Project Managers informed of stakeholder concerns, dependencies, and approval needs
- Coordinates with Support / Operations when customer impact, adoption, or service quality issues arise

---

## Working Together Across the Lifecycle

These personas complement the core OctoAcme roles and help clarify accountability across initiation, planning, execution, release, and retrospective work. In practice:

- Developers and QA Lead focus on implementation quality and validation
- Product Managers and Customer / Stakeholder Advocates focus on value, priorities, and user outcomes
- Project Managers and Release Managers coordinate delivery, timing, communication, and risk
- Security / Compliance and Support / Operations provide operational and governance guardrails

This broader set of responsibilities makes ownership clearer while preserving cross-functional collaboration. It reduces ambiguity, supports better escalation paths, and strengthens delivery throughout the project lifecycle.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These roles help teams model real-world cross-functional collaboration across planning, execution, release, and support.

