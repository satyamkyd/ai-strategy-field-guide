# Checklists & Templates

## Why it matters
- **Ready-to-use templates** accelerate project planning and reduce setup time.
- **Standardized checklists** ensure nothing is missed and maintain quality consistency.
- **Risk registers** help identify and mitigate AI-specific risks early.
- **Intake forms** standardize project evaluation and prioritization.

## Core concepts
- **Project one-pager**: Concise project summary for stakeholder communication and approval.
- **Use-case scoring**: Systematic evaluation framework for prioritizing AI opportunities.
- **Risk register**: Comprehensive identification and mitigation of AI project risks.
- **AI readiness assessment**: Evaluation of organizational preparedness for AI initiatives.
- **Template library**: Reusable formats for common AI project deliverables.

## Project one-pager template

```markdown
# AI Project One-Pager

## Project Overview
**Name**: [Project Name]
**Sponsor**: [Executive Sponsor]
**Product Lead**: [Name]
**AI Translator**: [Name]
**Timeline**: [Start Date] - [Target End Date]

## Business Case
**Problem**: [Clear description of the business problem]
**Solution**: [AI approach and expected outcomes]
**Value**: [Quantified business impact - revenue, cost, efficiency]
**Success Metrics**: [Specific, measurable success criteria]

## Technical Approach
**AI Pattern**: [ML/GenAI/Rules, specific use case]
**Data Sources**: [Key data inputs and quality status]
**Platform**: [Build vs buy decision and rationale]
**Integration**: [How it fits with existing systems]

## Risk Assessment
**Risk Tier**: [Low/Medium/High based on impact and uncertainty]
**Key Risks**: [Top 3-5 risks with mitigation strategies]
**Compliance**: [Privacy, security, regulatory requirements]
**Dependencies**: [Critical dependencies and contingency plans]

## Resource Requirements
**Team**: [Roles and time commitments]
**Budget**: [Estimated costs and ROI projection]
**Infrastructure**: [Technical requirements and capacity]
**Timeline**: [Key milestones and deliverables]

## Approval Status
**Business Approval**: [Date and approver]
**Technical Approval**: [Date and approver]
**Security/Legal Review**: [Date and status]
**Go/No-Go Decision**: [Date and decision]
```

## Use-case scoring sheet

```markdown
# AI Use Case Scoring Matrix

## Use Case: [Name]
**Business Owner**: [Name]
**Date**: [Date]
**Scorer**: [Name]

## Scoring Criteria (1-5 scale)

### Impact (Business Value)
- **Revenue Impact**: [1-5] - Direct revenue generation or protection
- **Cost Reduction**: [1-5] - Operational cost savings or efficiency gains
- **Strategic Importance**: [1-5] - Alignment with business strategy
- **User Experience**: [1-5] - Customer or employee satisfaction improvement

**Impact Score**: [Average of above] × 2 = [Weighted Score]

### Feasibility (Technical & Operational)
- **Data Availability**: [1-5] - Quality, quantity, and accessibility of data
- **Technical Complexity**: [1-5] - Development effort and skill requirements
- **Integration Complexity**: [1-5] - System integration and change management
- **Team Capability**: [1-5] - Available skills and capacity

**Feasibility Score**: [Average of above] × 1.5 = [Weighted Score]

### Data Readiness
- **Data Quality**: [1-5] - Accuracy, completeness, and consistency
- **Data Volume**: [1-5] - Sufficient quantity for training and validation
- **Data Freshness**: [1-5] - Recency and update frequency
- **Labeling Requirements**: [1-5] - Need for manual data annotation

**Data Score**: [Average of above] × 1 = [Weighted Score]

## Final Calculation
**Total Score**: Impact + Feasibility + Data = [Total]
**Priority**: [High/Medium/Low based on score]

## Recommendations
**Next Steps**: [Immediate actions]

## AI Readiness Intake Form

### AI Readiness Intake (short)
- **Problem owner & decision to influence**: 
- **Current process & KPI**: 
- **Expected output (schema or example)**: 
- **Data sources + owner + access status**: 
- **Constraints (latency, cost, privacy)**: 
- **Success metrics (leading & lagging)**: 
- **Pilot surface (UI/API/workflow step) & timeline**: 

## Risk Register Template

### AI Project Risk Register

| Risk ID | Risk Description | Probability | Impact | Risk Level | Mitigation Strategy | Owner | Status |
|---------|------------------|-------------|---------|------------|-------------------|-------|---------|
| R001 | Data quality issues | Medium | High | High | Data validation pipeline, quality gates | Data Lead | Open |
| R002 | Model performance degradation | Medium | Medium | Medium | Monitoring, retraining schedule | ML Engineer | Open |
| R003 | Security vulnerabilities | Low | High | Medium | Security review, penetration testing | Security Lead | Open |
| R004 | Regulatory compliance | Medium | High | High | Legal review, compliance checklist | Legal Lead | Open |
| R005 | Integration complexity | High | Medium | Medium | Proof of concept, phased rollout | Tech Lead | Open |

## Rollout Communications Plan

### AI Rollout Communications Plan

#### Stakeholder Communication Matrix
| Stakeholder | Interest | Influence | Communication Frequency | Key Messages | Owner |
|-------------|----------|-----------|-------------------------|--------------|-------|
| Executive Team | High | High | Weekly | Strategic progress, ROI updates | Project Sponsor |
| End Users | High | Medium | Bi-weekly | Feature updates, training opportunities | Product Lead |
| IT/Infrastructure | Medium | High | Weekly | Technical requirements, capacity planning | Tech Lead |
| Legal/Compliance | Medium | High | As needed | Risk assessment, compliance status | Legal Lead |

#### Communication Timeline
- **Month 1**: Announcement and stakeholder alignment
- **Month 2**: Technical deep-dive and training preparation
- **Month 3**: Pilot launch and feedback collection
- **Month 4**: Full rollout and adoption monitoring

## Champion Program Outline

### AI Adoption Champion Program

#### Champion Selection Criteria
- **Early adopters**: Naturally curious about new technology
- **Influencers**: Respected by peers and management
- **Problem solvers**: Motivated to improve processes
- **Communicators**: Can effectively share knowledge and excitement

#### Champion Responsibilities
- **Pilot testing**: Early access to new features and workflows
- **Feedback collection**: Gather user experience and improvement suggestions
- **Knowledge sharing**: Train peers and create documentation
- **Advocacy**: Promote AI adoption and address concerns

#### Champion Benefits
- **Early access**: First to try new AI features
- **Recognition**: Acknowledgment in company communications
- **Skill development**: Advanced training and certification opportunities
- **Career growth**: Leadership opportunities in AI initiatives

#### Program Structure
- **Quarterly meetings**: Share experiences and best practices
- **Monthly check-ins**: Individual progress and support
- **Annual recognition**: Awards and celebration of achievements
**Risks**: [Key concerns and mitigation]
**Timeline**: [Estimated development time]
**Resources**: [Required team and budget]
```

## Risk register template

```markdown
# AI Project Risk Register

## Project: [Name]
**Date**: [Date]
**Risk Owner**: [Name]

| Risk ID | Risk Description | Probability | Impact | Risk Score | Owner | Mitigation Strategy | Status |
|---------|------------------|-------------|---------|------------|-------|-------------------|---------|
| R001 | [Risk description] | [High/Med/Low] | [High/Med/Low] | [Score] | [Name] | [Strategy] | [Open/Closed] |

## Risk Categories

### Technical Risks
- **Model Performance**: Accuracy, bias, drift, hallucinations
- **Data Quality**: Availability, privacy, consent, retention
- **Infrastructure**: Scalability, availability, security, compliance
- **Integration**: API compatibility, data flow, error handling

### Business Risks
- **Stakeholder Alignment**: Resistance, competing priorities, scope creep
- **Change Management**: User adoption, training, support
- **Compliance**: Regulatory requirements, audit findings, legal issues
- **Vendor Dependencies**: Lock-in, pricing changes, service quality

### Operational Risks
- **Team Capacity**: Skills, availability, turnover
- **Timeline**: Delays, dependencies, resource constraints
- **Budget**: Cost overruns, ROI shortfalls, funding changes
- **Quality**: Testing gaps, deployment issues, monitoring failures

## Risk Response Strategies

### Avoid
- **When**: Risk is too high or mitigation too costly
- **How**: Change project scope, approach, or timeline
- **Example**: Reduce risk tier by limiting model scope

### Transfer
- **When**: Risk can be shared with partners or insurance
- **How**: Vendor contracts, insurance, shared responsibility
- **Example**: Use managed services for compliance requirements

### Mitigate
- **When**: Risk can be reduced to acceptable levels
- **How**: Additional controls, testing, monitoring
- **Example**: Implement bias detection and human review

### Accept
- **When**: Risk is low or mitigation cost exceeds benefit
- **How**: Monitor and respond if risk materializes
- **Example**: Accept low probability technical debt

## Risk Monitoring
**Review Frequency**: [Weekly/Monthly/Quarterly]
**Escalation Threshold**: [Risk score that triggers escalation]
**Reporting**: [Stakeholder communication plan]
**Contingency Plans**: [Response plans for high-impact risks]
```

## AI readiness intake form

```markdown
# AI Project Intake Form

## Project Information
**Project Name**: [Name]
**Business Owner**: [Name, Title, Contact]
**Project Sponsor**: [Name, Title, Contact]
**Request Date**: [Date]
**Target Launch**: [Date]

## Business Case
**Problem Statement**: [Clear description of the business problem]
**Current Process**: [How it's done today]
**Desired Outcome**: [What success looks like]
**Business Impact**: [Quantified value - revenue, cost, efficiency]
**Success Metrics**: [How you'll measure success]

## AI Approach
**AI Pattern**: [Classification, Generation, Prediction, Rules, Other]
**Use Case Type**: [Customer-facing, Internal operations, Analytics, Other]
**Data Requirements**: [What data is needed, sources, quality]
**Integration Points**: [Systems, processes, workflows affected]

## Organizational Readiness
**Stakeholder Support**: [Who supports this, who might resist]
**Change Impact**: [How many people affected, what changes required]
**Training Needs**: [Skills required, training approach]
**Policy Considerations**: [Compliance, governance, risk factors]

## Technical Assessment
**Data Availability**: [Existing data, quality, access, consent]
**Technical Skills**: [Team capabilities, gaps, training needs]
**Infrastructure**: [Current systems, cloud strategy, security]
**Vendor Preferences**: [Preferred platforms, existing relationships]

## Resource Requirements
**Team Composition**: [Roles needed, time commitments]
**Budget Estimate**: [Development and operational costs]
**Timeline**: [Key milestones and dependencies]
**External Resources**: [Consultants, vendors, training]

## Risk Assessment
**Risk Level**: [Low/Medium/High based on impact and complexity]
**Key Concerns**: [Top risks and mitigation strategies]
**Compliance Issues**: [Privacy, security, regulatory requirements]
**Dependencies**: [Critical dependencies and contingency plans]

## Next Steps
**Immediate Actions**: [What happens next]
**Approval Process**: [Who needs to approve what]
**Timeline**: [Next review and decision points]
**Questions**: [What needs to be clarified or researched]
```

## Additional templates

### Model card template
```markdown
# Model Card: [Model Name]

## Model Details
- **Purpose**: [What the model does]
- **Input**: [Data types and formats]
- **Output**: [Predictions or generations]
- **Architecture**: [Model type and size]

## Performance
- **Metrics**: [Accuracy, precision, recall, etc.]
- **Bias assessment**: [Fairness metrics and findings]
- **Limitations**: [Known issues and edge cases]

## Risk Assessment
- **Risk tier**: [Low/Medium/High]
- **Mitigation**: [Controls and safeguards]
- **Monitoring**: [Performance tracking plan]

## Governance
- **Approval**: [Who approved and when]
- **Review cadence**: [How often to reassess]
- **Rollback criteria**: [When to disable the model]
```

### Communication plan template
```markdown
# AI Project Communication Plan

## Project: [Name]
**Communication Owner**: [Name]

## Key Messages
1. **Why**: [Business drivers and benefits]
2. **What**: [Specific changes and capabilities]
3. **How**: [Implementation approach and timeline]
4. **Impact**: [What users can expect]

## Stakeholder Communication Matrix

| Stakeholder | Message | Channel | Frequency | Owner |
|-------------|---------|---------|-----------|-------|
| [Group] | [Message] | [Channel] | [Frequency] | [Name] |

## Communication Timeline
**Pre-launch**: [Messages and timing]
**Launch**: [Announcements and support]
**Post-launch**: [Updates and feedback collection]

## Feedback Mechanisms
**Channels**: [How users can provide feedback]
**Frequency**: [How often feedback is collected]
**Response**: [How feedback is addressed]
**Escalation**: [When and how issues are escalated]
```

## Anti-patterns

- **Template overload**: Using templates without customizing for project needs.
- **Checklist fatigue**: Too many checkboxes that become meaningless.
- **Static documents**: Templates that aren't updated based on lessons learned.
- **One-size-fits-all**: Same templates for very different project types.
- **No ownership**: Templates without clear responsibility for completion.

## Checklist (copy/paste)

- [ ] Project one-pager completed and approved by stakeholders.
- [ ] Use-case scoring completed with business and technical input.
- [ ] Risk register populated with identified risks and mitigation strategies.
- [ ] AI readiness assessment completed and gaps addressed.
- [ ] Templates customized for project-specific needs and requirements.
- [ ] Ownership assigned for each deliverable and milestone.
- [ ] Review process established for template completion and quality.
- [ ] Lessons learned captured and templates updated accordingly.

## Metrics / Proof of value

**Leading indicators**: Template completion rate, stakeholder satisfaction, project planning time.

**Lagging indicators**: Project success rate, template effectiveness, stakeholder adoption.

**Template quality**: Completion rates, stakeholder feedback, project outcomes.

**Process efficiency**: Planning time reduction, consistency improvement, quality enhancement.

## Further reading

- **The AI Playbook** — Eric Siegel (2024): project planning and template examples.
- **Project Management Templates** — PMI (2023): standard project management templates.
- **AI Project Management** — O'Reilly (2023): AI-specific project management approaches.
- **Risk Management for AI** — NIST (2023): comprehensive risk assessment frameworks.
