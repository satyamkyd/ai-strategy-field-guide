# Evaluation Harness

A lightweight framework for evaluating GenAI systems with golden sets, adversarial testing, and rubric scoring.

## What This Is

This evaluation harness provides:
- **Golden set examples** for baseline quality assessment
- **Configuration templates** for different evaluation scenarios
- **Scoring frameworks** for structured and free-text outputs
- **Baseline establishment** for detecting regressions

## Quick Start

### 1. Configure Your Evaluation
Edit `config.yaml` to match your use case:
```yaml
task: "summary"  # Your task type
provider: "openai"  # Your LLM provider
model: "gpt-4o-mini"  # Your model
```

### 2. Prepare Your Data
- **Golden set**: Add examples to `dataset.jsonl`
- **Adversarial set**: Create edge cases and attack scenarios
- **Live set**: Sample production traffic for shadow evaluation

### 3. Run Evaluations
```bash
# Basic evaluation
python runner.py --config config.yaml --dataset dataset.jsonl

# With adversarial testing
python runner.py --config config.yaml --dataset dataset.jsonl --adversarial adversarial.jsonl

# A/B comparison
python runner.py --config config_a.yaml --config config_b.yaml --dataset dataset.jsonl
```

## Configuration Options

### Task Types
- **Summarization**: Text compression with rubric scoring
- **Extraction**: Structured output with exact match/F1
- **Classification**: Label assignment with accuracy metrics
- **RAG**: Grounded responses with citation accuracy

### Metrics
- **Exact match**: For structured outputs
- **Rubric scoring**: For free-text quality assessment
- **Cost/latency**: Performance and efficiency tracking
- **Faithfulness**: Hallucination detection

### Thresholds
Set minimum acceptable scores for:
- Quality metrics (faithfulness, coverage)
- Performance (latency, cost)
- Safety (adversarial test pass rate)

## Dataset Format

### Golden Set
```json
{
  "id": "unique_identifier",
  "input": "Your input text or prompt",
  "reference": {
    "expected_output": "Expected result",
    "metadata": "Additional context"
  }
}
```

### Adversarial Set
```json
{
  "id": "adv_001",
  "input": "Malicious or edge case input",
  "category": "prompt_injection|data_exfil|content_violation",
  "expected_behavior": "refuse|escalate|block"
}
```

## Scoring Methods

### Rubric Scoring
1. **Coverage**: Did it capture all key points?
2. **Faithfulness**: Is it grounded in the source?
3. **Brevity**: Is it appropriately concise?
4. **Tone**: Does it match the intended voice?

### Exact Match
- **F1 Score**: Precision and recall for structured fields
- **Field-level accuracy**: Per-field success rates
- **Schema validation**: JSON structure compliance

### Safety Scoring
- **Block rate**: Percentage of adversarial inputs blocked
- **False positives**: Legitimate inputs incorrectly blocked
- **Escalation rate**: Cases requiring human review

## Integration

### CI/CD Pipeline
```yaml
# GitHub Actions example
- name: Run Evaluation
  run: |
    python eval/runner.py --config eval/config.yaml --dataset eval/dataset.jsonl
    python eval/runner.py --config eval/config.yaml --adversarial eval/adversarial.jsonl
```

### Monitoring Dashboard
- Track quality metrics over time
- Alert on performance regressions
- Monitor cost and latency trends
- Flag safety incidents

## Customization

### Adding New Metrics
1. Define scoring function in `scorers.py`
2. Add to configuration file
3. Update evaluation pipeline
4. Set thresholds and alerts

### New Task Types
1. Create task-specific configuration
2. Define output schema
3. Build appropriate test sets
4. Implement task-specific scorers

## Best Practices

### Golden Set Construction
- Start with 50-100 high-quality examples
- Cover edge cases and common scenarios
- Include diverse inputs and outputs
- Regular updates as system evolves

### Adversarial Testing
- Test prompt injection techniques
- Simulate data exfiltration attempts
- Validate content filtering effectiveness
- Monitor for new attack patterns

### Baseline Management
- Establish performance baselines
- Track changes over time
- Alert on significant regressions
- Document improvement strategies

## Troubleshooting

### Common Issues
- **Low scores**: Check golden set quality and relevance
- **High variance**: Ensure consistent input formatting
- **Timeout errors**: Adjust latency thresholds
- **Cost spikes**: Monitor token usage and pricing

### Performance Optimization
- Batch evaluation requests
- Cache model responses
- Parallel processing for large datasets
- Efficient data loading and processing

## Contributing

This evaluation harness is part of the AI Strategy Study Guide. To contribute:
1. Follow the established patterns
2. Add tests for new functionality
3. Update documentation
4. Submit pull requests

## License

MIT License - see LICENSE file for details.

---

*This evaluation harness provides a foundation for measuring and improving GenAI system quality. Customize it for your specific use cases and requirements.*
