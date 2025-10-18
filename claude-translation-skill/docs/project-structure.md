# Project Structure

This document explains the organization of the Claude Translation Skill repository.

```
claude-translation-skill/
├── .github/
│   └── workflows/
│       └── validate.yml          # GitHub Actions for CI/CD
│
├── docs/                          # Documentation
│   ├── installation.md            # How to install the skill
│   ├── usage.md                   # Usage guide with examples
│   ├── faq.md                     # Frequently asked questions
│   └── theory.md                  # Translation theory (planned)
│
├── examples/                      # Translation examples
│   └── README.md                  # Example translations showcase
│
├── translation/                   # The actual skill
│   └── SKILL.md                   # Main skill file
│
├── .gitignore                     # Git ignore patterns
├── CHANGELOG.md                   # Version history
├── CONTRIBUTING.md                # Contribution guidelines
├── LICENSE                        # MIT License
├── README.md                      # Main project README
└── translation.zip                # Packaged skill for distribution

```

## Key Files

### Root Level

**README.md**
- Main project documentation
- Quick start guide
- Feature overview
- Links to detailed docs

**LICENSE**
- MIT License terms
- Allows free use, modification, and distribution

**CHANGELOG.md**
- Version history
- Release notes
- Upgrade instructions

**CONTRIBUTING.md**
- How to contribute
- Pull request process
- Code of conduct

**.gitignore**
- Files to exclude from Git
- Build artifacts, temp files, etc.

**translation.zip**
- Distribution package
- Ready to upload to Claude
- Contains `translation/SKILL.md`

### translation/

**SKILL.md**
- The core skill file
- YAML frontmatter with metadata
- Translation framework and guidelines
- Used directly by Claude

### docs/

**installation.md**
- Step-by-step installation
- Troubleshooting
- Alternative methods

**usage.md**
- Comprehensive usage guide
- Examples for different scenarios
- Tips and best practices

**faq.md**
- Common questions and answers
- Troubleshooting
- Comparisons with alternatives

### examples/

**README.md**
- Real translation examples
- Shows skill output for different text types
- Demonstrates three-layer structure

### .github/

**workflows/validate.yml**
- GitHub Actions configuration
- Automated validation
- CI/CD pipeline

## File Naming Conventions

- **Markdown files**: Use `.md` extension
- **Documentation**: Lowercase with hyphens (e.g., `installation.md`)
- **Main docs**: ALL CAPS (e.g., `README.md`, `LICENSE`)
- **Directories**: Lowercase, no spaces

## Important Notes

### What NOT to Include

As per skill-creator guidelines, DO NOT create:
- Multiple README files (only root README.md)
- INSTALLATION_GUIDE.md (use docs/installation.md)
- QUICK_REFERENCE.md (include in main README)
- User-facing setup guides in skill directory

The skill itself (`translation/SKILL.md`) should contain only what Claude needs to perform translations, not setup information or user documentation.

### Distribution Package

The `translation.zip` file contains only:
```
translation/
└── SKILL.md
```

It does NOT include:
- Documentation files
- Examples
- README
- License

Users download the zip, upload to Claude, and it works immediately.

## Maintenance

### Adding New Features

1. Edit `translation/SKILL.md`
2. Update `translation.zip` (repackage)
3. Update documentation in `docs/`
4. Add examples if applicable
5. Update `CHANGELOG.md`
6. Update version in README if needed

### Keeping It Lean

The `SKILL.md` file should remain under 500 lines. If it grows beyond that:
1. Identify sections that could be moved to `references/`
2. Create reference files in `translation/references/`
3. Update `SKILL.md` to reference them
4. Repackage the skill

Currently, the skill is 6.5KB and doesn't need splitting.

## Development Workflow

```
1. Clone repo
2. Make changes to translation/SKILL.md
3. Test with Claude
4. Update docs if needed
5. Repackage: zip -r translation.zip translation/
6. Commit and push
7. GitHub Actions validates automatically
8. Create release when ready
```

## Questions?

See [CONTRIBUTING.md](../CONTRIBUTING.md) for how to contribute or ask questions.
