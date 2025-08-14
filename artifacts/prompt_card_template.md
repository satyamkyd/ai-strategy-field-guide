# Prompt Card Template

## Prompt Information
**Name**: [prompt_name_version]  
**Owner**: [Team/Individual]  
**Last Updated**: [Date]  
**Pattern**: [Summarization/Extraction/Classification/RAG/Other]

## Purpose
**What does this prompt do?**
[Clear description of the prompt's purpose and intended use]

**What problems does it solve?**
[Business problem and value proposition]

**Who are the intended users?**
[Primary and secondary users]

## Behavior
**Voice & Style**:
- **Tone**: [Professional/Casual/Technical/Other]
- **Persona**: [Role the AI should adopt]
- **Constraints**: [What the AI should NOT do]

**Output Format**:
```json
{
  "field1": "description",
  "field2": "description"
}
```
*Or describe the expected output format*

**Examples**:
- [Example input 1] → [Expected output 1]
- [Example input 2] → [Expected output 2]

## Technical Configuration
**Model**: [Model family and size]
**Temperature**: [Value and rationale]
**Max Tokens**: [Limit and reasoning]
**Stop Sequences**: [If applicable]

**Retrieval** (if RAG):
- **Top-k**: [Number of chunks retrieved]
- **Reranking**: [Yes/No, method if yes]
- **Filters**: [Domain, date, or other filters]

**Tools** (if function calling):
- [Tool 1]: [Purpose and parameters]
- [Tool 2]: [Purpose and parameters]

## Constraints
**Latency**: ≤ [X] seconds @ p95
**Cost**: ≤ $[X] per case
**Quality**: [Minimum quality thresholds]
**Safety**: [Safety requirements and guardrails]

## Evaluation
**Golden Set**: [X] examples with [criteria]
**Rubric Criteria**:
- [Criterion 1]: [Target score]
- [Criterion 2]: [Target score]
- [Criterion 3]: [Target score]

**Adversarial Test**: Pass rate ≥ [X]%
**Baseline Comparison**: [Performance vs. previous version]

## Risks & Mitigations
**Risk Level**: [Low/Medium/High]
**Key Risks**:
- [Risk 1]: [Mitigation strategy]
- [Risk 2]: [Mitigation strategy]

**Safety Controls**:
- [Control 1]: [How it works]
- [Control 2]: [How it works]

**Hallucination Prevention**:
- [Strategy 1]: [Implementation]
- [Strategy 2]: [Implementation]

## Monitoring
**Key Metrics**:
- [Metric 1]: [Target and alert threshold]
- [Metric 2]: [Target and alert threshold]
- [Metric 3]: [Target and alert threshold]

**Quality Checks**:
- [Check 1]: [Frequency and method]
- [Check 2]: [Frequency and method]

**Drift Detection**:
- [Input drift indicators]
- [Output quality drift indicators]

## Deployment
**Environment**: [Production/Staging/Development]
**Integration Point**: [Where in the workflow]
**Rollback Plan**: [How to revert to previous version]
**Change Control**: [Approval process for updates]

## Maintenance
**Update Cadence**: [How often to review and update]
**Trigger Conditions**: [When to update early]
**Version Control**: [How to track prompt changes]
**A/B Testing**: [Plan for testing improvements]

## Governance
**Approval**: [Who approved and when]
**Review Cadence**: [How often to review]
**Compliance**: [Regulatory requirements met]
**Audit Trail**: [Change tracking and logging]

## Contact & Support
**Technical Owner**: [Name and contact]
**Business Owner**: [Name and contact]
**Support Process**: [How to get help]
**Documentation**: [Additional resources]

---

*This prompt card provides transparency and accountability for GenAI systems. Update regularly as the prompt evolves.*
