# Contributing to AI Strategy Study Guide

Thank you for your interest in contributing to the AI Strategy Study Guide! This guide is designed to help product leaders, operations leaders, and individual contributors implement AI strategy effectively.

## How to Contribute

### Types of Contributions We Welcome

- **Content improvements**: Fix typos, clarify concepts, add examples
- **New sections**: Expand on existing topics or add new relevant content
- **Diagrams**: Improve or create new Mermaid diagrams
- **Templates**: Add new templates or improve existing ones
- **Case studies**: Share public case studies (no proprietary content)
- **Resources**: Suggest books, tools, or learning materials
- **Bug fixes**: Report and fix issues with formatting or links

### What We Don't Accept

- **Proprietary content**: No internal company materials or confidential information
- **Vendor-specific content**: Keep content vendor-neutral and pattern-focused
- **Legal advice**: This is not legal counsel; consult professionals for compliance
- **Promotional content**: No marketing materials or product endorsements

## Getting Started

### Prerequisites

- Basic familiarity with Markdown
- Understanding of AI/ML concepts (beginner level is fine)
- Access to a text editor or Markdown editor

### Setup

1. **Fork the repository** on GitHub
2. **Clone your fork** to your local machine
3. **Create a branch** for your changes: `git checkout -b feature/your-feature-name`

## Content Guidelines

### Writing Style

- **Clear and concise**: Use simple language, avoid jargon when possible
- **Actionable**: Provide specific steps and examples
- **Skimmable**: Use headers, bullet points, and short paragraphs
- **Inclusive**: Use inclusive language and diverse examples

### Structure Requirements

Each main section (0X_*.md) must follow this template:

```markdown
# [Title]

## Why it matters
- [3-5 bullet points explaining importance]

## Core concepts
- [Short explanations of key concepts]

## Diagram
```mermaid
[Your Mermaid diagram here]
```

## Playbook (step-by-step)
[Numbered steps with clear actions]

## Anti-patterns
[Common mistakes to avoid]

## Checklist (copy/paste)
[Actionable checklist items]

## Metrics / Proof of value
[How to measure success]

## Further reading
[Public sources and references]
```

### Mermaid Diagrams

- **Save source**: Every Mermaid diagram must be saved as a `.mmd` file in `/diagrams`
- **Keep it simple**: Focus on clarity over complexity
- **Test rendering**: Ensure diagrams render correctly in GitHub
- **Consistent style**: Use similar colors and shapes across diagrams

### Templates and Checklists

- **Actionable**: Every item should be something someone can actually do
- **Comprehensive**: Cover the main steps without being overwhelming
- **Copy-paste ready**: Format for easy use in real projects

## Making Changes

### Content Updates

1. **Edit the file** using your preferred editor
2. **Follow the structure** requirements above
3. **Test formatting** by previewing in GitHub or a Markdown viewer
4. **Update diagrams** if you modify any Mermaid content

### Adding New Files

1. **Follow naming conventions**: Use the established pattern (e.g., `0X_topic.md`)
2. **Update README.md**: Add new sections to the repository map
3. **Create diagrams**: If your content includes diagrams, save them in `/diagrams`
4. **Cross-reference**: Link to related content where appropriate

### Quality Checklist

Before submitting, ensure your changes:

- [ ] Follow the established structure and format
- [ ] Include all required sections
- [ ] Have working Mermaid diagrams (if applicable)
- [ ] Use clear, actionable language
- [ ] Include relevant further reading
- [ ] Are free of typos and formatting errors
- [ ] Don't contain proprietary or confidential information

## Submitting Changes

### Commit Messages

Use clear, descriptive commit messages:

```
feat: add new section on AI safety and red-teaming
fix: correct typo in use case scoring matrix
docs: improve clarity of evaluation harness instructions
```

### Pull Request Process

1. **Push your changes** to your fork
2. **Create a pull request** with a clear description
3. **Use the PR template** to provide context
4. **Link any related issues** or discussions
5. **Request review** from maintainers

### PR Description Template

```markdown
## Description
Brief description of what this PR adds or changes

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update
- [ ] Content improvement

## Files Changed
- List the main files you modified

## Testing
- [ ] Content renders correctly
- [ ] Mermaid diagrams display properly
- [ ] Links work correctly
- [ ] No broken formatting

## Additional Notes
Any other context or information
```

## Review Process

### What We Look For

- **Content quality**: Clear, accurate, and actionable information
- **Structure compliance**: Follows the established template
- **Technical accuracy**: Information is correct and up-to-date
- **Accessibility**: Content is easy to understand and navigate

### Review Timeline

- **Initial review**: Within 1-2 business days
- **Feedback**: Detailed comments on any issues
- **Revisions**: Opportunity to address feedback
- **Final approval**: Usually within 1 week for straightforward changes

## Getting Help

### Questions and Discussion

- **GitHub Issues**: Use issues for questions, bug reports, or feature requests
- **Discussions**: Start a discussion for broader topics or community input
- **Email**: Contact maintainers directly for sensitive matters

### Resources

- **Markdown Guide**: [GitHub's Markdown guide](https://docs.github.com/en/github/writing-on-github)
- **Mermaid**: [Mermaid documentation](https://mermaid-js.github.io/mermaid/)
- **AI Strategy**: Reference the existing content for style and approach

## Recognition

### Contributors

- **All contributors** are recognized in the README
- **Significant contributions** may be highlighted in release notes
- **Community members** are encouraged to share their work

### Attribution

- **Content**: Contributors retain rights to their original content
- **License**: All contributions are licensed under MIT
- **Credit**: Proper attribution for ideas and contributions

## Code of Conduct

This project follows the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## License

By contributing, you agree that your contributions will be licensed under the [MIT License](LICENSE).

---

Thank you for contributing to making AI strategy more accessible and practical for everyone!
