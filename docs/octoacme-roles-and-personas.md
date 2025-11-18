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

## UX Designer

### Role Summary
UX Designers ensure the product is user-friendly, accessible, and delightful. They conduct user research, create prototypes, and work closely with product and engineering teams to translate user needs into intuitive design solutions.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define user flows and information architecture
- Collaborate with Product Managers to understand user needs
- Work with Developers to ensure design feasibility and implementation
- Maintain design systems and style guides
- Advocate for accessibility and inclusive design

### Goals
- Create intuitive, user-centered product experiences
- Reduce user friction and improve satisfaction metrics
- Ensure design consistency across the product
- Validate design decisions through user research and testing

### Typical Communication
- Design review sessions with product and engineering teams
- User research findings and insights presentations
- Design specifications and handoff documentation
- Prototype walkthroughs and feedback sessions

---

## QA Engineer

### Role Summary
QA Engineers own quality assurance processes and ensure that delivered features meet acceptance criteria and quality standards. They build comprehensive test plans, conduct manual and automated testing, and collaborate with developers to maintain high test coverage.

### Responsibilities
- Develop and execute comprehensive test plans
- Create and maintain automated test suites
- Conduct manual, exploratory, and regression testing
- Identify, document, and track defects
- Validate acceptance criteria before release
- Collaborate with developers on test strategy and coverage
- Perform end-to-end and integration testing

### Goals
- Ensure high-quality, bug-free releases
- Increase automated test coverage and reliability
- Reduce production incidents and customer-reported issues
- Provide timely feedback on feature quality

### Typical Communication
- Test plan reviews with developers and product teams
- Bug reports and quality metrics dashboards
- QA sign-off and release readiness assessments
- Participation in sprint planning and retrospectives

---

## Scrum Master

### Role Summary
Scrum Masters facilitate agile ceremonies, remove team blockers, and coach the team on continuous process improvement. They act as servant leaders to enable the team's success and bridge communication between the team and stakeholders.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Remove impediments and blockers for the team
- Coach team members on agile principles and practices
- Shield the team from external disruptions
- Track and communicate team velocity and metrics
- Foster a culture of continuous improvement
- Ensure team adherence to agreed-upon processes

### Goals
- Maximize team productivity and efficiency
- Maintain sustainable delivery pace
- Improve team collaboration and communication
- Drive continuous process improvement

### Typical Communication
- Daily standups and agile ceremony facilitation
- Retrospective notes and action item tracking
- Team health and velocity metrics
- Coordination with other Scrum Masters and stakeholders

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business needs and technical solutions. They gather and analyze requirements, document business processes, and ensure that technical teams understand stakeholder needs and business context.

### Responsibilities
- Gather and document business requirements
- Analyze current processes and identify improvement opportunities
- Translate business needs into functional specifications
- Create process flows, data models, and requirements documents
- Facilitate requirements workshops with stakeholders
- Validate that delivered solutions meet business needs
- Support user acceptance testing (UAT)

### Goals
- Ensure alignment between business objectives and technical delivery
- Create clear, actionable requirements documentation
- Identify and resolve requirement conflicts early
- Minimize rework through thorough analysis

### Typical Communication
- Requirements gathering sessions with stakeholders
- Functional specification documents
- Business process documentation and diagrams
- Collaboration with product and project teams on scope and trade-offs

---

## Operations/Support

### Role Summary
Operations and Support teams ensure smooth post-release operations, monitor system health, respond to incidents, and relay user feedback to development teams. They bridge the gap between customers and engineering for continuous improvement.

### Responsibilities
- Monitor production systems and respond to incidents
- Provide technical support to customers and internal teams
- Document and escalate bugs and feature requests
- Maintain runbooks and operational documentation
- Coordinate with engineering on deployments and releases
- Track and report on operational metrics and SLAs
- Gather and communicate user feedback

### Goals
- Minimize downtime and service disruptions
- Maintain high customer satisfaction
- Ensure efficient incident resolution
- Provide actionable feedback for product improvement

### Typical Communication
- Incident reports and post-mortems
- Support ticket trends and escalations
- Operational health dashboards and metrics
- Feedback sessions with product and engineering teams

---

## Sponsor

### Role Summary
Sponsors are senior stakeholders or executives who champion the project, secure resources, and help remove organizational blockers. They provide strategic direction, make key decisions, and ensure the project aligns with business priorities.

### Responsibilities
- Provide strategic vision and business justification
- Secure and allocate necessary resources and budget
- Make high-level decisions and resolve escalated issues
- Remove organizational and political barriers
- Approve major project changes and scope adjustments
- Champion the project to senior leadership
- Ensure alignment with organizational strategy

### Goals
- Deliver business value and return on investment
- Ensure project aligns with organizational priorities
- Maintain stakeholder confidence and support
- Enable team success through resource allocation

### Typical Communication
- Executive briefings and steering committee meetings
- High-level status updates and milestone reviews
- Decision logs for major project decisions
- Escalation point for critical issues and blockers

---

## Role Collaboration and Handoffs

### Cross-Role Collaboration Points

Understanding how roles interact is critical for effective project execution. Here are key collaboration touchpoints:

**Discovery and Planning Phase:**
- **Business Analyst** gathers requirements from **Sponsor** and stakeholders
- **Product Manager** works with **Business Analyst** and **UX Designer** to define features
- **UX Designer** creates designs based on user research and product requirements
- **Project Manager** coordinates timeline and resource allocation with all roles

**Development Phase:**
- **Developers** implement features based on **UX Designer** specifications
- **QA Engineer** reviews acceptance criteria with **Product Manager** and **Developers**
- **Scrum Master** facilitates daily coordination and removes blockers
- **Business Analyst** clarifies requirements as questions arise

**Testing and Release Phase:**
- **QA Engineer** validates against acceptance criteria
- **Developers** fix defects identified by **QA Engineer**
- **Operations/Support** prepares for deployment and creates runbooks
- **Product Manager** validates business value and user impact

**Post-Release Phase:**
- **Operations/Support** monitors production and gathers user feedback
- **Product Manager** evaluates success metrics and user satisfaction
- **Business Analyst** documents learnings for future improvements
- **Project Manager** leads retrospective with all team members

### Key Handoff Points

1. **Requirements to Design**: Business Analyst → UX Designer
2. **Design to Development**: UX Designer → Developers
3. **Development to Testing**: Developers → QA Engineer
4. **Testing to Release**: QA Engineer → Operations/Support
5. **Feedback to Planning**: Operations/Support → Product Manager → Business Analyst

---

## Persona Onboarding Checklist

Use this checklist when onboarding new team members to clarify role expectations and collaboration patterns:

### For All Roles
- [ ] Review the OctoAcme Project Management Overview
- [ ] Understand your role's responsibilities and goals
- [ ] Identify your key collaborators and communication channels
- [ ] Review current project status and documentation
- [ ] Attend role-specific onboarding sessions
- [ ] Set up necessary tools and access permissions
- [ ] Schedule 1:1s with key stakeholders and collaborators

### Role-Specific Items

**Developers:**
- [ ] Set up development environment and GitHub access
- [ ] Review coding standards and PR conventions
- [ ] Understand testing requirements and coverage expectations
- [ ] Join technical architecture discussions

**Product Managers:**
- [ ] Review product vision, roadmap, and OKRs
- [ ] Understand customer segments and user personas
- [ ] Access analytics and metrics dashboards
- [ ] Meet with key stakeholders and customers

**Project Managers:**
- [ ] Access project tracking tools (GitHub Projects, etc.)
- [ ] Review risk register and communication plans
- [ ] Understand stakeholder landscape and reporting cadence
- [ ] Set up recurring meetings and status updates

**UX Designers:**
- [ ] Access design tools and design system
- [ ] Review existing user research and insights
- [ ] Understand accessibility and brand guidelines
- [ ] Connect with user research participants

**QA Engineers:**
- [ ] Set up test environments and automation frameworks
- [ ] Review test strategy and coverage requirements
- [ ] Access bug tracking and reporting tools
- [ ] Understand release and deployment processes

**Scrum Masters:**
- [ ] Understand team's current agile maturity and practices
- [ ] Review sprint cadence and ceremony schedule
- [ ] Access velocity and burndown metrics
- [ ] Meet with team members individually

**Business Analysts:**
- [ ] Review existing requirements documentation
- [ ] Understand business context and domain knowledge
- [ ] Access stakeholder contact information
- [ ] Learn internal business processes and systems

**Operations/Support:**
- [ ] Access monitoring and alerting systems
- [ ] Review incident response procedures
- [ ] Understand SLA commitments and escalation paths
- [ ] Set up support ticket systems and runbooks

**Sponsors:**
- [ ] Review business case and ROI projections
- [ ] Understand project scope, timeline, and budget
- [ ] Meet with Project Manager and Product Manager
- [ ] Clarify decision-making authority and escalation process

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Personas help establish clear accountability and facilitate effective collaboration across diverse teams.
- Reference these definitions when creating project charters, assigning responsibilities, or resolving cross-functional questions.

