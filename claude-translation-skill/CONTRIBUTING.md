# Contributing to Claude Translation Skill

Thank you for your interest in contributing! This document provides guidelines for contributing to the project.

## Ways to Contribute

### 🐛 Report Bugs

Found a bug? [Open an issue](../../issues/new) with:
- Clear description of the problem
- Steps to reproduce
- Expected vs actual behavior
- Example text that caused the issue
- Your Claude version (if known)

### 💡 Suggest Features

Have an idea? [Open an issue](../../issues/new) with:
- Feature description
- Use case / problem it solves
- Example of how it would work
- Any relevant examples from other tools

### 📖 Improve Documentation

Documentation improvements are always welcome:
- Fix typos or unclear explanations
- Add more examples
- Translate documentation to other languages
- Improve README clarity

### 🔧 Code Contributions

#### Before You Start

1. Check existing [issues](../../issues) and [pull requests](../../pulls)
2. For major changes, open an issue first to discuss
3. Fork the repository
4. Create a new branch for your feature

#### Making Changes

1. **Edit the skill**
   - The main skill file is `translation/SKILL.md`
   - Follow the existing structure and style
   - Keep it concise (skill-creator principle: only include what Claude doesn't already know)

2. **Test your changes**
   - Upload the modified skill to Claude
   - Test with various text types and language pairs
   - Verify all three output layers work correctly
   - Check edge cases (idioms, technical terms, poetry, etc.)

3. **Update documentation**
   - Update README if needed
   - Add examples if you've added features
   - Update relevant docs/ files

4. **Package the skill**
   - Use the skill-creator packaging tool if available
   - Ensure the zip file is properly formatted
   - Test the packaged version

#### Commit Guidelines

Use clear, descriptive commit messages:

```
Good:
- "Add support for specialized medical terminology"
- "Fix: Improve handling of poetic meter in translations"
- "Docs: Add Spanish translation examples"

Avoid:
- "Update file"
- "Fix stuff"
- "Changes"
```

### 📝 Share Examples

Help others by sharing examples:
- Add translation examples to `examples/`
- Include source text, output, and explanation
- Show interesting or challenging translations
- Demonstrate the skill handling edge cases

### 🌍 Translate Documentation

Help make the project accessible:
- Translate README to your language
- Create localized documentation
- Add language-specific usage tips

## Pull Request Process

1. **Fork and branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Make your changes**
   - Edit files
   - Test thoroughly
   - Update documentation

3. **Commit your changes**
   ```bash
   git add .
   git commit -m "Description of changes"
   ```

4. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

5. **Open a Pull Request**
   - Go to the original repository
   - Click "New Pull Request"
   - Select your branch
   - Fill in the PR template

### Pull Request Template

```markdown
## Description
[Clear description of what this PR does]

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update
- [ ] Example addition
- [ ] Other (please specify)

## Testing
[How did you test these changes?]

## Examples
[If applicable, provide example translations showing the improvement]

## Checklist
- [ ] I've tested the changes with Claude
- [ ] Documentation has been updated
- [ ] Examples have been added (if applicable)
- [ ] The skill still follows skill-creator principles
```

## Style Guidelines

### SKILL.md Style

- Use imperative/infinitive form (not "Claude should..." but "Use...")
- Be concise (challenge each sentence: "Does Claude really need this?")
- Use concrete examples over abstract explanations
- Organize with clear headings
- Include decision trees for complex workflows

### Documentation Style

- Use clear, simple language
- Include examples for every feature
- Use tables for comparisons
- Add code blocks with proper syntax highlighting
- Use emojis sparingly for visual scanning

### Example Style

When adding examples:
- Include full source text
- Show complete three-layer output
- Explain why specific choices were made
- Demonstrate skill adaptation to text type

## Code of Conduct

### Our Standards

- Be respectful and inclusive
- Welcome newcomers
- Accept constructive criticism
- Focus on what's best for the community
- Show empathy towards others

### Unacceptable Behavior

- Harassment or discriminatory language
- Trolling or insulting comments
- Public or private harassment
- Publishing others' private information
- Other conduct that's unprofessional

### Enforcement

Violations may result in:
1. Warning
2. Temporary ban
3. Permanent ban

Report issues to [project maintainer email].

## Development Setup

### Prerequisites

- Access to Claude AI
- Text editor
- Git
- (Optional) Python for skill packaging scripts

### Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR-USERNAME/claude-translation-skill.git
   cd claude-translation-skill
   ```

2. **Make changes**
   - Edit `translation/SKILL.md`
   - Test with Claude

3. **Package changes** (if you have skill-creator tools)
   ```bash
   python scripts/package_skill.py translation/
   ```

### Testing Checklist

Test your changes with:
- [ ] Simple sentences
- [ ] Complex academic text
- [ ] Literary passages
- [ ] Technical documentation
- [ ] Idiomatic expressions
- [ ] Multiple language pairs
- [ ] Different text types
- [ ] Edge cases (poetry, puns, etc.)

## Recognition

Contributors will be:
- Listed in the Contributors section
- Credited in release notes
- Thanked in the community

Significant contributions may earn you:
- Collaborator status
- Attribution in documentation
- Special thanks in releases

## Questions?

- 💬 [Open a discussion](../../discussions)
- 📧 Contact maintainers
- 📖 Read the [docs](docs/)

## License

By contributing, you agree that your contributions will be licensed under the MIT License.

---

**Thank you for making Claude Translation Skill better!** 🎉
